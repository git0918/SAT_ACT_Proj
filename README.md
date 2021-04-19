# Project 1: SAT 2018 and SAT 2019 Analysis Overview

### Contents:
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

### Problem Statement

The goal of the project is to analyze nationwide SAT scores and identify which states have the lowest participation rates, Math, and EBRW scores. The US Department of Education can identify whether there is a correlation between SAT participation rate and test scores, and then determine if an additional grant allocation should be recommended for programs to improve overall student SAT performance.

### Executive Summary

This notebook begins by importing and cleaning the SAT 2018 and SAT 2019 state, participation, reading and writing, math data files. Once cleaned, I performed some exploratory data analysis to uncover trends in the participation rates, reading and writing, math on a state-wide basis across all 51 states, then identify states that increase SAT participation rates does not appear to be a direct correlation test scores.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|ACT/SAT|the US state under consideration|
|**sat_2019_participation**|*int*|SAT|percentage of high school students (freshman through senior) in the state that took the SAT in 2019|
|**sat_2019_reading_and_writing**|*int*|SAT|scaled score between 200-800 (inclusive) measuring verbal reasoning, averaged over all test takers in state in 2019|
|**sat_2019_math**|*int*|SAT|scaled score between 200-800 (inclusive) measuring mathematical reasoning, averaged over all test takers in a state in 2019|
|**sat_2019_total**|*int*|SAT|sum of verbal and reading score, averaged over all test takers in a state in 2017|
|**sat_2018_participation**|*int*|SAT|percentage of high school students (freshman through senior) in the state that took the SAT in 2018|
|**sat_2018_reading_and_writing**|*int*|SAT|scaled score between 200-800 (inclusive) measuring verbal reasoning, averaged over all test takers in a state in 2018|
|**sat_2018_math**|*int*|SAT|scaled score between 200-800 (inclusive) measuring mathematical reasoning, averaged over all test takers in a state in 2018|
|**sat_2018_total**|*int*|SAT|sum of verbal and reading score, averaged over all test takers in a state in 2018|

### Conclusions and Recommendations

Conclusions and Recommendations
Based on SAT score averages for the years 2018 and 2019, we recommend additional grant funding be allocated to those states, where the EBRW and Math scores were below the nationwide lower 25th percentile values of 525 and 518 respectively. However, we do not recommend funding grants to increase SAT participation rates, because there does not appear to be a direct correlation between participation rate and test scores.
