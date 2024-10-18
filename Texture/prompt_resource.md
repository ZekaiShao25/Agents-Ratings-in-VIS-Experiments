# texture

+ For each prompt, where each sentence is preceded by a symbol identifying it, `[A]` indicates that the sentence was migrated directly from the paper material, `[B]` indicates that the sentence was modified slightly based on the paper material, and `[C]` indicates that the sentence was added by ourselves based on specific needs.
+ Sentences identified by `[A]` and `[B]` have a background color, which is used to distinguish between different sources of the paper material. Sentences identified by the `[C]` do not have a background color.

## Role Play

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #FFF2CC">[B]You are an average user.</span></div>

#### resource

<span style="background-color: #FFF2CC">[B]We recruited 150 valid participants (fluent English speakers, of legal age—18 years in most countries) through the Prolific platform.</span>

## Task (Rating)

### aesthetic

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;"><span style="background-color: #a8f0a7">[A]You need to rate the aesthetics of each visualization with iconic textures using a 7-point Likert scale via the 5 items of the BeauVis scale.</span> <span style="background-color: #a8f0a7">[B]BeauVis scale consists of five items, 'enjoyable', 'likable', 'pleasing', 'nice' and 'appealing'.</span> <span style="background-color: #58f066">[A]And you also added 1 item to assess the degree to which they perceived a vibratory effect (Also using a 7-point Likert scale).</span> <span style="background-color: #cbf1ca">[B]Vibratory effect is an optical illusion making patterns seem unstable, linked to the Moiré effect.</span> <span style="background-color: #34da31">[A]Then you also need to rank the four visualizations you have just evaluated based on your overall preference. You need to give the ranking of each image in order (1, 2, 3, ...).</span></div>

#### resource

<span style="background-color: #cbf1ca">We then gave them a brief explanation of the vibratory effect</span>, and instructed them to focus only on the visual appearance of the charts. Subsequently, we asked them to evaluate a total of eight images, presented in two separate blocks: one containing geometric and the other iconic textures. Each block contained four images, with the block order and the images within them randomized. <span style="background-color: #a8f0a7">For each block, we asked participants to rate the aesthetics of each visualization using a 7-point Likert scale via the 5 items of the BeauVis scale and</span> <span style="background-color: #58f066">added 1 item to assess the degree to which they perceived a vibratory effect.** We included one attention check question in this section.</span> <span style="background-color: #34da31">Following the rating section, we asked participants to rank the four visualizations they had just evaluated based on their overall preference.</span> In addition, we asked them to provide a rationale for their selection of the highest-ranking visualization.

### readable

#### prompt

<div style="background-color: #e1e1e1; color: #333333; padding: 10px; border-radius: 5px;">Describe three visualizations with unicolor, geometric, and iconic textures. <span style="background-color: #F0DFC4">You need to rate the 5 items of the BeauVis scale and an additional readability item on a 7-point Likert scale. </span><span style="background-color: #F0DFC4">[B]BeauVis scale consists of five items, 'enjoyable', 'likable', 'pleasing', 'nice' and 'appealing'.</span></div>

#### resource

Finally, we showed participants three charts with default data values, each featuring a different fill type, in random order. <span style="background-color: #F0DFC4">We asked the them to rate each chart using the 5 items of the BeauVis scale and an additional readability item on a 7-point Likert scale.</span>