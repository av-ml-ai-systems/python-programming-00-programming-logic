# Module 01 Exercises — What is Programming?

## Introduction

The purpose of these exercises is to reinforce the concepts introduced in Module 01. The exercises progress from basic conceptual recall to engineering-oriented reasoning. At this stage of the roadmap, no programming syntax is required. The emphasis is on computational thinking and understanding the fundamental principles of programming.

---

# Level 1 — Recall

### Exercise 1

- **Computer:** A computer is an electronic machine that receives data as input, processes the data according to a sequence of instructions, stores information in memory, and produces meaningful output. A computer system consists of two complementary components: hardware and software.

- **Hardware:** Hardware refers to the physical components of a computer, such as the processor, memory, storage devices, keyboard, mouse, and monitor. It provides the physical infrastructure required to execute software.

- **Software:** Software is the collection of programs and instructions that tell the hardware what to do. It enables a computer to perform specific tasks and solve problems.

- **Program:** A computer program is an ordered sequence of instructions that tells a computer how to perform a specific task. Programs transform inputs into useful outputs through a well-defined sequence of operations.

- **Programming:** Programming is the process of designing algorithms and translating them into instructions that a computer can execute. It is fundamentally a problem-solving discipline rather than simply writing code.

- **Algorithm:** An algorithm is a finite, ordered, and unambiguous sequence of steps designed to solve a problem or accomplish a specific task. Algorithms are independent of programming languages and can be expressed using natural language, pseudocode, flowcharts, or source code.

- **Programming Language:** A programming language is a formal language used to express algorithms in a way that computers can interpret and execute. Although programming languages have different syntax and features, they all serve the same fundamental purpose: communicating instructions to a computer.

---

### Exercise 2

The four basic stages of the information processing cycle performed by a computer are:

- **Input:** The computer receives data from a user, another program, or an external device.

- **Processing:** The computer performs operations on the received data according to the program's instructions.

- **Output:** The computer produces meaningful results that can be displayed, stored, or transmitted to another system.

- **Storage:** The computer saves data, programs, or results for future use.

Together, these four stages form the fundamental information processing cycle of every computer system.

---

### Exercise 3

A good algorithm should have the following characteristics:

- **Clearly defined inputs:** The algorithm should specify the information it requires to solve the problem.

- **Clearly defined outputs:** The algorithm should produce one or more well-defined results.

- **Well-ordered steps:** The instructions should follow a logical sequence.

- **Unambiguous instructions:** Every step should have only one possible interpretation.

- **Finite number of steps:** The algorithm must eventually terminate.

- **Correctness:** The algorithm should produce the expected result for valid inputs.

- **Efficiency:** The algorithm should solve the problem using an appropriate amount of time and computational resources.

---

# Level 2 — Understanding

### Exercise 4

Hardware and software are the two fundamental components of a computer system, but they serve different purposes.

- **Hardware** refers to the physical components of a computer that can be seen and touched, such as the CPU, memory (RAM), storage devices, keyboard, mouse, and monitor. It provides the physical resources required to perform computations.

- **Software** is the collection of programs and instructions that tell the hardware what to do. Unlike hardware, software is intangible—it cannot be touched, but it controls every operation performed by the computer.

Hardware and software are complementary and depend on each other. Without software, hardware is simply a collection of electronic components with no instructions to execute. Without hardware, software cannot be run. Together, they enable a computer to process information and solve problems.

---

### Exercise 5

Although the terms **algorithm** and **program** are closely related, they are not the same.

- An **algorithm** is a finite, ordered, and unambiguous sequence of steps designed to solve a problem or accomplish a specific task. Algorithms are independent of programming languages and can be expressed using natural language, pseudocode, flowcharts, or source code.

- A **computer program** is the implementation of an algorithm using a programming language so that a computer can execute it. A program consists of a sequence of instructions that transforms inputs into useful outputs.

In simple terms, an algorithm is the **solution or recipe**, while a program is the **actual implementation of that solution** that the computer can execute.

The same algorithm can be implemented as different programs using different programming languages, such as Python, Java, or C++.

---

### Exercise 6

The same algorithm can be implemented in different programming languages because an algorithm is independent of any particular language. An algorithm describes the logical sequence of steps required to solve a problem, while a programming language provides the syntax used to express those steps so that a computer can execute them.

For example, the same sorting algorithm can be implemented in Python, Java, C++, C#, or JavaScript. Although the syntax of each language is different, the underlying algorithm and its logic remain the same.

In other words, the algorithm defines **what** needs to be done, while the programming language defines **how** those instructions are written.

---

# Level 3 — Application

### Exercise 7

Write an algorithm (using natural language) for making a cup of coffee.

- Objective: Prepare one cup of coffee.

- Step 1: Gather the required ingredients and tools: coffee, water, a coffee maker, and a cup. Sugar is optional.

- Step 2: Add one tablespoon of coffee to the coffee maker.

- Step 3: Add one cup of water to the water reservoir.

