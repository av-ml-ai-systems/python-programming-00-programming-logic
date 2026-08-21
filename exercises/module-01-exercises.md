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

---

### Exercise 11

A computer executes instructions exactly as written. Explain why this characteristic makes algorithm design so important.

---

### Exercise 12

Why is programming considered a problem-solving discipline rather than simply writing code?

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

---

### Exercise 14

Imagine you are explaining programming to a new university student.

How would you describe the relationship between computers, programs, algorithms, and programming languages?

---

# Final Assessment

Answer the following question in a short essay (approximately one page).

**"Why are algorithms, rather than programming languages, considered the true foundation of programming?"**

Support your answer using concepts introduced throughout the module.

---

# Challenge Exercise (Optional)

Think of an everyday activity that you perform regularly.

Design a high-level algorithm that another person could follow without asking any additional questions.

After writing your algorithm, ask yourself:

> Could someone misunderstand any of the steps?

If the answer is yes, improve the algorithm until every instruction is precise and unambiguous.