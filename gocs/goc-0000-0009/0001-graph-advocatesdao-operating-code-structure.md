# 0001 - Graph AdvocatesDAO Operating Code Structure

<br>
  
## 1. Meta Data
  
* **Original Author(s)**: Oliver Zerhusen (ozerhusen@gmail.com)
* **Creation Date:** 04/10/2022
* **Stage:** Live
* **Live Date:** 05/04/2022
  
<br>
  
* **Version:** 1.01
* **Last Version Date:** 05/04/2022
* **Last Version Author(s):** Oliver Zerhusen (ozerhusen@gmail.com)

<br>

* **Organization:** DAO
* **Tag(s):** Governance, Procedure

<br>

| Version | GitHub Commit-Hash | Comment |
| - | - | - |
| 1.00 | ac4623221684daee22df47cddb650765af506e43| Current DAO-approved version
1.01 | | Updated Meta Data

<br>

## 2. Summary
This code describes the Graph AdvocatesDAO Operation Code (GOC) structure. A GOC describes important information for Graph AdvocatesDAO (DAO) members that is relevant enough to formally document and approve it via on-chain Signal Proposal. The catalog of GOCs represents the DAO operating procedures, information and guidelines specifying level 2 details beneath the Graph AdvocatesDAO Charter (Charter).
  
<br>

## 3. Motivation
The Charter provides the overarching structure of the DAO that its members adhere to. The daily execution of the DAO’s mission entails decentralized coordination by DAO members across a wide variety of processes, systems, tasks and timezones. DAO members encounter numerous situations where alignment is required on how to approach new problems, make decisions across different available options and agree on paths of implementation. GOCs aim to capture that need of alignment via on-chain voting and help communicate the details via GOC documentation to current and future DAO members.

GOCs are intended to capture critical information on recurring assignments or repeating intersections that DAO members come in contact with and that are not yet specified with required detail in the Charter. It is not meant to introduce unnecessary bureaucratic processes for the DAO to document every single decision or process detail that the DAO engages in.
  
<br>

## 4. Prior Art
This GOC design structure was informed heavily by the process of Graph Improvement Proposals (GIP) which in turn was deeply inspired by the processes surrounding Synthetix Improvement Proposals (SIPs), LivePeer Improvement Proposals (LIPs), Ethereum Improvement Proposals (EIPs), Bitcoin Improvement Proposals (BIPs), Python Enhancement Proposals (PEPs), and Javascript's TC39. This GOC structure  borrows similar language in numerous places, but with a specific focus on DAO operations vs. protocol improvements.
  
<br>

## 5. Specification

### 5.1. GOC Anatomy
The GOC structure is intended to be flexible enough to describe a variety of DAO related information. A submitted GOC should include filled out information for sections 1-3 along with details of the information in the fifth section (Specification). Rather than being overly prescriptive, author(s) are encouraged to choose a Specification structure that best conveys their ideas. Section 4 (Prior Art) and 6 (References) are optional and recommended to be populated as applicable.

A template is available called "GOC-0000 Template" which provides additional detail on all sections and should be kept up to date with the latest process as described in this code.

### 5.2. Process
The GOC process includes both the stages and acceptance criteria that a code passes through, as well as a meta-process that takes place before, during, and after a GOC is written in order to build credibility and community consensus behind an idea.

#### 5.2.1. Before writing a GOC
The author(s) should do the legwork to assess the quality of their idea with other DAO members. This includes discussing the initial idea in public Committee meetings, Discord or the Forum. The author(s) should also ensure the proposed code is in line with the values and mission of the Graph AdvocatesDAO. There is no formal voting required at this stage, and author(s) should use rough consensus as a gauge for future support by other DAO members for the proposed code.

