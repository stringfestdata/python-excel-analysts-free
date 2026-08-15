# Session 2: Python in Excel: Charts and exploration Excel can't do alone

45 minutes. Get a Python chart out of the cell, then make five more Excel can't.

| Time | Part | Steps |
|---|---|---|
| 0:00 | Welcome, what we'll do, housekeeping (4 min) | recorded; files at Gumroad; questions in chat |
| 0:04 | Your first seaborn chart, and getting it out of the cell (8 min) | 1.1 Load the table and draw a bar chart; 1.2 Title and axis labels |
| 0:12 | Charts Excel doesn't have (13 min) | 2.0 A histogram in one line; 2.2 Box plots by group; 2.3 Scatterplot with a colour for each group; 2.4 Correlation heatmap with the numbers on it |
| 0:25 | One grid of charts (6 min) | 2.5 Small multiples with FacetGrid |
| 0:31 | What it can't do (yet), recap, the book, next session, Q&A (8 min) | close |
| 0:39 | Buffer / extra Q&A (6 min) | |
| 0:45 | End | |

Pacing rule: every cell is typed together, budget 3 to 4 minutes each including the run and the look. If you run over, drop the last cell of the current part, never the close.

## What it can't do (say this out loud)
- Charts are static pictures: no hover tooltips, no click to drill, but always live and linked to the source cell.
- There is no refresh button on a picture: change the code or the data in the source cell and re-run; the reference image redraws.
- Heavy charts (pairplot, lmplot, a row by column FacetGrid) take a few seconds on standard compute; the cell shows #BUSY! while it renders.
- Formatting is code, not a GUI: no Chart Elements pane, no drag-to-resize handles; titles, labels and size are lines you type.
- Delete the source cell and the referenced picture goes blank; the picture is a view, not a copy.

## Links
- Book: https://stringfestanalytics.com/pyxlda/
- Free sessions (recording + files): https://stringfestdata.gumroad.com/l/pxlaf
- Repo: https://github.com/stringfestdata/python-excel-analysts-free
- Events: https://stringfestanalytics.com/events
