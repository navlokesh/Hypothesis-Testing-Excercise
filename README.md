# Hypothesis Testing:
A statistical hypothesis test is a method of statistical inference used to decide whether the data at hand sufficiently support a particular hypothesis. Hypothesis testing allows us to make probabilistic statements about population parameters.

In this excercise, we will check how to perform hypothesis testing. Below is the explanation of data being used and different hypothesis testings conducted.
Please visit the jupyter notebook for better insightful study on the coding part.

## Data:
An important quality characteristic used by the manufacturers of ABC asphalt shingles is the amount of moisture the shingles contain when they are packaged. Customers may feel that they have purchased a product lacking in quality if they find moisture and wet shingles inside the packaging. In some cases, excessive moisture can cause the granules attached to the shingles for texture and colouring purposes to fall off the shingles resulting in appearance problems. To monitor the amount of moisture present, the company conducts moisture tests. A shingle is weighed and then dried. The shingle is then reweighed, and based on the amount of moisture taken out of the product, the pounds of moisture per 100 square feet is calculated. The company claims that the mean moisture content cannot be greater than 0.35 pound per 100 square feet.
The file (A & B shingles.csv) includes 36 measurements (in pounds per 100 square feet) for A shingles and 31 for B shingles.

### Let us assume the below question:
For the A shingles, form the null and alternative hypothesis to test whether the population mean moisture content is less than 0.35 pound per 100 square feet.
tstat and p_value of the test comes out to be (-1.4735046253382782, 0.14955266289815025) respectively.

#### Assuming Alpha = 5%
#### Hypothesis:
#### Null : Mean moisture content is greater than or equal to 0.35
#### Alternate: Mean moisture content is less that 0.35
Since P value is 14.95 %, which is greater than alpha for all 3 significance values(99%, 95% and 90%), we fail to reject the null hypothesis.
Hence, for the A shingles, the population mean moisture content is greater than or equal to 0.35.
That is, the population mean moisture content is not less than 0.35

### Another such example would be:
For the B shingles, form the null and alternative hypothesis to test whether the population mean moisture content is less than 0.35 pound per 100 square feet.
tstat and p_value of the test comes out to be (-3.1003313069986995, 0.004180954800638363) respectively.

#### Assuming Alpha = 5%
#### Hypothesis:
#### Null : Mean moisture content is greater than or equal to 0.35
#### Alternate: Mean moisture content is less that 0.35
Since P value is 0.418 %, which is lesser than alpha for all 3 significance values(99%, 95% and 90%), we will reject the null hypothesis.¶
Hence, for the B shingles, the population mean moisture content is less than 0.35

### Test of equality
### Assumptions:

Few assumptions need to be made while performing hypothesis tests for equality. Listed below are the few assumption.

#### Data is randomly sampled from the population of interest
#### The data variables follow a normal distribution. Only then one can specify a level of probability (alpha level, level of significance, p) as a criterion for acceptance.
#### Sample size is reasonably large enough to perform the hypothesis tests.
#### The samples are independent of each other
#### Data is continuous

### Let us check an example of test of equality:
Checking if the population means for shingles A and B are equal. Forming the hypothesis and conduct the test of the hypothesis.
tstat and p_value of the test comes out to be (1.289628271966112, 0.2017496571835328) respectively.

#### Assuming Alpha = 5%
#### Hypothesis:
#### Null : Population means of shingles A and B are equal
#### Alternate: Population means of shingles A and B are not equal
#### Inference:
From the T Test of two independent variables, we see that the P value is 20.17%, which is higher than our Alpha value. So, we fail to reject the null hypothesis.
Hence, the population means for shingles A and B are equal.

### Assumptions about population data:
#### While conducting such tests or performing any such analysis on the data, a set of assumptions about the population distribution is needed. Below are such assumptions about the population data:
#### The data variables of the population follow a normal distribution. Only then one can specify a level of probability (alpha, level of significance, p) as a criterion for acceptance or rejection.
#### Data is continuous

#### We would also need to have few Assumptions about Sample data as well. They are listed below:

#### Sample data is randomly selcetd from the population
#### Sample size is suffuciently large enough to perform the hypothesis tests.
#### Each sample of population data is independed of each other
