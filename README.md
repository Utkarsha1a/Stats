# Z Test

Z-test is a statistical method to determine whether the distribution of the test statistics can be approximated by a normal distribution. It is the method to determine whether two sample means are approximately the same or different when their variance is known and the sample size is large (should be >= 30).

#### When to Use Z-test:

1. The sample size should be greater than 30. Otherwise, we should use the t-test.
2. The standard deviation of the population should be known.
3. The data should be normally distributed, however for large sample size, it is assumed to have a normal distribution.
	
![image](https://user-images.githubusercontent.com/89068470/149986807-9276907f-d277-46f8-b2be-cca8ef06e24c.png)

#### Type 1 and Type 2 Error
![image](https://user-images.githubusercontent.com/89068470/149988317-b6ec6dcd-859d-4324-ad1a-729c4f83d128.png)


### Z Test Or T Test

![image](https://user-images.githubusercontent.com/89068470/149987148-9e66ea60-8bc3-47f4-bfbf-1c9fbc47bd6b.png)



# ONE WAY ANNOVA :- 

ANOVA tells you if there are any **statistical differences between the means of three or more independent groups.**

![image](https://user-images.githubusercontent.com/89068470/149974899-4c2bcc48-a32f-482b-a75a-b86dc19c0d2a.png)

![image](https://user-images.githubusercontent.com/89068470/149975702-575e2f91-94d5-4d3c-9111-a82da4944d1f.png)


Fcalculated > Ftabulated/critical or p<0.05     **Reject Ho & Accept Ha**

Fcalculated < Ftabulated/critical or p>0.05     **Accept Ho**

### Limitations of one-way ANOVA

A one-way ANOVA tells us that at least two groups are different from each other. But it won’t tell us which groups are different. 

If our test returns a significant f-statistic, we may need to run a post-hoc test to tell us exactly which groups have a difference in means.
