                                                          # Consumer-Complaint-Resolution-Analysis-Using-Python
Consumer Complaint Resolution Analysis Using Python

Scenario:
  Product review is the most basic function/factor in resolvingcustomerissues and increasingthe sales growth of any product.Wecan understandtheir mindset toward our service withoutasking each customer.When consumers are unhappywith some aspect of a business, they reach out to customer service and might raise a complaint. Companiestry their best to resolve the complaints that they receive. However, it might not always be possible to appease every customer.So Here, we will analyze data, and with the help ofdifferent algorithms, we are finding the best classification ofcustomercategoryso thatwe can predict our test data.

Objective:
  Use Python libraries such as Pandas for data operations, Seaborn and Matplotlib for data visualization and EDA tasks, Sklearn for model building and performance visualization, andbased on the best model,make a prediction for the test file and save the output.The mainobjective is to predict whetherour customer is disputedor not with the help ofgiven data.

Dataset description:
  Customersfaced some issuesand triedto report their problems to customer care.
  
  Dispute: This is our target variable based on train data; wehave two groups, one with a dispute with the bank and another don’t have any issue with the bank.
  Date received: The day complaint was received.
  Product: different products offered by the bank (credit cards, debit cards, different types of transaction methods, accounts, locker services, and money-related)
  Sub-product: loan, insurance, other mortgage options
  Issue: Complaint of customers 
  Company public response: Company’s response to consumer complaint
  Company: Company name
  State: State where the customer lives (different state of USA)
  ZIP code: Where the customer lives
  Submitted via: Register complaints via different platforms (online web, phone, referral, fax, post mail) 
  Date sent to company: The day complaint was registered
  Timely response?: Yes/no
  Consumer disputed?: yes/no (target variable)
  Complaint ID: unique to each consumer

Tasks to be performed:
  The following tasks are to be performed:
  Note:Please completethe given steps on both train and test data.
    •Read the Data from the Given excel file.
    •Check the data type for both data (test file and train file)
    •Do missing value analysis and dropcolumns where more than 25% of data are missing 
    •Extracting Day, Month,and Year from Date Received Column and create new fields for a month, year,and day 
    •Calculatethe Number ofDays the Complaint was with the Companyand create a new field as “Days held”
    •Drop "Date Received","Date Sent to Company","ZIP Code", "Complaint ID"fields
    •Imputing Nullvalue in “State”by Mode
    •with the help ofthe days we calculated above,create a newfield 'Week_Received'where we calculate the week based on the day of receiving.
    •store data of disputed people into the “disputed_cons” variable for future tasks 
    •Plot bar graph of thetotal no of disputes of consumers with the help ofseaborn
    •Plot bar graph of thetotal no of disputes products-wise with the help ofseaborn
    •Plot bar graph ofthe total no of disputes with Top Issues by Highest Disputes, with the help ofseaborn
    •Plot bar graph ofthe total no of disputes by State with Maximum Disputes
    •Plotbar graph ofthe total no of disputes Submitted Via differentsource
    •Plot bar graph ofthe total no of disputes where the Company's Response to the Complaints
    •Plot bar graph ofthe total no of disputes where the Company's Response Leadsto Disputes
    •Plot bar graph ofthe total no of disputes.Whether there are Disputes Instead of Timely Response
    •Plot bar graph ofthe total no of disputes over Year Wise Complaints
    •Plot bar graph ofthe total no of disputes over Year Wise Disputes
    •Plot bar graph ofTop Companies with Highest Complaints
    •Converte all negative days held to zero(it is the time taken by the authority that can't be negative)
    •Drop UnnecessaryColumns for the Model Buildinglike:'Company', 'State', 'Year_Received', 'Days_held'
    •Change Consumer Disputed Column to 0 and 1(yes to 1, and no to 0)
    •Create Dummy Variables for categoricalfeaturesand concat with the original data framelike: 'Product,’'Submitted via,’'Company response to consumer,’'Timely response?'
    •Scaling the Data Sets (note:discard dependent variable before doing standardization)and Makefeature Selection with the help ofPCAup to 80% of the information.
    •Splittingthe Data Sets Into X and Y by the dependent and independent variables (data selected by PCA)
•Buildgivenmodelsandmeasuretheirtestandvalidationaccuracy:
      oLogisticRegression
      oDecisionTreeClassifier
      oRandomForestClassifier
      oAdaBoostClassifier
      oGradientBoostingClassifier
      oKNeighborsClassifier
      oXGBClassifier
•Whoever gives the most accurate result uses it and predicts the outcomefor the test file and fills its dispute column so the business team can take some action accordingly.


