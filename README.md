# structured_paper_setter
--------------------------------------------------

OVERVIEW
This project is an automated university-level question paper generator.
It generates structured and CO-compliant exam papers using user inputs.

--------------------------------------------------

OBJECTIVE
To generate a fully structured, numerical and application-based question paper
by strictly following syllabus, course outcomes, and exam rules.

--------------------------------------------------

USER INPUTS
The system requires the following inputs from the user:

1. Subject Name
   Example: Computer Networks

2. Course Outcomes (COs)
   Defines learning objectives for the subject

3. Syllabus
   Ensures all questions are strictly within academic scope

4. Previous Year Question Papers
   Helps maintain pattern, difficulty level, and important topics

--------------------------------------------------

EXAM STRUCTURE

Total Marks: 36
Total Questions: 3

--------------------------------------------------

Q.1 (Objective Type – 12 Marks)
- 6 sub-questions (a–f)
- Each question carries 2 marks
- Includes:
  * Numerical problems
  * Analytical questions
  * True/False with justification
- CO Coverage:
  * Mixed COs preferred

--------------------------------------------------

Q.2 (12 Marks) – Attempt ANY TWO out of THREE
- Each question = 6 marks
- Formats allowed:
  * (6) OR (4+2) OR (3+3)

STRICT RULE:
- All three questions must belong to SAME CO
- No mixing of COs
- Questions must be:
  * Numerical
  * Algorithm-based
  * Application-oriented

--------------------------------------------------

Q.3 (12 Marks) – Attempt ANY ONE OPTION

- Two options: Option 1 and Option 2
- Each option contains two questions (6 marks each)

RULES:
- COs can be mixed within an option
- Both options must have SAME set of COs

--------------------------------------------------

MANDATORY REQUIREMENTS
Each question must include:
- Course Outcome (CO)
- Bloom’s Level:
  Apply / Analyze / Evaluate

--------------------------------------------------

RESTRICTIONS
- No out-of-syllabus questions
- No purely theoretical questions
- No violation of CO rules
- No mismatch in Q.3 CO sets

--------------------------------------------------

SYSTEM WORKFLOW

1. User provides:
   - Subject
   - COs
   - Syllabus
   - Previous year papers

2. System generates structured prompt

3. LLM generates questions based on rules

4. Output is formatted into exam-ready paper

--------------------------------------------------

KEY FEATURES
- Strict CO-based mapping
- Syllabus-bound questions
- Numerical and problem-solving focus
- Uses previous year patterns
- Ready-to-use exam format

--------------------------------------------------

USAGE (Python)

result = chain.invoke({
    "SUBJECT": SUBJECT,
    "COs": COs,
    "syllabus": syllabus,
    "previous_year_papers": previous_year_papers,
    "format_instructions": format_instructions
})

--------------------------------------------------

OUTPUT
- Structured question paper
- Q.1, Q.2, Q.3 clearly labeled
- Marks distribution included
- CO and Bloom’s level mentioned

--------------------------------------------------

FUTURE ENHANCEMENTS
- Answer key generation
- Difficulty control
- Multi-subject support
- PDF/Word export

--------------------------------------------------

TARGET USERS
- Faculty members
- Paper setters
- Universities
- EdTech platforms

--------------------------------------------------

SUMMARY
This system generates high-quality, structured, and CO-based question papers
using user inputs, ensuring accuracy, consistency, and reduced manual effort.

--------------------------------------------------
```
