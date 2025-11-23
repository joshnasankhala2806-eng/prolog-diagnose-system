# Disease Diagnosis Expert System (Prolog)

## 📌 Project Overview
This project is a simple **Expert System** built using *Prolog (SWI-Prolog / SWISH)*.  
The system asks the user for symptoms and provides a possible disease based on the rules defined in the knowledge base.

This project is created as part of the *Fundamentals of AI & ML* flipped course.

## 🧠 Problem Statement
Many students and users struggle to identify possible illnesses from basic symptoms.  
This expert system provides a basic symptom-checker using logic programming (Prolog).

## 🎯 Objectives
- Build a rule-based medical diagnosis system using Prolog.  
- Demonstrate knowledge representation using facts and rules.  
- Show simple inference for illness suggestion.


## 🧩 Features
- Accepts two symptoms as input.  
- Suggests a possible disease that matches both symptoms.  
- Easy to extend with more diseases and symptoms.  
- Runs on SWISH or SWI-Prolog.


## 🛠️ Technologies Used
- **SWI-Prolog / SWISH**  
- Prolog facts and rules (logic programming)


## ▶️ How to Run
1. Open **SWISH** (https://swish.swi-prolog.org) or open **SWI-Prolog** on your system.  
2. Load the file `diagnose.pl` (copy the file content into SWISH or load in SWI-Prolog).  
3. Run the query:
   diagnose
4. enter the two symptoms when asked.
```prolog
?- diagnose.
