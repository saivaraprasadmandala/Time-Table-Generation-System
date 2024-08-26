## **Time-Table-Generation-System**
A Django-based system that generates timetables using a Genetic Algorithm.

## **Overview**

The **Time Table Generation System (TTGS)** is a web-based application developed using **Django** and **Genetic Algorithms** to efficiently generate optimal timetables for educational institutions. The system is designed to cater to various constraints such as teacher availability, classroom capacity, and subject requirements.


## **Features**

- **Automated Timetable Generation:** Utilizes a Genetic Algorithm to create optimal timetables based on the provided constraints.
- **User-Friendly Interface:** Simple and intuitive UI for administrators to input data and manage the timetable generation process.
- **Constraint Handling:** Accounts for multiple constraints like teacher availability, room capacity, and course conflicts.
- **Customizable:** Easily adaptable to different institution requirements.
- **Conflict Detection:** Automatically detects and highlights scheduling conflicts.

## **Technology Stack**

- **Backend:** Django, Python
- **Algorithm:** Genetic Algorithm
- **Database:** SQLITE
- **Frontend:** HTML, CSS, JavaScript
- **Version Control:** Git

## **Installation and Setup**

To run this project locally:

1. **Clone the repository:**
   
   git clone https://github.com/saivaraprasadmandala/Time-Table-Generation-System.git
   
   cd Time-Table-Generation-System
3. **Install the required dependencies:** pip install -r requirements.txt
4. **Setup the database:** python manage.py migrate
5. **Run the development server:** python manage.py runserver
6. **Access the application:** Open http://127.0.0.1:8000 in your browser.

## **Project Structure**

![Screenshot 2024-08-26 170854](https://github.com/user-attachments/assets/d4a34c86-e6c7-4703-9698-ace3d775207d)

## **Output Screens**

i)Home Page:
![image](https://github.com/user-attachments/assets/f1d91aca-bb05-45e1-8b30-826da5ff4ca7)
![image](https://github.com/user-attachments/assets/2c93fd19-b9a1-461b-a147-4b64a45b0476)

ii)Add Teachers:
![image](https://github.com/user-attachments/assets/52b71802-948b-4b36-9730-78cefc399d74)

iii)Add Rooms:
![image](https://github.com/user-attachments/assets/58d0bbaa-ab8f-4869-bc3d-695a1653791b)

iv)Add Timings:
![image](https://github.com/user-attachments/assets/a8f72a09-3eb8-42bb-a1fa-a8c7603aba7d)

v)Add Courses:
![image](https://github.com/user-attachments/assets/63d797ab-4213-484e-831a-cd46eacc755c)

vi)View Courses:
![image](https://github.com/user-attachments/assets/24739e6e-e359-41c4-98cc-652ffd8321be)

vii)View Department:
![image](https://github.com/user-attachments/assets/4d01bec6-7d5b-4907-ba95-f7fc33228bda)

viii)Add Sections:
![image](https://github.com/user-attachments/assets/78b27b26-3dba-4e93-add0-9d074dca953c)

ix)Click to Generate Final Time Table:
![image](https://github.com/user-attachments/assets/877798c4-f9bd-4fc8-a020-2d3105a5caa8)

x)Generate Final Time Table:
![image](https://github.com/user-attachments/assets/77c46e8c-01fa-4526-822b-ec03851b5021)

![image](https://github.com/user-attachments/assets/b971588e-c2df-4e86-96aa-9879f8632530)

![image](https://github.com/user-attachments/assets/c25cc87d-aed2-4fc1-87aa-15d63750f2aa)


##

## **Future Enhancements**:

**Multi-Institution Support:** Extend the system to handle multiple institutions within a single deployment.
Advanced Conflict Resolution: Implement more sophisticated algorithms for detecting and resolving scheduling conflicts.
User Roles: Introduce different user roles with varying permissions (e.g., Admin, Teacher, Student).

## **Contribution**

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

## **Contact**
For any inquiries or feedback, please reach out to: mandalasaivaraprasad@gmail.com
