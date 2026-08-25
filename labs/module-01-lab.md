# Module 01 — Lab

## Student Assignment Submission System

### Scenario

A small university wants to automate its student assignment submission system.

Students currently submit assignments manually through email. The university wants a simple system where students can submit an assignment electronically.

The system should:

Identify the student.
Identify the course and assignment.
Record when the assignment was submitted.
Determine whether the submission meets the basic submission rules.
Store the submission information.
Provide useful information to the instructor.

You are the programmer responsible for designing the solution before writing any code.

Lab Objective

Design the logical solution to this problem using the concepts learned in Module 01:

Problem solving
Algorithms
Programs
Programming languages
Inputs
Processing
Outputs
Storage
Step-by-step execution

Do not write Python code.

### Part 1 — Problem

The university currently manages student assignment submissions manually through email. This process can make it difficult to consistently organize, record, track, and manage submitted assignments.

The problem is to design an electronic system that allows students to submit assignments and enables the university to reliably record, process, store, and provide information about those submissions to students and instructors.

### Part 2 — Inputs

The system would need to receive or access information such as:

- Student ID or other student identification.
- Course ID.
- Assignment ID.
- The assignment file or files being submitted.
- Submission timestamp.
- Assignment requirements and submission rules.
- Assignment deadline.
- Allowed file types or formats.
- Other relevant information required to validate the submission.

### Part 3 — Processing

When a student submits an assignment, the system would perform several processing steps:

- Validate that the student ID corresponds to a valid student.
- Verify that the student is enrolled in the specified course.
- Verify that the assignment belongs to the specified course.
- Compare the submission timestamp with the assignment deadline to determine whether the submission is on time or late.
- Validate that the submitted file or files comply with the assignment requirements.
- Check applicable rules such as allowed file formats, file size, number of files, and other submission requirements.
- Determine the final status of the submission.
- Store or update the submission record in the system.
- Trigger the appropriate notifications based on the submission result.

### Part 4 — Outputs

The system would produce several outputs after processing a submission:

- A confirmation notification to the student indicating whether the submission was successfully received and its current status.
- A notification to the instructor indicating that the student submitted the assignment.
- A submission record containing relevant information such as the student ID, course ID, assignment ID, submission timestamp, and submission status.
- Information made available to the university system for tracking and managing the submission.
- If applicable, a status such as received, late, or rejected because the submission did not meet the required rules.

### Part 5 — Design the Algorithm

1. Receive the student's assignment submission and the associated information.
2. Validate the student's identity and verify that the student is enrolled in the specified course.
3. Verify that the assignment belongs to the specified course.
4. Compare the submission timestamp with the assignment deadline and determine whether the submission is on time or late.
5. Validate that the submitted file or files comply with the assignment's submission requirements.
6. Determine the final status of the submission.
7. Store the submission and its relevant information in the system.
8. Notify the student and instructor about the submission and its status.

### Part 6 — Programming Connection

Python would be the programming language used to implement the algorithm as an executable program. The logical steps defined in the algorithm would be translated into Python instructions and structures that the computer can execute.

For a real assignment submission system, Python could be used to implement the application's processing and business logic. A user interface could collect the student's submission information, the Python program could receive and validate the inputs, process the submission according to the algorithm, store the resulting information, and produce outputs such as submission confirmations and notifications.

A development environment such as VS Code could be used to write and manage the Python code, but VS Code itself is not the programming language or the program executing the algorithm.