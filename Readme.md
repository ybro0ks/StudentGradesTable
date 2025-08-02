# Student Grades Table Web App

## Project Overview

This project implements a dynamic student gradebook web application using **HTML**, **CSS**, and **JavaScript**. It simulates assignment tracking for ten students with editable grade fields and real-time calculation of final averages. The interface replicates a clean, modern table layout with usability-focused features.

---

## Key Features

### Auto-Average Calculation
- Final grades are automatically calculated as the average of five assignments.
- Updates in real time as grades are entered or modified.
- Output format: whole-number percentages (e.g., `72%`).

### Invalid Input Handling
- Input values outside the `0–100` range or non-numeric entries are treated as invalid.
- Invalid entries are replaced with a dash (`-`), indicating a missing submission.

### Missing Assignment Counter
- A live counter below the table displays how many assignments are unsubmitted.
- Empty or invalid cells are highlighted in **yellow** for visibility.

### Grade Format Toggle
- Clicking the **"Average"** column header toggles grade formats:
  - **Percentage:** e.g., `85%`
  - **Letter Grade:** e.g., `B`
  - **4.0 GPA Scale:** e.g., `3.0`
- The header text updates accordingly:
  - `Average [%]`
  - `Average [Letter]`
  - `Average [4.0]`

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **No Backend Required**

---

## How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Interact directly with the grade table.

---

## Notes

- All cells except the final average column are editable.
- Uses native DOM manipulation—no external libraries.
- Clean and responsive design with alternating row colors for readability.
