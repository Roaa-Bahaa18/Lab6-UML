# Lab 6 – SkillForge UML Design

## Overview
This lab demonstrates the **UML design** of the *SkillForge* learning platform, showcasing the relationships and interactions between system components.  
The project includes a **Sequence diagram**,**Class diagram**,**Activity diagram**, and **UseCase Diagram** illustrating how users (students, instructors, admins) interact with the system’s backend services and data management layer.

---

##  System Description
The **SkillForge Platform** is an educational management system that supports:
- Course creation and management  
- Lesson and quiz organization  
- Student enrollment and certificate generation  
- Interaction with a JSON-based database through service classes  

---

## UML Components

### Entities
| Class | Description |
|--------|--------------|
| **Instructor** |  can create and manage courses, upload lessons, and design quizzes. |
| **Student** |  can browse available courses, enroll, complete lessons and quizzes, and earn certificates. |
| **Admin** | can manage users, approve or remove courses, and monitor platform analytics. |
| **Course** | Represents a learning module containing lessons and quizzes. |
| **Lesson** | Individual learning unit within a course. |
| **Quiz** | Assessment for students linked to a course. |
| **Question** | Defines each question within a quiz. |
| **Certificate** | Awarded to students upon completion of courses or quizzes. |
| **Analytics** | tracks account statistics such as completed courses, time spent, and quiz grades for each student. |

---

### Services
| Service | Responsibility |
|----------|----------------|
| **CourseService** | Handles course-related logic and interactions. |
| **QuizService** | Manages quiz creation, attempt evaluation, and scoring. |
| **UserService** | Responsible for user registration, login, and data retrieval. |
| **JsonDatabaseManager** | Handles all read/write operations to the JSON data files. |

---

## Authors
1. Habiba Ahmed – Class diagram
2. Roaa Bahaa – Use Case diagram 
3. Darine Islam – Activity diagram
4. Heba Tarek - Sequence diagram 
