# Student Results Analyzer

A beginner-friendly Python project that analyzes multiple student marks and generates a detailed performance report.

The application calculates pass/fail counts, highest and lowest marks, average marks, and validates user input to ensure accurate analysis.

---

##  Features

- Accepts multiple student marks as comma-separated input
- Calculates pass student count
- Calculates fail student count
- Finds highest mark
- Finds lowest mark
- Computes average mark
- Input validation for invalid values
- Exception handling for better reliability

---

##  Technologies Used

- Python 3

---

##  Project Structure

```
student-results-analyzer/
│
├── student_results_analyzer.py
└── README.md
```

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/student-results-analyzer.git
```

2. Navigate to the project folder:

```bash
cd student-results-analyzer
```

3. Run the program:

```bash
python student_results_analyzer.py
```

---

##  Sample Input

```
45, 80, 22, 99, 35
```

### Sample Output

```
--- Student Results Report ---

Total Students Analyzed : 5
Pass Students Count     : 4
Fail Students Count     : 1
Highest Mark            : 99
Lowest Mark             : 22
Average Mark            : 56.20
```

---

## Grading Rule

| Marks | Status |
|---------|---------|
| 35 and above | Pass |
| Below 35 | Fail |

---

##  Input Validation

The program validates:

- Non-numeric values
- Marks below 0
- Marks above 100
- Incorrect input formats

Example:

```
45, 80, abc, 90
```

Output:

```
Please enter valid numbers only.
```

---

##  Learning Outcomes

- User Input Handling
- Lists and Loops
- Conditional Statements
- Exception Handling
- Data Analysis Basics
- Report Generation
- Python Functions

---

##  Future Improvements

- Grade Classification (A, B, C, D)
- Export Reports to CSV
- Student-wise Performance Analysis
- Graphical Reports using Matplotlib
- GUI using Tkinter
- Web App using Streamlit

---

##  Author

Developed as a Python project to practice data analysis, input validation, exception handling, and report generation.

⭐ If you found this project useful, consider giving it a star on GitHub!****
