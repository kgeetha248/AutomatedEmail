# AutomatedEmail

Covid data of the year 2020 is analyzed, pre-processed to find the top three states having higher number of deaths due to covid.

Step 1: Get the input from the user for which the analysis/ info needed to be known.

step 2: Feature Engineering was done by creating 'month' feature from 'date' feature.

step 3: The excel file read thru pandas is then filtered for the input(month) provided by user.

step 4: Top 3 states has been sorted out and converted to DataFrame

step 4: Death percentage of the state wise deaths is then calculated and rounded off

step 5: Final dataFrame is mailed to the end user via python libraries 'smtplib' and 'email.message'