- Step 4: Close the coffee maker and make sure it is properly assembled.

- Step 5: Connect the coffee maker to a power source and turn it on.

- Step 6: Wait until the brewing cycle is complete.

- Step 7: Place the cup under the coffee outlet and pour the freshly brewed coffee into the cup.

- Step 8: Add sugar if desired.

- Step 9: Serve the coffee.

---

### Exercise 8

Identify the inputs, processing, and outputs for an online shopping checkout process.

- Input: Cart items, including product IDs, quantities, selected options, customer information, shipping information, payment information, and applicable discounts or promotional codes.

- Processing: Validate the provided information, check product availability, calculate item prices, apply discounts and taxes, calculate shipping costs, authorize the payment, create the order, and update inventory and other system records.

- Output: An order confirmation containing the order number and delivery information, a receipt or invoice, a confirmation email, and a fulfillment request sent to the appropriate warehouse or fulfillment system.

```
Customer Input
      ↓
Validation
      ↓
Business Logic
      ↓
Payment Processing
      ↓
Database / Inventory Updates
      ↓
Outputs
 ┌────┼───────────────┐
 ↓    ↓               ↓
User  Email       Fulfillment
```

---

### Exercise 9

Describe a real-world task that could be automated with a computer program. Explain why programming would be useful.

- Task: Automatically send daily reminders by email or another notification system for routine tasks such as submitting a work log, watering plants, or taking scheduled medication.

- How the program works: The program runs according to a predefined schedule, such as every morning at 8:00 a.m. It checks whether the reminder should be sent based on predefined conditions, such as the day of the week, and then automatically sends the appropriate message.

- Why programming is useful: Programming automates repetitive tasks consistently and reduces the need for manual intervention. A program can run according to a predefined schedule, apply customized conditions, and be easily modified when requirements change.

---

# Level 4 — Analysis

### Exercise 10

Compare two different algorithms for solving the same everyday problem. Which one is more efficient? Justify your answer.

- Problem: Prepare a cup of coffee.

- Algorithm 1 — Coffee maker: Add the coffee and water, close the coffee maker, start the brewing cycle, wait until it is complete, pour the coffee into a cup, and add sugar if desired.

- Algorithm 2 — Pot and strainer: Add water and coffee to a pot, heat the mixture, monitor the brewing process, remove the pot from the heat, and manually strain the coffee before serving.

- Comparison: Both algorithms solve the same problem, but they use different procedures and require different amounts of manual intervention.

- More efficient algorithm: The coffee-maker algorithm is generally more efficient because the machine automates part of the brewing process, requires fewer manual operations, and makes the procedure simpler and more consistent.

- Justification: For this specific task, efficiency can be evaluated in terms of time, effort, and the amount of manual work required. The coffee maker performs part of the process automatically, making the overall procedure more efficient.

```
Same problem
     ↓
 ┌───────────┐
 ↓           ↓
Algorithm A  Algorithm B
 ↓           ↓
Compare their characteristics
     ↓
Determine which is preferable
     ↓
Justify the decision
```

---

### Exercise 11

A computer executes instructions exactly as written. Explain why this characteristic makes algorithm design so important.

- Why algorithm design is important: A computer follows the instructions provided by a program according to their defined rules and does not independently infer the programmer's intention. Therefore, the algorithm must provide clear, precise, ordered, and unambiguous instructions.

- Importance of correctness: If the algorithm contains an incorrect step or does not properly address the problem, the resulting program may produce an incorrect result.

- Importance of efficiency: Different algorithms can solve the same problem, but some may require more time, resources, or manual operations than others. Therefore, algorithm design also involves choosing an appropriate and efficient approach.

- Conclusion: Careful algorithm design is important because it provides the logical foundation for the program and determines how the computer will approach and solve the problem.

---

### Exercise 12

Why is programming considered a problem-solving discipline rather than simply writing code?

- Why programming is a problem-solving discipline: Programming is fundamentally about understanding a problem, designing a solution, and expressing that solution as instructions that a computer can execute.

- Role of algorithms: An algorithm defines the logical sequence of steps required to solve a problem or accomplish a task. It provides the reasoning behind the program before the solution is expressed in a specific programming language.

- Role of code: Code is the implementation of the algorithm in a programming language. Writing code is therefore one part of the programming process, rather than the entire process.

- Conclusion: Programming is considered a problem-solving discipline because its primary purpose is to develop correct and useful computational solutions. Code is the means used to communicate those solutions to a computer.

```
Real-world problem
       ↓
Understand requirements
       ↓
Define computational problem
       ↓
Design solution
       ↓
Choose appropriate approach
       ↓
Implement in Python
       ↓
Test / debug
       ↓
Evaluate
       ↓
Improve
```

---

# Level 5 — Engineering Thinking

### Exercise 13

A company wants to automate its employee attendance system.

Without writing code, describe how you would approach the problem as a software engineer.

Consider:

