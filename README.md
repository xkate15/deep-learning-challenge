# deep-learning-challenge
### Data Preprocessing

The target variable in this model is the "IS_SUCCESSFUL" column.

The feature variables in the final model were:
* NAME
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE
* ORGANIZATION
* INCOME_AMT
* ASK_AMT

The variables that were removed from the final model were:
* EIN - just an id number
* SPECIAL_CONSIDERATIONS - this column had over 34,000 'N' values and only 27 'Y' values. Not helpful.
* STATUS - this column had over 34k 1's and only 5 0's - only five of the rows are zeroes which is not helpful.

### Compaire two result
![image](https://user-images.githubusercontent.com/111816492/229983202-2d3eaced-0a3f-425f-a7a2-f5d9ab6a72c7.png)

![image](https://user-images.githubusercontent.com/111816492/229983261-1b835004-bab7-472a-ba03-066ace6ddc6e.png)

As an alternative to the nn model, a random forest classifier could be used
