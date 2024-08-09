This Python-based Phonebook Management System is a graphical application created using Tkinter for the user interface and MySQL for database management. It allows users to manage their contacts efficiently, providing features for adding, modifying, searching, and deleting contacts. Additionally, the system includes user authentication, requiring users to sign up and log in before accessing their phonebook.

Key Components:
User Authentication: Users must first sign up by creating an account. This involves storing a unique username and password in the users table. For existing users, the system provides a login interface where they can authenticate and access their phonebook.

Phonebook Management: Once logged in, users can add new contacts, each associated with a name and phone number, which are stored in the contacts table. Users can also search for contacts by name, delete contacts by ID, and modify existing contact information.

Contact Description: The system includes an additional feature where users can add descriptions to their contacts, such as an email address and physical address. This information is stored in the contact_description table and is linked to the corresponding contact.

User Interface: The application has a clean and intuitive graphical interface, built using Tkinter. It features multiple windows, such as sign-up, login, and the main phonebook management window. The UI is enhanced with background images and a structured layout for easy navigation.

Database Management: All contact data, user accounts, and descriptions are stored in a MySQL database. The application handles database operations such as creating tables, inserting data, and executing queries, ensuring data persistence and integrity.

This system is a comprehensive tool for managing personal contacts, combining a user-friendly interface with robust backend support.
