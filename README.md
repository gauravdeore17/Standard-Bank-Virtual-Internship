# Standard-Bank-Virtual-Internship
Standard Bank aims to improve the current process in which potential borrowers apply for a home loan. The current process involves loan officers having to manually process home loan applications. This process takes 2 to 3 days to process upon which the applicant will receive communication on whether or not they have been granted the loan for the requested amount. To improve the process Standard Bank wants to make use of machine learning to assess the credit worthiness of an applicant by implementing a model that will predict if the potential borrower will default on his/her loan or not, and do this such that the applicant receives a response immediately after completing their application.

**Tools used**- Jupyter notebook

**Language and Packages uesd**- SQL,Python (Pandas,Numpy,Matplotlib,Seaborn,Sweetviz,Sklearn)

**We will be required to follow the data science lifecycle to fulfil the objective. The data science lifecycle includes the following:**

- Business Understanding

- Data Understanding

- Data Preparation

- Modeling

- Evaluation

- Deployment.

![CRISP-DM](https://user-images.githubusercontent.com/27211670/206142421-404b73a0-ea12-4c10-ad7b-73445756b6b6.png)

## Task 1 - SQL for Data Scientists

A relationship with relational databases.

The beginning of any data science project involves understanding the business and the data. Business understanding is focused on setting the business objectives, project assessment, defining the success criteria and project planning. Understanding the business is essential to any data science project. 

After this, the next phase is Data Understanding. To understand the data, we have to identify, collect, analyze and verify data quality from one or multiple data sources to accomplish the business goals. These tasks can be done in SQL. **SQL** is a crucial skill to have as a data scientist, as you will be required to work with structured data stored in relational databases.

## Task 2 - Data Science With Python
AutoML vs bespoke

In this task, We will make use of automated machine learning as well as traditional machine learning. The manager of the home loans department, who has provided us with sample data, wants to know a few things about the data.  

The manager is also interested in understanding what machine learning really is with particular use case.

We will use Python and its extensive collection of libraries to derive valuable insights from the data, prepare the data and train machine learning models - the old fashioned way and in newer, automated ways.

## Task 3 - Preparing to Present
Back to understanding the business

As a data scientist, we will be required to present your findings. This tests just how well we understood the business problem and business objectives. The manager of the home loans department, like many other project sponsors we might have to present to, has a limited technical background. Her interest is business-oriented, so we should discuss our results in terms of the business problem with minimal technical details and using visuals.

![image](https://user-images.githubusercontent.com/131190846/233275204-57f1f255-8528-4ace-92cb-06e9145ebb2e.png)

![image](https://user-images.githubusercontent.com/131190846/233275235-1946d656-5c35-4c9a-9fdc-d7a75f9bcb14.png)


## Task 4 - Putting It All Together
Presenting our insights to a non-technical audience

In this task,  we will prepare to present our findings. we will be presenting to the manager of the home loans department and also your manager and team by video presentation outlining our findings from the previous task.

## Insights

1.An overview of the data

- Train Data contains 614 Rows and total 13 columns.

- Out of 13 columns there are 4 float columns, 1 integer columns and 8 object columns.

- Test Data contains 367 Rows and total 12 columns.

- And out of 12 columns there are 3 float columns, 2 Integer columns and 7 object columns.

2.What data quality issues exist in both train and test?

- There are no duplicate values in both train dataset and test dataset.

- But both dataset have some missing values.

3.How do the loan statuses compare? i.e. what is the distrubition of each?

- There are 422 loans with a Yes status, which is the majority, and 192 loans with No status.

4.How do women and men compare when it comes to defaulting on loans in the historical dataset?

- Men have a higher loan status of Yes than women do, and same goes to loan status of No.

5.How many of the loan applicants have dependents based on the historical dataset?

- According to the historical dataset, 269 loan applicants have dependents.

6.How does the income of those who are employed compare to those who are self-employed based on the historical dataset?

- The average income of those who are employed is 5049 which is low compared to self-employed that is 7380.

- The minimum income of those who are employed is 150 which is low compared to self-employed that is 674.

- But the maximum income of those who are employed is 81000 which is high compared to self-employed that is 39147.

- Additionally, 500 people are employed, which is a large number when compared to the 82 people who were self-employed in the historical dataset.

7.Are applicants with a credit history more likely to default than those who do not have one?

- Indeed, candidates with credit histories may be more likely to default than those without them

8.Is there a correlation between the applicant's income and the loan amount they applied for?

- Yes, there is a positive correlation between the applicant's income and the loan amount they applied for.

