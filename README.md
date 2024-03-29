# MechaCar_Statistical_Analysis
Statisitical analysis of automobile performance with R
## Linear Regression to Predict MPG
<img width="624" alt="Screen Shot 2021-06-29 at 6 00 16 PM" src="https://user-images.githubusercontent.com/77812423/123873466-85092e00-d904-11eb-9bdc-8e0933da1f04.png">

- The variable that gives a non-irregular measure of difference to the mpg values in the dataset is vehicle length and vehicle ground freedom since they altogether affect miles per gallon on the mechanical model. The p-upsides of vehicle weight, spoiler point, and all-wheel drive demonstrate an arbitrary measure of difference with the dataset.

- The incline of this straight model isn't zero in light of the fact that the p-worth of this model is 5.35e-11 which is more modest than the critical degree of 0.05% and furthermore gives adequate proof to dismiss the invalid speculation.

- The straight model predicts the mpg of MechaCar models viably on the grounds that the r-squared worth is 0.7149, which implies about 71% of all mpg expectations will be dictated by this model

## Summary Statistics on Suspension Coils
<img width="342" alt="Screen Shot 2021-06-29 at 6 07 39 PM" src="https://user-images.githubusercontent.com/77812423/123873811-18426380-d905-11eb-9810-5cf555651364.png">
<img width="492" alt="Screen Shot 2021-06-29 at 6 07 54 PM" src="https://user-images.githubusercontent.com/77812423/123873818-19739080-d905-11eb-8954-7a1b753f15d1.png">

- Taking a statistics at rundown insights for the PSI of MechaCar suspension curls the change of the loops is 62.29PSI, which meets the necessities determinations for the MechaCar suspension curls that direct that the difference of the suspension curls should not surpass 100.

- While the overall variance, as shown in the Total Summary data above, is under 100 psi and meets specifications, there is a problem with one of the individual lots. As shown in the Lot Summary stats, the variance for Lot 3 is well over the acceptable threshold, at 170.28.

## T-Tests on Suspension Coils
<img width="412" alt="Screen Shot 2021-06-29 at 6 11 02 PM" src="https://user-images.githubusercontent.com/77812423/123873991-69eaee00-d905-11eb-935e-f7a53e84578b.png">
- The p-value incentive for all assembling parcels is 0.06, which is over the 0.05% huge level, which implies that this information isn't genuinely critical and demonstrates solid proof for the invalid theory.

<img width="571" alt="Screen Shot 2021-06-29 at 6 14 01 PM" src="https://user-images.githubusercontent.com/77812423/123874229-d36afc80-d905-11eb-9611-018106eddc30.png">
- A review of the results of the T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough (1) for us to reject the null hypothesis.

<img width="573" alt="Screen Shot 2021-06-29 at 6 16 58 PM" src="https://user-images.githubusercontent.com/77812423/123874502-4a07fa00-d906-11eb-9441-09d3e6fc084f.png">

- A review of the results of the T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis.

<img width="574" alt="Screen Shot 2021-06-29 at 6 18 57 PM" src="https://user-images.githubusercontent.com/77812423/123874696-8f2c2c00-d906-11eb-9e45-1786ddf8bd72.png">
- A review of the results of the T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis. This lot may be need to be discarded, or at least more closely evaluated.

## Study Design: MechaCar vs Competition
There are many factors that consumers take into consideration when evaluating a car to purchase. However, in a world where ridesharing is becoming more ubiquitous and it's easy and cheap to get around in other people's vehicles, customers looking to purchase a car are looking for more than just a conveyance. They will be looking to buy a car that is an economical means to regularly transport themselves and their items on a reliable, regular basis.

## Metric to test
To narrow down our test, we should evaluate MechaCar's carrying capacity, in cubic inches, in comparison to various competitors' vehicles.

## Null and Alternate Hypothesis
H0: MechaCar prototypes' average carrying capacity is similar to competitor's vehicles in the same vehicle class Ha: MechaCar prototypes' average carrying capacity is statistically above or below that of competitor vehicles.

## Statistical Test Used
The best statistical test for this would be two-sample t-tests.

## What data is needed
We would need to gather cubic space data from the carrying compartments of all MechaCar prototypes, as well as from all major competitor vehicles.
