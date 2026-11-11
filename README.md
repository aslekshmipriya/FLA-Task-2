# FLA Task 2 – Designing Validation Automata

<p align="center">
  <b>Finite Automata-Based Validation System Using Python</b>
</p>

## 📌 Project Overview

This project demonstrates the application of **Deterministic Finite Automata (DFA)** in designing input validation systems for real-world scenarios.

Three different validation problems are modelled using finite automata. Each case study consists of a defined input language, DFA construction, state transitions, and testing with valid and invalid inputs.

The project demonstrates how theoretical concepts from Formal Language and Automata can be implemented practically using Python.

## 🎯 Objectives

- Understand the working principles of Deterministic Finite Automata.
- Design DFA models for different input validation problems.
- Identify states, input alphabets, start states, and accepting states.
- Implement state transitions using Python.
- Validate inputs through accepted and rejected test cases.
- Perform automated testing to verify the correctness of the implementations.

## 🧩 Case Studies

### 1. ATM PIN Verification

**Objective:** To validate ATM PIN inputs using a DFA.

The automaton checks whether the entered PIN satisfies the defined length and numeric input requirements.

**DFA State Diagram:**

![ATM PIN DFA](ATM_PIN_DFA.png)

### 2. Password Validation

**Objective:** To determine whether a password satisfies the validation conditions implemented in the project.

The DFA processes the input characters through a sequence of states and accepts or rejects the password based on the defined conditions.

**DFA State Diagram:**

![Password DFA](Password_DFA.png)

### 3. Email Format Validation

**Objective:** To validate email inputs using finite automata.

The automaton processes the input according to the email format rules defined in the implementation and determines whether the input is accepted or rejected.

**DFA State Diagram:**

![Email Validation DFA](Email_DFA.png)

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Implementation of DFA logic |
| Google Colab | Development and execution |
| Jupyter Notebook | Code organization |
| DFA | Formal modelling of validation systems |
| Pytest | Automated testing |

## 🏗️ Implementation Details

The project follows a structured implementation approach:

1. Define the validation requirements for each case study.
2. Identify the input alphabet and required DFA states.
3. Construct the transition functions.
4. Implement the automata using Python.
5. Process input strings and determine acceptance or rejection.
6. Execute test cases to verify the automata.
7. Perform automated testing to check implementation correctness.

## 🧪 Testing and Validation

The implementations are tested using both valid and invalid input examples.

Testing covers:

- Correctly formatted inputs.
- Inputs with missing or additional characters.
- Inputs containing invalid characters.
- Boundary and edge cases.

Automated testing is used to verify that the implemented DFAs produce the expected results.

## 📂 Repository Structure

```text
FLA-Task-2/
│
├── FLA_Task_2.ipynb
│
├── ATM_PIN.png
│
├── Password Validation.png
│
├── Email Validation.png
│
└── README.md
```

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Open the project folder.

3. Open `FLA_Task_2.ipynb` using Google Colab or Jupyter Notebook.

4. Execute the notebook cells in sequence.

5. Observe the DFA validation outputs and testing results.

## 📚 Academic Information

- **Institution:** SRM Institute of Science and Technology, Tiruchirappalli
- **Faculty:** Engineering and Technology
- **Department:** Artificial Intelligence and Machine Learning
- **Programme:** B.Tech – Artificial Intelligence and Machine Learning
- **Semester:** V
- **Course Code:** 21CSC301T
- **Course Title:** Formal Language and Automata
- **Assessment:** Continuous Learning Assessment – 2
- **Task:** Task 2 – Designing Validation Automata

## 👩‍💻 Conclusion

This project demonstrates the practical application of Deterministic Finite Automata in solving input validation problems. Through three case studies, it connects theoretical automata concepts with Python-based implementations and automated testing.
