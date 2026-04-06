---
title: "University Registeration System "
categories: [Game Dev, Unreal Engine]
featured: /assets/images/project_re1.png
---
<br>
A full-stack university registration system developed as part of a Software Engineering course. The system models real-world academic workflows, allowing students, administrators, and staff to manage course registration efficiently.

**Technologies Used:**

*-Laravel (MVC Architecture)* <br>
*-PHP*<br>
*-Bootstrap (Frontend UI)*<br>
*-MySQL (Database)*<br>

**Key Features:**<br>
-Student course registration system<br>
-Role-based access (Student, Dean, Employee)<br>
-Course management (add, edit, delete)<br>
-GPA-based credit limits<br>
-Schedule conflict detection<br>
-Automated fee calculation and payment handling<br>
-Course recommendation system<br>
-Printable schedule output<br>

**System Overview**

This system simulates a real university registration environment. Students can log in, browse available courses, and register based on their academic constraints and performance.

-The system enforces credit limits based on GPA:

Up to 21 credits for GPA ≥ 3.0
Up to 18 credits for GPA < 3.0

-It also recommends courses if a student has previously failed a subject, helping guide academic progress.


**Student Workflow**<br>
1. The student logs into the system<br>
2. Views available courses and allowed credit hours<br>
3. Selects subjects and corresponding classes (theoretical & practical)<br>
4. Ensures no schedule conflicts between selected classes<br>
5. Registers a minimum of 12 credits before submission<br>
6. Finalizes registration within the allowed credit range (18–21 max)<br>

**Once confirmed:**

1. The system calculates total fees based on credit hours<br>
2. Automatically deducts the amount from the student’s account (e.g., bank or e-wallet)<br>
3. Blocks registration if the balance is insufficient<br>



**Dean:**

Full control over courses and students
Can add, edit, or delete courses
Manage student records

**Employees:**

Can register students using their ID
Access student registration data
Limited permissions during certain periods (e.g., cannot add courses outside registration period)

<br>
The goal of this project was to design and implement a realistic academic registration system, applying core software engineering principles such as MVC architecture, role-based access control, and data validation, while ensuring usability and reliability.

{% include figure image_path="/assets/images/UniversityRegisteration/sw2-7.png" caption="Use case diagram" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-8.png" caption="Component diagram" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-6.png" caption="Login page" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-2.png" caption="Student list page" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-1.png" caption="Dean home page" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-3.png" caption="Courses page" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-4.png" caption="Enrolling a student" %} <br>
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-5.png" caption="Deleting a student page" %} <br>

