
# Library-System-Application-Using-Python-and-CSV

The program is a simple library management system implemented using the Tkinter library in Python. It provides a graphical user interface (GUI) with multiple tabs for different functionalities. Here is a brief description of each tab:

1. **Home Tab:**
   - Displays a welcome message to the library.
   - Retrieves book data from a CSV file and dynamically creates labels for each book, including the title, author, and an optional thumbnail image.

2. **Borrow Tab:**
   - Allows users to input their name, student ID, and choose a book title from a dropdown menu.
   - Provides a "Borrow" button to initiate the borrowing process.
   - Validates the input and updates the data in a CSV file, indicating that the book is now borrowed.

3. **Return Tab:**
   - Enables users to input their name, student ID, and select a book title from a dropdown menu.
   - Includes an "Update Dropdown" button to refresh the dropdown list based on the user's input.
   - Offers a "Return" button to complete the return process.
   - Updates the CSV file to reflect the returned status of the selected book.

4. **Invoice Tab:**
   - Lets users input their name and student ID.
   - Provides a "Generate Invoice" button to display a list of borrowed books along with their current status (borrowed or returned).

5. **Rules Tab:**
   - Displays a set of library rules and regulations.
   - Outlines borrowing limits, loan durations, and consequences for rule violations.

The program uses a CSV file to store and retrieve book and borrowing information. It employs object-oriented programming principles, utilizing classes and methods to organize and manage the GUI components and data interactions.




## Demo

![Screenshot (431)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/c6465908-0da0-435f-9510-3f2fa15d8cfe)

![Screenshot (432)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/480c4569-f489-4733-b803-17e995e08cf4)

![Screenshot (433)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/27dcabe4-9df1-4e44-b46e-d69d62950838)

![Screenshot (434)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/01a83943-23de-4fec-bfd6-78bf338e07e0)

![Screenshot (435)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/88f57b2c-4f60-4db5-a426-933b83b4703a)

![Screenshot (436)](https://github.com/Ahmad-Izzuddin/Library-System-Application-Using-Python-and-CSV/assets/112834529/cba19cbc-8a05-45a0-a5c1-3229f3381377)
## Environment Variables

To run this project, you will need to install following library

```python
pip install tk
```
```python
pip install Pillow
```

