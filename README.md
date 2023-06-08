# Analisis for internship Alternaria strains

## Experimental design

The practical work of the internship students in 2023 will consist of several in vitro studies on Alternaria alternata. 

## Split data

Lam Nguyen will use the data for the Clemenville species in Clemenville species. 

Mohamed Samu will use the data for the crosses between species and also carob and persimon. 

## Data scripts

### Data survey

*01_data-survey-clean-export.qmd* script does:

- fix all the variables, 
- put together all the original data frames and legends.
- Split the data for Lam and Samu
- Export the data to *data/clean-data.Rdata*. 

To load the clean data in next scripts you only need to write:

```
load("data/clean-data.Rdata")
```

### Automatic Exploratory data analysis

*02_EDA.qmd* script does:

- EDA with `skimr` package.
- Correlation funnel plots. 


### Pathogenicity analysis
 
## Repositories
 
 GitHub repository: 
 https://github.com/lamle47/git_internship.git
 
 
