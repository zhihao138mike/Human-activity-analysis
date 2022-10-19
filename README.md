# Personal Informatics

## Driving question

'Was I more active in the last 12 months than the 12 months before that?'

To explore this question, the measurment of activity for each person had to be determined. For the purpose of this research, activity over the course of a year was measured in two different ways: as the number of days with a daily step count over 10 000, and the number of weeks with a weekly step count over 35 000. From these, the calender years of 2019 and 2020 was compared for person 1 and person 2.

## Important Information

In the product notebook, the package named ‘pyecharts’ was used. 
In order to compile the code successfully, please install the pyecharts package first. The installation code is:

```pip install pyecharts```

Due to the limitation of the package, in order to see the visualized pictures successfully, please run the notebook in Jupyter Notebook environment, thank you!

## Table of contents

1. [Background](#background)
2. [Key files in repository](#key)
3. [Check list](#checklist)
4. [Contributions](#Contributions)
5. [Project owner(s) & contact details](#owner)
6. [License](#license)

## Background

### Data origin
Data provided by Professor Judy, the details are described in [License](#License) part

### Data definitions

A snippet from the dataset:

| Source | Date | Hour | Count |
|--------|------|------|-------|
| Person 1 iPhone SE  | 2014-12-07 | 8    | 13     |
| Person 1 iPhone SE  | 2014-12-07 | 8    | 13     |
| Person 1 iPhone SE  | 2014-12-07 | 8    | 1      |
| Person 1 iPhone SE  | 2014-12-07 | 8    | 9      |
| Person 1 iPhone SE  | 2014-12-07 | 8    | 15     |

Source: Which device is being used to record the number of steps at that time i.e. 'Person 1 iPhone SE', 'Person1 Apple Watch'.

Date: The date which the step count was recorded.

Hour: Hour interval in 24-hour time which the step count was recorded - from 0 (mininum) to 23 (maximum).

Count: The step count recorded for each time interval.


For person1, there are 183787 records, from 2014/12/7 (Y/M/D) to 2021/9/22. 

For person2, there are 486259 records, from 2014/11/29 to 2021/9/22.


## Key files in repository <a name="key"></a>
- [Product notebook](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/blob/master/Product%20Notebook.ipynb)
- [Process notebooks](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/tree/master/Process%20notebook)
- [Ethical analysis](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Ethical-Analysis)
- [Think aloud](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Think-aloud-and-Cognitive-Walkthrough)
- [Reflection](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Reflection-on-Group-Processes)

## Check list <a name="checklist"></a>
### Presentation
- [ ] **Explaining the driving question** 10pts 
- [ ] **statement of anticipated benefit** 10pts 
- [ ] **outline one key ethical aspect of the raw data** 10pts 
- [ ] **one highlight of the nature of the raw data** 10pts 
- [ ] **carefully selected highlights of results** 20pts 
- [ ] **outline one key ethical aspect of the meaningfulness of the results** 10pts 
- [ ] **careful and appropriate indication of uncertainty in the information presented** 10pts 
- [ ] **all information displays clear, with captions, labels, units** 10pts 
- [ ] **presentation quality** 10pts

### Report
- [ ] **README** 10pts 
- [ ] **ethical analysis** 10pts 
- [ ] **Use of Issues and wiki for group processes** 10pts 
- [ ] **Reflection on group processes** 10pts 
- [ ] **Report of Think-aloud and Cognitive Walkthrough and reflection of lessons learnt** 10pts 
#### Product notebook
- [ ] **literate programming** 10pts 
- [ ] **code quality overall, including raw data processing and data engineering and testing** 10pts 
- [ ] **presentation of information clear, consistent, easy to understand, careful accounting for uncertainty** 10pts 
- [ ] **presentation and organisation** 10pts
- [ ] **holistic assessment based on all the above and going beyond the core (e.g. considering additional datasets, additional driving questions)** 10pts
note that groups are only eligible for this part of the marks if each of the above criteria have earned a grade of D+ as described below.


## Contributions

- **Shengjie Yuan** 

Overview: Initial data exploration, data visualization(Bar charts), data analysis on different hour interval, README file etc.

Link to the [notebooks](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/tree/master/Process%20notebook/Samuel)

Link to the [Wiki](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Samuel%27s-Wiki)

Link to all [issues](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/issues/assigned/syua7793)



- **Iliana Young** 

Overview: Initial data exploration, code for dealing with outliers, code for calculating weekcount, writing ethical analysis and group reflection sections of the report. 

Link to the [notebooks](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/tree/master/Process%20notebook/Iliana)

Link to the [Wiki](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Iliana's-Wiki)

Link to all [issues](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/issues/assigned/iyou8314)


- **Angela Wong** 

Overview: Initial data exploration, comparative data visualisation (line charts), dealing with missing dates - finding them as well as inputing reasonable values (mean), ensuring clean datasets, maintaining literate programming in cleaning and aggregation section of product notebook.

Link to the [notebooks](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/tree/master/Process%20notebook/Angela)

Link to the [Wiki](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Angela's-Wiki)

Link to all [issues](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/issues/assigned/awon5389)

- **Zhihao Chen**

Overview: Initial data exploration, data visualization(Calendar), data analysis on daily interval, README file, Repository, WIKI page.


Link to the [notebooks](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/tree/master/Process%20notebook/Mike)

Link to the [Wiki](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/wiki/Mike's-Wiki)

Link to all [issues](https://github.sydney.edu.au/zche4995/2021-DATA3406-PRAC06-Group03/issues/assigned/zche4995)


## Project owner(s) & contact details <a name="owner"></a>

- **Shengjie Yuan** syuan7793@uni.sydney.edu.au
- **Iliana Young** iyou8314@uni.sydney.edu.au
- **Angela Wong** awon5389@uni.sydney.edu.au
- **Zhihao Chen** zche4995@uni.sydney.edu.au

## License

In this analysis, our group does **not** have the ownership of these datasets. 

The permission were given by Professor Judy(judy.kay@sydney.edu.au) to conduct the analysis as part of DATA3406
