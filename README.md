Bank Marketing (logistic regression)
Project link: https://www.kaggle.com/code/phamhuyen286/bank-marketing-project-logistics-regression/edit/run/200758699
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
Link of Dataset:https://archive.ics.uci.edu/dataset/222/bank+marketing
Link of research paper on this dataset: https://www.sciencedirect.com/science/article/abs/pii/S016792361400061X?via%3Dihub
Campaign propensity: predicts which bank customers respond to a campaign. Matches "propensity models" and "campaign management".
In the dataset the following is my understanding on columns description:
age: This column represents the age of individuals, with unique values ranging from 18 to 94 years.
job: The job column categorizes individuals into various occupations such as management, technician, and entrepreneur, with several entries also marked as NaN for missing data.
marital: This column indicates the marital status of individuals, classified into three categories: married, single, and divorced.
education: The education column specifies the highest level of education attained, including unique values for tertiary, secondary, primary, and NaN for missing values.
default: This binary column indicates whether an individual has defaulted on a loan, with unique values of 'yes' or 'no'.
balance: The balance column records the account balance of individuals, with a range of unique values that reflect financial status.
housing: This column indicates whether individuals have a housing loan, with unique values of 'yes' or 'no'.
loan: Similar to the housing column, this binary field indicates whether individuals have a personal loan, with values of 'yes' or 'no'.
contact: The contact column describes the type of communication method used to reach individuals, with unique values including cellular, telephone, and NaN for missing data.
day_of_week: This column indicates the day of the week when contact was made, represented by unique numerical values corresponding to each day.
month: The month column captures the month of the year when contact was made, with unique string values for each month from January to December.
duration: This column records the duration of the last contact in seconds, capturing a wide range of unique values.
campaign: The campaign column reflects the number of contacts performed during this campaign for this client, with unique numerical values indicating the count.
pdays: This column records the number of days since the client was last contacted from a previous campaign, with unique values that include -1 (indicating no previous contact).
previous: The previous column indicates the number of contacts performed before this campaign for this client, with a range of unique numerical values.
poutcome: This column describes the outcome of the previous marketing campaign, categorized as 'success', 'failure', 'other', or NaN for missing data.
