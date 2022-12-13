# Amazon_Vine_Analysis

## Overview of Analysis

### The purpose of this analysis is to examine amazon sports items by creating different tables to show their different aspects. The big data is also being used with pgAdmin and AWS databases. This allows tables to be created and the data to be inputted via the PySpark code. This README addresses Deliverable 2.

## Results

How many Vine review and non-Vine reviews were there?
  - Vine reviews = 334
  - Non-vine reviews = 61,614

How many Vine review were 5 stars? How many non-Vine reviews were 5 stars?
  - 5 star Vine = 139
  - 5 star non-vine = 32,665

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 41.62% of vine reviews were 5 stars
- 53.02% of non-vine reviews were 5 stars

## Summary

The sports dataset I examined seemed to have a much larger amount of non-vine reviews to vine reviews. This can lead towards a large amount of information geared toward non-vine reviews. In other words, with so much data, one can see a bias towards the non-vine reviews. Equally, there is a higher percentage of 5 star reviews for non-vine products. Not only are there a larger portion of non-vine reviews, but a larger portion of 5-star reviews compared to vine.

Instead of strictly looking at 5 star reviews, it would be useful to see how many negative reviews there may be. One can define a negative review as anything given 3 or lower stars. This number can be justified throughout the exploratory analytic process to define what constitutes a bad product.
