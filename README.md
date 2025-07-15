Note Management System (OOP Lab)

A simple Note Management System implemented using Object-Oriented Programming in Python. It allows users to create, view, edit, and delete notes, organized per user. Notes are saved as text files, and users are tracked in an Excel file.

Features : 

. Add new notes per user

. View existing notes

. Edit or delete notes

. Track users with an Excel file
(users.xlsx)

. Modular OOP design (main.py, note_manager.py)

. Demonstrates file handling and class usage for learning OOP



Technologies Used :

. Python 3.x

. openpyxl for Excel handling

. Standard libraries: os, datetime



Project Structure :

oop-lab

├── main.py                  # Entry point, CLI for note management

├── note_manager.py          # NoteManager class handling operations

├── users.xlsx               # Tracks user registration

├── notes/                   # User-specific notes

│   ├── user1.txt

│   ├── user2.txt

│   └── ...

└── README.md


Setup & Usage :

1. Clone the repository:
git clone https://github.com/yourusername/oop-lab.git
cd oop-lab

2. Install dependencies:
pip install openpyxl

3. Run the application:
python main.py

4. Follow the CLI instructions to manage notes.

Learning Outcomes :

. Practice classes and OOP design

. File handling in Python

. Using Excel with openpyxl

. Modular project structuring
   
Contributing :
Contributions for adding a GUI or database backend are welcome. Fork the repo and open a pull request.

License :
For educational use and OOP lab practice.

