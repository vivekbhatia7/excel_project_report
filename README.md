# excel_project_report

People’s reactions 
agenda
  Project recap
  Problem
  The Analytics team
  Process
  Insights
Social Buzz is the fastest growing technology unicorn that needs to adapt quickely to its global scale.
Accenture has began a 3 month PPC focusing on these tasks : • An audit of Social Buzz’s big data practice
• recommendation for a successful IPO
• Analysis to find Social Buzz’s top 5 most popular categories of content .
#Problem
• Over 100000 posts per day
• 36500000 pieces of content per year !
• But how to capiatalize on it when there is so much ?

#The Analytics team
  Andrew Fleming -Chief Technical Architect
  Marcus Rompton - Senior Principle
  Vivek Bhatia -  Data analyst
#Process
  Data Understanding
  Data Cleaning
  Data Modeling
  Data Analysis
  Uncover Insights

#The client has sent through:
7 data sets - each data set contains different columns and values
• A data model - this shows the relationships between all of the data sets, as well as any links that you
can use to merge tables. • There is a lot of information here and it’s easy to get lost in the data. So, to make sure you are using 
the right data to answer the business questions you’ll follow these steps: • Requirements gathering
• Data cleaning
• Data modelling
• Reaction, Content, Reaction Types


Reaction, Content, and Reaction Types as our relevant data sets. • To clarify why you made this selection:
• The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
• As explained in the data model, popularity is quantified by the “Score” given to each reaction type. 
• We therefore need data showing the content ID, category, content type, reaction type, and reaction 
score. 
• So, to figure out popularity, we’ll have to add up which content categories have the largest score. 
• But! Before we begin to work with the data sets, we’ll need to ensure that the data is clean and ready for analysis



#Data cleaning
• Data cleaning is a common and very important task when working with data. • What you need to do: • First: Open the three data sets below
• Reaction type , content , reactions
• Second: Clean the data by: • removing rows that have values which are missing, • changing the data type of some values within a column, and
• removing columns which are not relevant to this task. – Think about how each column might be relevant to the business question you’re investigating. If you can’t think of 
why a column may be useful, it may not be worth including it




#Data Modelling
• Now we want to figure out the top 5 categories. To complete your data modelling, follow these steps: • 1. Create a final data set by merging your three tables together
• We recommend using the Reaction table as your base table, then first join the relevant columns from your 
Content data set, and then the Reaction Types data set. • Hint: You can use a “VLookUp” formula
• 2. Figure out the Top 5 performing categories
• Add up the total scores for each category. • Hint: You can use the “Sum If” formula
• The end result should be one spreadsheet which contains: • A cleaned dataset • The top 5 categories
• Once you have a final data file, upload it to complete this task! We'll provide you with some explanation 
videos in the next step - but first give it a go to see if you can figure it out. • You can use Excel or any other tool of your choice to create your final data set.


Uusing pivot table data analysis and visualization is done.
