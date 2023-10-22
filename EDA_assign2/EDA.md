# Exploratory Data Analysis 
### - StudentID: 21900338
### - Name: Yunjin Bae
### - 1st Major: Economics
### - 2nd Major: AI convergence
<br>

<i>Here's a concise summary of my project: I used General Social Survey (GSS) data to analyze two main aspects. First, I investigated how the survey year relates to the average age at which people marry, separately for men and women. I calculated yearly averages and standard deviations and visualized the relationship with scatter plots.

Second, I explored the link between individuals' highest education level and their age at marriage. I calculated the average age at marriage based on education level and visualized it using scatter plots. </i>

<br><br>
## 1. Data overview <br>
- sample size: 59600 11232
- number of variables: 11232
- data type: object

  <br> 

<br><br>
## 2. Univariate analysis <br>

### 2.1  Survey Yearwise first Marriage Age Statistics<br>

This is a statistical analysis of the average first marriage age by survey year. The analysis is conducted separately for women and men, and it includes the calculation of mean, median, and standard deviation for each group

<figure>
  <img src="summary of yearM F.png" alt="Statistics of women's first marriage age by survey year"/>
  <figcaption>Figure 1. Statistics of women's first marriage age by survey year</figcaption>
</figure>


<figure>
  <img src="summary of yearM M.png" alt="Statistics of men's first marriage age by survey year"/>
  <figcaption>Figure 2. Statistics of men's first marriage age by survey year</figcaption>
</figure>

Both men and women show a gradual increase in the average first marriage age over the survey years

### 2.2 Average age at first marriage statistics categorized by highest degree <br>


<figure>
  <img src="summary of degreeM.png" alt="Statistics of average marriage age by Highest Degree"/>
  <figcaption>Figure 3. Statistics of average marriage age by Highest Degree</figcaption>
</figure>


### 3.1 Correlation between survey year and age at first marriage <br>

<figure>
  <img src="change in MA fe.png" alt="Change in Average Women's Marriage age over time"/>
  <figcaption>Figure 4. Change in Average Women's Marriage age over time</figcaption>
</figure>


<figure>
  <img src="change in MA ma.png" alt="Change in Average Men's Marriage age over time"/>
  <figcaption>Figure 4. Change in Average Men's Marriage age over time</figcaption>
</figure>

Upon analyzing the data, it was observed that the average marriage age increases over time when separated by gender, but when examining the entire dataset, the correlation coefficient was 0.05. This indicates that there is a weak relationship between the survey year and the average marriage age, suggesting that survey year and marriage age are not strongly related. 


### 3.2 Correlation between highest education and age at first marriage <br>
<figure>
  <img src="change in MA on degree.png" alt="Change in Average Marriage age over time"/>
  <figcaption>Figure 4. Change in Average Marriage age depend on degree</figcaption>
</figure>

This is a plot depicting the relationship between marriage age and the highest level of education. It was observed that as the level of education increases, the average marriage age also increases. When calculating the correlation coefficient for the entire dataset, it was found to be 0.13, indicating a very weak positive correlation.


<br><br>
## 4. Suggestion <br>
In this analysis, it was found that survey year and educational level had limited impact on marriage age. Therefore, in a new project, investigating other variables that may influence marriage age is a consideration.

For instance, factors such as economic indicators, regional influences, family composition, cultural elements, changes in marriage rates, and factors like home purchases after marriage can be examined. Through this additional investigation, the aim is to uncover complex patterns and causal relationships affecting marriage age and identifying potential determinants that may impact future marriage trends.

Exploring additional variables provides insights into the factors influencing marriage age, potentially shedding light on future marriage trends.