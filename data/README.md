# Data files for COMM318 _Stories from data_ Final Project

Hello! This folder contains the data files I have used in my analysis. I divided them into two separate sub-folders: `Raw` contains the original data files I downloaded from open data portals and `Cleaned` consists of cleaned versions of these data sets that I worked with to clean up and organize, subset, and merge the files. Below you can find the list of all my data files, and a brief description to introduce you to each of them. 
    
## Data files

### Raw

Google Trends data:
* `anxiety.csv` - results from Google search trends for "anxiety" from 2012 to 2018 for CA.
* `depression.csv` - results from Google search trends for "depression" from 2012 to 2018 for CA.
* `sad.csv` - results from Google search trends for "sad" from 2012 to 2018 for CA.
* `therapy.csv` - results from Google search trends for "therapy" from 2012 to 2018 for CA.
* `wellness.csv` - results from Google search trends for "wellness" from 2012 to 2018 for CA.

Others:
* `adult_depression_CA_2012_to_2018.csv` - data from California Health and Human Services Open Data Portal about proportion of adults who were told they had a depressive disorder at any point in their lives.
* `adult_ACEs.csv` - data from LGHC indicator that gives information about respondents who indicate having at least one type of adverse childhood experience, defined: "These include verbal/emotional abuse, physical abuse, sexual abuse, and negative household situations including the incarceration of an adult, alcohol or drug abuse by an adult, violence between adults, mental illness of a household member, and parental divorce or separation."
* `adult_cigarette_use.csv` - from California Behavioral Risk Factor Surveillance System (BRFSS); data showing adult cigarette use prevalence in CA.
* `adult_current_smokers.csv` - another LGHC indicator, from CA BRFSS, data showing proportion of CA adults who are current smokers. Current cigarette smoking is defined as having smoked at least 100 cigarettes in lifetime and now smoking every day or some days.
* `adult_diabetes.csv` - LGHC indicator, from CA BRFSS, data showing adults with diabetes per 100 people, based on the question: "Has a doctor, or nurse or other health professional ever told you that you have diabetes?" 
* `adult_tobacco_use.csv` - from the CA BRFSS, data showing adult tobacco use prevalence in CA. Tobacco use includes cigarettes, cigars, little cigars or cigarillos, pipe tobacco, smokeless tobacco (e.g. chew, snuff, snus), hookah, or electronic smoking devices (e.g. e-cigarettes, vape pens, pod mods). 
* `adult_unemployment.csv` - data that contains non-seasonally adjusted CA Unemployment Rate by age groups, from the Current Population Survey (CPS).
* `adult_physical_activity.csv` - from LGHC Indicator 16, CA BRFSS, displays the percentage of adults meeting Aerobic Physical Activity guidelines in CA. 

### Cleaned

* `ACEs_CLEANED.csv` - renamed columns, organized by the columns I want to analyze.
* `depress_CLEANED.csv` - organized data, renamed columns, cleaned data set.
* `diabetes_CLEANED.csv` - renamed columns, cut columns I don't want.
* `gtrends_CLEANED.csv` -  cleaned the rows, renamed columns, merged each of the 5 Google trends data set into one, cut the baseline term "drought" data set, inserted DateTime index, organized into one.
* `physical_activity_CLEANED.csv` - renamed columns, organized by those of interest and cleaned data set.
* `smoke_CLEANED.csv` - renamed columns to match preferences, organized them.