DAO members are strongly advised to verify if there are already existing GOCs or language of the proposed code in the Charter. Conflicts that may arise from conflicting specifications among different GOCs and/or with the Charter are resolved via the process described in [Precedence](#heading=h.yx0vaocdi1l4). Prior to creating a new GOC, author(s) should evaluate the feasibility of modifying an existing GOC as their preferred option.

#### 5.2.2. Writing a GOC
The author(s) should aim to solicit insights from as many community members as possible to produce a proposal for a code that best serves the entire DAO community. Activities an author may participate in during this time, include, but are not limited to:

* Evangelizing their proposal in the forums.
* Present at community calls and receive feedback from community members.
* Form working groups with other community members interested in a similar idea.
* Advocate for community polls on the proposal when it is sufficiently mature.

#### 5.2.3. Submitting a GOC
Author(s) are encouraged to keep fine-tuning GOCs based on feedback provided from the community in an effort to arrive at a proposal for a code with broad community support. There is no exact process to identify community consensus. Feedback in Forum, Discord and community calls provide signals, so do optional off-chain voting polls.

It is generally encouraged for author(s) to gain a good sense of support from the community on a GOC in order to maximize chances for a successful voting outcome. Once that is obtained, GOCs should be submitted for on-chain voting approval via a Signal Proposal. A GOC is Accepted when the corresponding Signal Proposal receives one more Yes votes than No votes.

#### 5.2.4. Implementing a GOC
An approved GOC may not readily go live and become implemented. The DAO is a decentralized body and it is up to DAO members to take the necessary steps to turn an Accepted GOC into a living element within the DAO. This part should be a critical consideration as the GOC moves through prior stages of the GOC process and may include deliberations on  the following topics:

* Incremental labor capacity required to adopt the GOC
* Committee (or DAO member) ownership definition
* Timeline required for planning and ramping up resources
* Costs associated with setting up new systems and platforms

The GOC reaches the Live stage once it is fully operationalized into DAO workflows and therefore executed as part of the DAO operations. Owners and contributors to the deliverables of the GOC should be committed to adhering to the specifications of the GOC at this point.

#### 5.2.5. GOC Stages
The below describes the stages a GOC may move through

* **Proposal** - initial high level idea for the creation of a new code or modification of an existing code
* **Draft** - early stage of a GOC where the content is still under development. It is not Accepted yet and is hence not being enacted   			 
* **Candidate** - initial release of the GOC where the content is completed and under review by the DAO, such as being actively discussed amongst DAO members. It is not an Accepted GOC yet and is hence not being enacted   			 
* **Accepted** - a GOC has successfully passed as an on-chain SIgnal Proposal. Actions to implement the statute can begin, but the GOC is not yet an active code during this time and is hence not being enacted.   			 
* **Live** - GOC is fully enacted in the DAO. If applicable, the assigned Committee has operational responsibility to fulfill delivery of the specified rules & procedures.	 
* **Rejected** - GOC never moved past the Candidate stage and was hence never enacted.
* **Replaced** - GOC was previously Live and has since been replaced by another GOC. It is no longer active and hence is not enacted.
* **Retired** - GOC was previously Live and has since been eliminated and/or replaced. It is no longer active and hence is not enacted.

### 5.3. Precedence
A GOC may be Accepted and subsequent conflicts may emerge during the Live stage that identity cross-purposes with other Live GOCs and/or the Charter. The following specifies what takes precedence in such situations.

1. **Charter**
In case there is a conflict identified between the Charter and a GOC, then the language of the Charter takes precedence. The GOC should subsequently be modified to remove that conflict.

2. **Oldest GOC release**
In case there is a conflict between two different GOCs, then whichever GOC’s latest version was Accepted earlier takes precedence. A new GOC may in fact aim to remove sections and/or replace a prior GOC. That can be included in the specification of a GOC itself as a requirement. Older GOCs taking precedence over newer GOCs is meant to resolve accidental conflicts that were not intentional. 

3. **Latest Version**
GOCs may be regularly updated with new information as necessary. A committee may want to change a system platform to execute a certain process, and hence it modifies an existing GOC with that information to obtain approval from the DAO. That would create a new version (+1 to the prior version) following DAO approval. A higher version number of a GOC therefore always takes precedence over a lower version number.
  
<br>

## 6. References

### 6.1. Relevant GOCs
- [GOC-0000 GOC Template](https://gocs.graphadvocates.com/gocs/goc-0000-0009/0000-goc-template)
