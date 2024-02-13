![Instacart logo, taken from google search](https://github.com/MojoS96/Python_InstaCart_Analysis/assets/159794763/ec3f3ec0-3537-446a-8227-8c6ced6ac319)
# Python InstaCart Grocery Analysis

### Overview:
InstaCart is an online grocery store that operates through an app - They want to use their data to uncover more information about their sales patterns and are considering implementing a targeted marketting campaign tailored to the varied customer groupings.
Using Python I was able to perform the necessary data consistency checks and wranggling steps to prep the Data for Analysis. New variables were generated after defining customer groupings and visualizations where generated in order to answer some of the key project questions.

<details>
<summary> Key Stakeholder Questions: </summary>

- The sales team needs to know what the busiest days of the week and hours of the day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders.
- They also want to know whether there are particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times.
- Instacart has a lot of products with different price tags. Marketing and sales want to use simpler price range groupings to help direct their efforts.
- Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
- The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviours differ. For example:
  - What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?
  - Are there differences in ordering habits based on a customer’s loyalty status?
  - Are there differences in ordering habits based on a customer’s region?
  - Is there a connection between age and family status in terms of ordering habits?
  - What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
  - What differences can you find in ordering habits of different customer profiles? Consider the price of orders, the frequency of orders, the products customers are ordering, and anything else you can think of. 

</details>

### Project Folders Outline:

1. Project Management: Project Brief 
2. Data:
     - Raw Data: Original dataframes prior to manipulation
     - Prepared Data: Data Frames that have been cleaned up and prepared for Analysis
3. Scripts: Jupyter Notebooks containing the all the code used from data consistency checks and wrangling to defining new variables and performing merges.
4. Analysis: .png files for each of the generated Visualizations
5. Final Deiverables:
   -  Excel report detailing the following:
       - Population Flow
       - Consistency checks
       - Wrangling Steps
       - Column Derivations
       - Visualizations
       - Recommendations
    - favourite department by user report Generated for Marketting

### Toolset

The provided data was analyzed using Python via Jupyter Notebooks. The following libraries were imported to perform the analysis:
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy

### DataSets

InstaCart is a real company that's made a portion of their data public - It is accessible via the following [LINK](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)

Data Dictionary: [HERE](https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b)

The download package consists of the following data files:
- Orders
- Orders_products_prior
- Products
- Departments

As part of the Career Foundry course an additional **fictional** datasets were added to suppliment learning:
- Customers
- Prices
