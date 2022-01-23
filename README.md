# Amazon_Vine_Analysis

## Overview of the project

The Vine program allows sellers to pay a small fee to recieve feedback from customers. This analysis will try to determine if ther is any bias that might cause Vine program buyers to give higher grades.

## Results:

### Total votes (filters)

![over_20_votes](https://user-images.githubusercontent.com/89816213/150699299-5d78e949-4ada-4a46-ac64-dba35db0d6c1.PNG)

Some products don't count with a significant number of votes to be considered in our analysis. We have determined that only productos with a vote count equal or higher than 20 will be considered for our study.

![helpful_votes](https://user-images.githubusercontent.com/89816213/150699301-448dcba3-0529-44c0-9e90-8dceec215927.PNG)

Not all votes are useful for a wide range of possibilites, so we will only consider the products which percentage of helpful votes is equal or higher than 50%.

### Vine Reviews

![vine_rev](https://user-images.githubusercontent.com/89816213/150699410-16cec1ea-0ce7-4031-8ba0-d7095e08f2b5.PNG)

This image shows the filter to consider only those reviews that come from the Vine program.

![vine_five_stars](https://user-images.githubusercontent.com/89816213/150699411-82158bb6-3694-4ea5-9eae-c4e4ffb951e5.PNG)

The number of Vine reviews is quite low, and it might not be significant. Eventhough, ther seems to be no proof that beeing involved in the vine program causes a bias towards positive ratings.

### Non Vine Reviews

![non_vine_rev](https://user-images.githubusercontent.com/89816213/150699660-a638fece-2797-4412-a1c3-73185ef33024.PNG)

Just as we did with the Vine reviews, we filtered all reviews not related to the Vine program to set a parameter of how good the ratings are when not invovling incentives.

![non_vine_five_stars](https://user-images.githubusercontent.com/89816213/150699663-a9a79ccb-d8c3-4901-9a9c-3f1f84bb96ac.PNG)

The non Vine related ratings are considerably higher than those from the paid program.

## Summary

If we consider both datasets, we might think that the premise might actually be the opposite to the one we first stated, since non-paid clients givee higher ratings, this could lead to think that the incentive makes buyers more incisive.

An additional analysis to clear all doubt could  involve integrating a new dataset and compare Vine and non Vine related ratings with their match on the other dataset, if there is any similarity we could think that ratings could be affected, though not necessarily possitively biased.
