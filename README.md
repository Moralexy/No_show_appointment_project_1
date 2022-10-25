# (Investigate a Dataset- No-show Apointments )
## by (Oloruntoba James Moritiwon)


## Dataset

The dataset analysed is associated with 100k medical appointments in Brazil. Each rows of these dataset contain descriptions about patients which include choosen days of appointment, location of hospital and Bolsa Família (Brazillian welfare program) enrollment status. The dataset contained 110527 observations and 14 variables which changed to 110526 and 15 respectively after wrangling. The dataset can be found on Kaggle servers- https://www.kaggle.com/datasets/joniarroba/noshowappointments/download?datasetVersionNumber=5


## Summary of Findings

Assessing the csv file imported into Dataframe-df, it can be seen that the total number of appointment identities and schedules are a little less than double the number of patients documented. This implies that patients with more than one identities have booked multiple schedules with medical personnels within the 27 days under scrutiny!. Also, there are several scheduled appointments per day for most of the 27 days under scrutiny.Furthermore, one negative entry is detected in the column representing age of patients. This would require cleaning to make a realistic analysis. Sentence cased data headings are inconsistent with pythonic standards and would required conversion to lower case. Clumsy headings would need re-arrangement for clarity too.

This dataset is well structured and easy to manipulate. However, some constrains to the dataset include the minimal representation of some categories (there are only 7 centinarians compared to more than 12000 children!) to arrive at conclusions.Also, exaggeratons are likely should graphical presentation be relied on its entirety (there are no male centinarians patients documented hence, they can neither show up nor miss appointments thereby, yielding a false zero for males). Rather, textual results should be used together with these graphics. conclusively, being female and younger in age indicates a strong likelyhood to keeping with schedules. However, not getting a medical sponsorship seemed to make patients take their medical appointments seriouslly too.



## Key Insights for Presentation

For visualisations, I gave priority to age and its influence on patients' no-show behaviour. Afterwards, I showed how patient gender can predict no-show behavior of patients in total and within age brackets and how medical scholarship influence no-show behavior of patients under study.  

I started with the barchart of of no_show appointments with age, and went further to show the Barh chart of no_show appointments by gender and age bracket. Finally, I showed the Proportions of no-show by patient medical sponsorship with a pie chart. I have made sure to pass the right messages with colours for each variable clearly.
