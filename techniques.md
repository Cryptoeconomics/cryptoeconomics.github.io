---
layout: page
title: Techniques
---

This page describes techniques for designing more sophisticated kinds of referendums and citizens' initiatives.

* [Scale](#scale)
    * [Random sampling](#random-sampling)
    * [Verifiable randomness](#verifiable-randomness)
    * [Decoy ballots](#decoy-ballots)
    * [Stratified sampling](#stratified-sampling)
    * [Statistical quorum]()
    * [Hybrid selection]()
    * [Delegation networks]()
* [Proposal making]()
    * [Signature collection]()
    * [Pairwise comparison]()
    * [Progressive refinement]()
* [Deliberation]()
    * [Meetings]()
    * [Compensation]()

## Scale

It is common to hear that direct democracy cannot work at the scale of modern nation-states.
It would be impossible to hold thousands of referendums every year.

### Random sampling

A simple technique to address the problem of scale is random sampling.
Instead of consulting the entire population on every issue, we can consult a random sample on each issue.

Let us consider the example of Brazil, where more than 100 million people vote in each election.
Suppose Brazil held a special kind of referendum in which a random sample of 2,000 people voted to approve or reject a particular legislative proposal.
The results would be approximately the same as if everybody had voted.
A mathematical theorem, called "the law of large numbers," guarantees that with 99% probability, the fraction of people in the sample set who are in favor of the proposal would be within 3% of that fraction in the entire population.

Interestingly, the confidence (99%) and error (3%) depend only on the sample size (2,000), and not on the population size at all!
The same sampling would work equally well if all the people in the world (over six billion) were eligible voters in Brazil, or even if all atoms in the universe were voters.[^randomness]

[^randomness]: This explanation was adapted from Avi Widgerson, [Randomness and Pseudorandomness](https://www.ias.edu/ideas/2009/wigderson-randomness-pseudorandomness), Institute for Advanced Study, 2009.

Thus, if Brazilian voters were divided into 50,000 random samples of 2,000 people each, they could vote on 50,000 different proposals (many times more than the National Congress does).
Although the results would be approximations, the margins of error due to random sampling would be minuscule compared to variations due to the self-selection of voters.
(In Brazil, abstention rates are consistently above 15%.)

To be sure, opinion polls, which also employ random sampling, often fail to predict voting results.
But the causes of the inaccuracy of polls, such as response bias and coverage bias, derive from differences between the conditions under which polls and actual votes are conducted, not from random sampling itself.

Random-sample voting could enable a large number of legislative issues to be decided by popular vote.
It would be feasible to significantly lower the barriers to the introduction of citizens' initiatives.
(In Brazil, an initiative currently requires more than 1.35 million signatures.)

Moreover, random-sample voting is resistant to targeted advertising.
Suppose we wanted to spend money to influence the outcome of a vote.
If the randomly-selected voters cannot be identified, it is costly to reach them.
In order to deliver an ad to a given fraction of the voters, it is necessary to reach the same fraction of the entire population.
(In the Brazilian example, in order to reach half of the 2,000 in a sample, it is necessary to reach half of all 100 million voters.)

### Verifiable randomness

If a government were to implement random-sample voting, there would be a high incentive to tamper with the randomization process. 
Fortunately, it is possible to make the process auditable, and thus ensure its integrity, by using public verifiable sources of random bits, such as stock prices and meteorological measurements.[^verifiable-randomness]

[^verifiable-randomness]: Christopher Vatcher, [Verifiable Randomness Pillar Technical Summary](http://rsvoting.org/random_beacon/random_beacon_summary.pdf), Random-Sample Voting.

### Decoy ballots

A major disadvantage of random-sample voting is that it increases the incentives of vote buying.
One vote in 2,000 weighs much more than one vote in 100 million.

There are clever strategies to thwart vote buying.
One idea is to prevent voters from being able to provide proof or evidence to anybody else that they were selected to vote on a given issue.

### Stratified sampling

 
