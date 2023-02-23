# Amazon_Vine_Analysis
## Analysis Overview
In this analysis we used PySpark and the ETL process to look into the Amazon Vine program and see if there is any bias toward favorable reviews from Vine members.
## Results
### How many Vine reviews and non-Vine reviews were there?
After sorting through the datasets, it was revealed that there were a total of 94 Vine reviews and 40,471 non-Vine reviews.

![94](https://user-images.githubusercontent.com/115501756/220843867-11c322a8-8066-4561-851b-fa31a7dd0209.png)
![40471](https://user-images.githubusercontent.com/115501756/220843887-450977dd-114c-4c25-b138-3b70ad81e746.png)

### How many Vine reviews were 5 stars? How many non-Vine rewviews were 5 stars?
The data reveals that there were a total number of 48 five-star reviews from Vine reviewers and 15,663 five-star reviews from non-Vine reviewers.

![48](https://user-images.githubusercontent.com/115501756/220843937-2a7033e8-5694-4657-8533-f60bb0b511f1.png)
![15663](https://user-images.githubusercontent.com/115501756/220843954-c6c774d4-0f1f-49e6-b936-42ba3ef0e04a.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Roughly 51% of Vine reviews were 5 stars and 38% of non-Vine reviews were 5 stars.

![51](https://user-images.githubusercontent.com/115501756/220843999-b5f1118a-14c8-4b9c-bcff-4bfe9e7e524f.png)
![38](https://user-images.githubusercontent.com/115501756/220844024-dde7dfcc-a7ec-4f2d-adb7-2b2e215b4204.png)

## Summary
Aftering reviewing the data, it was revealed that a considerably larger percentage of Vine reviewers were providing five-star reviews as to non-Vine reviewers. While only 39% of reviews from non-Vine reviewers were five-stars, it was 51% for Vine reviews. This proves, or at least further suggests, that Vine creates positive bias in its reviews.

For further analysis, I would consider looking at the means, medians and modes of the data.
