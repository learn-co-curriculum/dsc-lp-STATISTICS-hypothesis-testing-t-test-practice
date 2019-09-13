---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 Sec 20 V2         <br/>
**Topic**:  Hypothesis Testing and T-Tests  <br/>
**Amount of time**: ~ 60 minutes <br/>
**Author**: Alison Peebles


***

#### Lesson Summary:

This lesson should begin with a teacher led discussion of reviewing hypothesis testing. For example, you might pose to the class "what are some scenario's in which we might want to conduct a hypothesis test?" From there, a discussion onto how to state an hyothesis test in terms of a null hypothesis and alternative hypothesis is reviewed. Afterwards, error rate are discussed as well as the difference between t and z-tests. Be sure to discuss the degrees of freedom's influence on the t-distributions tails, and how the distribution converges to the normal distribution as the degree's of freedom goes to infinity. Before moving on to the typical exercises, ask students how they would interpret the significance of a .05 alpha threshold. The XKCD cartoon provided should speak nicely to p-value hacking, and the implications of a p-value of .05; while we are 95% confident in the result, there is a 1 in 20 chance that even if all of our assumptions hold true, the results could have been the result of random chance alone. Be sure to point out the multiple comparisons problem as implied by the cartoon as well. Finally, 3 word problems regarding hypothesis t-tests are posed for students.


#### Topic:

#### Learning goals for this lesson:

* Students will be able to discuss the relationship between alpha and error.
* Student's will be able to describe hoow the degrees of freedom of a t-distribution affects the tails of the corresponding probability distribution function
* Students will be able to conduct 1-tailed t-tests using scipy.
* Students will be able to conduct 2-tailed t-tests using scipy.
* Students will be able to translate a problem into an appropriate 1 or 2 tailed t-test
* Students will be able to conduct a hypothesis using a t-test for a given scenario

#### Prerequisite knowledge:

* Student's should be able to estimate p-values from z-scores using the empirical rule.
* Student's should be able to interpret and explain z-scores.
* Student's should have previous exposure to Hypothesis Testing.
* Student's should have previous exposure to the t-distribution. 


#### Prequisite Learn-Materials:

* [Introduction to Experimental Design](https://github.com/learn-co-curriculum/dsc-experimental-design)
* [P-values and the Null Hypothesis](https://github.com/learn-co-curriculum/dsc-p-values-and-null-hypothesis)
* [Effect Sizes](https://github.com/learn-co-curriculum/dsc-effect-sizes)
* [Conducting T-Tests](https://github.com/learn-co-curriculum/dsc-t-tests)

#### Post Learn-Materials:

* [One Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-one-sample-t-tests-lab)
* [Two Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-two-sample-t-tests-lab)
* [Type 1 and Type 2 Errors](https://github.com/learn-co-curriculum/dsc-type-1-and-2-error)
* [Type 1 and Type 2 Errors - Lab](https://github.com/learn-co-curriculum/dsc-type-1-and-2-error-lab)


#### Relevant learning goals from Airtable: 

HYPOTHESIS_TESTS.1.recLqmFvhP7GR4PyT 
HYPOTHESIS_TESTS.1.recbxkgNPXSPG3iN4
HYPOTHESIS_TESTS.1.rec5Kh9sEvkkS0clN
HYPOTHESIS_TESTS.1.rec1Fok8VlRSDesEH
HYPOTHESIS_TESTS.2.recOBGkvuQiqdXrJq
HYPOTHESIS_TESTS.2.rec22hTTtcp6G1HLa
HYPOTHESIS_TESTS.2.recEEA8ZaFnsMSgN4
HYPOTHESIS_TESTS.3.rec5SXilsktLBVrLe
HYPOTHESIS_TESTS.2.recvJ1SIT8XkBjAzo
HYPOTHESIS_TESTS.2.recHMI9uZaDHbUvmQ
HYPOTHESIS_TESTS.3.recKRxrFajPLHlGsm



#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Degrees of freedom
* T-Distribution
* Z-Distribution
* Alpha
* Null Hypothesis
* Alternative Hypothesis

#### Lesson Outline:

* Introduction: Brainstorming Hypothesis Testing Scenarios (5-8 minutes)
* Review of Hypothesis Testing (10 minutes)
	* Null / Alternative Hypothesis
	* Error, Alpha
* Review of T Distribution (5 minutes)
	* T Distribution vs Z-Distribution
	* Degrees of Freedom
* Review of P-Value Interpretation (5-10 minutes)
	* Multiple Comparison Problem
* Question 1 (~ 10 minutes)
	* Problem Posed / Student work time (3+ minutes)
	* Solutions discussion / review (5+ minutes)
* Question 2 (~ 10 minutes)
	* Problem Posed / Student work time (3+ minutes)
	* Solutions discussion / review (5+ minutes
* Question 3 (~ 10 minutes)
	* Problem Posed / Student work time (3+ minutes)
	* Solutions discussion / review (5+ minutes)