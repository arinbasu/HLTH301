---
title: Test
author: Arindam Basu
bibliography: references.bib
---

## Concepts of Cause and effect
A is a cause of Y if:
- A precedes Y in time
- if A is validly associated with Y

A valid association between A and Y is deemed when:
- The association between A and Y cannot  be accounted for due to chance,
- When a third variable L cannot explain the association between A and Y,
- When the association between A and Y cannot be due to observation, 
reporting,
or measurement errors referred to as biases.

Only after we have ruled out the play of chance,
eliminated biases,
and controlled for confounding variables,
we will be able to state A and Y have a valid association between them. 
But presence of such association does not necessarily mean that they are causally linked with each other.
This is why it is often said that correlation does not prove causation. 
What factors must we consider before we can state that an association is also causal?
There are several ways in which such associations can be discussed in the context of health sciences.
In 1965, Sir Austin Bradford Hill identified nine viewpoints,
which later were used as 'Hill's Criteria' @hill1965. 
These are:
1. Strength of association
2. Consistency
3. Biological gradient
4. Temporality
5. Replicability

However, these conditions are not always satisfied in all situations.
In 1987, 
Rothman and Greenland came up with the theory of counterfactual theories of causation,
where they showed that causal models can be constructed such that they would be necessary and sufficient[@rothman].
A sufficient causal model is one where different causal factors combine to cause the event. 
A necessary causal variable is one that must be present in all the different sufficient causal models.

## How do we assess the extent to which a factor is strong enough to be causal?

This is where counterfactual theories of causation play a role and we will discuss this here.
Counterfactual theories of causation state that if a factor A is deemed to be a cause of an event Y,
then,
we will be able to show that the likelihood of Y occurring is different when A is present as opposed to when A is absent.
If we are able to observe the occurrence of Y or Probability of occurrence of Y under two circumstances,
once when A is present, and when A is absent, 
and then,
if we are able to measure the probabilities of Y occurrence under those two situations,
then,
we are able to assess whether A might be a cause of Y or not.
If the likelihoods of Y occurrence are same regardless of whether A is present or absent,
then we state that Y is indepdent of A. 
In symbol:
Y $\perp$ A
Besides,
The strength of association of A with Y is estimated from its effect size.
For example,
consider the following table:

| Treatment  | Outcome Y | not Y |
|------------|-----------|-------|
| A          | 80        | 40    |
| Not A      | 40        | 80    |

As can be seen in the above table,
treatment A was effective in reaching outcome A in 80/120 individuals,
and,
treatment not A was effective in achieving outcome A in 40/120 individuals.
This gives us the following value for risk reduction or effectiveness,
80 / 120 - 40 / 120 = 40 / 120.
This figure is also referred to as Attributable Risk, 
or absolute risk reduction (ARR).
Another measure is Relative Risk,
which in this case is given by 80/120 / 40/120 = 2.0.
These numbers also help us to find another way to state the risk reduction,
that is,
what proportion of the risk reduction from the treatment A then can be attributed to treatment A proper,
after accounting for improvement anyway (i.e., not A)?
This is given by 80 - 40 / 80 = 50%,
and is referred to as attributable risk percentage (AR%).
This is a useful concept as if we can show that A causes Y, 
then we can state that A accounts for AR% in the variation of Y. 
In other words, for public health interventions, 
if we were to remove A as a cause, 
we would be able to show a reduction of AR% in Y.
One way to calculate AR% is from RR or relative risk estimates.
So, 
AR%  = (RR - 1)  * 100 / RR in percentages.

To give you an example,
let's say we know that RR of antimalarial treatment of bednets in eliminating malaria from households is about 5.0. 
This tells us that if we were to achieve 100% success in infusing bednets with antimalarial treatment,
then we would be able to reduce incidence of malaria in the region where they were prevalent by 5 - 1/ 5 = 80%.
This still leaves another question,
that of the baseline prevalence of the outcome we want to study.
The higher the prevalence, the more effective will be our intervention based on our attributable risk percent.
To understand this, we can multiply AR% with the prevalence of the condition,
and get a relative sense of the impact our intervention will have on the overall public health issues.

To give you another example,


