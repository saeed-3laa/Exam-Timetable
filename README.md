# Exam Scheduler

A Python tool for scheduling exams with graph coloring to avoid conflicts.

## Overview
This project automates the process of creating an exam timetable by:
- Reading student course data from an Excel file (`studentcourses.xlsx`).
- Using graph coloring to assign non-conflicting periods.
- Distributing exams across days and periods with constraints (e.g., max 300 students per day, 3 periods per day).
- Saving the final schedule to an Excel file (`exam_schedule_by_day.xlsx`).

## Files
- **`ExamTimetable.ipynb`**: The main Python script that generates the exam timetable.
- **`studentcourses.xlsx`**: Input Excel file with student IDs and course enrollments (example data).
- **`exam_schedule_by_day.xlsx`**: Output Excel file with the generated timetable (each day in a separate sheet).
