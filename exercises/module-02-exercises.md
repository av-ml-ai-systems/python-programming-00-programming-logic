# Module 02 — Computational Thinking: Exercises

## Exercise 1 — Understanding Computational Thinking
Define computational thinking in your own words. Explain how it differs from programming and why it is useful when solving problems.

Computational thinking is a systematic approach to solving problems by breaking them down, identifying relevant information and patterns, simplifying complexity, and designing logical solutions.
It does not mean thinking like a computer or simply writing code. It is a problem-solving process that can be applied before any programming language or technology is selected.

Computational thinking and programming are closely related, but they are not the same.

Computational thinking focuses on **understanding and solving the problem**.

Programming focuses on **implementing the solution using a programming language**.

A simplified relationship is:

Problem → Computational Thinking → Algorithm → Program

Computational thinking helps a programmer transform a real-world problem into a form that can be understood and eventually solved by a computer program.


## Exercise 2 — The Four Techniques
Briefly explain decomposition, pattern recognition, abstraction, and algorithmic thinking. Give a simple example of how each technique helps solve a problem.


- **Decomposition:** breaking a complex problem into smaller and more manageable parts.
- **Pattern Recognition:** identifying similarities, repetitions, or relationships that can help simplify a problem.
- **Abstraction:** focusing on the important information while ignoring unnecessary details.
- **Algorithmic Thinking:** developing a logical and ordered sequence of steps to solve a problem.

These techniques are complementary. A programmer may use several of them together when analyzing a problem and designing a solution.

1. Decomposition
(Breaking a complex problem into smaller and more manageable parts)

Programming Example: Building a Simple Calculator App

How it connects: Instead of trying to write one giant chunk of code for the whole app, you break it down into smaller, manageable functions: a function for addition (add()), one for subtraction (subtract()), one for multiplication, and one for division.

2. Pattern Recognition
(Identifying similarities, repetitions, or relationships that can help simplify a problem)

Programming Example: Using a for loop instead of repeating code

How it connects: If you notice you are writing almost identical lines of code over and over (like print(1), print(2), print(3)), you recognize that repetitive pattern and simplify it into a single loop (for i in range(1, 4): print(i)).

3. Abstraction
(Focusing on the important information while ignoring unnecessary details)

Programming Example: Creating a User Profile Object/Class

How it connects: When writing code for a user profile, you focus only on the important data needed by the program (like username and email), while ignoring unnecessary details (like their eye color, favorite food, or what shoes they are wearing).

4. Algorithmic Thinking
(Developing a logical and ordered sequence of steps to solve a problem)

Programming Example: Writing code to find the highest number in a list

How it connects: You write a step-by-step logical sequence: (1) Assume the first number is the largest, (2) Compare it to the next number in the list, (3) If the next number is larger, update your "largest" variable, and (4) Repeat until you reach the end of the list.


## Exercise 3 — Analyzing a Real-World Problem
A university wants to develop a system to manage student assignment submissions.

Identify:
- The Main Problem: Managing student assignment submissions efficiently by building a system that can reliably receive submissions, validate them, store records, and provide confirmation to students.
- The relevant information: Student IDs, course names, assignment due dates, submission timestamps, and uploaded files.
- The requirements and constraints.
  - Requirements: Secure student/professor logins, a file upload feature, automated submission timestamps, and a grading interface.
  - Constraints: Strict deadline cutoffs, allowed file formats (e.g., PDF), and file size limits.
- The expected outcome: A centralized online portal where students can easily submit coursework on time and professors can reliably receive, organize, and grade it.

## Exercise 4 — Applying Computational Thinking
Using the university assignment submission system from Exercise 3:
- Decompose the problem into smaller tasks.
- Identify any patterns or repeated processes.
- Explain which details are essential and which can be ignored.
- Describe the logical steps needed to solve the problem.

1. Decomposition (Breaking into smaller tasks)The system is broken down into separate, manageable modules:Student authentication (login).File uploading interface.Validation logic (checking deadlines and file formats).Data storage (saving files and transaction records).Confirmation notification (sending a receipt).
2. Pattern Recognition (Repeated processes)The Pattern: Every single time a student submits an assignment—whether it is Student A turning in a homework for Math 101 or Student B turning in an essay for History 202—the exact same sequence repeats: authenticate $\rightarrow$ upload $\rightarrow$ validate $\rightarrow$ store $\rightarrow$ confirm.Instead of writing custom code for every student or course, you design a single reusable pipeline that handles all submissions.

3. Abstraction (Essential vs. Ignored details)Essential Details: Student ID, course code, submission timestamp, file format, and file size.Ignored Details: The student's device type, operating system, browser window size, or the aesthetic styling of the text editor they used to write their paper.

4. Algorithmic Thinking (Logical steps to solve the problem)The step-by-step sequence for processing a submission:Verify that the student is logged in and authorized.Check if the current time is before the assignment deadline.Check if the uploaded file matches the allowed format (e.g., PDF) and size limit.If valid: Save the file to the database, record the exact timestamp, and display a success confirmation.If invalid: Reject the file and display an error message explaining why.

## Exercise 5 — Algorithm Design
Write a basic algorithm in plain English for the assignment submission system. Include the main steps from receiving a submission to providing confirmation.

Do not write Python code.

- Assignment Submission Algorithm
1. Start: Receive the student's submission request (containing the student ID, assignment ID, and uploaded file).

2. Authenticate: Check if the student is logged in and authorized to submit for that course.
    If unauthorized: Display an error message and Stop.

3. Check Deadline: Compare the current time to the assignment due date.

    If past the deadline: Display a "Submission closed" error message and Stop.

4. Validate File: Check the uploaded file's format (e.g., PDF) and size against allowed limits.

    If invalid (wrong format or too large): Display an error message explaining the issue and Stop.

5. Store Record: Save the uploaded file securely on the server and record a database entry containing the student ID, file path, and exact submission timestamp.

6. Confirm: Generate and display a success confirmation message with a receipt timestamp to the student.

7.  End.