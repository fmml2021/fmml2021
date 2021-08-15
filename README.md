## The case at Madagascar. 

People are falling sick due to Covid 19 and the government wants to vaccinate the citizens who are at highest risk, on priority.
A few features that contribute to risk, has been identified alongwith their extent of contribution. The risk factors are to be calculated and measured against a threshold value. All citizens who score beyond this threshold value are to be categorised as Risk-prone.

The data given is as such:

|Citizen ID | Age | Sugar Level (Blood) | Pollutant Level (Air) |
|-----|-----|----|----|
|AAA| 20 | 122 | 20 |
|AAB |35 | 180 | 35|
|ACA | 50 | 220 | 65|
|ABB | 70 | 300 | 30 |

Contribution of features to the disease:
|Feature| Weight|
|---|---|
|Age| 0.05|
|Blood Sugar| 0.002|
|Pollutant Level| 0.02|

The high-risk people are those whose "weighted-sum of all features" falls above 4.0

FMML team members are required to develop a prototype (preferably, a python function) that works, as soon as possible, and host it on their personal GitHub account. The python function should accept input data, which would be a set of features for citizens of Madagascar, and inform which of those citizens are prone to risk.
