# Introduction

A/B tests are very commonly performed by data analysts and data scientists.

For this project, I will be working to understand the results of an A/B test run by an e-commerce website. My goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

I first find the results manually using binomial distribution and bootstrap, and again using the statsmodels library.
I then use a regression with interaction terms to come to the same conclusions for our test.
