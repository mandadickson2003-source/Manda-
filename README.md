ICS-Quadratic-Grader-<Manda-Dickson>

Quadratic Solver and Grading System (Single-File Web App)

📝 Project Description

This project is a single-page web application built using HTML and JavaScript that performs two main functions:
FEATURES:
1. Quadratic Equation Solver

Solves equations of the form: ax² + bx + c = 0

Calculates and displays:

The discriminant (D = b² - 4ac)

The nature of roots:

D > 0 → Two distinct real roots

D = 0 → One real repeated root

D < 0 → Two complex conjugate roots



Displays results neatly formatted, with friendly error messages for invalid inputs.

Includes a Reset/Clear button.



2. Grading System

Converts a numeric score (0–100) to a letter grade using the following scale:

Range	Grade

85–100	A+
75–84	A
65–74	B+
60–64	B
55–59	C+
50–54	C
0–49	D


Validates the score input and shows an error message if it is out of range or empty.

Displays the computed letter grade with a short message (e.g., “Score 82 → Grade A”).





---

⚙️ How to Run

1. Download or clone the repository:

git clone https://github.com/<your-username>/ICS-Quadratic-Grader-<Surname-Firstname>.git


2. Open the folder and double-click the file index.html.


3. The web app runs offline in your browser — no additional setup required.

🧪 Test Cases

Quadratic Solver

Input (a, b, c)	Expected Discriminant (D)	Expected Roots	Nature of Roots

1, 5, 6	1	Two real roots	D > 0
1, 2, 1	0	One real root	D = 0
1, 2, 5	-16	Complex roots	D < 0


Grading System

Input Score	Expected Grade

90	A+
78	A
66	B+
61	B
57	C+
52	C
40	D



---

🧑‍💻 Repository Structure

ICS-Quadratic-Grader-<Surname-Firstname>/
│
├── index.html      # Single-file web application (HTML + JS)
└── README.md       # Project description, usage, and test cases


---

💡 Notes

The project was developed for ICT251 – Web Technologies.

All code is written in plain HTML + JavaScript with no external 
