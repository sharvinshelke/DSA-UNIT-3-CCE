# DSA-UNIT-3-CCE
# Airplane Luggage Handling System Using Singly Linked List in C++

1. Introduction
The Airplane Luggage Handling System is a simple C++ project that manages luggage records using a Singly Linked List. It demonstrates basic data structure operations such as insertion, traversal, searching, and deletion.

Each luggage record contains a unique Bag ID. The program provides a menu-driven interface for managing luggage records.

2. Problem Statement
Managing luggage records at an airport can be difficult when many bags need to be handled. Develop a C++ program using a Singly Linked List to add, display, search, and delete luggage records based on their Bag IDs.

3. Objectives
- To understand the concept of a Singly Linked List.
- To add new luggage records dynamically.
- To display all stored luggage IDs.
- To search for luggage using its Bag ID.
- To delete a luggage record using its Bag ID.
- To implement linked-list operations in C++.

4. Features
. Add Luggage:** Insert a new Bag ID into the linked list.
. Display Luggage:** Display all stored Bag IDs.
. Search Luggage:** Search for a specific Bag ID.
. Delete Luggage:** Remove a luggage record using its Bag ID.
. Exit: Terminate the program.


6. Data Structure
Each node contains:
- id: Stores the luggage ID.
- next: Stores the address of the next node.

The head pointer points to the first node of the linked list. The last node points to NULL

 7. Algorithm

Step 1: Start
Initialize the head pointer to NULL

Step 2: Display Menu
Display the following options:
1. Add Luggage
2. Display Luggage
3. Search Luggage
4. Delete Luggage
5. Exit

Step 3: Read Choice
Accept the user's choice.

 Step 4: Perform Operation
If choice = 1: Create a new node, enter the Bag ID, and insert it at the beginning of the linked list.
  If choice = 2: Traverse the list from head to NULL and display all Bag IDs.
  If choice = 3: Search for the entered Bag ID and display whether it is found.
  If choice = 4: Search for the Bag ID, adjust the links, and delete the matching node if it exists.
  If choice = 5: Exit the program.
  Otherwise, display an invalid-choice message.

Step 5: Repeat
Repeat the menu until the user selects Exit.

Step 6: Stop
Terminate the program.

8. Sample Output

text
1.Add  2.Display  3.Search  4.Delete  5.Exit
1
Enter Bag ID: 101

1.Add  2.Display  3.Search  4.Delete  5.Exit
1
Enter Bag ID: 102

1.Add  2.Display  3.Search  4.Delete  5.Exit
2
102 -> 101 -> NULL

1.Add  2.Display  3.Search  4.Delete  5.Exit
3
Enter ID: 101
Found

1.Add  2.Display  3.Search  4.Delete  5.Exit
4
Enter ID: 102
Deleted

1.Add  2.Display  3.Search  4.Delete  5.Exit
2
101 -> NULL

1.Add  2.Display  3.Search  4.Delete  5.Exit
5



 Conclusion
The Airplane Luggage Handling System demonstrates how a Singly Linked List can be used to manage luggage IDs in C++. This project helps develop an understanding of dynamic memory allocation, node creation, traversal, searching, and deletion.

