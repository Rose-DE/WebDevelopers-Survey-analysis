<center>
    <img src="https://res.cloudinary.com/dezsrv0us/image/upload/c_pad,w_500,h_300/v1706448387/1_juhm4z.png">
</center>

<font color='forestgreen'> <font face="roboto" size="2">
**Developer Insights Project - Stack Overflow 2023**

<font color='black'> <font face="roboto" size="2">
Welcome to the Developer Insights Project - an in-depth exploration into the lives of developers worldwide, based on Stack Overflow data for the year 2023. This project delves into key aspects such as developers' education levels, current salaries, skill proficiency, preferred programming languages, databases in use, and more. Through comprehensive analysis, we aim to provide valuable insights and a deeper understanding of the diverse experiences and trends within the global developer community.

<center>
    <img src="https://res.cloudinary.com/dezsrv0us/image/upload/c_pad,w_500,h_300/v1706449232/2_oa4m8v.png">
</center>

<font color='black'> <font face="roboto" size="2">
A comprehensive analysis of a 2023 Stack Overflow dataset encompassing computer professionals from diverse geographic backgrounds. We explored factors like age, employment, education, and database usage, addressing missing values (notably 2251 imputations in 'ConvertedCompYearly'). This in-depth investigation revealed a critical mismatch between the global distribution of developers across countries and databases and the evolving demands of the tech industry. This disparity generates significant consequences, potentially leading to:

	1	Skill Gaps: The concentration of developers in certain countries may not align with regions experiencing increased tech adoption and demand, creating localized skill shortages and hindering economic growth.
	2	Misallocation of Resources: Investments in tech education and infrastructure may not be effectively targeted to regions with burgeoning tech needs, leading to inefficient resource utilization and hampered technological development.
	3	Competitive Disadvantage: Countries or companies relying on an outdated tech talent pool risk falling behind in the global innovation race, jeopardizing their economic competitiveness and ability to adapt to rapidly evolving technological landscapes.
<font color='black'> <font face="roboto" size="2">The analysis aims to bridge this gap by providing comprehensive insights into the global distribution of developer expertise across popular databases and programming languages. By identifying key trends and discrepancies, we hope to empower stakeholders, decision-makers, and professionals to:

	•	Optimize Tech Education & Training: Tailor programs and curricula to address regional skill gaps and equip developers with the tools and knowledge demanded by the evolving tech landscape.
	•	Guide Strategic Investments: Direct resources towards regions and technologies with robust potential, fostering regional tech ecosystems and promoting sustainable technological development.
	•	Enhance Career Planning: Inform career decisions by equipping developers with data-driven insights into emerging trends and high-demand skills across different geographic locations.
<font color='black'> <font face="roboto" size="2">Ultimately, this research aspires to contribute valuable knowledge to the broader tech community, fostering a more informed and balanced global distribution of developer talent and propelling the industry towards its full potential.

<font color='DarkGreen'> <font face="roboto" size="5"> **IMPORTING TOOLS**

    <img src="https://res.cloudinary.com/dezsrv0us/image/upload/c_pad,w_500,h_300/v1706450114/3_jb00sy.png">
</center>
<font color='black'> <font face="roboto" size="2">The first step, and indeed the most crucial one, in any data analysis project is to import the necessary tools that enabled us to effectively manipulate and visualize our data.
In this case, we start by importing some of the most powerful libraries available. Each of these libraries brings a unique set of functionalities that are essential for data manipulation and visualization.

1.  <font color='black'> <font face="roboto" size="2"> Pandas provides powerful data structures such as DataFrames that make it easy to work with structured data.
2.  <font color='black'> <font face="roboto" size="2"> Numpy offers an array-oriented computing capability along with a vast range of mathematical functions.
1.   <font color='black'> <font face="roboto" size="2">Matplotlib allows us to create visually appealing plots and charts.
2. <font color='black'> <font face="roboto" size="2">  Seaborn complements Matplotlib by providing additional statistical plotting capabilities with ease of use.
1.  <font color='black'> <font face="roboto" size="2"> Finally, Counter from the collections module helps in counting elements efficiently.

<font color='black'> <font face="roboto" size="2">By importing these indispensable tools at the beginning of our analysis, we ensured that we have everything at our disposal to successfully handle any data-related challenge that comes our way confidently.

<font color='DarkGreen'> <font face="roboto" size="5"> **DATA COLLECTION/ EXTRACTION**

<center>
    <img src="https://res.cloudinary.com/dezsrv0us/image/upload/c_pad,w_500,h_300/v1706450882/8_ldsnpy.png">
</center>

<font color='black'> <font face="roboto" size="2">In order to perform a comprehensive analysis of the data from [Stack Overflow](https://insights.stackoverflow.com/survey), the next step entailed adding the csv data into Google Colab.
By importing the csv file containing the Stack Overflow data, We were able to leverage various Python libraries such as Pandas and NumPy to extract meaningful insights. This process ensures that all relevant information is readily available for examination.

<font color='DarkGreen'> <font face="roboto" size="5"> **DATA CLEANING**

<center>
    <img src="https://res.cloudinary.com/dezsrv0us/image/upload/c_pad,w_500,h_300/v1706451141/9_uhjpfd.png">
</center>

<font color='forestGreen'> <font face="roboto" size="4"> **ISSUES IDENTIFIED**

* <font color='black'> <font face="roboto" size="2">Issue we saw with the data
Columns had null values- for columns with data type 'object' we dropped the null values, columns with data type 'interger' or "float" we replaced with the mean
* <font color='black'> <font face="roboto" size="2">Unwanted columns- we dropped the columns we did not need for our analysis and only picked the ones we  needed when defined the data to be used (devs_clean)
* <font color='black'> <font face="roboto" size="2"> Column YearsCode had the data as 'object', we changed that to interger
* <font color='black'> <font face="roboto" size="2">We checked for duplicate values, fortunately our data didn't have duplicate values
* <font color='black'> <font face="roboto" size="2">We also renamed some columns like YearsCode to Years of coding
* <font color='black'> <font face="roboto" size="2">To make our visualisation appealing, we replaced values in the Age column. Values replaced was 'under 18 years old' with '0-17 years old'

<font color='DarkGreen'> <font face="roboto" size="5"> **DATA VISUALIZATIONS**

* * <font color='black'> <font face="roboto" size="2"> Univariate
  *  <font color='black'> <font face="roboto" size="2"> Bivariate
  *   <font color='black'> <font face="roboto" size="2"> Multivariate
  
