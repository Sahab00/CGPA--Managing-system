CGPA Manager - A GUI-Based Academic Record Manager 📚

CGPA Manager is a user-friendly desktop application built using Python’s Tkinter library. It allows coordinators to manage students' academic records, including CGPA calculations, and enables students to view their CGPA. It offers an interactive graphical interface for easy use by both coordinators and students.

Key Features 🎉
1)Coordinator Login: Secure login functionality for coordinators to manage student records.
2)Student Record Management: Add student details such as name, roll number, semester, total subjects, and CGPA.
3)Automatic CGPA Calculation: Calculate CGPA based on subject marks and credit hours.
4)Student Access: Students can check their CGPA by entering their roll number.
5)Data Storage: Records are saved in a file, ensuring persistence across sessions.
6)Exit Functionality: The user can exit the application at any time using the exit button.
How It Works 🚀
1. Coordinator Mode:
After logging in with the correct credentials (default username and password are set as "123"), the coordinator can:
a) Add new student records.
        Input student names, roll numbers, semesters, subjects, marks, and credit hours.
b) Calculate and display the cumulative CGPA.
c) Store student data in a text file for future retrieval.
d) Can add multiple student records
2. Student Mode:
Students can enter their roll number to view their CGPA, as calculated and saved by the coordinator.
3. Persistent Data:
All student records are stored in a text file (student_records.txt), making it possible to access previously saved information.

Installation and Usage 🖥️
Prerequisites:
Python 3.x must be installed on your system.
Tkinter (pre-installed with Python).

Installation Steps:

Clone the repository or download the source code:
git clone https://github.com/Sahab00/cgpa-manager.git

Navigate to the project directory:
cd cgpa-manager

Run the program:
python your_script_name.py

Project Structure 📂

CGPA_Manager/
├── CGPA_Manager_Notebook.ipynb  # Jupyter notebook containing all code (login, menu, CGPA calculation, file management)
├── README.md                    # Project overview and instructions
└── student_records.txt          # Stores student records

Screenshots 📸
Main Menu: A welcome screen offering options for both coordinators and students.
Login Screen: Secure login for coordinators with predefined credentials.
Student Record Entry: Form for coordinators to input student details and marks.
CGPA Display: A section where students can check their CGPA by entering their roll number.

Contributing 🤝
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request. You can improve features or suggest new ones. Let's make this tool even more powerful for managing academic records.

License 📄
This project is licensed under the Apache License 2.0: - see the LICENSE file for details.
