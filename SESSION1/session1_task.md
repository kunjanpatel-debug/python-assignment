# Python Assignment - Session 1: Development Environment Setup & Basics

This document provides a comprehensive log of the completed tasks for Session 1, including the required Python scripts, notebook documentation, and execution steps.

---

## Task 1: Anaconda Installation & Jupyter Notebook Launch

### Execution Steps:
1. **Download & Install:** Downloaded the official Anaconda Individual Edition installer for Windows from the Anaconda website and successfully went through the setup wizard.
2. **Launch Navigator:** Opened the **Anaconda Navigator** desktop application from the Windows Start Menu.
3. **Launch Jupyter:** Clicked the **Launch** button under the Jupyter Notebook application module inside the Navigator dashboard, which initialized the local notebook server inside the web browser at `localhost:8888`.

---

## Task 2: Jupyter Notebook Creation (`analytics_intro.ipynb`)

A fresh notebook was created and saved as `analytics_intro.ipynb` inside the working directory workspace.

### Notebook Cell Code:
```python
# Printing name and favorite application profile
print("Name: Kunjan Patel")
print("Favorite Application: Zomato")
```

### Expected Execution Output:
```text
Name: Kunjan Patel
Favorite Application: Zomato
```

---

## Task 3: Independent Python Script Execution (`hello_app.py`)

A separate, standalone Python file named `hello_app.py` was created using Visual Studio Code (VS Code) to test external terminal executions.

### Script Source Code (`hello_app.py`):
```python
# Standalone execution test script
print('Welcome to Data Analytics with Python!')
```

### Terminal Execution Command:
To run this file from the system command prompt or integrated terminal window, the following command was executed:
```bash
python hello_app.py
```

### Terminal Output:
```text
Welcome to Data Analytics with Python!
```

---

## Task 4: Dynamic Year Retrieval via Datetime Module

A new cell block was added inside `analytics_intro.ipynb` to dynamically extract system-level time metrics.

### Notebook Cell Code:
```python
import datetime

# Fetching and displaying the current system calendar year
current_year = datetime.datetime.now().year
print("Current Year:", current_year)
```

### Expected Execution Output:
```text
Current Year: 2026
```

---
*End of Session 1 Log.*
