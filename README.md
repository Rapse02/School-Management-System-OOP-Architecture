# School Management System (OOP Architecture)  

## Project Overview
This repository contains a School Management System built entirely in Python. The primary objective of this project is to demonstrate strong fundamentals in **Object-Oriented Programming (OOP)** and basic software architecture. 

The system models the interactions between core educational entities (Students, Teachers, and Subjects) through structured classes and logical hierarchies. *(Note: Code variables and internal documentation are written in Spanish as originally designed).*

## Tech Stack & Concepts
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Core Concepts Applied:** Object-Oriented Programming, Data Encapsulation, Class Inheritance.

## Software Architecture & Key Features
1. **Inheritance & Class Hierarchy:**
   * Designed a base parent class `Persona` (Person) to handle universal attributes.
   * Created specialized child classes `Alumno` (Student) and `Profesor` (Teacher) that inherit from `Persona`, optimizing code reuse.
2. **Data Encapsulation:**
   * Implemented private attributes (e.g., `__nombre`, `__edad`) to protect data integrity within the objects.
   * Developed getter and setter methods to control how object data is accessed and modified.
3. **Object Interaction:**
   * Built a `Materia` (Subject) class that establishes relationships between Teacher objects and Student records.
   * Utilized Python lists as basic data structures to store and manage multiple instances of students, teachers, and subjects in memory.

## 📂 Repository Structure
* `Sistema_Control_Escolar.ipynb`: Main notebook containing the class definitions, object modeling, and execution logic.

---
*Created by Jose Emmanuel Mendoza Luna - Data Science Engineering Student*
