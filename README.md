## Overview

This project is to analyze Amazon reviews written by members of the Amazon Vine program(a service from thata allows manufacturers to review the reviews of their own products to detect any biases from Vine reviewers and non-Vine reviewers. We will apply the ETL process with data hosted on AWS.


## Results

The dataset based on video game reviews had over a million reviews recorded. Using Google Collab, we reduced the reviewers down based on this criteria:

- Count of Total Votes equal or greater than 20.
- Percent of Helpful Votes to Total Votes equal or greater than 50%.

Based on this data we were able to answer the following questions:


How many Vine reviews and non-Vine reviews were there?
94 Vine reviews and 40,471 non-Vine reviews.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
48 5 star Vine reviews, 15,663 5 star non-Vine reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51% for Vine users gave 5 star reviews, 39% for non-None users gave 5 star reviews

<img src="https://raw.githubusercontent.com/hdolci/Amazon_Vine_Analysis/main/Vine%20Analysis%20Final%20Result.png" width="50%" height="50%">


## Summary

Vine members did not show a convincing bias when rating their products. Vine users did have a higher rate of giving 5 star reviews but there appears to be a limited number of Vine users. If this exercise was done again, I would suggest we change the criteria to allow more reviews to be analyzed to see if this still holds true.
