
## GLOBAL SUPER STORE PROJECT IN POWER BI

## Introduction

<p>In this project we manage gloabl super store sales and shipping analysis.When starting this we have done some process are mentioned below,</p>

### Process that Need to Follows,
<ol>
<li>First of all we import the data(any format) that import into power bi using <b>getData</b> function.</li>
<li>Alter we get huge collection of data we need to <b>clean</b> it in power query editor through <u>tranform data</u>.For cleaning there are many properties we have example,eliminate duplicate rows,remove all rows with null value,etc.This all changes apply in <i>Table view</i> in power bi.</li>
<li>After that,In the cleaned data we have creating some <b>new measures,new calculated columns,new calculated tables</b>.In our project we have a new table named as customer for save customer data.</li>
<li>Then we move into <i>Model view</i> where tha relationship between the models are set.In our project we could find three relationship, where order table is the center table connection with all other tables.</li>
<li>Then we make report in <i>Report View</i> where we created differnt table,graphical,Dashboard representations from our huge dataset.From that representation we have arrive some conclusions are decribed below.</li>
</ol>

### GLOBAL SUPER STORE REPORT ANALYSIS
<p>For the reports shown by we dividing the section as home page,shipping analysis,sales analysis,table dashboard,sign out.Explanation are given below,</p>
<UL>
  <LI><b>Home Page</b>:-In this we give a header portion.A image is given that give a image like store.On the left side there are certain page navigations(sales analysis,shipping details,sign out) are listed.</LI>
  <li><b>Sales Analysis</b>:-In this page give some charts, that convey the information about sales analysis.First we give a navigation to home.because it is the main page.Then we listed some <i>cards</i>,that describes some counts like profit,discount,customers,etc.Here charts analysis are described below,
    <ul>
   <li>Then give a <i>Donut chart</i> that give info about Sum of Sales by Product Name.Here Apple smartphone has the highest sale will happen.ie,74.34k.</li>
         <li>Then give a <i>Line chart</i> that give info about Count of Category by Order Year.Here In the year 2014 has highest count of category is shown.</li>
         <li>Then we have search with all countries are listed there.</li>
         <li>Then give a <i>Stacked Bar chart</i> that give info about Sum of Sales by State.Here "Aquitine" has the highest sales would happen.ie,30,904.46.</li>
         <li>Then give a <i>Funnel chart</i> that give info about Average Sales by City.Here City "Kamina" has the highest average sale.ie,30,817.26.</li>
         <li>Then give a <i>Pie chart</i> that give info about Total Sales by Market.Here Market "APAC" has the highest sales.ie,22,53,765.13.</li>
         <li>Then give a <i>Scatter chart</i> that give info about Average Sales by Profit and Region.</li>
         </ul>

<li><b>Shipping Analysis</b>:-In this page give some charts, that convey the information about shipping analysis.First we give a navigation to home.Here charts analysis are described below, </li>
 <ul>
   <li>Then give a <i>Ribbon chart</i> that give info about Total Sales by Ship Mode.Here Standard class has the highest total sales would happen.ie,47,69,253.46.</li>
          <li>Then give a <i>Area chart</i> that give info about Count of State and Total Customers by DaysTakenToShip.Here DaysTakenToShip=4 has highest count of state & highest total customers .ie,4631 & 909 respectively.</li>
   <li>Then give a <i>Stacked area chart</i> that give info about Sum of Shipping Cost by Ship Mode.Here Standard class has the highest sum of shipping cost.ie,4,11,560.85.</li>
   <li>Then give a <i>Line & Stacked column chart</i> that give info about Sum of Shipping Cost and Count of Ship Mode by Product Name.Here "Motorola Smart Phone"  has the highest sum of shipping cost and Count of Ship Mode.ie,8,293,55 & 31 respectively.</li>
   <li>Then give a <i>Map</i> that give info about Total Sales by Country and Ship Mode.Here "United States" has the highest Total Sales and Ship Mode.ie,678602 and standard class respectively.</li>

  </ul>

     </li>
</UL>

<p>For Analysis we also use some tables listed below,First Table Header and no of columns in it,</p>
<ol>
  <li>No Of Days needed For Shipping - we have 2 columns are product name,sumOfDaysTakenToShip. </li>
    <li>Category Avg Sales & Discount  - we have 3 columns are Category,Average sale & sum of discount. </li>
    <li>Total Orders under region & Country  - we have 3 columns are Country,Region & Total orders.</li>
        <li>Average Profit Against state & Market  - we have 3 columns are State,Market & Average Profit.</li>
        <li>Total Quantity Against City  - we have 2 columns are City,Total quantity.</li>
        <li>Total Sales under product  - we have 3 columns are Product Name,Ship Mode & Total Sales.</li>


</ol>

## Conclusion

<p>In the above analysis using graphs and table structure, we get a complete picture about the Global super store.It helpful for data analysis and make reports.So power-bi is an effective tool for this.</p>

[Check out this video for complete flow about Project] 
