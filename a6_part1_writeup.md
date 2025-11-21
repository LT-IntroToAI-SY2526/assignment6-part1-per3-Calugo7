# Assignment 6 Part 1 - Writeup

**Name:** Caleb  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**
I would trust this model to predict a score for a student who studied 10 hours because in our data set, we have students who studied close to 10 hours so we can see a trend of what the data would look like. This would allow us to roughly estimate the score for a student who studied ten hours. The more and more outside of the range in our training data set we get, the more and more inacurrate the output may be.



---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
The relationship bewtween hours studied and test scores is pretty strong and linear because in real life, if one studies, they statistically have a better chance at getting a good score than those who do not study. This results in a linear relationship.



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. If the test taker is good at taking tests. (If they work well under pressure, retain the studying information)
2. Time management
3. Oddly worded questions may have the student confused even though they understand the topic


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**
We split our data into training and testing sets so that the program can have practice with the format of what it is going to see and later, test it again but with new numbers to see if there is mastery. If we trained and tested on the same data, the computer would probably already know the answers if thats possible, and you will not really see what the computer struggles with.



---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**
The most challenging part of this assignment was trying to understand everything. I already basically had the answers and just had to sub in a few things but I still do not understand why we use certain things because I am still learning this language.



---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** Square footage of a house
- **Target (Y):**  Price of house
- **Why this relationship might be linear:**
This relationship might be linear because the price varies depending on the square footage of a house. This bigger the house is, the more expensive the house gets, thus resulting in a linear relationship.
**YOUR ANSWER:**
Above This



---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [x ] Completed all functions in `a6_part1.py`
- [X ] Generated and saved `scatter_plot.png`
- [X ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