- Inputs
- Processing
- Outputs
- Possible challenges

- Approach: First, define the business requirements and map the attendance workflow before selecting the technology. A no-code or low-code platform such as Microsoft Power Automate could then be used to connect the attendance data source, company directory, database, notification system, and HR dashboard.

- Inputs: Employee ID, check-in and check-out events, timestamps, attendance location when applicable, employee information, work schedules, approved time off, and other relevant attendance rules.

- Processing: Validate employee information and attendance events, determine whether the employee is scheduled to work, compare attendance events against the applicable work rules, identify situations such as late arrivals, early departures, missing punches, or absences, and store or update the attendance records.

- Data storage: Store attendance events and processed attendance records in a central database or appropriate business data store.

- Outputs: Provide an attendance dashboard for managers and HR, generate notifications for relevant attendance events, and provide approved attendance information to payroll or other HR systems.

- Engineering considerations: The solution should address data accuracy, access permissions, privacy, error handling, auditability, integration with existing HR systems, and the ability to modify business rules when company policies change.

- Overall approach: Design the workflow and business rules first, then select appropriate no-code or low-code components to implement each part of the process without developing a traditional custom application.

```
Business Problem
      ↓
Requirements
      ↓
Inputs / Data Sources
      ↓
Business Rules
      ↓
Processing
      ↓
Data Storage
      ↓
Integrations
      ↓
Outputs
      ↓
Engineering Considerations
```
---

### Exercise 14

Imagine you are explaining programming to a new university student.

How would you describe the relationship between computers, programs, algorithms, and programming languages?

- Computer: A computer is a physical electronic system capable of executing instructions and processing data.

- Algorithm: An algorithm is an abstract, well-defined sequence of steps designed to solve a problem or accomplish a task. It describes the logic of the solution independently of a specific programming language.

- Programming language: A programming language is a formal system used by programmers to express algorithms and computational logic in a form that can be implemented and executed by a computer system.

- Program: A program is an implementation of an algorithm and other required logic written in a programming language. It contains instructions that can be processed and executed by a computer system.

- Relationship: An algorithm describes the solution conceptually. The programmer expresses that solution using a programming language, producing a program that can then be executed by a computer.

- Analogy: An algorithm is like a recipe describing how to prepare a meal. A programming language is the language used to write the recipe. The program is the actual written set of instructions, and the computer is the system that follows those instructions to perform the task.

```
                    PROBLEM
                       ↓
                 ┌───────────┐
                 │ Algorithm │
                 └───────────┘
                       ↓
             Express the algorithm
                       ↓
             ┌─────────────────┐
             │ Programming     │
             │ Language        │
             └─────────────────┘
                       ↓
                 ┌───────────┐
                 │  Program  │
                 └───────────┘
                       ↓
              Execution system
                       ↓
                 ┌───────────┐
                 │ Computer  │
                 └───────────┘
                       ↓
                    RESULT
```

---

# Final Assessment

## Final Challenge

A small company wants to automate its employee attendance process.

Employees check in using a computer or mobile device. The system must record the employee, the check-in event, and the relevant information. It should determine whether the attendance event follows the company's rules and provide useful information to managers.

Describe how you would approach this problem as a programmer.

Your answer should briefly explain:

- What the problem is.
- What the algorithm would represent.
- What the program would do.
- What programming language means in this context.
- What inputs the system would receive.
- What processing would occur.
- What outputs the system would produce.

Do not write code. Focus on the logic and explain the relationship between the problem, algorithm, program, and computer.

- Problem: Automate the company's employee attendance process so that employee attendance events can be recorded, validated, processed, stored, and made available to managers, HR, and other relevant systems.

- Algorithm: The algorithm would define the logical sequence of steps required to process an attendance event. It would receive the relevant information, validate the employee and attendance event, apply the company's attendance rules, determine the appropriate attendance status, and store or update the resulting attendance record.

- Program: The program would implement the algorithm using a programming language. It would contain the instructions necessary for the computer system to receive inputs, process the attendance information, interact with data storage, and produce the required outputs.

- Programming language: The programming language would provide the formal syntax and structures used by the programmer to express the algorithm and implement the attendance system.

- Inputs: Employee ID, check-in and check-out events, timestamps, attendance location when applicable, employee information, work schedules, approved time off, and other information required by the company's attendance rules.

- Processing: The system would validate the attendance information, verify that the employee is active and scheduled to work, apply the relevant attendance rules, identify conditions such as late arrivals or missing attendance events, and create or update the appropriate attendance records.

- Storage: Attendance events and processed attendance records would be stored in a central database or other appropriate data-storage system.

- Outputs: The system could provide an attendance dashboard for managers and HR, generate notifications for relevant attendance events, and provide approved attendance information to payroll or other HR systems.

- Overall relationship: The problem defines what needs to be solved. The algorithm describes the logical solution. The programming language is used to express that solution, producing a program that can be executed by a computer to process the inputs and produce the required outputs.