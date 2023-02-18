# Evidence-Based Kapsalon

Seven kapsalon locations were included in the study. Establishments have been anonymized with a number (1--7).

There were 12 human participants, whose role was to collect the kapsalon samples, obtain quantitative metrics and provide (very) subjective opinions on various qualitative measures. Participants have been anonymized with a letter (A--L).

Teams of 2 were sent to 4 areas of the city and visited 7 establishments in total. 4 establishments were visted by a team of 4 that split into 2 groups of 2. Teams returned to the base station in pairs at 4 different times; 3 groups returned with 2 kapsalon samples and one group returned with 1 sample. This information is specified in files `00.csv` and `01.csv`, which, along with the rest of the data collected, are described in the table below:

| No. | Survey name | $N_q$ | $N_c$ | $N_r$ | Description |
| :--: | :--: | :--: | :--: | :--: | :-- |
| 0 | Leaving the base station | 4 | 6 | 7 | Time of departure of each team |
| 1 | At the place | 13 | 14 | 7 | At the establishment during the order and pickup |
| 2 | The numbers | 9 | 10 | 7 | Measurements of the entire kapsalon |
| 3 | All the parts | 8 | 9 | 7 | Measurements of each part of the kapsalon |
| 4 | The rating of the parts | 6 | 7 | 60 | Main ingredients assessed individually |
| 5 | The whole shebang | 13 | 14 | 46 | Entire kapsalon assessed |
| 6 | The best or worst parts | 7 | 8 | 4 | Attempt to identify which of the 7 samples had the best or worst ingredients |

$N_q$: number of questions in survey (not the same as columns in `*.csv`)
$N_r$: number of responses (also number of rows in `*.csv`, not including header)
$N_c$: number of columns in `*.csv`

Data was anonymized and saved in this repo as `*.csv` files numbered according to the numbered list above. There is a mixture of data types (e.g., strings, floats, etc) and the headers can be quite long, often containing the entire string of the questions asked in each survey. A data quality control team was reviewing the entire data entry process and did an excellent job of making sure very little information was missing. However, due to external factors that were definitely avoidable---but whose absence would have negatively impacted the entertainment value of the data collection process---there are indeed some data missing in the `*.csv` files. Miraculously, it seems that there is only one erroneously entered data: `04.csv` contains response by an unkown person "Nas".