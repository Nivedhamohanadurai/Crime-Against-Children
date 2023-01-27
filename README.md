# Crime-Against-Children
Using Hadoop

## Pre-Processing:

-> Field structure for year is formatted to YYYY-MM-DD instead of YYYY.

-> State and District formatted together as single field.

## Methodolgy:

-> Initially, the Euclidean distance is calculated between the given test data and each record that is to be classified.

-> The distance is sorted and we take the top 5 values.

-> Among the chosen 5 values, we calculate the number of data points in each category.

-> The test data points are assigned to the category (i.e., state_district) with the highest number of neighbors.

## Processing:

![image](https://user-images.githubusercontent.com/67183417/215157375-34955002-5776-4441-9a76-73f3e3a31bde.png)

![image](https://user-images.githubusercontent.com/67183417/215157614-bc35e3c1-b23f-422e-8c0a-605f90676e4f.png)

## Output:

![image](https://user-images.githubusercontent.com/67183417/215157684-29f49ccb-b644-4d9e-b95d-8db044de539e.png)

## Inference:

MANDI district of Himachal Pradesh have a higher chance of murder, rape and kidnapping and abduction cases occuring for the input with ration (3:10:5).

## Other outputs:

![image](https://user-images.githubusercontent.com/67183417/215158512-2683f1c4-71a3-4460-9a6e-dcc8086c63e2.png)
