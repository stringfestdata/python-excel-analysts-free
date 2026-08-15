# Session 4: Python in Excel: 10,000 what-ifs

45 minutes. Monte Carlo simulation, worksheet cells that drive Python, and comparing decisions on the same futures.

| Time | Part | Steps |
|---|---|---|
| 0:00 | Welcome, what we'll do, housekeeping (4 min) | recorded; files at Gumroad; questions in chat |
| 0:04 | 10,000 what-ifs: Monte Carlo in one cell (12 min) | 1.2 The profit model: demand in, profit out; 1.4 The whole distribution: a histogram with mean and break-even lines; 1.5 Any 'how often' question is one line |
| 0:16 | Python that a manager can use: input cells and dropdowns (9 min) | 2.1 A moving average over a noisy daily series; 2.2 Let a worksheet cell drive the window |
| 0:25 | Which decision? Percentiles and a comparison (9 min) | 3.3 Percentiles for planning; 3.4 Which decision? Compare two inventory levels |
| 0:34 | What it can't do (yet), recap, the book, next session, Q&A (8 min) | close |
| 0:42 | Buffer / extra Q&A (3 min) | |
| 0:45 | End | |

Pacing rule: every cell is typed together, budget 3 to 4 minutes each including the run and the look. If you run over, drop the last cell of the current part, never the close.

## What it can't do (say this out loud)
- A simulation is only as honest as its assumptions: normal demand with a mean of 1,000 and a swing of 200 is a guess you must own, and the distribution is the assumption.
- Input cells need Data Validation, or people type text, decimals and blanks into them and the Python cell errors.
- Dropdown-driven charts take helper tables, an XLOOKUP and a spilled list: today was one input cell; the full build is Chapter 10.
- The comparison used the mean only; a real decision also weighs the downside, which is why Chapter 8 compares percentiles and probability of loss.

## Links
- Book: https://stringfestanalytics.com/pyxlda/
- Free sessions (recording + files): https://stringfestdata.gumroad.com/l/pxlaf
- Repo: https://github.com/stringfestdata/python-excel-analysts-free
- Events: https://stringfestanalytics.com/events
