# US-VISA-Data-Analysis

## Why am I creating this repo?
This mini project is dedicated to proposing an [organized way](https://www.coursera.org/learn/analytics-tableau) of working through a Data Science problem. I see Data Analysis as the most important part of a data science project. If you do not know your data well, you can never produce conclusive results. In addition to this it is particularly impossible to model a data effectively if you do know how your fields impact the target attribute. <br> Further, according to my observation the only stand alone reason for the cloud around the definition of Data Science is actually the absence of a defined paradigm for solving the Data Science problem. I think there isn't any. This method I am about to introduce will however help a beginner to at least approach a problem with some clarity in mind and be confident of the end product.<br>

 > For me Data Science is an art of first being passionate about your problem, understanding the problem statement, collecting the relevant data and analyze it to solve the problem at hand.

 I think this is pretty much I try to do with each one of my data science project. Let me try to break down my definition of data science. <br>

 1. Being passionate about your problem - This allows you to put in the required amount of mental resources to actually think about the problem and formulate a problem statement. i.e a Specific, Measurable, Attainable, Relevant, Time bound **(SMART goal)**. For instance, if you aspire to come to USA to have a taste of real innovation, you might wonder about the most successful route of getting your VISA approved.
 2. After you are down with your problem statement, you should have a **dependent variable**, the variable you want to make conclusions about. Here it is Case Status.
 3. Followed by this you might want to think about the **independent variables**, the variables that would affect this dependent variable.
 4. Further you can go ahead and think about the ways (or specific **visualizations**) you can make to be clear about the relation ships about your IVs and DV.
 5. Going ahead down the line use a tool to create the planned visualizations and digest the overall theme of your data. It is important to be sure what your data says about your DV. This will help you to get a feel of fields you would want to use when you use ML algorithms to model your data.
 6. Finally now when you are clear about your final list of IVs and their relationship with the DV, you can go ahead and model the problem with any of the **machine learning algorithms**.

 The most important point - Since this is just a paradigm, it takes a lot of practice to master the skill. So be patient and be curious. <br>
 Be sure to have all the information in a mind map (SPAP). So that you can re iterate over it and continuously evolve it.

## Introducing the motivation
When a US company wants to hire someone from outside of the United States for a technical
position, they have to file an application to the United States government to get a green card or visa
for the foreign applicant. These applications allow the US government to track who is entering and
leaving the country for work-related reasons, and ensure that immigrants are neither being taken
advantage of nor causing adverse effects for U.S. workers. To ensure equity for US and non-US
workers, companies have to state how much they are planning on paying the employee every time
they submit a visa or green card application. They also have to state the average amount an
employee with similar skills and background typically gets paid for the same position, a figure
called “the prevailing wage.” This publically available data provides a unique view into what types
of salaries you might encounter for different data–related jobs in the US.<br>

*Skewed nature of the data*<br>
![here](https://github.com/gauscian/US-VISA-Data-Analysis/blob/master/Skewed-data-wrt-case-status.png)

<br>This skewed nature makes the predictive modelling around case status impractical.



## Source
The original data was compiled by the [US Department of Labor’s Office of Foreign Labor
Certification](http://www.foreignlaborcert.doleta.gov/performancedata.cfm).

## Analysis

### SPAP - (Structured Analysis Plan)
[Here](https://github.com/gauscian/US-VISA-Data-Analysis/blob/master/What%20maximizes%20the%20chances%20of%20a%20US%20-%20VISA%20being%20Certified%20%20.png) is the SPAP for the above problem. This plan was prepared after a brief look into the data and imbibing the overall intuition of the data.
#### Description of the SPAP :
    1.  Layer 1 : SMART GOAL of the analysis. Since the data I analyze is particularly skewed with respect to the Case Status field I only use the SMART goal for thinking about the possible Independent variables.
    2.  Layer 2 : Dependent variable (Case status in our case).
    3.  Layer 3 : Independent varibles hypothesized to be associated with the Case Status variable.
    4.  Layer 4 : Describes the plan for the vizualizations to be created.
    5.  Layer 5 : Is the reference to the conclusions drawn as mentioned in this mini report.


### My Analysis of the problem.

List or related resources.
1. The Tableau [dashboard](https://public.tableau.com/shared/32BSS87B3?:display_count=yes)
2. [SPAP](https://github.com/gauscian/US-VISA-Data-Analysis/blob/master/What%20maximizes%20the%20chances%20of%20a%20US%20-%20VISA%20being%20Certified%20%20.png)

The last layer of the SPAP defines the numbers I use here to conclude on my findings about the respective Independent variables.<br>


