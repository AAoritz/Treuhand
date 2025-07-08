# Treuhand Data: Privatization Outcomes and Firm Ratings

## Overview

This is a repository for the raw data used in the paper [The big sell: Privatizing East Germany’s economy](https://www.sciencedirect.com/science/article/abs/pii/S0047272724002275) 
by [Lukas Mergele](https://sites.google.com/view/lmergele/home), [Moritz Hennicke](https://hennicke.science/) and [Moritz Lubczyk](https://sites.google.com/view/moritzlubczyk/). 

This repository contains two data sets: The privatization status of East German firms in 2016 and the Treuhand Firm Ratings dataset.
Please consult the [data appendix](https://ars.els-cdn.com/content/image/1-s2.0-S0047272724002275-mmc1.pdf) for further details. 

## 1. Privatization Status

In 2018, we submitted a freedom of information request to the successor organization of the Treuhandanstalt, the Bundesanstalt für vereinigungsbedingte Sonderaufgaben (BvS), to obtain firm-level data. 
In response, Mr. Dieter Freund from the BvS provided the Excel file shared here. 
The file contains information on the privatization outcomes of East German firms as of 2016, including, among other variables: firm name, Treuhand ID, company registry number, federal state, and privatization status. 
A codebook describing the variables is included in the final tab of the Excel file.


## 2. Firm Ratings

The Treuhand Firm Ratings dataset contains internal scores assigned by the Treuhand’s Leitungsausschuss to prioritize large firms under its administration during its first year of operation (July 1990–June 1991). 
Ratings range from 1 (profitable and stable) to 6 (unviable and recommended for liquidation), based on a mix of financial data and qualitative assessments, without a standardized formula. 
We manually digitized these ratings from meeting minutes of the agency's rating committee (Leitungsausschuss), obtained from the Federal Bundesarchiv in Berlin. 
The dataset excludes firms already in the process of privatization, municipalization, or liquidation. 
Firms can be matched to other data using Treuhand’s internal identifiers. 
A codebook for the variables is provided in the second CSV file.


## Citation

If you use these datasets in your work, please cite the following paper (author ordering is [random](https://www.aeaweb.org/journals/random-author-order) indicated by the ⓡ ): 

Mergele, Lukas ⓡ  Hennicke, Moritz ⓡ Lubczyk,  Moritz. 2025. "Big sell: Privatizing East Germany’s economy." Journal of Public Economics, 242, 105291. https://doi.org/10.1016/j.jpubeco.2024.105291


```
@article{bigsell2025,
title = {The big sell: Privatizing East Germany’s economy},
journal = {Journal of Public Economics},
volume = {242},
pages = {105291},
year = {2025},
issn = {0047-2727},
doi = {https://doi.org/10.1016/j.jpubeco.2024.105291},
url = {https://www.sciencedirect.com/science/article/pii/S0047272724002275},
author = {Lukas Mergele \textcircled{r} Moritz Hennicke \textcircled{r} Moritz Lubczyk},
keywords = {Privatization, Firm ownership, Labor productivity, German reunification},
abstract = {Departing from communism, East Germany witnessed history’s most extensive privatization program. While the program sparked global interest as a blueprint for economic transformation, its effectiveness remains disputed. Using unique firm-level data, we examine the program’s objective to privatize the most competitive firms. We document that firms with higher baseline productivity are more likely to be privatized, yield higher prices, are more often acquired by West Germans, and are more likely to survive 20 years later. Inspecting the inner workings of the privatization agency, we illustrate challenges and lessons for how governments can design and implement industrial policy goals.}
}
```


