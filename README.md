# COS 201 — Computer Programming I

## Student Details
- **Name:** Ughamadu Chimkamso
- **Matriculation Number:** 25/16264
- **Programme:** Software Engineering 
- **Course Code:** COS 201
- **Repository URL:** https://github.com/ughamaduchimkamso/cos201-programming-I.git

---

## Week 1: Introduction to Programming and Problem-Solving
### Objectives
- Define computer programming and algorithmic problem-solving.
- Understand the Input-Process-Output (IPO) model.
- Write pseudocode, algorithms, and draw flowcharts.
- Set up a Java practical workflow and Git version control.

### Files
- `week01/FirstProgram.java`: Introduces basic Java program structure and outputs course objectives and personal goals.

### How to Run
```bash
cd week01
javac FirstProgram.java
java FirstProgram
```

---

## Week 2: Development Environment and First Java Program
### Objectives
- Install and configure the Java Development Kit (JDK) and Visual Studio Code.
- Understand the distinction between JDK, JVM, and the Java compiler (`javac`).
- Learn Java syntax fundamentals, standard output statements (`print`, `println`), and comments.
- Establish Git version control and remote synchronization on GitHub.

### Files
- `week02/HelloWorld.java`: Introductory Java application demonstrating console output.
- `week02/StudentProfile.java`: Displays student academic profile, topic, and learning goals.

### How to Run
```bash
cd week02
javac HelloWorld.java
java HelloWorld

javac StudentProfile.java
java StudentProfile
```

---

## Week 3: Variables, Data Types, Expressions and Input/Output
### Objectives
- Declare, initialize, and update Java variables and constants using appropriate primitive and reference data types.
- Construct arithmetic, relational, and logical expressions with proper operator precedence.
- Read and process user input from the console using the `Scanner` class.
- Display formatted output using `System.out.print()`, `println()`, and `printf()`.
- Test and debug boundary conditions, such as division by zero and score range validation.

### Programs
1. `week03/SimpleCalculator.java`
   - Prompts the user for two numbers.
   - Calculates and prints sum, difference, product, and quotient (formatted to 2 decimal places).
   - Handles zero-division safety (`secondNumber != 0`).

2. `week03/AverageCalculator.java`
   - Prompts for a student's name and scores in three courses.
   - Computes total score and floating-point average (`total / 3.0`).
   - Validates that entered scores lie between 0 and 100.

3. `week03/ItemCost.java`
   - Prompts for an item name, integer quantity, and decimal unit price.
   - Computes total purchase cost and presents an itemized receipt summary.

### How to Run
```bash
cd week03

# Run SimpleCalculator
javac SimpleCalculator.java
java SimpleCalculator

# Run AverageCalculator
javac AverageCalculator.java
java AverageCalculator

# Run ItemCost
javac ItemCost.java
java ItemCost
```

### Testing
- **SimpleCalculator:** Verified with standard inputs (e.g. 20 and 4), floating numbers, and division by 0 (verifying graceful error message).
- **AverageCalculator:** Verified with decimal inputs (e.g. 70, 80, 90 giving total 240.00 and average 80.00) and out-of-bounds scores.
- **ItemCost:** Verified with integer quantities and decimal unit prices (e.g. 3 books at 1500 each resulting in 4500.00).
