**Time-Table-Generation-System**
A Django-based system that generates timetables using a Genetic Algorithm.

**Overview**

The **Time Table Generation System (TTGS)** is a web-based application developed using **Django** and **Genetic Algorithms** to efficiently generate optimal timetables for educational institutions. The system is designed to cater to various constraints such as teacher availability, classroom capacity, and subject requirements.


**Features**

- **Automated Timetable Generation:** Utilizes a Genetic Algorithm to create optimal timetables based on the provided constraints.
- **User-Friendly Interface:** Simple and intuitive UI for administrators to input data and manage the timetable generation process.
- **Constraint Handling:** Accounts for multiple constraints like teacher availability, room capacity, and course conflicts.
- **Customizable:** Easily adaptable to different institution requirements.
- **Conflict Detection:** Automatically detects and highlights scheduling conflicts.

**Technology Stack**

- **Backend:** Django, Python
- **Algorithm:** Genetic Algorithm
- **Database:** SQLITE
- **Frontend:** HTML, CSS, JavaScript
- **Version Control:** Git

**Installation and Setup**

To run this project locally:

1. **Clone the repository:**
   git clone https://github.com/saivaraprasadmandala/Time-Table-Generation-System.git
   cd Time-Table-Generation-System
2. **Install the required dependencies:** pip install -r requirements.txt
3. **Setup the database:** python manage.py migrate
4. **Run the development server:** python manage.py runserver
5. **Access the application:** Open http://127.0.0.1:8000 in your browser.

**Project Structure**


**Future Enhancements**:

Multi-Institution Support: Extend the system to handle multiple institutions within a single deployment.
Advanced Conflict Resolution: Implement more sophisticated algorithms for detecting and resolving scheduling conflicts.
User Roles: Introduce different user roles with varying permissions (e.g., Admin, Teacher, Student).

**Contributing**

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

**Contact**
For any inquiries or feedback, please reach out to: mandalasaivaraprasad@gmail.com
