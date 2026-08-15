# Session 3: Python in Excel: From trendline to real forecast

45 minutes. A statistical test, a regression, and a seasonal forecast, and how to tell if they're any good.

| Time | Part | Steps |
|---|---|---|
| 0:00 | Welcome, what we'll do, housekeeping (4 min) | recorded; files at Gumroad; questions in chat |
| 0:04 | Is the difference real? One t-test (8 min) | 1.1 Describe mpg by origin; 1.2 The t-test, with results in the grid |
| 0:12 | From trendline to a model you can read (11 min) | 2.1 Load the penguins and drop incomplete rows; 2.2 Look first: regplot; 2.3 Fit the line and read the coefficient table |
| 0:23 | A forecast you can see inside (13 min) | 3.1 Make the date the index; 3.2 Decompose: trend, season, residual; 3.3 Holt-Winters: fit and forecast 24 months |
| 0:36 | What it can't do (yet), recap, the book, next session, Q&A (8 min) | close |
| 0:44 | Buffer / extra Q&A (1 min) | |
| 0:45 | End | |

Pacing rule: every cell is typed together, budget 3 to 4 minutes each including the run and the look. If you run over, drop the last cell of the current part, never the close.

## What it can't do (say this out loud)
- A statistical test does not fix bad data: wrong groups, biased samples or typos give you a confident p-value on the wrong question.
- Regression has assumptions: linearity, no wild outliers, predictors not too correlated. Check them before a real decision, not after.
- A forecast is only as good as its holdout check: no time-ordered train/test split and a baseline, no forecast you should trust.
- The airline series is really a little multiplicative: the swings widen as it grows. We stayed additive for readability; switch when your December spike keeps doubling.
- No ARIMA today, and no bootstrap, ANOVA, chi-square or logistic regression: they are all in the book, Chapters 5 to 7.

## Links
- Book: https://stringfestanalytics.com/pyxlda/
- Free sessions (recording + files): https://stringfestdata.gumroad.com/l/pxlaf
- Repo: https://github.com/stringfestdata/python-excel-analysts-free
- Events: https://stringfestanalytics.com/events
