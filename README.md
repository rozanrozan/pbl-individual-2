# Second PBL Individual : Annual People Analytics Report

<p>Tools 
  <ul>
    <li>Google Bigquery :
      <ul>
        <li>Part 1 : (<a href="https://console.cloud.google.com/bigquery?sq=889224908686:9d0eddf376934ee79dfe1557f481d1f6">Click Here</a>)</li>
        <li>Part 2 : (<a href="https://console.cloud.google.com/bigquery?sq=889224908686:516bd18a4d5b4fb0b1d9abda854f18c2">Click Here</a>)</li>
        <li>Part 3 : (<a href="https://console.cloud.google.com/bigquery?sq=889224908686:d8356b1b1ad04b6dbe6afc647c8407a9">Click Here</a>)</li>
        <li>Part 4 : (<a href="https://console.cloud.google.com/bigquery?sq=889224908686:82f462e93dc54c308ac9fb497e6515ed">Click Here</a>)</li>
        <li>Part 5 : (<a href="https://console.cloud.google.com/bigquery?sq=889224908686:8b98fc18851f4cb2a14f375a29e53eb8">Click Here</a>)</li>
      </ul>
    </li>
    <li>Visualization : Looker Studio (<a href="https://datastudio.google.com/reporting/93772ec1-5775-44dd-aa72-1e25313037bf">Click Here</a>)</li>
  </ul>
</p>

## Project Introduction

<p>PBL (Project Based Learning) Individual is the final task of Data Analytics for Business bootcamp at Bitlabs Academy which is done individually. In this project, I want to help a company to improve employee retention rates & growth rates, through initiatives such as allocating budgets for new ownership-based rewards programs, conducting more thorough workforce planning based on historical data, as well as ensuring recruitment inclusivity in terms of age & gender distribution among employees.</p>

<br>

<strong> SQL Objectives </strong>
<p> The SQL objective/target of this project is:</p>
<ol>
  <li> Calculate the Employee Retention Rate at the end of 2011 by dividing the total number of active employees at the end of 2011 by the total number of employees from the beginning of 2010. Compare the number with our previous retention rate at the end of 2010.</li>
  <li> Calculate Company Growth Rate by dividing the total number of active employees at the end of 2011 by the total number of active employees from the end
of 2010. Compare the number with our previous growth rate at the end of 2010.</li>
  <li> The company going to launch a new tenure-based reward program in 2012. Only those who stayed until the end of 2011 will be eligible for this program. Calculate the total budget that the company will have to allocate for this program with details as stated below (p.s. Each employee will be categorized into based on their tenure by the time the 2011 data was recorded).
    <ul>
      <li>Tenure group 0 - 5 years: $100 / person</li>
      <li>Tenure group 6 - 10 years: $200 / person</li>
      <li>Tenure group 11 - 15 years: $300 / person</li>
      <li>Tenure group 15 years & above: $500 / person</li>
    </ul>
  </li>
  <li>In terms of hiring, the company wanted to ensure that we maintain a roughly equal number of male & female active employees across age groups:
    <ul>
      <li>Below 30 years</li>
      <li>31 - 40 years</li>
      <li>41 - 50 years</li>
      <li>51 - 60 years</li>
      <li>60 years and above</li>
    </ul>
  </li>
  <li>To make an informed decision in regards to man power planning, figure out what are the Top 3 Department & City in terms of hiring (based on number of new joiners).
  </li>
</ol>

<br>

<strong> Data Visualization Objectives </strong>
<p> The data visualization objective/target of this project is:</p>
<ol>
  <li> Construct an interactive dashboard visualization in Tableau/Google Data Studio/Power BI/Metabase/Redash (tools of your choice), consists of the following metrics:
    <ul>
      <li>Total Employees (beginning of 2010)</li>
      <li>Total Active Employees (end of 2011)</li>
      <li>Retention Rate (2010 - 2011)</li>
      <li>Growth Rate (2010 - 2011)</li>
      <li>Active Employee Distribution by City</li>
      <li>Total Active Employees by Tenure Group & Age Group</li>
      <li>Estimated Budget for Tenure-Based Reward Program in 2012 by Tenure Group</li>
      <li>Top 3 Department & City based on Total New Joiners</li>
    </ul>
  </li>
</ol>

<br>

<strong> Datasets </strong>
<p> This data set is provided by recruitment partners. So, I'm not allowed to provide the dataset in full.</p>

## Analysis Result
<p> Here are some analysis results obtained from SQL processing: </p>
<ol>
  <li>Total employees from 2010-2011 were 5,205 employees. However, the total number of active employees until the end of 2011 was as many as 4,972 employees.</li>
  <li>The company managed to retain 95.52% of its employees from the beginning of 2010 to the end of 2011. This decreased by 0.23% from the previous period.</li>
  <li>The company experienced an employment growth rate of 2.73% at the end of 2011. This is an increase of 1.23% from the previous year.</li>
  <li>Most of the active employees in the companiy are employees with a long working time of 0-5 years. Meanwhile, the largest amount of salary expenditure is found in the group of employees with a long working time more than 15 years.</li>
  <li>Vancouver is the city with the highest number of active employees and the highest number of new employees at the company.</li>
  <li>The largest number of active employees in the company is male with an age of 30 years</li>
  <li>Customer Service is the department with the most employee recruitment activities in 2010-2011.</li>
</ol>

## Recommendations
<p> Here are some recommendations that can be given to companies : </p>
<ol>
  <li>The company should create attractive programs for employees so that employees can beta work in this company so that the next period can experience increased employee retention.</li>
  <li>The company can open a branch or promote its company in the city of Vancouver because the city contributes the most in terms of a number of employees.</li>
</ol>
