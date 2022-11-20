<!-- omit in toc -->
# Table of Content
- [Project Description](#project-description)
- [Source](#source)
- [Structure](#structure)
- [To start](#to-start)

# Project Description
> This is a project to be done for PDAS CA1 which test the basic competency in writing Python program and Python packages such as Python Numpy and Matplotlib for Data Analysis and Visualization

The objective of the project is:
```md
Are the more popular courses in ITE, Poly, UNI correlated with better employment opportunities?
```
[^1]

[^1]: The data for 2019 from the 2017-2019 employment is slightly different from the 2019-2021 employment data set. This is likely due to the statistical noise generated to provide privacy to graduates.

Notes: _Courses are grouped into course clusters based on the Graduate Employment Surver provided by MOE. These courses are:_

> Fresh Graduates
1. Arts, Design & Media
2. Built Environment
3. Business
4. Dentistry
5. Education (NIE)
6. Engineering
7. Health Sciences
8. Humanities & Social Sciences
9. Information & Digital Technologies
10. Music
11. Sciences
12. Yale-NUS

> Follow up Graduates
1. Architecture
2. Biomedical Sciences and Chinese Medicine
3. Law
4. Medicine
5. Pharmacy

# Source
|       Dataset name   | Link |
|----------------------|------|
| Employment (2017-2019) | https://www.moe.gov.sg/-/media/files/post-secondary/joint-web-publication-6-aus-ges-2019.pdf?la=en&hash=DE36C0FF72D7FB96B7B29B96DBC8D67D03A7B3C3|
| Employment (2019-2021) | https://www.moe.gov.sg/-/media/files/post-secondary/ges-2021/joint-web-publication-4-aus-ges2021.ashx?la=en&hash=2CB3200A8C1B7D935D0253470072DE82DDF49B42
| Intake by course (UNI) | https://data.gov.sg/dataset/universities-intake-enrolment-and-graduates-by-course|
| Intake by course (Poly) | https://data.gov.sg/dataset/polytechnics-intake-enrolment-and-graduates-by-course|
| Intake by course (ITE) | https://data.gov.sg/dataset/intake-of-students-trainees-under-the-full-time-institutional-training-and-traineeship-programmes|

_The first two datasets are from MOE while the last three datasets are from Data.gov.sg_

# Structure
File structure:
- datasets_cleaned => contains the cleaned csv files
- datasets_src => contains the csv files for all the original uncleaned datasets
- datasets.zip => contains the backup zip file for the datasets
- clean.ipynb => to clean the data from datasets_stc 
- main.ipynb => where all the code will be
- README.md => contains all the source for the datasets

# To start

1. Delete the entire contents of the directory 'datasets_cleaned'. To clean the data, run the cells inside 'clean.ipynb' (This will recreate the contents of 'datasets_cleaned')
2. Run the cells inside 'main.ipynb' to see the analysis and visualization performed
3. For a summary head to the [powerpoint slides](https://google.com)