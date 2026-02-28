260225_Problemset2_Q3.ipynb
 -python code for data cleaning.

merged_left_data_removed_nonunique_id_not_clearned_forQ1Q2.csv
 -dataset for Question1 and Question2 
 -remove only the observation with non unique id

cleaned_data_forQ3_Q9
- dataset for other questions
- rule for data cleaning as follows
   Remove observations which has no subject_id
   Remove the observations which have missing values in any columns.
   Remove the observations which have negative age.
   Remove observations whose hours are more than 100.
   Remove observations whose "bmi" column contains values less than 1.0.
   Convert the value 'Woodlawn' to '0', and 'Hydepark' to '1',  regardless of whether the value is uppercase or lowercase,     in order to use it as a categorical variable.
   Convert the value "female" to "1" and the value "male" to "0".
   Convert the string variable "education" into dummy variables. The column names are "less than high school", "high           school", and "higher degree", which are the same as the string values.
   Make values included in the column "race_ethnicity" lowercase characters.
   Convert the string variable "race_ethnicity" into dummy variables. The column names are "white", "black", and               "hispanic", which are the same as the string values

