# 0012 - DAO Committee Compensation

<br>

## 1. Meta Data

* **Original Author(s):** Oliver Zerhusen (ozerhusen@gmail.com), Kyle LaRue (kylelarue00@gmail.com)
* **Creation Date:** 08/11/2022
* **Stage:** Candidate
* **Live Date:** 

<br>

* **Last Version:** 
* **Last Version Date:**
* **Last Version Author(s):**

<br>

* **Organization:** DAO
* **Tag(s):** Coordinape, DAOHaus, Financials

<br>

Version| Github Commit-Hash | Comment
  | - | - | - |
Not yet live

<br>

## 2. Summary

This GOC describes the implementation of the DAO Committee compensation structure. It includes details of how Coordinape is used as the compensation distribution model in conjunction with accommodating algorithms and supporting processes. Besides the base compensation structure for all DAO Committee members, this GOC also describes a committee rewards program for highly engaged committee members that significantly contribute to the success of a committee. 

<br>

## 3. Motivation

As specified in the Charter, the DAO is tasked with implementing and publishing detailed instructions of the compensation structure for committees. This GOC is written to accomplish that goal.

<br>

## 4. Prior Art

Various discussions and proposals have preceded this GOC. Most notably, GOC-0017 DAO Committee Operators was intended to become an adjacent component of the overall compensation structure for committees. GOC-0017 did not reach consensus and was withdrawn. However, the core spirit of GOC-0017 was to identify paths to reward highly engaged contributors with reasonable compensation levels relative to committee peers that are reporting less hours, on average. That main goal gained broad consensus in various discussions and was adopted in this GOC with the introduction of the committee rewards program.

<br>

## 5. Specification


### 5.1. Eligibility


#### 5.1.1. DAO Committees

DAO compensation for work performed in the DAO is executed via DAO Committees, see also GOC-0003 DAO Committees. Only members of DAO Committees are therefore eligible to receive compensation for contributions made within these committees.


#### 5.1.2. Qualifying Contributions

Contributions eligible for compensation should focus on work performed in the DAO and for advancing the mission of the DAO. Such contributions should be made in DAO-approved systems and established structures that are generally transparent and accessible to fellow committee members.

A noteworthy distinction shall be made between DAO contributions and Advocate contributions, as DAO members may perform both roles. Contributions made to the Advocates Program by a DAO member shall be submitted via established Advocate Program processes to get recognition or compensation for Advocate contributions. However, such contributions shall not also be eligible for compensation by the DAO. Likewise, contributions for which DAO members get compensated by the DAO shall not also be submitted as contributions towards the Advocates Program. This guideline is designed to prevent double counting of contributions that would result in being rewarded and recognized twice.


### 5.2. GIVE Allocations

The DAO uses Coordinape as a platform to help determine compensation distributions each month. One month is referred to as one epoch in Coordinape. During each epoch, DAO committee members are tasked with distributing 100 GIVE (reputation token) across fellow committee members, except to oneself. The more GIVE individual DAO committee members receive, the higher their monthly compensation payout. This process repeats itself every month with a new epoch.

The guideline for DAO members to distribute GIVE is based on two factors: 1) time commitment shown throughout an epoch dedicated to a committee and 2) the value of contributions a DAO member has made to a committee. There is no exact science or framework for this exercise, and this model purposefully provides room for interpretation of that guideline for each DAO member. Everyone perceives the concept of “value” somewhat differently, and this structure allows to make GIVE allocations to other DAO members based on one’s own performance assessment as a peer.

Further details explaining Coordinape workflows and the subsequent epoch distribution process shall be developed in a dedicated GOC aligned with the specifications and parameters of this GOC.


### 5.3. Hour Reporting

Each epoch, DAO members are encouraged to keep track of their time contributions and make that data transparently available to fellow committee members. The DAO will provide time tracker sheets that enable recording hours across all compensation eligible committees, including the ability to provide details to the contributions. The time tracking sheet and platform can be changed via an off-chain vote. It is recommended for committee members to make timely updates to one’s own tracking sheet to ensure accurate data capturing.

Committee members are strongly advised to report hours accurately and to not falsely report hours that were not contributed to DAO work, which includes contributions made to the Graph Advocates Program described in the Qualifying Contributions section of this GOC. Committee members who have strong suspicions about the accuracy of reported hours made by another committee member are able to respond to such situations via adjustments of their GIVE allocation to that committee member in Coordinape.


### 5.4. Rewards Program


#### 5.4.1. Purpose

The DAO recognizes varying degrees of engagement by DAO members in committees. In an effort to reward high-performing contributors, committee members have the opportunity to be awarded 5% rewards each epoch coming from the committee compensation budget. The below criteria are guidelines to inform the decision which committee members may be suitable candidates for the 5% rewards program:


* Reporting a minimum average of 30 hrs in the committee across the two prior epochs
* Demonstrating  active engagement and leadership in discussions and decision making processes
* Showing up and demonstrating a roll-up-the-sleeves attitude, such as actively participating in workflows, leading committee meetings, creating agendas, keeping notes, etc

