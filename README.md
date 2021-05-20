# P19.-Hypothesis-Testing-2-Proportion-T-test-Students-Jobs-in-2-States-
![image](https://user-images.githubusercontent.com/71163471/118952779-da533680-b979-11eb-82c9-557e1a8c2593.png)

2 Proportion ttest (comparing percentages) 

Assume Null Hypothesis as Ho is p1-p2 = 0 i.e. p1 ≠ p2. Thus Alternate Hypthesis as Ha is p1 = p2.

Explanation of bernoulli Binomial RV: np.random.binomial(n=1,p,size) Suppose you perform an experiment with two possible outcomes: either success or failure. Success happens with probability p, while failure happens with probability 1-p. A random variable that takes value 1 in case of success and 0 in case of failure is called a Bernoulli random variable. Here, n = 1, Because you need to check whether it is success or failure one time (Placement or not-placement) (1 trial) p = probability of success size = number of times you will check this (Ex: for 247 students each one time = 247) Explanation of Binomial RV: np.random.binomial(n=1,p,size) (Incase of not a Bernoulli RV, n = number of trials) For egs: check how many times you will get six if you roll a dice 10 times n=10, P=1/6 and size = repetition of experiment 'dice rolled 10 times', say repeated 18 times, then size=18.

As (p_value=0.7255) > (α = 0.05); Accept Null Hypothesis i.e. p1 ≠ p2 There is significant differnce in population proportions of state1 and state2 who report that they have been placed immediately after education.
