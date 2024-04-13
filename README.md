
## COVID-19 ANALYSIS PROJECT IN POWER BI

## Introduction

<p>In this project we manage Covid-19 analysis daywise,globalwise,countrywise,etc.When starting this we have done some process are mentioned below,</p>

### Process that Need to Follows,
<ol>
<li>First of all we import the data(any format) that import into power bi using <b>getData</b> function.</li>
<li>Alter we get huge collection of data we need to <b>clean</b> it in power query editor through <u>tranform data</u>.For cleaning there are many properties we have example,eliminate duplicate rows,remove all rows with null value,etc.This all changes apply in <i>Table view</i> in power bi.</li>
<li>After that,In the cleaned data we have creating some <b>new measures,new calculated columns,new calculated tables</b>.</li>
<li>Then we move into <i>Model view</i> where tha relationship between the models are set.In our project we could find three relationship, where worldometer table is the center table connection with all other three tables.USA countrywise & Daywise tables are the independent tables.</li>
<li>Then we make report in <i>Report View</i> where we created differnt table,graphical,Dashboard representations from our huge dataset.From that representation we have arrive some conclusions are decribed below.</li>
</ol>

### COVID-19 REPORT ANALYSIS
<p>For the reports shown by we dividing the section as home page,daywise analysis,usa countrywise analysis,countrywise analysis,worldwise analysis,sign out.Explanation are given below,</p>
<UL>
  <LI><b>Home Page</b>:-In this we give a header portion.A image is given that give a image against covid-19.On the left side there are certain page navigations(daywise analysis,usa countrywise analysis,countrywise analysis,worldwise analysis,sign out) are listed.</LI>
  
  <li><b>Daywise Analysis</b>:-In this page give some charts, that convey the information about daywise covid-19 analysis.First we give a navigation to home.because it is the main page.Then we listed some <i>cards</i>,that describes some counts like active,deaths,recovered,etc.Here charts analysis are described below,
    <ul>
   <li>Then give a <i>Pie chart</i> that give info about New cases against each Month.Here July has the highest new cases will happen.ie,6030911.</li>
         <li>Then give a <i>Scatter chart</i> that give info about Count of Deaths by Month.Here May & March has highest count of Deaths is shown.ie,31</li>
         <li>Then we have search with all Months are listed there.</li>
         <li>Then give a <i>Donut chart</i> that give info about Confirmed count against each month.Here March & May has the highest confirmed count would happen.ie,31.</li>
         <li>Then give a <i>Funnel chart</i> that give info about Active Count by Month.Here March & May has the highest active count.ie,31.</li>
         <li>Then give a <i>Area chart</i> that give info about Recovered Count by Month.Here March & May has the highest Recovered count.ie,31.January has the lowest recovered count .ie,10.</li>
         <li>Then give a <i>Ribbon chart</i> that give info about Count of new cases.March & May has the highest count.ie,31</li>
         </ul>
  </li>

  <li><b>USA Countrywise Analysis</b>:-In this page give some charts, that convey the information about USA countrywise covid-19 analysis.First we give a navigation to home.because it is the main page.Then we listed some <i>cards</i>,that describes some counts like confirmed & Deaths.Here charts analysis are described below,
    <ul>
       <li>A Filled Map was plotted first describes about the confirmed count against province state.</li>
   <li>Then give a <i>Pie chart</i> that give info about New cases against each Month.Here March & May has the highest new cases will happen.ie,103540.June & April has the second highest count would happen.ie,100200.</li>
         <li>Then give a <i>Scatter chart</i> that give info about Count of Deaths by iso2.Here US has highest count of Deaths is shown.ie,612128</li>
         <li>Then we have search with all Months are listed there.</li>
         <li>Then give a <i>Donut chart</i> that give info about Count of Deaths by iso3.Here Us & PRI has the highest Deaths count would happen.ie,612128 & 15040 respectively.</li>
         <li>Then give a <i>Funnel chart</i> that give info about Sum of deaths under provision state.Here Newyork has the highest sum of deaths.ie,3176945.Puerco Rico has the lowest sum of Deaths.ie,2</li>
         <li>Then give a <i>Area chart</i> that give info about Confirmed Count by Month.Here March & May has the highest Confirmed count.ie,103540.January has the lowest confirmed count .ie,33400.</li>
         <li>Then give a <i>Tree Map</i> that give info about Sum of FIPS against province state.Texas has the highest Sum of FIPS.ie,2336203056.</li>
         </ul>
  </li>


   <li><b> Countrywise Analysis</b>:-In this page give some charts, that convey the information about countrywise covid-19 analysis.First we give a navigation to home.because it is the main page.Then we listed some <i>cards</i>,that describes some counts like confirmed,active,Deaths,etc.Here charts analysis are described below,
    <ul>
       <li>Then give a <i>Pie chart</i> that give info about New cases against each Country/Region.</li>
         <li>Then give a <i>Scatter chart</i> that give info about Count of Deaths by WHO Region.Here Europe has highest count of Deaths is shown.ie,56</li>
         <li>Then we have search with all Country/Region are listed there.</li>
         <li>Then give a <i>Donut chart</i> that give info about Confirmed count against each Country/Region</li>
         <li>Then give a <i>Funnel chart</i> that give info about Active Count by WHO Region.Here Europe has the highest active count.ie,56.And South-East Asis has the lowest active count.ie,10.</li>
         <li>Then give a <i>Area chart</i> that give info about Recovered Count by WHO Region.Here Europe has the highest active count.ie,56.And South-East Asis has the lowest active count.ie,10.</li>
         <li>Then give a <i>Ribbon chart</i> that give info about Sum of confirmed Last Week.US has the highest Sum of confirmed.ie,3834677.</li>
         </ul>
  </li>




       <li><b>Worldwise Analysis</b>:-In this page give some charts, that convey the information about worldwise covid-19 analysis.First we give a navigation to home.because it is the main page.Then we listed some <i>cards</i>,that describes some counts like confirmed,active,Deaths,critical,etc.Here charts analysis are described below,
    <ul>
       <li>Then give a <i>Pie chart</i> that give info about Serious cases against WHO Region.Here Americans has the highest cases.ie,39973.</li>
         <li>Then give a <i>Scatter chart</i> that give info about New cases by Country/Region.Here Mexico has highest count of new cases is shown.ie,6590</li>
         <li>Then we have search with all Country/Region are listed there.</li>
         <li>Then give a <i>Tree Map</i> that give info about Serious Cases by Country/Region.Here India has the highest serious cases.ie,8944</li>
         <li>Then give a <i>Line $ Stacked column chart</i> that give info about Active Count by WHO Region.Here Luxembourg has the highest active count.ie,995282.And Yamen has the lowest active count.ie,4.</li>
         <li>Then give a <i>Area chart</i> that give info about Recovered Count by WHO Region.Here Americans has the highest Recovered count.ie,2.And Weatern Pacific Asis has the lowest Recovered count.ie,1.</li>
         <li>Then give a <i>Ribbon chart</i> that give info about Sum of confirmed Last Week against population.</li>
         </ul>
  </li>

  <li><b>Sign Out</b>:-Here we simply give a message that thanks for searching.</li>
</UL>



## Conclusion

<p>In the above analysis using graphs and table structure, we get a complete picture about the Covid-19 Report Analysis.It helpful for data analysis and make reports.So power-bi is an effective tool for this.</p>

Check out this video for complete flow about Project : [(https://drive.google.com/file/d/1cBODRz3Ye7D9Lhp3vGXWz4oo9U5Loeer/view?usp=drive_link)]
