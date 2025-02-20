# README: Big Data Analytics, Group Examination (Presentation, Code, Report)

*Fall Term 2024*

*Sandro Heiniger, PhD HSG*

*(University of St. Gallen)*


## Overview
This is your group's GitHub repository for the presentation and technical report. In this readme file, you will find all the instructions needed to work on your group project and the corresponding two examination parts. 

### Contents
- In the main directory of this repository you see this readme-file, a file called `disposition.Rmd`, and three directories: `code/`, `report/`, and `presentation/`.
- The file `disposition.Rmd` serves as a template for your project disposition.  To prepare your disposition, open the file in RStudio and follow the instructions (commented out) in each of the three sections. Push your final commits to the repository and send me the compiled version (PDF or HTML) document (sandro.heiniger@unisg.ch).
- Store all of your project-related code in `code/`. You are free to organize your code in sub-directories within the `code`-directory.
- In `report/` you will find a file called `report.Rmd`. This file serves as a template for the technical report (Examination Part I). You will be writing your report according to the structure pre-defined in this document. The report is organized into sections, each section addresses one component of the data pipeline underlying your project (and some additional topics). You will find instructions regarding how to write the report directly in this document (commented out). Once all the parts are in place, make sure that you can run the compilation of `report.Rmd` (with all the corresponding code parts) and generate the report (either as HTML or a PDF file). Note: the first thing I will do when grading your report is exactly this (I will open `report.Rmd` in RStudio and click on `Knit` to compile the report). Thus, make sure that it runs through without any errors (hint: do always work with relative paths!)
- Store your presentation slides in `presentation/`(Examination Part II). Before you present in class, please ensure that your presentation file(s) in this repository is/are up to date.


## General instructions and rules

### Rules
 - Only members of your team are allowed to contribute to your project.
 - All team members will get the same number of points and the same grade.
 - The presentation, slides, as well as your responses/expositions in the report must be in English.
 - Your team will be assessed based on the presentation and the corresponding slides (40% of grade), as well as on the technical report (60%) including all parts like R code, documentation of the code, etc. residing in this repository.
 - The slides/presentation will be assessed on the day of your team's presentation.
 - You are not obliged to use cloud computing resources, working on your local machine is perfectly fine. 
 - Choose your data and your system architecture such that you reach/surpass the limits of basic analytics approaches.
 
### Instructions
For all tasks of the group examination, observe the following instructions.
 - Use commenting (`#`) to document your R-code well, so others (including your lecturer in this course) can understand what the overall scripts are for and what the individual parts of a script are for.
 - Follow a common convention when writing R code. For example, follow the suggestions in [Google's R Style Guide](https://google.github.io/styleguide/Rguide.xml). You are free to follow other suggestions or define your style guide. Just make sure that all of your code follows the same style and commenting conventions.
 
### Deadlines
 - You may send me your project disposition until *03.11.2024, 23:59* to get a feedback.
 - Handing in of technical report is through your repository. Compile your report to a HTML or pdf file and push the final version. After *18.12.2024, 16:15* no additional changes to the repository will be possible. Thus, whatever is in your team's repository at this time/date, will be the basis for the evaluation of your team's technical report.
 - Presentations are held in the last lecture on *18.12.2024, 16:15-18:00*.
 
 
## Examination Criteria 

### Report
Points will be given for the following aspects of your code, expositions, and explanations.
Project setup (15%):
 - Are the research questions and objectives clear, coherent, and aligned with the dataset?
 - Is the preprocessing thorough and appropriate for the data?
 - Are the chosen methods suitable and well-explained?
Results and interpretation (15%)
 - Is the analysis accurate, and does it answer the research questions?
 - Are the results conceptually sound and clearly explained?
Code (15%)
 - Does the code run correctly and produce expected results?
 - Is the code well-organized and documented?
 - Does the code follow good practices (e.g., readability, efficiency)?
Big Data Considerations (45%)
 - Are big data challenges (e.g., volume, variety) addressed?
 - Are appropriate big data tools used and justified?
 - Is the code optimized for handling big data efficiently?
 - Does the analysis demonstrate scalability for large data?
Report (10%)
 - Is the report clear, well-structured, and does it effectively communicate findings?

### Presentation
 - Are the project objectives and research questions clearly stated and easy to understand?
 - Is the relevance of the research questions to the dataset explained?
 - Are the main results of the analysis clearly and concisely presented?
 - Are appropriate visual aids (e.g., graphs, charts) used to illustrate the results?
 - Are the big data challenges encountered during the project clearly identified and explained?
 - Are the solutions to these challenges well-justified, with a focus on the methods and tools used?
 - Is there a reflection on the effectiveness of the solutions? Are limitations or remaining challenges acknowledged?
 - Is the presentation well-structured and are the slides easy to follow?


## Tips for a successful examination
 - Working with real-life data can be tedious at times. Keep calm, plan, and organize your team well to meet unforeseen challenges with the data.
 - Make sure you commit your solutions to your team's GitHub repository step by step. Preferably, make sure the version residing in your team's repository is always the best current version of your report/slides/code. Do not wait for the last day to commit and push your solutions to the repository!


*GOOD LUCK!*


