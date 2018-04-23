# GCcodefestMtl_FoodTraceability

# The CFIA Food Safety Information System (FSIS): a tokenized ecosystem for improving food traceability and security

## Problem Statement 

The Canadian Food Inspection Agency (CFIA) has difficulty assessing food safety and traceability within the food supply chain because they lack access to relevant data from the actors of the industry. Corporations inside the food industry are reticent in sharing their data with the gouvernement for free, and without any guarantee. But without this data, the CFIA has problems accomplishing its mission in an increasingly complex and globalized industry.

Private enterprise and the government have a common moral and economic interest in creating better food safety. The government wants to spend about as much time and money on doing inspections as private industry wants in preparing for them: none at all.

If all private sector stakeholders (food processors, importers, exporters, wholesalers etc...) shared information about their food management practices the government would do fewer inspections, companies in turn would prepare for fewer inspections, and food safety would improve because of more targeted inspections.

## Objective of the project

What new technologies can help the government improve food security by having an increased access to relevant data? We propose a Food Safety Information System (FSIS) to increase data transparency in the industry. With access to better data about the supply chain, CFIA will be able to focus their efforts where their are the most needed by identifying the bad actors. Good actors on the other hand will be less scrutinized by the CFIA because they can prove through their willingness to share data and participate in the FSIS that they are ahead of others in term of food safety practices. 

## Proposed solution 

The FSIS we propose is a peer-review system with less government oversight using a technology called blockchain. The actors of the industry are encouraged to share their data and evaluate the data of their peers through the distribution of tokens that reward them for their transparency. 

## How it works 

The distribution of tokens is the incentivization mechanism needed to encourage the participation of the industry actors in the system. The transaction of these tokens, including their distribution and exchange, are enabled by blockchain technologies. In this regard, the FSIS can be viewed as a blockchain technology.

## Incentive mechanism

Every actor participates in the network by first sharing their food safety relevant data whenever requested by another participant above them in the food supply chain, namely their clients.

They are also encouraged to evaluate the data of upstream participants, namely their suppliers. They do so by voting on the relevance, quality and quantity of the provided data using their tokens as a proof of their stake. 

Actors have thus an economic advantage in sharing good quality data that encourage others to vote for them. A reputation system score is also attributed to each actor for their participation in the system. The higher their reputation, the higher their future reward. This incentivization mechanism is designed to create a fortuitous feedback loop toward more data sharing, transparency, ultimately improving food security and traceability.

## Block reward function

Through the distribution of tokens, every actor in the system is incentivized to:

1) Share their safety and traceability related data with their current and potential clients UP in the supply chain.

2) Evaluate the quality, quantity and relevance of the data provided by their current and potential suppliers DOWN in the supply chain in terms of food traceability, security and transparency. 

### Incentivization for sharing data
The expected reward for sharing data with your clients can be expressed with the following equation:

E(R_share) = Sum_over_clients(Si * Ri) * T

Where:

Si is the stake client i puts in your data

Ri is the reputation score of client i

T is the amount of tokens awarded during this interval

NB.: The sum is over all (current and potential) clients with whom you proovably shared data during the interval.

### Incentivization for curating data
The expected reward for evaluating your suppliers’ data can be expressed with the following equation:

E(R_curation) = Sum_over_suppliers(Sj * Rj) * T

Where:

Sj is the stake you put in supplier i’s data

Rj is the reputation score of supplier j

T is the amount of tokens awarded during this interval

NB.: The sum is over all (current and potential) suppliers who proovably shared data with you during the interval.

### Total reward function

The total expected reward you can get from share and curating data in this ecosystem is the following:

E(Rtotal) = [E(R_sharing) + E(R_curation)] * R

Where:

R is your reputation score

## The reputation system

At this point in the project, the problem of establishing the reputation score has not been thought through completly. We are exploring diffenrent possibilities. Reputation score could be established in an automated manner based on participation in the system, the velocity of your tokens, your amount of stake, etc. It can also be established with an other voting mechanism. But this still has to be determined.

