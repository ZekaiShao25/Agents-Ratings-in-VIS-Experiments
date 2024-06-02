# uncertainty

## Role Play

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #FFF2CC">[B]You are an average user.</span></div>

#### resource

As a result, we were left with 202 participants. All participants were fluent in English, and resided in the United States; 49% of our participants self-identified as Female while one did not disclose, and all but one participants had completed a college degree.

## INTRODUCTION

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #d7eefc">[A]The graphs show the relationship between two variables X and Y. The points belong to two groups Cyan and Orange. However, the original dataset has certain missing values in either the X or Y for every variable.</span>
<span style="background-color: #cedfff">[A]We use a statistical method called imputation to estimate these points. The point represents the most likely (average) estimate of the missing data point derived from the imputation method.</span> 
<span style="background-color: #aac9ff">[A]However, as imputation cannot precisely estimate values for the missing data points, we also get some uncertainty from our imputation method. </span>
<span style="background-color: #7dacff">[A]There are five different uncertainty representations, each for a graph provided. In the first graph (none), data points with missing values are not shown as they cannot be accurately plotted on the chart. In the second graph (mean), the missing points are estimated, and the mean of these estiamtes are represented as hollow points. In the third graph (ci), we represent this uncertainty using the bars which represent the 95% confidence interval.This interval tells you the uncertainty associated with the imputed value. In the fourth graph (density), we represent this uncertainty using the probability density plots. In the fifth graph (gradient), we represent this uncertainty using the gradient plots showing 95% confidence intervals.This interval tells you the uncertainty associated with the imputed value.</span> </div>

#### resource

<span style="background-color: #d7eefc">The graph on the left shows the relationship between two variables X and Y. The points belong to two groups Cyan and Orange. However, the original dataset has certain missing values in either the X or Y for every variable. The total amount of missing data in this graph is 46%; 12% of the observations in Group Cyan are missing, and 34% of the observations in Group Orange are missing.</span>

<span style="background-color: #cedfff">We use a statistical method called imputation to estimate these points. The point represents the most likely (average) estimate of the missing data point derived from the imputation method. However, as imputation cannot precisely estimate values for the missing data points, we also get some uncertainty from our imputation method. In this graph, the missing points are estimated, and the mean of these estiamtes are represented as hollow points.</span>

<span style="background-color: #aac9ff">However, imputation methods cannot precisely calculate the value of a missing observation, instead providing an estimate with some degree of uncertainty.</span>

<span style="background-color: #7dacff">Baseline: No Imputation All complete cases are represented using a scatterplot with any missing observations not presented to the viewer. Mean: Mean Point Estimate Mean point estimates derived from our imputation method are represented using unfilled circle marks, while observed values are represented using filled circles similar to the baseline. CI: Mean Point Estimate with 95% Confidence Intervals 95% confidence intervals are one of the most commonly used encodings for communicating uncertainty. Since we have distributional information about each imputation, we estimate the 95% upper and lower bounds of this distribution and represent each imputed value using a point estimate and the corresponding 95% confidence interval. Density: Probability Density Plots. Gradient: Gradient Plots Showing 95% Confidence Intervals.</span>

## TASK

### MEAN

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">[A]With the introduction above, you need to understand the visualizations and finish the tasks based on the visualization.</span> 
<span style="background-color: #a8f0a7">[B]PRIOR PRINCIPLE: When dealing with the task, please simulate the role of an average human participant who is reading the visualizations and answering the questions without any computational tools. So you need to choose the way of dealing with the task based on a human perspective, and NOTE that humans are subject to cognitive and perceptual factors.</span> 
<span style="background-color: #58f066">[A]For each uncertainty representation, complete the following task: Based on the understanding of how missing data is imputed, estimate the average value of X of the whole dataset(including both cyan and orange group, and both real and imputed data).</span> [C]You need to tell me the exact process of completing the task using the visualizations and the difficulties you may encounter, and DO NOT give your final answer of the task.</div>

#### resource

