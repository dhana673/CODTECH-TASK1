Name : RENTALA DHANUSH

Company : CODTECH IT SOLUTIONS

ID : CT08DS7187

Domain : PYTHON PROGRAMMING

Duration : SEPTEMBER TO OCTOBER 2024

Mentor : 

### Overview of the Library Management System

The **Library Management System** is a Python-based application designed to manage various types of resources in a library such as books, magazines, and DVDs. It allows users to add, check out, return, and search for items in the library's collection. The system also manages overdue fines for late returns and provides basic functionalities for tracking the status of library items.

#### Key Features:
1. **Add New Items**: 
   - Users can add new items to the library's collection by specifying the title, author, category, and item type (Book, Magazine, or DVD).

2. **Search for Items**:
   - The system allows users to search the library's collection based on title, author, or category. It returns details about the items, including their availability status (checked out or available).

3. **Check Out Items**:
   - Users can check out items from the library for a period of 14 days. The system sets a due date and tracks whether the item is currently checked out or not.

4. **Return Items**:
   - When an item is returned, the system calculates if it is overdue. If the return is late, the system calculates an overdue fine based on the number of overdue days (with a fine rate of $0.50 per day).

5. **Overdue Fine Calculation**:
   - If the user returns an item after the due date, the system calculates the fine based on the number of overdue days and applies the fine rate.

#### Key Components:

1. **LibraryItem Class**:
   - Represents a general item in the library (books, magazines, DVDs).
   - Tracks details such as title, author, category, and whether the item is checked out or available.
   - Contains methods for checking out and returning the item, with due date tracking.

2. **FineManager Class**:
   - Manages the overdue fine calculation based on the number of overdue days and the fine rate.

3. **Library Class**:
   - Manages the library's collection of items.
   - Provides methods to add new items, check out items, return items, and search for items based on title, author, or category.
   - Interacts with the `FineManager` class to calculate fines for overdue returns.

#### Program Flow:
1. The system starts by adding some sample items (books, magazines, DVDs) to the library's collection.
2. The user interacts with the system through a menu, where they can:
   - Add a new item to the library.
   - Search for an item by title, author, or category.
   - Check out an item, which will set its due date to 14 days from the current date.
   - Return an item, which will calculate any overdue fine if the item is returned late.
3. The program loops, allowing the user to perform multiple actions until they choose to exit.

#### Example Usage:

1. **Adding an Item**:
   - The user can input details such as the type of item (Book, Magazine, or DVD), its title, author, and category. The item will then be added to the library's collection.

2. **Searching for an Item**:
   - The user can search by title, author, or category. For example, if the user searches for "George Orwell," all items by that author will be displayed with their status (checked out or available).

3. **Checking Out an Item**:
   - If a user checks out an item, the system sets a due date for 14 days in the future and marks the item as checked out.

4. **Returning an Item**:
   - When an item is returned, the system checks if it is overdue. If the return is late, it calculates the number of overdue days and displays the fine.

5. **Overdue Fines**:
   - If an item is returned late, the fine is calculated at a rate of $0.50 per day overdue.

#### Potential Future Enhancements:
- **User Accounts**: Add the ability for users to create accounts and track who has checked out specific items.
- **Persistent Storage**: Implement a database or file system to store library data permanently, so it can persist between sessions.
- **Notifications**: Notify users when their checked-out items are about to be overdue.
- **Reservations**: Allow users to reserve items that are currently checked out.
- **Multiple Categories**: Support for adding multiple categories or tags to each item for more precise searching.

This Python-based **Library Management System** offers a simple yet functional approach to managing the core operations of a library, such as borrowing, returning, and tracking overdue items. It provides a good foundation for a more robust system with additional features and functionalities.

### Output of the Project
![Screenshot (51)](https://github.com/user-attachments/assets/3f2b6ae8-568c-4820-a135-dad3528f745e)
