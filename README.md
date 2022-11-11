# DESCRIPTION
- **STUDENT** - A student is associated with a seat and course. A student consist of student id, student name, student address. 
- **SEAT** – A seat is associated with a student. A seat consists of seat no, and seat position.
- **COURSE** – A course is associated with a student and a section. A course consists of course name and course number. 
- **SECTION** – A section is associated with course and professor. A section consists of a section number.
- **PROFESSOR** – A professor is associated with a section. A professor consists of professor id, professor name, and professor faculty. 
- **INSTRUCTOR** – A instructor is associated with a course. A instructor consists of instructor no, instructor name, and instructor faculty.

# RELATIONSHIP
- A **STUDENT** can <ins>fill</ins> one and only one **SEAT**, each **SEAT** can be <ins>filled</ins> by one and only one **STUDENT**.
- A **STUDENT** can <ins>take</ins> one or more **COURSE**, each **COURSE** can be <ins>taken</ins> by one or more **STUDENT**.
- A **COURSE**  <ins>has</ins> one or more **SECTION**, each **SECTION** <ins>has</ins> one or more **COURSE**.
- A **PROFESSOR** can <ins>teach</ins> zero or more **SECTION**, each **SECTION** can be <ins>taught</ins> by zero or more **PROFESSOR**.
- A **INSTRUCTOR** can <ins>teach</ins> one or more **COURSES**, each **COURSE** can be <ins>taught</ins> by one **INSTRUCTOR**.

# ASSUMPTIONS
- Can a **STUDENT** have more than one **SEAT**?
- Can a **COURSE** exist with zero **STUDENTS**? No
- Can a **PROFESSOR** teach zero **COURSES**?  No


![image](https://user-images.githubusercontent.com/77816985/201399924-04e1d6df-67a0-4efc-82e2-2f3188951585.png)
