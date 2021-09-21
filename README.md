# loan_defaults_project
 
Project summary:  analysis of default among unsecured consumer loans.  Coded in Python in Jupyter notebook files.

Steps of the project:

Defining: 
the brief is to (i) understand what are the qualities of borrower who defaulted, and (ii) 
determine which loan applicants to approve in the future.

Planning: 
the initial stage includes background reading (e.g. visiting the website of the
client, www.lendingclub.com) and exploratory data analysis of the raw data.
Next is cleaning of the raw data and further analysis and generation of lines of enquiry.
Then a statistical model is built, in order to address the main client question.
Insights are drawn and visualised, with recommendation made.

Understanding: 
the main dataset is from a U.S. peer-to-peer, 'LendingClub'.
The dataset includes 42,538 unsecured consumer loans made via the site, some of which are 
repaid, charged-off (defaulted), or remain live.

Analysing: 
the data was cleaned by selecting only columns of data which were pertinent to the brief and variables which were predominantly populated with data.  The 'loan_status' variable has current loans removed, as they would not explain the default outcome.

Concluding: 
the visualisations contain in the file analysis_of_clean_data.ipynb help explain the distribution of values in the key variables.  The logistic regression model output in the file statistical_model.ipynb identifies the variables of (i) annual income, and (ii) FICO score, as being the most explanatory of default.  Other variables which might have been expected to explain borrower default, e.g. debt-to-income ratio, did not have meaningful explanatory power. 

Implementing: 
there is potential to streamline the loan origination process by focussing only on the key variables of choice, rather than the 100+ variables gathered.  This could be used as a value proposition to the borrower market, i.e. an quick application process.  

The question of who to lend to requires further investigation, and is more of a portfolio optimisation process which would balance income maximisation with risk appetite for expected loss across a portfolio of loans.