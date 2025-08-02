Student Grades Table

This project recreates a dynamic student gradebook as a web app using HTML, CSS, and JavaScript.
It manages hypothetical assignment grades for ten students, allowing manual editing of grades and providing real-time calculations of final scores. 
The design mimics a clean online table with alternating row colors, aligned text, and editable fields—except for the final average column, which is calculated automatically.


Interactive Functionality
Auto-Average Calculation
Final grade (average of the five assignments) updates in real time whenever a grade is entered or changed. Results are rounded, whole-number percentages (e.g., "72%").

Invalid Input Handling
Entries outside the 0–100 range or invalid data are replaced with “-”, meaning not submitted.

Missing Assignment Counter
A counter beneath the table shows how many assignments are unsubmitted. Yellow highlights mark these cells.

Grade Format Toggle
Clicking the "Average" column header toggles all final grades between:

Percent format (e.g., 85%)

Letter grade (e.g., B)

4.0 GPA scale (e.g., 3.0)
The column header updates accordingly: Average [%], Average [Letter], or Average [4.0].