The rewards program is designed to recognize contributors that show up on a continuous basis and who generally engage on multiple fronts to keep things moving forward. They show a deep sense of caring about the success of the DAO’s mission and therefore the workflows, initiatives and processes that deliver on the goals.


#### 5.4.2. Cap

The aggregate amount of all rewards distributed in a committee shall not exceed 30% of the total committee compensation budget. Therefore, the first six (6) rewards recipients would receive their 5% rewards in full. If a 7th member gets approved for the rewards program, then the rewards percentage for all recipients is reduced to an even amount accordingly. In the case of 7 recipients, the rewards for each one of them would therefore be 4.3%, and so on.


#### 5.4.3. Nomination

Any committee member can nominate another committee member for the rewards program via an off-chain vote. Committee members vote per established off-chain voting parameters with a period of 10 days. The nominated committee member is approved for the rewards program on that respective committee if there is one more yes vote than no vote. The activation of the rewards program is effective upon the conclusion of the voting period, to be applied in full on whichever epoch the voting period ends.


#### 5.4.4. Revocation

A rewards recipient of a specific committee choosing to leave that committee loses entitlement to the rewards program in full, effective immediately for that epoch which the committee member has left. If that DAO member rejoins that same committee at a future time, then the rewards program does not get reinstated, but instead must be earned again via a new nomination by a fellow committee member.

Any Committee member can nominate an existing rewards recipient of that committee for revocation of the rewards program, if that committee member feels that the rewards recipient no longer qualifies for it. The same voting rules and effective dates apply as specified in the Nomination section.


### 5.5. Payout Structure


#### 5.5.1. Compensation Budget

Each compensation eligible DAO Committee shall be allocated with compensation funds each quarter per the agreed upon budget. That process shall be described in a future GOC covering DAO funding in more detail. Compensation budgets are denominated and paid out in USDC.


#### 5.5.2. Distribution

Compensation levels per committee member vary by a number of different factors:

1. Committee-specific compensation budget level
2. GIVE allocation received by fellow committee members via Coordinape
3. Rewards program

The rewards are first deducted from the total committee compensation budget for each committee member receiving rewards. The remainder of the total monthly compensation budget gets distributed to its members based on GIVE allocations received in Coordinape. If not 100% of all GIVE was allocated by the committee members, then the remaining GIVE shall be evenly distributed across all active rewards program recipients of the respective committee who have distributed 100 GIVE themselves in that epoch. If there are no qualifying rewards recipients to distribute unallocated GIVE to, then the budget reflecting that unallocated GIVE shall be carried forward into the committee's next epoch and increase the total compensation budget for that epoch accordingly.

<br>

![Committee Compensation Distribution](https://github.com/ZorroZ77/docs/blob/Main/.gitbook/assets/Committee%20Compensation%20Distribution.png)

<br>

Below is a fictional example of the calculation of the distribution where DAO member A is the only reward recipient in committee ABC:

![Committee Compensation Distribution Example](https://github.com/ZorroZ77/docs/blob/Main/.gitbook/assets/Committee%20Compensation%20Distribution%20Example.png)

<br>

#### 5.5.3. Disperse Proposal

Committee members shall receive their compensation monthly, following the end of an epoch and after all required calculations are performed. The disbursement shall be executed via an on-chain Disperse Proposal in DAOHaus for each committee individually from their respective committee minions. DAO members voting on the approval of these proposals are advised NOT to vote with the mindset of whether they fundamentally agree with the individual payout levels for committee members, but they should rather vote to confirm that the calculations were performed accurately, especially for their own payouts, if applicable.

Important to note is that all compensation paid out via DAOHaus will be executed on Gnosis Chain. Anyone planning to utilize tokens on different chains, such as Ethereum, is required to first bridge the tokens using an established platform, as shown in the Links section.

<br>

## 6. References

### 6.1. Relevant GOCs
* [GOC-0003 DAO Committees](https://gocs.graphadvocates.com/gocs/goc-0000-0009/0003-dao-committees)
* GOC-0008 DAO Funding (to come)
* [GOC-0017 DAO Committee Operators](https://gocs.graphadvocates.com/gocs/goc-0010-0019/0017-dao-committee-operators)


### 6.2. Links
* [Bridging from Gnosis Chain](https://app.clickup.com/37437860/v/dc/13pgd4-6987/13pgd4-13467)

### 6.3. Attachments
* [Time Tracker Template](https://docs.google.com/spreadsheets/d/1v0arJSOcuDtMotx_CDCcFS0oZ-0m2b4gNqi-XjkTAf4/edit#gid=0)
* [Committee Epoch Distribution](https://docs.google.com/spreadsheets/d/1ltPLXgcWc83tBDh8QKJBbAL8bZ0sMjIrYzTh9l9Y9xc/edit?usp=sharing)
* [DAO Financials](https://docs.google.com/spreadsheets/d/1u20XfGxsUf-guhiHrM-M58jIZ66kuBSj9f_rCvUAbKE/edit?usp=sharing)
