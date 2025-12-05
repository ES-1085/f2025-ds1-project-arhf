Project title
================
by Aasya, Rachel, Froal and Hannah

## Summary

This project analyzes how different workout types and body composition characteristics influence fitness outcomes, specifically focusing on calorie expenditure and heart rate response. Using a lifestyle dataset of 20,000 participants tracked through wearable fitness devices, we examined 11 key variables including demographic information (age, gender), physical characteristics (weight, height, BMI), workout details (type, duration, calories burned), and heart rate metrics (max, average, and resting BPM).

## Methods

We used visualization-based analysis using R (tidyverse, ggplot2) to explore patterns across workout types and body composition categories. Our approach included violin plots combined with box plots to compare calorie burn distributions and identify the median and outliers across workout types, smoothed line charts to examine weight-heart rate relationships across genders, and box plots to analyze BMI group differences. We categorized BMI into four standard groups (Underweight <18.5, Normal 18.5-24.9, Overweight 25.0-29.9, Obese ≥30.0) to examine body composition effects.

## Key Findings

`Workout Type Dominates Intensity`: HIIT workouts produce the highest median calorie burn (1,700 calories) with the widest variation (500-3,000 calories), indicating high intensity with individual performance differences. Cardio shows consistent moderate burn (~1,200 calories) with narrow distribution, Strength training demonstrates variable results (1,400 median), and Yoga produces the lowest burn (~850 calories) with the most consistent outcomes.

`Weight Heart Rate Relationship` : Across all workout types and both genders, individuals weighing 90-110 kg consistently reach the highest maximum heart rates. This "sweet spot" likely represents optimal cardiovascular demand, which is heavy enough to elevate heart rate significantly, yet participants remain fit enough to achieve true maximum intensity. When the weight increases and reaches this range, it is likely that the heart is pumping blood faster than for a person with less body mass or with excess body mass(<110 kgs). The relationship between weight and max BPM follows similar patterns for males and females, though males show slightly more variability at higher weights.

`Gender Specific Workout Ressponses` : An interesting finding emerged in gender specific heart rate peaks. For females, Strength and Yoga produce the highest max BPM values, while males reach peak heart rates during Strength and HIIT workouts. This suggests different physiological responses or training approaches between genders, where males may push harder during explosive, interval-based exercise, while females achieve higher heart rates during sustained effort activities like Yoga.

`BMI shows Weak Predictive power` : Unlike workout type, BMI does not clearly predict calorie expenditure. The Normal BMI group displays the largest interquartile range, indicating high variability in calorie burn regardless of a 'healthy' body composition. Underweight and Obese categories produce more outliers and lower median calorie expenditure, but the wide spread within each category suggests that factors beyond body size, such as fitness level, effort intensity, and conditioning, play more significant roles.

## Conclusions

Our analysis makes us beliebe that workout type selection matters more than body composition when determining exercise intensity and energy expenditure. While body weight correlates with maximum heart rate (particularly in the 90-110 kg range), BMI alone is a poor predictor of workout performance. The data suggests that individuals should prioritize choosing appropriate exercise types based on their fitness goals rather than just focusing on body composition metrics. HIIT delivers the highest calorie burn for those seeking maximum energy expenditure, while Cardio provides consistent, moderate intensity options. The gender specific patterns in heart rate response highlight the importance of personalized exercise programming that accounts for individual physiological differences beyond simple body measurements.

## Handout

Our handout can be found [here](handout/handout.pdf). You can update the filename and extension of your handout, currently it is called handout.pdf

## Memo

A link to the code and how we created our graphics in our memo can be found [here](memo/memo.html).

## Data

Include a citation for your data here. See
<http://libraryguides.vu.edu.au/c.php?g=386501&p=4347840> for guidance
on proper citation for datasets. If you got your data off the web, make
sure to note the retrieval date.

## References

List any references here. You should, at a minimum, list your data
source.
