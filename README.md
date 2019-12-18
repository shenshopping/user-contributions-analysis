# User Contributions Analysis
Eluvio DS Challenge from the perspective of user contribution behavior on social media.

### 0 Exploratory Data Analysis

This part is about some basic exploratory analysis of the dataset.

### 1 Text Preprocessing and Classification Model

- Text preprocessing, including tokenizing, lemmatizing.
- Divided each post into two categories based on the number of upvotes it received. Developed two different classification models to predict the number of upvotes of an author’s initial post on the platform. I only chose each author’s first post to eliminate irrelevant factors.
- It turns out that both models did not perform much better than random assignment, indicating the number of upvotes of an author’ first post is unpredictable, or to say, is more like a random assignment.

### 2 Further Discussion

Given the conclusion from the last part, we want to know what’s the impact of the number of upvotes on an author’s continuous contribution behaviors. Conclusions include:

- Authors with high initial upvotes (more than 20 upvotes for the very first post of the author) are more likely to contribute continuously to the platform. However, they might not post as frequent as those with low initial upvotes. Probably because they feel more pressure and are more cautious about their new posts.
- In short term (a month), there seem to be no difference in number of posts.
- In long term (a year), authors with high initial upvotes tend to contribute more, indicating incentive effect of the number of upvotes from their first post.
