# Module 02 — Mini Lab: Library Book Borrowing System

## Objective
Apply the four computational thinking techniques to analyze a real-world problem and design a logical solution before writing code.

## Scenario
A university library wants a simple system to manage book borrowing. Students should be able to request books, but the system must verify that the student is eligible to borrow and that the requested book is available.

The system should record successful loans and inform students when a request cannot be completed.

## Task 1 — Problem Analysis
Identify:
- The main problem.
- The relevant information.
- The system's requirements and constraints.
- The expected outcome.

## Task 2 — Decomposition
Break the problem into smaller tasks or components. Briefly explain the purpose of each.

## Task 3 — Pattern Recognition
Identify any repeated process or common workflow that could be handled consistently for every borrowing request.

## Task 4 — Abstraction
Identify the information the system must consider and give examples of details it can ignore when processing a borrowing request.

## Task 5 — Algorithm Design
Write a basic algorithm in plain English for processing a borrowing request.

Include:
- Checking student eligibility.
- Checking book availability.
- Handling rejected requests.
- Recording a successful loan.
- Confirming the result to the student.

Do not write Python code.

## Completion Criteria
Your solution should be logical, clear, and consistent with the stated requirements. Consider what happens when a check fails, and ensure that the system does not record a successful loan unless the required conditions are met.

# Module 02 — Mini Lab: Library Book Borrowing System



## Task 1 — Problem Analysis

- The Main Problem: Managing book borrowing efficiently by building a system that verifies student eligibility and book availability, records successful loans, and clearly informs students when a request cannot be completed.

- The Relevant Information: Student ID, student account status (e.g., active enrollment, unpaid fines, overdue books), Book ID/ISBN, copy availability count, and transaction dates.

- Requirements: Student verification, book inventory checks, loan transaction logging, inventory updating, and messaging for success or rejection.

- Constraints: Students cannot borrow if they are ineligible (fines/overdue books) or if the book is out of stock. Loans must not be recorded unless all conditions are met.

- Expected Outcome: A seamless borrowing process where eligible students successfully check out available books, inventory updates automatically, and ineligible requests are safely blocked with an explanation.



## Task 2 — Decomposition

- Student Eligibility Module: Verifies the student's identity and checks if their account is in good standing (no fines or overdue items).

- Book Availability Module: Checks the library inventory to see if a copy of the requested book is currently in stock.

- Transaction & Inventory Update Module: Records the successful loan (linking student and book) and decreases the available stock count by 1.

- Notification Module: Generates and delivers the final response (either a success confirmation with a due date or a clear rejection reason).



## Task 3 — Pattern Recognition

- The Pattern: Every single time a student requests a book—regardless of who the student is or what book they want—the exact same verification and transaction pipeline runs: Verify Student -> Check Book -> Update Record -> Notify.

- Workflow Consistency: Instead of writing custom logic for every individual book or student, you design a single standardized, repeatable workflow that handles all borrowing requests consistently.



## Task 4 — Abstraction

- Essential Information: Student ID, account standing (fines/active status), Book ID, available stock count, and due date.

- Ignored Details: The student's major, GPA, phone number, the physical color of the book, how many pages it has, or where the book is physically located on the library shelf.



## Task 5 — Algorithm Design

- Step 1 (Start): Receive the student's book borrowing request (containing Student ID and Book ID).

- Step 2 (Check Student Eligibility): Verify that the student is active and check if they have any unpaid fines or overdue books.

  - If ineligible: Display a rejection reason (e.g., "Account suspended due to unpaid fines") and Stop.

- Step 3 (Check Book Availability): Check the inventory to see if the requested book has at least one copy available.

  - If unavailable: Display a rejection reason (e.g., "Book is currently out of stock") and Stop.

- Step 4 (Record Successful Loan): Create a new loan record linking the Student ID and Book ID with the checkout date and due date. Reduce the book's available stock count by 1.

- Step 5 (Confirm Result): Display a success confirmation message to the student including the return due date.

- Step 6 (End): Complete the process.