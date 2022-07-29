# TAG Environmental Sustainability Proposal

## Mission Statement

### Why TAG Environmental Sustainability? 

<!--- reference needed for all numbers 
According to the International Energy Agency, data centers consume approximately 200 terawatt-hours (TWh) of electricity, or nearly 1% of global electricity demand, contributing to 0.3% of all global CO2 emissions.

Scott: k8s on prem makes CNCF a vital impact on sustainability. on-prem/cloud are both in scope.
EK: cloud transition energy saving (citation)
English format (US vs UK)
---> 
Data Centers, and therefore every compute resource accessible, are currently using [1% of the world's electricty use](https://www.science.org/doi/10.1126/science.aba3758). This is conservatively expected to grow to hold 1-2% in the next couple of years, up to 12% by 2040. The growth in energy for computing is out-pacing the global growth in energy production. The contributing factors include explosion in data, emergence of energy-intensive workloads such as Blockchain/AI/video streaming/VR, and the flattening of Moore's law. 

The Paris Climate Accords outline the link between economic activity, greenhouse gas emissions (GHG), and the impacts of climate change. GHG  emissions, primarily made from Carbon Dioxide are released during the combustion of fossil fuels to produce electricity. In order to reach net zero goals, we need to identify how to reduce the environmental footprints of increasingly large data centers. In order to curb this trend, we need to identify how to reduce the environmental footprints of increasingly large data centers. The good news is that there is also an increase in industry initiatives for environmental sustainability. This TAG's goal is to advocate for, develop, support, and help evaluate environmental sustainability initiatives.

All activities aim to positively impact the community by changing mindset, increasing resource efficiency, and putting energy efficiency and environmental sustainability on everyone's agenda.  We also seek to define, prevent, and identify patterns of inadvertent or overt [greenwashing](https://en.wikipedia.org/wiki/Greenwashing).

We recognize that: 
- there is limited direction in how and much of the technology is within the early stages
- balancing resource consumption with desire for performance is difficult
- much of the tooling is scattered, not well tested, or not integrated with CNCF projects.
- there is considerable inconsistency in how emissions are calculated and what is included/excluded by software in scopes of emission. 
 
In this light, we belive it is essential to achieve the TAG's goals by making sustainability-oriented projects, methodologies, and technologies more accessible to the community and guiding the end users to use resources efficiently to achieve sustainability and climate aligned financial goals.

We want projects that cover more materials, such as:
 - Standards and taxonomy that define the metrics and goals of system sustainability. This is similar but not limited to the existing works such as the [Software Carbon Intensity Specification](https://github.com/Green-Software-Foundation/software_carbon_intensity/blob/main/Software_Carbon_Intensity/Software_Carbon_Intensity_Specification.md) under The Green Software Foundation.
 - Tooling for test, evaluation, and audit sustainability metrics during the lifecycle of software development.
 - Tooling that highlights wasted/inefficient resources (whether Data Centers, platforms, Cloud, etc.)
 - Tooling that improves optimization of carbon footprint/sustainability (for example, energy efficiency/carbon aware scheduling, placement, dispatchers and autoscalers for Data Centers, platforms, Cloud, etc.) 
 - Methodology to measure Scope 1,2,and 3 energy and carbon footprint of systems.

## Responsibilities & Deliverables

### In-Scope

- Define users/personas/needs/customer demands in the power metrics/measurements/management
- Develop methodology to assess organizational maturity and capability to implement improvements
- Identify areas of focus on performance per Watt, power savings, etc
- Identify, define, and develop methodology, tools, framework for evaluation - how do products and tools fit the users in the area?
- Evaluate architectures - what power measurement and management as well as performance gaps are there?
- Integrate common tooling into different projects, particularly where that tooling is a CNCF project 
- Identify, define, and develop procedures to improve environmental sustainability factors, benchmarks for the quantification of energy consumption of software, techniques to manage software such that the overall energy consumption and associated carbon is reduced.
- Identify, define, and develop procedures and technologies that can be used to create carbon "unit economics"
- Enhance energy efficiency and reduce carbon footprint of CNCF projects both on-prem and Cloud services
- Define, prevent, and identify patterns of overt and inadvertent greenwashing
- Collaborate with existing efforts from perspective of Cloud Native
- Limit the scope of our activities by referring to the [CNCF Cloud Native definition](https://github.com/cncf/toc/blob/main/DEFINITION.md)

### Out of scope
- Form an umbrella organization beyond the CNCF
- Establish a compliance and standards body beyond the CNCF

<!---
### Under Consideration 
Scope 1,2,3 support (operational and embeded), it it still complicated, but very important, wait for standardization
Scope 3 for hybrid architecture
--->

## Deliverables to ToC
- framework document for the cloud-native carbon and energy metrics/measurements/management space
- landscape for the carbon and energy metrics/measurements/management savings
- recommendations for sandbox projects where exploration is needed
- recommendations for new CNCF projects where there is clear use cases
- scheduled regular reporting to ToC on ongoing and completed work
- reporting on carbon and energy saving/metrics/measurements/management projects for graduation and other events, summarizing the external power related research, reviews and other relevant information
- help with regular health checks of projects in the category

#### Audiences

- Education - audience is end users and developers
- Project intelligence - audience is TOC / TOC Community
- External collaboration - organizations with the same mindset

#### The issue of the Landscape(s)

- Being “deliberate” about what this (these) are for, and for whom?
- Main landscape has become an anti-pattern (kitchen sink effect)

#### Execution & Focus

- How do we spell out CNCF “work items” that can be executed by both CNCF staff and the TOC community
- Can the TOC ask questions of the SIGs?  “Go ruminate on this please”
- Making sure recommendations don’t over-determine users’ tech choices. For reference, the storage WG was successful because it provided genuine guidance about a *range* of approaches, in a way that is transparent, unbiased, actionable

## Roles and Responsibilities

### TOC Liasons: 

Up to two CNCF TOC members are nominated to advise the chairs and technical committee, as well as review the status and progress of the TAG. 

<!-- this needs to be determined -->

### Co-Chairs:

The term of the chairs is inline with the best practices established by CNCF TAGs.

The three co-Chair team selection process is to following these criteria, among other best practices used by the CNCF community:
- Do the nominees have strong tracking records in community management and project maintenance, especially in sustainability and related areas? 
- Are the nominees committed to work with their best knowledge for the TAG and CNCF for the duration of their tenure (the term is in line with CNCF conventions)?
- Does the team represent a balance between research, development, and community management?

<!-- these need to be determined -->


### Technical Committee: 
The technical committee is to help the chairs in managing and developing projects and best practices, gathering the community input, and conducting research works. 

The committee consists up to five members for six months terms.

<!-- these can be determined after the fact, but we can get a march by doing it beforehand. -->

## Acknowledgement
The format of this proposal is inspired from TAG security.
The initial doc was taken from the [Environmental WG charter](https://docs.google.com/document/d/1JaF7lSUmLQ2zmScmca6UF7PgbjMzSxjhhjx2LThThaY/edit#heading=h.x77xxicolnig) and modified by the community.

## Contributors
This proposal is contributed by (in alphabetical order):
- Cara Delia
- Chen Wang
- Eun Kyung Lee
- Huamin Chen
- Jorge Palma
- Mark Butcher
- Marlow Weston
- Max Körbächer
- Niki Manoledaki
- Scott Rigby
- William Caban

