---
title: "Noise vs. Bias: Are they really the same?"
meta_title: ""
description: "Sejal's Blog"
date: 2025-01-24T05:00:00Z
image: "/images/Noisemain.jpg"
categories: ["Behavioral Science"]
author: "Sejal Gupta"
tags: ["Bias"]
draft: false
---

An average adult makes about 33,000 to 35,000 daily decisions— from what we eat and wear to which source of entertainment we will consume at the end of the day. But are our choices truly our own? Is every decision we make influenced only by the factors we consciously consider, or are there hidden forces at play?

Let’s look at the below image and do an exercise. Which one of the following lines is shorter? 

{{< image src="images/Muller-Lyer1.jpg" caption="[Muller-Lyer Illusion](https://www.verywellmind.com/how-the-muller-lyer-illusion-works-4111110)" alt="alter-text" height="200" width="400" position="center" command="fill" option="q100" class="img-fluid" title="Humans and Rationale?"  webp="false" >}}

Now, since we are doing this exercise here, I guess it is no surprise that all three lines are the same length. However, if we focus on this image repeatedly for as long as we can, we continue to perceive the three lines differently—the first one appearing the shortest and the second one the longest. This illusion is famously known as the “Müller-Lyer Illusion” and gives us a glimpse of how something as simple as arrows can create the illusion of varying lengths. In fashion, some dresses are designed to make you look taller— a real-life example of the Müller-Lyer illusion in action! 

{{< image src="images/Muller-Lyer2.jpg" caption="Muller-Lyer Illusion Explained!" alt="alter-text" height="200" width="400" position="center" command="fill" option="q100" class="img-fluid" title="Humans and Rationale?"  webp="false" >}}

The point is, that cognitive biases are everywhere, shaping our decisions in ways we don’t always realize. These mental shortcuts, often in the shape of heuristics or biases, affect our daily lives. For example, a mother may favors her son without noticing, or a campaign manager might believe their marketing plan is great, even if it falls short. But is every mistake a bias? Or is there more to the story? 

Let’s take a forecasting problem as an example. Imagine five different forecasters predicting how many ice creams will be sold in India in April 2025. Even though they all analyze the same data, it’s almost certain they’ll produce five different forecasts. The gap between their predictions could be as small as 0.1% or as large as 50%. But why does the same sales data lead to such different results when examined by equally skilled forecasters? Is this due to bias? Or is it something else—noise?

But what exactly are bias and noise, and how do they differ? Can the two co-exist?

### Understanding Noise and Bias

Simply put, noise and bias are two distinct types of errors that affect human judgment. However, in everyday conversations, we often use these terms interchangeably. When we see variations in the predictions of five different forecasters, we might quickly assume they are biased—when in reality, it could just be noise. When a mother favours her child, is her decision biased or noisy? 

Let's understand the definition with an example. (In case you’re wondering we've considered too many examples, it’s because, in my experience, the best way to understand our own biases is by seeing them in action.)

Imagine that four teams of friends have gone to the shooting arcade. Each team consists of 5 people, they share one rifle and each person fires one shot. Figure 1 above shows their results. In an ideal world, every shot would hit the bull's eye.  

{{< image src="images/Noise1.png" caption="Figure 1: Four Teams, Image Source: Noise: A Flaw in Human Judgement" alt="alter-text" height="350" width="450" position="center" command="fill" option="q100" class="img-fluid" title="Humans and Rationale?"  webp="false" >}}

In Figure 1, that's exactly the case with **Team A with each shot being ideal**. We label **Team B as biased** because their shots consistently miss the target in the same way. As shown in the figure, the pattern of bias allows us to make predictions—if a team member takes another shot, we can expect it to land in the same area as the previous ones. This consistent error, known as bias, also suggests a probable cause—perhaps the rifle's gunsight is misaligned.

**Team C is noisy**, with shots scattered in all directions and no clear pattern. If a team member were to take a sixth shot, it would be difficult to predict where it would land. **Team D is both biased and noisy**, with shots consistently off-target and widely dispersed, showing a mix of systematic error and randomness.

**Bias refers to a systematic deviation, while noise represents random scatter present in data and decision-making.** As evident from the shots fired by Team D, both bias and noise can coexist.


{{< image src="images/Noise2.jpeg" caption="Figure 2: Looking at the back of the Target, Image Source: Noise: A Flaw in Human Judgement" alt="alter-text" height="400" width="450" position="center" command="fill" option="q100" class="img-fluid" title="Humans and Rationale?"  webp="false" >}}

Figure 2 highlights an important **difference between bias and noise**. It shows what you would see at the shooting range if you were shown only the back of the targets at which the teams were shooting, without any indication of the bull's eye they were aiming at. From this view, we can't tell whether Team A or B is closer to the target. However, we can clearly see that Team C and D are noisy, while Team A and B are not.

In general, noise is an error that can be identified and quantified without any knowledge of the target or underlying bias. It is independent of the specific target, meaning it persists regardless of the desired outcome. In contrast, bias is inherently linked to the target, as it represents a systematic error that arises when the target or goal is factored into the process. Bias is context-dependent, shaped by the alignment or misalignment with the target, whereas noise remains a random, uncontrollable disturbance.

> **"Wherever there is judgment, there is noise. And more than we can expect."** - _Noise: The Flaw in Human Judgement_

### Conclusion 

Flaws in intuitive judgment and decision-making are pervasive in various aspects of our lives. Whether it’s the [decoy effect](https://www.thelatenttruth.com/blog/decoyeffect/) influencing our choices  as consumers at the movies, or the noise disrupting clarity in S&OP meetings where stakeholders strive to reach consensus on sales projections, these biases and errors shape our decisions in subtle yet impactful ways. 

This doesn’t mean all variability is detrimental. Take, for example, ten different movie critics reviewing the same film— variability is not only expected but valued in areas like taste and competition. However, it’s essential to distinguish between unwanted variability, like noise, and wanted diversity. In our upcoming blogs, we'll explore how to differentiate the two and measure the impact of noise in systems. 

##### Sources 
- Noise: A flaw in human judgement 2021- Daniel Kahneman. Olive Sibony. Cass R. Sunstein. 
- Blog image from: https://www.linkedin.com/pulse/decision-making-daniel-kahneman-laxmi-abhay-yesff/ 
- Muller-Lyer image from: https://www.verywellmind.com/how-the-muller-lyer-illusion-works-4111110
 