<span style="background-color: #cbf1ca">On this page, we will briefly describe the chart and provide an example question. Please read carefully and try out the task on this page before proceeding.</span>

 <span style="background-color: #a8f0a7">As a result, we were left with 202 participants. All participants were fluent in English, and resided in the United States; 49% of our participants self-identified as Female while one did not disclose, and all but one participants had completed a college degree.</span>

<span style="background-color: #58f066">What is the average value of X?</span>

### TREND

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">With the introduction above, you need to understand the visualizations and finish the tasks based on the visualization. </span>
<span style="background-color: #a8f0a7">PRIOR PRINCIPLE: When dealing with the task, please simulate the role of an average human participant who is reading the visualizations and answering the questions without any computational tools. So you need to choose the way of dealing with the task based on a human perspective, and NOTE that humans are subject to cognitive and perceptual factors. </span>
<span style="background-color: #58f066">[A]For each uncertainty representation, complete the following task: Based on the understanding of how missing data is imputed, identify the trend line which best represents the relationship between x and y(including both cyan and orange group, and both real and imputed data).</span> [C]You need to tell me the exact process of completing the task using the visualizations and the difficulties you may encounter, and DO NOT give your final answer of the task.</div>

#### resource

<span style="background-color: #cbf1ca">On this page, we will briefly describe the chart and provide an example question. Please read carefully and try out the task on this page before proceeding.</span>

<span style="background-color: #a8f0a7">As a result, we were left with 202 participants. All participants were fluent in English, and resided in the United States; 49% of our participants self-identified as Female while one did not disclose, and all but one participants had completed a college degree.</span>

<span style="background-color: #58f066">Identify the trend line which best represents the relationship between X and Y?</span>

## RATING

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #F0DFC4">[A]From the human perspective you are simulating, for each of the representations, rate your confidence in your answer on a scale of 1 to 5 with 5 representing the highest confidence.</span> [C]As an average human participant, DO NOT state individual variance on this task, and you MUST give an specific answer.</div>

#### resource

<span style="background-color: #F0DFC4">In addition, we elicit participants’ self-reported confidence in their response using a five-item Likert-style question.</span>

EXTRA EXPERIENCE (without image)

## Role Play

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">[C]You are an expert in visualization.</div>

## INTRODUCTION

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #7dacff">[A]There are five kinds of uncertainty representations: baseline(not showing imputed data), mean(only showing the mean of point estimation of imputed data using hollow points), CI(represent the uncertainty using the bars which represent the 95% confidence interval), density(represent the uncertainty using the probability density plots), gradient(represent the uncertainty using the gradient plots showing 95% confidence intervals).</span></div>

#### resource

<span style="background-color: #7dacff">Baseline: No Imputation All complete cases are represented using a scatterplot with any missing observations not presented to the viewer. Mean: Mean Point Estimate Mean point estimates derived from our imputation method are represented using unfilled circle marks, while observed values are represented using filled circles similar to the baseline. CI: Mean Point Estimate with 95% Confidence Intervals 95% confidence intervals are one of the most commonly used encodings for communicating uncertainty. Since we have distributional information about each imputation, we estimate the 95% upper and lower bounds of this distribution and represent each imputed value using a point estimate and the corresponding 95% confidence interval. Density: Probability Density Plots. Gradient: Gradient Plots Showing 95% Confidence Intervals.</span>


## TASK

### MEAN

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">[C]What difficulties will human observer encounter when faced with uncertainty representations for imputed data on a 2D scatter plot and required to estimate the mean of the whole dataset, considering human are subject to cognitive and perceptual factors.</div>

### TREND

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">[C]What difficulties will human observer encounter when faced with uncertainty representations for imputed data on a 2D scatter plot and required to identify the trend line which best represents the relationship between x and y, considering human are subject to cognitive and perceptual factors.</div>

## RATING

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">[C]From the human perspective you are simulating, for each of the representations, <span style="background-color: #F0DFC4">rate your confidence in your answer on a scale of 1 to 5 with 5 representing the highest confidence.</span></div>

#### resource

<span style="background-color: #F0DFC4">In addition, we elicit participants’ self-reported confidence in their response using a five-item Likert-style question.</span>