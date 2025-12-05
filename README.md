Workout Intensity and Calorie Burn Analysis
================
by Aasya, Rachel, Fraol and Hannah

## Summary

This project analyzes how different workout types and body composition characteristics influence fitness outcomes, specifically focusing on calorie expenditure and heart rate response. Using a lifestyle dataset of 20,000 participants tracked through wearable fitness devices, we examined 11 key variables including demographic information (age, gender), physical characteristics (weight, height, BMI), workout details (type, duration, calories burned), and heart rate metrics (max, average, and resting BPM).

## Research Questions

Our analysis addressed two primary questions:

1. How do different workout types (Strength, HIIT, Cardio, Yoga) affect an individual's heart rate response?
2. How do physical characteristics such as BMI, weight, and age influence calories burned and heart rate during workouts?

## Methods

We used visualization-based analysis using R (tidyverse, ggplot2) to explore patterns across workout types and body composition categories. Our approach included violin plots combined with box plots to compare calorie burn distributions and identify the median and outliers across workout types, smoothed line charts to examine weight-heart rate relationships across genders, and box plots to analyze BMI group differences. We categorized BMI into four standard groups (Underweight <18.5, Normal 18.5-24.9, Overweight 25.0-29.9, Obese ≥30.0) to examine body composition effects.

## Key Findings

`Workout Type Dominates Intensity`: HIIT workouts produce the highest median calorie burn (1,700 calories) with the widest variation (500-3,000 calories), indicating high intensity with individual performance differences. Cardio shows consistent moderate burn (~1,200 calories) with narrow distribution, Strength training demonstrates variable results (1,400 median), and Yoga produces the lowest burn (~850 calories) with the most consistent outcomes.

`Weight Heart Rate Relationship` : Across all workout types and both genders, individuals weighing 90-110 kg consistently reach the highest maximum heart rates. This "sweet spot" likely represents optimal cardiovascular demand, which is heavy enough to elevate heart rate significantly, yet participants remain fit enough to achieve true maximum intensity. When the weight increases and reaches this range, it is likely that the heart is pumping blood faster than for a person with less body mass or with excess body mass(<110 kgs). The relationship between weight and max BPM follows similar patterns for males and females, though males show slightly more variability at higher weights.

`Gender Specific Workout Ressponses` : An interesting finding emerged in gender specific heart rate peaks. For females, Strength and Yoga produce the highest max BPM values, while males reach peak heart rates during Strength and HIIT workouts. This suggests different physiological responses or training approaches between genders, where males may push harder during explosive, interval-based exercise, while females achieve higher heart rates during sustained effort activities like Yoga.

`BMI shows Weak Predictive power` : Unlike workout type, BMI does not clearly predict calorie expenditure. The Normal BMI group displays the largest interquartile range, indicating high variability in calorie burn regardless of a 'healthy' body composition. Underweight and Obese categories produce more outliers and lower median calorie expenditure, but the wide spread within each category suggests that factors beyond body size, such as fitness level, effort intensity, and conditioning, play more significant roles.

## Limitations
1. `No fitness level data`: We cannot distinguish between trained athletes and beginners, which significantly affects calorie burn and heart rate response.
2. `No workout intensity control`: HIIT sessions vary widely (Tabata vs. longer intervals). We don't know exact protocols used.
3. `Yoga type unknown`: Yoga could range from gentle restorative to intense Power Yoga, and both have vastly different intensities.
4. `Missing duration details`: We have session duration but don't know rest periods, which affect total calorie expenditure.
5. `BMI doesn't distinguish muscle vs fat`: A muscular athlete and an untrained person with high body fat could have identical BMI but vastly different fitness outcomes, and it is also not a fitness indicator since BMI tells us nothing about cardiovascular fitness, strength, or metabolic health.
6. `Self Selection Bias`: Participants may have chosen workout types they already excel at, inflating certain metrics.

## Conclusions

Our analysis makes us believe that workout type selection matters more than body composition when determining exercise intensity and energy expenditure. While body weight correlates with maximum heart rate (particularly in the 90-110 kg range), BMI alone is a poor predictor of workout performance. The data suggests that individuals should prioritize choosing appropriate exercise types based on their fitness goals rather than just focusing on body composition metrics. HIIT delivers the highest calorie burn for those seeking maximum energy expenditure, while Cardio provides consistent, moderate intensity options. The gender specific patterns in heart rate response highlight the importance of personalized exercise programming that accounts for individual physiological differences beyond simple body measurements.

## Future Research

Future research should employ longitudinal designs tracking individuals over time to observe training adaptations. Replacing BMI with body composition analysis would provide more accurate insights into how muscle mass and body fat influence workout performance. Standardizing workout protocols and controlling for fitness level would allow more precise comparisons and additionally, investigating recovery metrics, metabolic health markers, and gender-specific physiological mechanisms could enhance personalized exercise prescription.

## Handout

Our handout can be found [here](handout/handout.pdf).

## Memo

A link to the code and how we created our graphics in our memo can be found [here](memo/memo.html).

## Data

Kaggle and Omar Essa, “Lifestyle,” Data set, September 2025, accessed December 4, 2025, https://www.kaggle.com/datasets/jockeroika/life-style-data/data.

## References

1. Kaggle and Omar Essa, “Lifestyle,” Data set, September 2025, accessed December 4, 2025, https://www.kaggle.com/datasets/jockeroika/life-style-data/data. 
2. Carla E. Cox, “Role of Physical Activity for Weight Loss and Weight Maintenance,” Diabetes Spectrum 30, no. 3 (August 1, 2017): 157–60, https://doi.org/10.2337/ds17-0013. 
3. Christine Byrne Mph Ldn Rd, “6 Factors That Can Affect How Many Calories You Burn,” EverydayHealth.com, November 21, 2023, https://www.everydayhealth.com/fitness/factors-that-can-affect-how-many-calories-you-burn/. 
