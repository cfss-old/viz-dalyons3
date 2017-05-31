Neurophysiological responses to threatening and/or unexpected stimuli
========================================================
author: Don Lyons and Nicole Sullivan
autosize: true





Applied Question
========================================================

Why are some individuals resilient in the face of experienced aggression, while others develop high aggression?

Research Question
========================================================

How do those who have high lifetime committed aggression differ neurophysiologically from those who have low committed aggression?  How does lifetime experienced aggression impact this relationship?

Background, Methods & Techniques
========================================================

Lower alpha-amplitude, recently, has been correlated with high aggression.  This lower alpha-amplitude, generally, is correlated with recruitment of lesser cognitive resources in response to a stimulus.  In athletes, this "alpha burst" has been found to be helpful in reducing cognitive activity and increasing motor activity just prior to execution of a well-rehearsed movement, with optimal performance occurring following lowest alpha amplitude.  This study sought, first, to replicate findings that aggressive individuals exhibit lower alpha in response to angry stimuli, and second, sought explore differences between individuals who had low committed aggression, but high experienced aggression, and individuals who had both high committed and experienced aggression.

Stripchart of Expressions in the Angry Task
========================================================

```
{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE, warning = FALSE, message = FALSE)
```


Stripchart of Expressions in the Neutral Task
========================================================

![plot of chunk unnamed-chunk-3](Final_project-figure/unnamed-chunk-3-1.png)

Cairo's 5 Qualities of Great Visualizations
========================================================
*Truthful & Functional*  
We chose a stripchart because we wanted to preserve the amplitude for each individual and then map LHA score onto points using the color channel.  Each electrode was given a separate column because this is generally the most truthful way of conveying EEG data (vs. a cortical average which could be seen as data manipulation).  
  
*Beautiful*  
We chose jittering and transparency as further aesthetics for the points because we felt it a beautiful way of conveying the data truthfully.  
  
*Insightful & Enlightening*  
Using color to encode LHA, it's possible to see that there is really no pattern with increasing aggression - those with both low and high LHA scores are scattered across all amplitudes.

Race Boxplot for P3 in Angry Task
========================================================

![plot of chunk unnamed-chunk-4](Final_project-figure/unnamed-chunk-4-1.png)

Cairo's Qualities
========================================================
*Truthful & Functional*  
When analysis returned several significant interactions for race, we wondered if the P3 component also differed as a function of race.  However, via visualization, we were able to determine that this result was due to the responses of the Asian/Pacific Rim group, which had only two subjects.  Therefore, this visualization itself was an end to truth in analysis.  
  
*Beautiful*  
We chose color because we found it a highly attractive way to distinguish each race from another.  
  
*Insightful & Enlightening*  
Again, the insights gleaned via this visualization were highly useful - not only did they deter us from drawing improper conclusions (that neurophysiological responses differ as a function of race), but they enlightened us:  quite interestingly, it appears that all races have similar P3 amplitude in response to different facial stimuli.

Comparing Responses as a Function of Aggression
========================================================

![plot of chunk unnamed-chunk-5](Final_project-figure/unnamed-chunk-5-1.png)

Comparing Responses as a Function of Aggression
========================================================

![plot of chunk unnamed-chunk-6](Final_project-figure/unnamed-chunk-6-1.png)

Cairo's Qualities
========================================================
*Truthful & Functional*  
We chose to use color to encode expression so that expressions would appear on the same graph and would be easier to compare to one another.  In this case, infrequent neutral stimuli were jittered with frequent happy stimuli for the purposes of the P3 analysis; hence, we were interested if responses appeared to be significantly different in the frequency condition based on expression.  
  
*Beautiful*  
We used the built-in ggplot colors to distinguish between the two different expressions because we felt that the red and blue contrast nicely.  We greyed fonts to bring out the color of the points, and to complement the palette more closely.  We also changed most of the fonts to serif as these are generally easier to read and used more often for scientific audiences.  
  
*Insightful & Enlightening*  
We chose to include trend lines because their close proximity is enlightening - it shows that responses to the two different expressions don't differ significantly - furthermore, despite a spike in the middle (which is easier to see is caused by one or two individuals with especially high amplitude alpha), the line is mainly flat, indicating that low aggressives and high aggressives don't exhibit significant differences in alpha amplitude in response to either neutral or happy faces.

Comparing Responses of Groups
========================================================

![plot of chunk unnamed-chunk-7](Final_project-figure/unnamed-chunk-7-1.png)

Comparing Responses of Groups
========================================================

![plot of chunk unnamed-chunk-8](Final_project-figure/unnamed-chunk-8-1.png)

Cairo's Qualities
========================================================
*Truthful & Functional*  
We chose to use color to encode expression so that expressions would appear on the same graph and would be easier to compare to one another.  In this case, infrequent neutral stimuli were jittered with frequent happy stimuli for the purposes of the P3 analysis; hence, we were interested if responses appeared to be significantly different in the frequency condition based on expression. 
  
*Beautiful*  
We used the built-in ggplot colors to distinguish between the two different expressions because we felt that the red and blue contrast nicely.  We greyed fonts to bring out the color of the points, and to complement the palette more closely.  We also changed most of the fonts to serif as these are generally easier to read and used more often for scientific audiences.  
  
*Insightful & Enlightening*  
We chose to include trend lines because their close proximity is enlightening - it shows that responses to the two different expressions don't differ significantly - furthermore, despite a spike in the middle (which is easier to see is caused by one or two individuals with especially high amplitude alpha), the line is mainly flat, indicating that low aggressives and high aggressives don't exhibit significant differences in alpha amplitude in response to either neutral or happy faces.
