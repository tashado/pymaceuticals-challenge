# Name

Module 5 Challenge - Data Visualization


## Description

The following data showcases trends across 249 mice who were identified with SCC tumors that received treatment with a range of drug regimens. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

From the following analysis, we can find the more effective drug regimens for tumors in mice, and find correlations between the mice and other factors.

## Discrepencies between this file and the outputs generated in file "pymaceuticals_starter.ipynb"
* Line 269: When counting the no. of mice in the cleaned DataFrame after dropping duplicates, the no. matches the previous mice count generated in line 265: 249 mice. Whereas the mice count in file "pymaceuticals_starter.ipynb" was 248. I believe my file contains the correct result as there should not be change in mice count after removing duplicates.
* Line 274 / 275: There is a slight discrpency of the percentage distribution of female vs male mice. I believe this to either be a formatting difference between the 2 files, or an onflowing result of the discrepency in the aforementined line 269.
* Line 277: Only one outlier was obtained from the Infubinol, versus two outliers identified in "pymaceuticals_starter.ipynb". I double checked my one outlier by exporting DataFrame "tumor_list" and manually checking the file in Excel, and believe my answer is correct.
* Line 280: I interpreted the question as "Calculated the average tumor volume per weight for the Capomulin regimen", which generates one scatter point per weight in the Capomulin_data DataFrame. I'm not sure why there are multiple tumor volumes for the same weight in the "pymaceuticals_starter.ipynb" file.

Please address these discrepencies in the marker comments.

## Acknowledgment

Code in line [278] was taken from: https://stackoverflow.com/questions/47657651/boxplot-from-dictionary-with-different-length

  [278] labels, data = [*zip(*tumor_list.items())] 

