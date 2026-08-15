# Setup guide: before Lesson 1

## 1. Do you have Python in Excel?
Open Excel, click the **Formulas** tab, and look for a **Python** group (Insert Python, Initialization, Python Editor). If it's there, you're set. If not, work through the checklist below.

| Requirement | What to check |
|---|---|
| Subscription | Microsoft 365 (Business/Enterprise, or Family/Personal). Python in Excel is not in perpetual-licence Excel (2019/2021/2024). |
| Excel build | Windows: Current Channel or Monthly Enterprise Channel version 2408+; Semi-Annual Enterprise Channel 2502+. Also available in Excel for the web. Mac support is rolling out: check the availability page. |
| Compute | Standard compute is included; a paid **Python in Excel add-on** buys premium (faster) compute. You do not need the add-on for this course. |
| Network | Code runs in Microsoft's cloud, not on your PC. Corporate tenants can disable it: if you see the ribbon group but formulas return errors, ask IT. |

Official references: [Introduction to Python in Excel](https://support.microsoft.com/en-us/excel/python/introduction-to-python-in-excel) · [Get started](https://support.microsoft.com/en-us/office/get-started-with-python-in-excel-a33fbcbe-065b-41d3-82cf-23d05397f53d) · [Add-on licensing FAQ](https://support.microsoft.com/en-us/office/python-in-excel-add-on-licensing-faq-6d90fc0e-f080-4799-9d28-9754c77fb308)

## 2. Three ways to start a Python cell
1. Formulas → **Insert Python**
2. Type `=PY(` in any cell
3. **Ctrl+Alt+Shift+P**

Press **Ctrl+Enter** to run (plain Enter runs too but moves selection). **Esc** backs out of a half-typed cell.

## 3. Shortcuts you'll use constantly
| Keys | Does |
|---|---|
| Ctrl+Alt+Shift+P | Insert Python cell |
| Ctrl+Enter | Commit/run |
| Ctrl+Alt+Shift+M | Toggle Python Object ↔ Excel Value (spill DataFrames, render charts) |
| Ctrl+Alt+Shift+F | Toggle full/partial calc mode |

Full list: [Python in Excel keyboard shortcuts](https://support.microsoft.com/en-us/office/python-in-excel-keyboard-shortcuts-62e3e455-c233-443d-87bb-d7456988c904)

## 4. What's already imported (don't `import pandas` again)
Formulas → Python → **Initialization** shows the defaults: `numpy as np`, `pandas as pd`, `matplotlib.pyplot as plt`, `seaborn as sns`, `statsmodels as sm`. Everything else (SciPy, scikit-learn, NLTK…) is installed but must be imported in your cell. Which libraries exist: [Open-source libraries and Python in Excel](https://support.microsoft.com/en-us/office/open-source-libraries-and-python-in-excel-c817c897-41db-40a1-b9f3-d5ffe6d1bf3e) · [Initialization settings](https://support.microsoft.com/en-us/office/python-in-excel-initialization-settings-ab0868da-cdfd-4f2d-a61e-1a242a97ea39)

## 5. Two habits that prevent 80% of the confusion
- **Put data in an Excel Table** (Ctrl+T) before pointing Python at it. `xl("table_name[#All]", headers=True)` is the pattern for the whole course.
- **Python runs top-to-bottom, left-to-right** across the workbook. A cell can only see objects defined above/left of it. If you get `#PYTHON!` when referencing a variable, that's usually why.

## 6. When something goes wrong
[Troubleshoot Python in Excel errors](https://support.microsoft.com/en-us/office/troubleshoot-python-in-excel-errors-7736520d-47ef-43a8-b640-d826afb63249) covers `#PYTHON!`, `#BUSY!`, `#CONNECT!`, `#BLOCKED!`, `#TIMEOUT!`. The [Python Editor pane](https://support.microsoft.com/en-us/office/python-in-excel-code-editor-b74ac883-3bc1-4253-90cb-c1a09887acc1) shows the full error text and traceback.

## 7. Course files
Download the course zip and keep the folder structure. Every module has a `starter.xlsx` (open this) and a `solution.xlsx` (finished state). Never overwrite the starter: Save As with your name.
