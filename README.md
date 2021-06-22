# Term-Deposit-Subscription-UCI
Predicting Term Deposit Subscription by a client

Portugal-Banking-Data-UCI (https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

<u>Abstract:</u>

  Marketing campaigns are characterized by focusing on the customer needs and their  overall satisfaction. 
  Nevertheless, there are different variables that determine whether a marketing campaign will be successful or not. 
  There are certain variables that we need to take into consideration when making a marketing campaign.  
  A Term deposit is a deposit that a bank or a financial institution offers with a fixed rate  (often better than just opening a deposit account) in which your money will be returned  back at a specific maturity time.

<u>Problem Statement:</u>

  Predict if a customer subscribes to a term deposits or not, when contacted by a marketing agent, by understanding the different features and performing predictive analytics
  
<u>Steps Performed:</u>
 
  1. Data Cleaning
  2. Outlier removal using z-score
  3. Basic EDA
  4. Splitting into train and test
  5. Encoding the independednt variables
  6. Model building and prediction
  7. Over-sampling minority class by SMOTE
  8. Model building and evaluation
  9. Conclusion
  
<u>Data-set Info:</u>
  1) age (numeric)
  2) job: type of
  job(categorical:"admin.","bluecollar","entrepreneur","housemaid","management","retired","selfemployed","services","student","technician","unemployed","unknown")
  3) marital: marital status (categorical: "divorced","married","single","unknown"; note: "divorced"
  means divorced or widowed)
  4) education: education of individual (categorical:
  "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","u
  nknown")
  5) default: has credit in default? (categorical: "no","yes","unknown")
  6) housing: has housing loan? (categorical: "no","yes","unknown")
  7) loan: has personal loan? (categorical: "no","yes","unknown")
  Related with the last contact of the current campaign:
  8) contact: contact communication type (categorical: "cellular","telephone")
  9) month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")
  10) dayofweek: last contact day of the week (categorical: "mon","tue","wed","thu","fri")
  11) duration: last contact duration, in seconds (numeric). Important note: this attribute highly
  affects the output target (e.g., if duration=0 then y="no"). Yet, the duration is not known before a call
  is performed. Also, after the end of the call y is obviously known. Thus, this input should only be
  included for benchmark purposes and should be discarded if the intention is to have a realistic
  predictive model
  Other attributes:
  12) campaign: number of contacts performed during this campaign and for this client (numeric,
  includes last contact)
  13) pdays: number of days that passed by after the client was last contacted from a previous
  campaign (numeric; 999 means client was not previously contacted)
  14) previous: number of contacts performed before this campaign and for this client (numeric)
  15) poutcome: outcome of the previous marketing campaign (categorical:
  "failure","nonexistent","success")
  Social and economic context attributes
  16) emp.var.rate: employment variation rate - quarterly indicator (numeric)
  17) cons.price.idx: consumer price index - monthly indicator (numeric)
  18) cons.conf.idx: consumer confidence index - monthly indicator (numeric)
  19) concavepoints_se: standard error for number of concave portions of the contour
  20) euribor3m: euribor 3 month rate - daily indicator (numeric)
  21) nr.employed: number of employees - quarterly indicator (numeric)
  Output variable (desired target):
  22) y: has the client subscribed a term deposit? (binary: "yes","no")
