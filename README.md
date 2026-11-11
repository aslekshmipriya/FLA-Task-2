# FLA Task 2 – Designing Validation Automata

<p align="center">
  <b>Finite Automata-Based Validation System Using Python</b>
</p>

## 📌 Project Overview

This project demonstrates the practical application of **Deterministic Finite Automata (DFA)** for real-world input validation problems.

Three validation systems are designed and implemented using Python. Each system uses states, input alphabets, transition functions, and accepting states to determine whether a given input satisfies the defined validation rules.

## 🎯 Objectives

- Understand the concepts of Deterministic Finite Automata.
- Design DFA models for real-world validation problems.
- Identify states, input alphabets, and accepting states.
- Implement DFA transition functions using Python.
- Test automata using valid and invalid input strings.
- Verify the correctness of the implementations through automated testing.

## 🧩 Case Studies

### 1. ATM PIN Verification

**Description:** Validates ATM PIN inputs based on the required length and numeric-only input conditions.

**DFA State Diagram**

![ATM PIN DFA](ATM_PIN_DFA.png)

### 2. Password Validation

**Description:** Validates passwords according to the password requirements defined in the implementation.

**DFA State Diagram**

![Password DFA](Password_DFA.png)

### 3. Email Format Validation

**Description:** Validates email inputs using finite automata based on the format conditions implemented in the project.

**DFA State Diagram**

![Email DFA](Email_DFA.png)

## ⚙️ Technologies Used

- Python
- Google Colab
- Jupyter Notebook
- Deterministic Finite Automata
- Pytest

## 🏗️ Implementation

The project follows these steps:

1. Define the validation requirements.
2. Construct the DFA for each validation problem.
3. Define the states and transition functions.
4. Implement the automata using Python.
5. Process input strings and determine acceptance or rejection.
6. Perform testing with different input examples.

## 🧪 Testing and Validation

Each case study is tested using valid and invalid inputs.

Testing includes:
- Valid input verification.
- Invalid input verification.
- Boundary conditions.
- Automated test execution.

## 📂 Repository Structure

```text
FLA-Task-2/
│
├── FLA_Task_2.ipynb
├── ATM_PIN.png
├── Password_Vallidation.png
├── Email_Vallidation.png
└── README.md
```

## ▶️ Execution

1. Open `FLA_Task_2.ipynb` in Google Colab.
2. Execute the notebook cells in sequence.
3. Observe the validation results.
4. Run the automated tests to verify the implementations.

## 📌 Conclusion

This project demonstrates how Deterministic Finite Automata can be applied to practical input validation problems. The three case studies connect theoretical concepts of Formal Language and Automata with Python-based implementation and testing.
