# timeline

## Role Play

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #FFF2CC">[B]You are an average user.</span></div>

#### resource

<span style="background-color: #FFF2CC">Participants. We recruited 192 participants. The experiment was expected to last 5 minutes, and each participant received $2 base pay plus a bonus of $0.2 for each correct question after the sixth correct one. Our participants self-reported their demographics.. By gender 53% were male, 31% were female, while the rest chose not to answer. By education 32.8% had a Bachelor’s degree, 17.7% had a high school degree, 16.6% attended some college but do not have a degree, and the rest had either a Master’s degree, an Associate Degree, a Doctorate, had no degree, chose not to answer. By employment 62.5% were employed for wages, 17.2% were self-employed, 5.2% were out of work, and the rest were either students, homemakers, retired, unable to work, or chose not to answer.</span>

## TASK

### **WHEN**

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">[A]There are several different timelines represented on different shapes. The data presented on the timeline is made up specifically for this experiment. </span><span style="background-color: #a8f0a7">[A]You are given the question as '{question}', and you need to select one from {number} options: {options}.</span></div>

#### resource

<span style="background-color: #cbf1ca">When did <event> happen? Example: When did the earthquake happen? In this case, we are asking for the location of a target. The location is unknown but the target is known. Users would need to explore the timeline and report the year as an answer.</span><span style="background-color: #a8f0a7"> We will show you several different timelines. They will contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment.</span>

### WHAT

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">[A]The timelines contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment. </span><span style="background-color: #a8f0a7">[A]You are given the question as '{question}', and you need to select one from {number} options: {options}.</div></span>

#### resource

<span style="background-color: #cbf1ca">What happened at <time>? Example: What happened in 1999? What happens at the start of the timeline? Location is given, target is not. Users will look at the location and report the name of the event. </span><span style="background-color: #a8f0a7">We will show you several different timelines. They will contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment.</span>

### FIND

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">[A]The timelines contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment. </span><span style="background-color: #a8f0a7">[A]You are given the question as '{question}'.</div></span>

#### resource

<span style="background-color: #cbf1ca">Find <event> that happened at <time>? Example: The earthquake happened in 1898. Click on it. Participants will answer this type of question by clicking on a specific point on the timeline. This question gives to the users both the target and the location. </span><span style="background-color: #a8f0a7">We will show you several different timelines. They will contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment.</span>

### COMPARE

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #cbf1ca">[A]The timelines contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment. </span><span style="background-color: #a8f0a7">[A]You are given the question as '{question}', and you need to select one from {number} options: {options}.</div></span>

#### resource

<span style="background-color: #cbf1ca">Compare time of <event1> relative <event2> or <event3>? Example: Did Cleopatra live closer to the launch of the first iPhone or the construction of the Pyramids? Users need to find 3 data points on the timelines and then compare the distance between pairs of data points. </span><span style="background-color: #a8f0a7">We will show you several different timelines. They will contain different events and be represented on different shapes. The data presented on the timeline is made up specifically for this experiment.</span>

### **EASIEST READ**

没有按照论文中先预热后评估的顺序

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">[C]Please complete the above question first and give your answer. Then you are given the question '<span style="background-color: #a8f0a7">[A]Which timeline shape was the easiest to read for the {type} dataset?', and you need to select one from 5 options: {options}.</span></div>

#### resource

<span style="background-color: #a8f0a7">Which timeline shape was the easiest to read for the {type} dataset?</span>