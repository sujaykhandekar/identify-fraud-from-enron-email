# identify-fraud-from-enron-email
## Goal of the project

Enron was an energy trading company that was one of the top 10 largest companies in the US in 2001. In 2002, the company was bankrupt and people were put in jail due to corporate fraud and corruption. Enron was involved in the following schemes:

selling assets to shell companies at the end of each month, and buying them back at the beginning of the next month to hide accounting losses
causing electrical grid failures in California
Enron had a second life because of its data set that includes one of the largest corpus of real emails.I have used this data set combined with financial information to indetify persons of interest involved in this fraud by implementing machine learning techniques.

A person of interest is a person who was:

indicted

settled without admitting being guilty

testified in exchange for immunity

The aggregated Enron email + financial dataset is stored in a dictionary, where each key in the dictionary is a person’s name, and the value is a dictionary containing all the features of that person.
