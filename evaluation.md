# Lab 01 Evaluation

## 1. What was the most challenging part of this lab for you, and how did you overcome it?

The most challenging part for me was creating the average_coffee column. I had to understand how to use the coffee_consumed and swipes columns together. I overcame this by dividing coffee consumption by the number of swipes. I also checked the results to make sure the calculation was correct.

## 2. Which dining hall did you choose to analyze?

I chose to analyze the Brooks dining hall.

## 3. For your chosen dining hall, which day had the highest coffee consumption per swipe?

For Brooks, January 26, 2024 had the highest coffee consumption per swipe. The average was approximately 0.3077 coffee per swipe.

## 4. How would you determine which day had the lowest coffee consumption per swipe for your dining hall?

I would sort the average_coffee column in ascending order instead of descending order. The first row would then show the day with the lowest coffee consumption per swipe. I could use: filtered_df.sort_values(by="average_coffee", ascending=True).head()
