# TAG Environmental Sustainability Proposal

## Mission Statement

### Why TAG Environmental Sustainability? 

<!--- reference needed --->Data Centers, and therefore every compute resource accessible, are currently using 2% of the world's energy. This is conservatively expected to grow to hold 1-2% in the next couple of years, up to 12% by 2040. The growth in energy for computing is out-pacing the global growth in energy production. The contributing factors include explosion in data, emergence of energy-intensive workloads such as Blockchain/AI/video streaming/VR, and the flattening of Moore's law. 

GHG emissions are one of the key factors for global warming. In order to curb this trend, we need to identify how to reduce the environmental footprints of increasingly large data centers. The good news is that there is also an increase in industry initiatives for environmental sustainability. This TAG's goal is to advocate for, develop, support, and help evaluate environmental sustainability initiatives.

All activities aim to positively impact the community by changing mindset, increasing efficiency, and putting energy efficiency and environmental sustainability on everyone's agenda.  We also seek to prevent greenwashing.

We recognize that: 
- there is limited direction in how and much of the technology is within the early stages
- balancing resource consumption with desire for performance is difficult
- much of the tooling is scattered, not well tested, or not integrated with CNCF projects.
- there is considerable inconsistency in how emissions are calculated and what is included/excluded
 
In this light, we belive it is essential to achieve the TAG's goals by making sustainability-oriented projects, methodologies, and technologies more accessible to the community and guiding the end users to use resources efficiently to achieve sustainability and climate aligned financial goals.


We want projects that cover more material, such as:
 - Standards and taxonomy that define the metrics and goals of system sustainability. This is similar but not limited to the existing works such as the Software Carbon Intensity Specification under The Green Software Foundation.
 - Tooling for test, evaluation, and audit sustainability metrics during the lifecycle of software development.
 - Tooling that highlights wasted resources (whether datacentre, platform, cloud etc.)
 - Tooling that improves optimization of carbon footprint/sustainability (whether data center, platform, cloud, etc.) 
 - Methodology to measure energy and carbon footprint of systems.

## Responsibilities & Deliverables

### In-Scope

- users/personas/needs/customer demands in the power metrics/measurements/management
- methodology to assess organisational maturity and capability to implement improvements
- identifications of areas of focus on performance per Watt, power savings, etc
- methodology, tools, framework for evaluation - how do products and tools fit the users in the area?
- architecture evaluations - what power measurement and management as well as performance gaps are there?
- integration of common tooling into different projects, particularly where that tooling is a CNCF project 
- procedures to improve environmental sustainability factors, benchmarks for the quantification of energy consumption of software, techniques to manage software such that the overall energy consumption and associated carbon is reduced.
- procedures and technologies that can be used to create carbon <!--- please explain how this related to CNCF and open source -->"unit economics"

### Out of scope
<!---
- a standards body: We won't be creating standards. 
- a certification board for applicability to sustainability for individual projects.
// Per William C: Will this prevent working on defining the equivalent of a "Software Energy Index" to agree on a way to calculate the actual energy consumed by a software delivering a service and taking into account the indirect energy impact (like energy consumed by external storage consumed by the Pod, or the network paths used by an intercommunication of microservices)
-  We will not answer any specific questions regarding the state of any project unless there is some impact to cloud-specific systems. //what does this mean? can this be rephrased, e.g. not to address questions/issues of non-CNCF projects? //(Marlow) This is to not become the "experts" at having to answer questions on specific projects. Providing guidance is good. Being on the hook to recommend specific things, less good. 
 --->
- an umbrella organization. We interact with other groups for knowledge sharing, not decision-making.
- a compliance body.

## Deliverables to ToC

- framework document for the cloud-native power metrics/measurements/management space
- landscape for the power metrics/measurements/management savings
- recommendations for sandbox projects where exploration is needed
- recommendations for new CNCF projects where there is clear use cases
- scheduled regular reporting to ToC on ongoing and completed work
- reporting on power saving/metrics/measurements/management projects for graduation and other events, summarizing the external power related research, reviews and other relevant information
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
- Making sure recommendations don’t over-determine users’ tech choices.  The storage WG was successful because it provided genuine guidance about a *range* of approaches, in a way that is transparent, unbiased, actionable

## Roles and Responsibilities

### TOC Liasons: 

Up to two CNCF TOC members are nominated to advise the chairs and technical committee, as well as review the status and progress of the TAG. 

<!-- this needs to be determined -->

### Co-Chairs:

The term of the chairs is inline with the best practices established by CNCF TAGs.

The three co-Chair team selection process is to following these criteria, among other best practices used by the CNCF community:
- Do the nominees have strong tracking records in community management and project maintenance, especially in sustainability and related areas? 
- Are the nominees committed to work with their best knowledge for the TAG and CNCF for the duration of their tenure (the term is in line with CNCF conventions)?
- Does the leadership team represent a balance between research, development, and community management?

<!-- these need to be determined -->


### Technical Committee: 
The technical committee is to help the chairs in managing and developing projects and best practices, gathering the community input, and conducting research works. 

The committee consists up to five members for six months terms.

<!-- these can be determined after the fact, but we can get a march by doing it beforehand. -->

# Acknowledgement
The format of this proposal is inspired from TAG security. 
