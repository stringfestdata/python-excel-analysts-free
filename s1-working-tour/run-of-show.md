# Session 1: Python in Excel: A working tour for Excel analysts

45 minutes. Your first Python cell, your first DataFrame, and two things Excel couldn't do last year.

| Time | Part | Steps |
|---|---|---|
| 0:00 | Welcome, what we'll do, housekeeping (4 min) | recorded; files at Gumroad; questions in chat |
| 0:04 | Your first Python cell (7 min) | 1.1 Hello, world; 1.2 Reference the object from C3; 1.3 The ordering error |
| 0:11 | Your first DataFrame (14 min) | 2.1 Load a table into a DataFrame; 2.3 A bigger table: sales_df.head(); 2.4 Descriptive statistics in one line; 2.5 The PivotTable in one line |
| 0:25 | Two things Excel couldn't do last year (12 min) | 3.1 Small multiples in one line; 3.6 10,000 futures: a Monte Carlo profit histogram |
| 0:37 | What it can't do (yet), recap, the book, next session, Q&A (8 min) | close |
| 0:45 | End | |

Pacing rule: every cell is typed together, budget 3 to 4 minutes each including the run and the look. If you run over, drop the last cell of the current part, never the close.

## What it can't do (say this out loud)
- Charts are static pictures: no hover tooltips, no click to drill, but always live and linked to the source cell.
- Code runs in the Microsoft cloud, not on your PC: you need a connection, and the first run of a session takes a few seconds.
- No internet or API calls from a cell: pd.read_csv from a URL will not work; bring external data in with Power Query first.
- You need Microsoft 365 with Python in Excel switched on: look for the Python group on the Formulas tab.
- Cells run in reading order, top to bottom and left to right, so an object must be created above or left of where you use it.

## Links
- Book: https://stringfestanalytics.com/pyxlda/
- Free sessions (recording + files): https://stringfestdata.gumroad.com/l/pxlaf
- Repo: https://github.com/stringfestdata/python-excel-analysts-free
- Events: https://stringfestanalytics.com/events
