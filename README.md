<h2>Problem Statement- To check whether the mean height of the given sample of students is equal to the specified value</h2>
<br>
<h3>✔️Import the necessary libraries</h3>
  ▶️<i>import numpy as np</i>
  <br>
  ▶️<i>import pandas as pd</i>
  <br>
  ▶️<i>from scipy import stats</i>
<br>
<h3>✔️Create a DataFrame df containing height of different students. </h3>
<h3>✔️Let's assume </h3>
  
   <i>▶️H0 (NULL Hypothesis):  Mean height of the sample is equal to the specified value. </i>
  <br>
   <i>▶️H1 (ALTERNATE Hypothesis): Mean height of the sample is not equal to the specified value. </i>
  <br>
  <i> ▶️Consider significance level (alpha) = 0.05 </i>
 
<h3>✔️Use stats.ttest_1samp() and pass the sample and specified mean value of height.</h3>
    
   <i> ▶️Stats.ttest_1samp():
       It is used to calculate the T test for the mean of one group of sample.
  This is a 2 sided test for the null hypothesis that the expected value of the mean of sample of independent
  observation is equal to the given population mean.</i>
   <br>
  
  ✔️ <i>On executing the above expression, P value is generated.</i>
  <br>
  ✔️ <i> P value is observed less than the significance value (alpha) </i><br>
  <i>   Hence, we can consider H1 (ALTERNATE Hypothesis) True and H0(NULL Hypothesis) False </i>
  
    
