---
title: "UniversityRegisterationSystem "
categories: [Game Dev, Unreal Engine]
featured: /assets/images/project_re1.png
---
A full-stack university registration system developed as part of a Software Engineering course. The system models real-world academic workflows, allowing students, administrators, and staff to manage course registration efficiently.

Technologies Used:

**-Laravel (MVC Architecture)**
**-PHP**
**-Bootstrap (Frontend UI)**
**-MySQL (Database)**

**Key Features:**
-Student course registration system
-Role-based access (Student, Dean, Employee)
-Course management (add, edit, delete)
-GPA-based credit limits
-Schedule conflict detection
-Automated fee calculation and payment handling
-Course recommendation system
-Printable schedule output

**System Overview**

This system simulates a real university registration environment. Students can log in, browse available courses, and register based on their academic constraints and performance.

The system enforces credit limits based on GPA:

Up to 21 credits for GPA ≥ 3.0
Up to 18 credits for GPA < 3.0

It also recommends courses if a student has previously failed a subject, helping guide academic progress.


*Student Workflow*
1.The student logs into the system
2.Views available courses and allowed credit hours
3.Selects subjects and corresponding classes (theoretical & practical)
4.Ensures no schedule conflicts between selected classes
5.Registers a minimum of 12 credits before submission
6.Finalizes registration within the allowed credit range (18–21 max)

*Once confirmed:*

1.The system calculates total fees based on credit hours
2.Automatically deducts the amount from the student’s account (e.g., bank or e-wallet)
3.Blocks registration if the balance is insufficient


*Admin & Staff Functionality*

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

{% include figure image_path="/assets/images/UniversityRegisteration/sw2-7.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-8.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-6.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-2.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-1.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-3.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-4.png" caption="Home Page" %} 
{% include figure image_path="/assets/images/UniversityRegisteration/sw2-5.png" caption="Home Page" %} 

