# Prompt Summary

+ The columns of this table represent the different experiments (seven in total), and the rows represent the kinds of prompts that the experiments may require.
+ For the prompt in each cell, where each sentence is preceded by a symbol identifying it, `[A]` indicates that the sentence was migrated directly from the paper material, `[B]` indicates that the sentence was modified slightly based on the paper material, and `[C]` indicates that the sentence was added by ourselves based on specific needs.
+ Sentences identified by `[A]` and `[B]` have a background color, which is used to distinguish between different sources of the paper material. The specific content of the paper material and its correspondence with the prompt are shown in the `prompt_resource.md` file in the directory corresponding to each experiment. Sentences identified by the `[C]` do not have a background color.
  
<table>
    <tr>
        <th></th>
        <th>ROLE PLAY</th>
        <th>INTRODUCTION</th>
        <th>TASK</th>
        <th>RATING</th>
    </tr>
    <tr>
        <th>Time Series</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span></td>
        <td><span style="background-color: #cedfff">[B]These visualizations represent each day's sales. By looking at the visualization, you know that here are 112 days: Each day follows the structure 'Day X-Week Y-Month Z', where 'X' denotes the day of the week (ranging from Day 1 to Day 7) , 'Y' indicates the week of the month (ranging from Week 1 to Week 4), and 'Z' specifies the month of the year (January, February, March, April). </span><span style="background-color: #d7eefc">[B]For line chart, the y-value of point indicates the the daily sale. For heatmap, the color shade of the cell indicates the daily sale. For icicle plot, the size of the rectangle indicates the sale.</span></td>
        <td><span style="background-color: #cbf1ca">[A]By looking at these three visualizations (line chart, heatmap, icicle), your goal is to identify the day(Day X-Week Y-Month Z) with the absolute highest sales through individual visualisations.</span> [C]Just determine which day has the maximum sale.</td>
        <td>[C]Here's how one person accomplishes a task: {steps} Based on the knowledge you have, assuming you are this person, <span style="background-color: #F0DFC4">[A]you should answer two 5-point Likert scale questions for three different visualisations, ranging from strongly agree (5) to strongly disagree (1): (i) I feel confident about the given answer and (ii) I think this visualisation is easy to use for this task.</span> [C]And give the reason.</td>
    </tr>
    <tr>
        <th>Fit Estimation</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span></td>
        <td>/</td>
        <td><span style="background-color: #cbf1ca">[A]Here are {number} scatterplots. You are instructed to estimate how well the data points fitted to the shown line. Your score ranges from 0 (very low fit) to 100 (very high fit), a perfect fit would be to have all data points on the line. Please list the scores and the reason in the order of the images.</span></td>
        <td>In Task</td>
    </tr>
    <tr>
        <th>Imputation for Uncertainty</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span></td>
        <td><span style="background-color: #d7eefc">[A]The graphs show the relationship between two variables X and Y. The points belong to two groups Cyan and Orange. However, the original dataset has certain missing values in either the X or Y for every variable.</span><span style="background-color: #cedfff">[A]We use a statistical method called imputation to estimate these points. The point represents the most likely (average) estimate of the missing data point derived from the imputation method.</span> <span style="background-color: #aac9ff">[A]However, as imputation cannot precisely estimate values for the missing data points, we also get some uncertainty from our imputation method. </span><span style="background-color: #7dacff">[A]There are five different uncertainty representations, each for a graph provided. In the first graph (none), data points with missing values are not shown as they cannot be accurately plotted on the chart. In the second graph (mean), the missing points are estimated, and the mean of these estiamtes are represented as hollow points. In the third graph (ci), we represent this uncertainty using the bars which represent the 95% confidence interval.This interval tells you the uncertainty associated with the imputed value. In the fourth graph (density), we represent this uncertainty using the probability density plots. In the fifth graph (gradient), we represent this uncertainty using the gradient plots showing 95% confidence intervals.This interval tells you the uncertainty associated with the imputed value.</span></td>
        <td><span style="background-color: #cbf1ca">[A]With the introduction above, you need to understand the visualizations and finish the tasks based on the visualization.</span> <span style="background-color: #a8f0a7">[B]PRIOR PRINCIPLE: When dealing with the task, please simulate the role of an average human participant who is reading the visualizations and answering the questions without any computational tools. So you need to choose the way of dealing with the task based on a human perspective, and NOTE that humans are subject to cognitive and perceptual factors.</span> <span style="background-color: #58f066">[A]For each uncertainty representation, complete the following task: Based on the understanding of how missing data is imputed, estimate the average value of X of the whole dataset(including both cyan and orange group, and both real and imputed data).</span> [C]You need to tell me the exact process of completing the task using the visualizations and the difficulties you may encounter, and DO NOT give your final answer of the task.</td>
        <td><span style="background-color: #F0DFC4">[A]From the human perspective you are simulating, for each of the representations, rate your confidence in your answer on a scale of 1 to 5 with 5 representing the highest confidence.</span> [C]As an average human participant, DO NOT state individual variance on this task, and you MUST give an specific answer.</td>
    </tr>
    <tr>
        <th>Timeline</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span></td>
        <td>/</td>
        <td><span style="background-color: #cbf1ca">[A]There are several different timelines represented on different shapes. The data presented on the timeline is made up specifically for this experiment. </span><span style="background-color: #a8f0a7">[A]You are given the question as '{question}', and you need to select one from {number} options: {options}.</span>
        [C]Please complete the above question first and give your answer. Then you are given the question '<span style="background-color: #a8f0a7">[A]Which timeline shape was the easiest to read for the {type} dataset?', and you need to select one from 5 options: {options}.</span>
        </td>
        <td>/</td>
    </tr>
    <tr>
        <th>Texture</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span></td>
        <td>/</td>
        <td><span style="background-color: #a8f0a7">[A]You need to rate the aesthetics of each visualization with iconic textures using a 7-point Likert scale via the 5 items of the BeauVis scale.</span> <span style="background-color: #a8f0a7">[B]BeauVis scale consists of five items, 'enjoyable', 'likable', 'pleasing', 'nice' and 'appealing'.</span> <span style="background-color: #58f066">[A]And you also added 1 item to assess the degree to which they perceived a vibratory effect (Also using a 7-point Likert scale).</span> <span style="background-color: #cbf1ca">[B]Vibratory effect is an optical illusion making patterns seem unstable, linked to the Moiré effect.</span> <span style="background-color: #34da31">[A]Then you also need to rank the four visualizations you have just evaluated based on your overall preference. You need to give the ranking of each image in order (1, 2, 3, ...).</span></td>
        <td>In Task</td>
    </tr>
    <tr>
        <th>Magnitude Judgement</th>
        <td><span style="background-color: #FFF2CC">[B]You are an average user.</span</td>
        <td>/</td>
        <td><span style="background-color: #cbf1ca">[A]The graph below shows the chance of damage to the item for three randomly selected airlines. Task: If you fly with one of these airlines... What is the chance your item is damaged? Answer on a scale from 1(very unlikely) to 7(very likely). What is the severity of consequences if your item is damaged? Answer on a scale from 1(very mild) to 7(very severe).For each question, please rate each graph with only one score.</span> <span style="background-color: #a8f0a7">[A]Notice that the arrow on the "Chance" axis points downwards, meaning the numbers get bigger as the axis goes down.Rate the following two graphs separately and give the reason.</span></td>
        <td>In Task</td>
    </tr>
</table>
