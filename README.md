# Student Grading System Assignment

## Overview
This project implements a **Student Grading System** for automating the GPA calculation of students. It is designed to:
- Assign grades to students.
- Calculate GPA based on grades for multiple courses.
- Reject invalid grade values.
- Handle students with no courses by returning a GPA of 0.

## Key Features
- **Grade Assignment**: Grades are assigned to students for each course.
- **GPA Calculation**: The system calculates the GPA based on valid grades.
- **Invalid Grade Rejection**: Any invalid grade (e.g., "E") is rejected, and an exception is raised.
- **No Courses GPA**: Students with no enrolled courses will have a GPA of 0.
  
## Classes in the System
- **Student Class**: Represents the student with attributes like name and enrolled courses. Methods include `enroll()` for course enrollment and `calculate_gpa()` for GPA calculation.
- **Course Class**: Represents the course, with attributes like course name and grade received. It does not have additional methods beyond its constructor.
- **Grade Class**: Represents a grade in the system. It includes a method `get_grade_point()` to map letter grades to numerical grade points (A = 4.0, B = 3.0, etc.).

## How to Use
1. **Clone the Repository**:
   git clone https://github.com/Hruthikaveldi/Student_Grading_System_Assignment.git
