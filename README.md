# OOP-Final_Project
Build and Publish a Python Library for Data Science

🎯 Objective Create and publish a Python library (package) that applies Object-Oriented Programming (OOP) principles to a data science application. You will collaborate as a group, manage your project on GitHub, and publish your package to PyPI, complete with documentation.

# Folders
- Fanal PRoject/ — chosen library implementation
- Report/ — weekly narrative reports and peer evaluations
- Documentation / — UML, screenshots, and design materials

# Members — Role — Task

| Member      | Role                                | Main Responsibilities                                                                                                                                         |
| ----------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Odchigue, Jave Melchor P.**    | **Leader / Project Coordinator**    | Leads project planning and coordination, manages GitHub repository and branches, compiles weekly reports, and ensures all deliverables are submitted on time. |
| **Ruiz, Rynzo Rapheal R.**   | **Lead Developer**                  | Develops main modules and core OOP classes, implements key features (`inspect()`, `diagnose()`, `treat()`), and maintains clean, efficient code.              |
| **Angni, Sodais M.**  | **Assistant Developer / Debugger**  | Supports coding tasks, focuses on method testing and debugging, and ensures that modules work together without errors.                                        |
| **Magtrayo, Harold Hope**  | **Documentation & Testing Officer** | Writes documentation (`README.md`, docstrings), conducts testing of features, and assists in creating the demo notebook.                                      |
| **Padillo, Reymart** | **Design & Research Analyst**       | Creates UML/class diagrams, researches data cleaning techniques, and helps design the logic for inspections and reports.                                      |

# PROJECT OVERVIEW: DataMedic
Concept Summary

DataMedic is a Python library that acts as a data health assistant — it inspects, diagnoses, and treats common data quality issues such as missing values, duplicates, and outliers.

Instead of directly applying cleaning functions, DataMedic first analyzes the dataset’s condition, gives recommendations, and then applies fixes with the user’s confirmation.

It aims to make data preparation easier for beginners in data science by offering:

- automatic detection of issues,
- simple function calls, and
- clear, human-readable reports.

# CORE FEATURES (Planned)

| Feature               | Description                                                        | Example                 |
| --------------------- | ------------------------------------------------------------------ | ----------------------- |
| 🧾 **inspect()**      | Analyze dataset for common issues and summarize findings           | `doctor.inspect()`      |
| 💡 **diagnose()**     | Suggest possible cleaning actions based on inspection              | `doctor.diagnose()`     |
| 🧹 **treat()**        | Automatically fix detected issues (missing values, outliers, etc.) | `doctor.treat()`        |
| 📊 **report()**       | Generate a summary of all cleaning actions taken                   | `doctor.report()`       |
| 📈 **health_score()** | Provide a data quality score from 0–100                            | `doctor.health_score()` |

# DataMedic – Feature-Integrated Class Design
Main Classes

1. DataInspector → handles 🧾 inspect()

- Focus: Scanning and identifying dataset problems (missing values, duplicates, outliers, etc.)

2. DataDoctor → handles 💡 diagnose() and 🧹 treat()

- Focus: Suggests and applies fixes based on inspection.

3. ReportGenerator → handles 📊 report() and 📈 health_score()

- Focus: Summarizes actions and evaluates data quality.


