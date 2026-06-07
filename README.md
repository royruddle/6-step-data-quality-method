# 6-step-data-quality-method ![DOI: 10.5281/zenodo.20578862](https://github.com/royruddle/6-step-data-quality-method/blob/main/images/zenodo.20578862.svg)
Consider these three facts:
1. There are more than 100 ways in which data can be of “low”' quality
2. Data preparation (which includes data quality checks) often takes more than half of a data science project’s time
3. Few data scientists or analysts have had much training in data quality.

This practical 6-step method enables you to investigate data quality efficiently and rigorously. It will:
- Save you time, by defining a set of tasks and giving you questions to ask about your data
- Reduce cost by avoiding re-work
- Improve your results, by enabling you to
  - Correct any mis-held assumptions
  - Understand any limitations of your data
  - Improve your data so it is a more valuable asset

The original version of this method was published as A Practical Guide to Characterising Data and Investigating Data Quality (2024) by Roy Ruddle, James Cheshire and Sarah Johansson Fernstad (https://doi.org/10.5518/1481), under the CC BY 4.0 licence.

This github repository contains the most up to date version of the method, which is now called *The 6-Step Data Quality Method*. It has been improved with input from practitioners and comments from participants in the training courses we run.

&copy; 2026. This work is openly licensed via CC BY 4.0.

## The 6 steps
The method is divided into six steps ([see Overview on YouTube](https://www.youtube.com/watch?v=qymfk1inGVg)) that will help you to identify whether there are any issues with your data, and remedy them as early as possible. The steps are:
1.	Is anything obviously wrong (look at your data and any documentation)? [Step 1 on YouTube](https://www.youtube.com/watch?v=m7zjU5ojoBo).
2.	Watch out for special values (e.g., indicating a missing or invalid value; you will need to flag them as missing, etc. before proceeding to the next step). [Step 2 on YouTube](https://www.youtube.com/watch?v=ibY5oAvSC-w).
3.	Is any data missing (is it safe to proceed or do you need more data?)? [Step 3 on YouTube](https://www.youtube.com/watch?v=uHSxjYqwY_Q).
4.	Check each variable (is it what you expect?). [Step 4 on YouTube](https://www.youtube.com/watch?v=QRo_kHNol6A).
5.	Check combinations of variables (do they violate any of your assumptions or business rules?). [Step 5 on YouTube](https://www.youtube.com/watch?v=BIrYUAYY7K4).
6.	Profile the cleaned data. [Step 6 on YouTube](https://www.youtube.com/watch?v=XYL80v2_vjc).

## Tasks
You may approach investigations from two complementary perspectives: establishing the characteristics of your data and assessing its quality. For example, you may wish to determine how the number of records varies with time (data characterisation) or check whether records are missing from a given time-period (data quality). Similarly, you may calculate the distribution of data (characterisation) or determine if outlying values are implausibly high/low (quality).

The 6-step method contains 69 tasks, which will enable you to perform those investigations efficiently and rigorously. The tasks are articulated as questions for you to answer about your data:
- Document containing the [Tasks and Questions](https://github.com/royruddle/6-step-data-quality-method/blob/main/downloads/tasks_and_questions.pdf).
- Checklist of the the tasks for each step (Excel and OpenDocument Spreadsheetformats). To download them, go to [downloads](https://github.com/royruddle/6-step-data-quality-method/blob/main/downloads), click on the file and then click "view raw".

## Implementation
You can use any software to perform the 6-step method (e.g., Python, R, SQL, data profiling tools or even spreadsheets). The Python [vizdataquality](https://pypi.org/project/vizdataquality/) package contains an example implementation, with the six Jupyter Notebooks (one for each step) that were used in the above YouTube videos.
