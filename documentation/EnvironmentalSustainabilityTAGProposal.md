# TAG Environmental Sustainability Proposal

## Mission Statement

### Why TAG Environmental Sustainability? 

<!---
08/02: 
Max: old research (4~5 years). Current evidence. Precise numbers, CO2 guessmate. Clear pictures needed. 
Highlight that our approach is transparent, creditable, and accountable, in addition to statements.  
Leo: how to use the numbers and what CNCF can do in these areas.
Scott: other sources of mentioning data centers, scope of this community focusing on CNCF. How does this paragraph relate to CNCF? *Alignment with other groups*.

other sources (e.g. https://www.iea.org/reports/data-centres-and-data-transmission-networks)

--->

The Paris Climate Accords outline the link between economic activity, greenhouse gas emissions (GHG), and the impacts of climate change. GHG  emissions, primarily made from Carbon Dioxide, are released during the combustion of fossil fuels to produce electricity. To reach net zero goals, we need to identify how to reduce the environmental footprints of increasingly large data centers. The good news is that there is also an increase in industry initiatives for environmental sustainability. This TAG's goal is to advocate for, develop, support, and help evaluate environmental sustainability initiatives.

We seek to provide feedback and tools, along with promoting practices and standards.

All activities aim to positively impact the community by changing mindset, increasing resource efficiency, and putting energy efficiency and environmental sustainability on everyone's agenda.  We also seek to define, prevent, and identify patterns of inadvertent or overt [greenwashing](https://en.wikipedia.org/wiki/Greenwashing).

We recognize that: 
- there is little direction in how and much of the technology is within the early stages
- balancing resource consumption with the desire for performance is difficult
- much of the tooling is scattered, not well tested, or not integrated with CNCF projects.
- there is considerable inconsistency in how emissions are calculated and what is included/excluded by software in scopes of emission. 
 
In this light, we believe it is essential to achieve the TAG's goals by creating sustainability-oriented projects, methodologies, and technologies more accessible to the community and guiding the end users to use resources efficiently to achieve sustainability and climate-aligned financial goals.

We want projects that cover more materials, such as:
 - Standards and taxonomy that define the metrics and goals of system sustainability. This is similar to but not limited to the existing works such as the [Software Carbon Intensity Specification](https://github.com/Green-Software-Foundation/software_carbon_intensity/blob/main/Software_Carbon_Intensity/Software_Carbon_Intensity_Specification.md) under The Green Software Foundation.
 - Tooling for test, evaluation, and audit sustainability metrics during the lifecycle of software development.
 - Tooling designed to highlight wasted/inefficient resources (whether located in Data Centers, platforms, Cloud, etc.)
 - Tooling that improves optimization of carbon footprint/sustainability (for example, energy efficiency/carbon aware scheduling, placement, dispatchers, and autoscalers for Data Centers, platforms, Cloud, etc.) 
 - Methodology to measure Scope 1 and 2, and software systems to manage and track scope 3 energy and carbon footprint.

## Responsibilities & Deliverables

### In-Scope
<!--
08/15/2022 (Jochen Joswig): See below my idea to narrow down this section.

- Research, develop and define tools, processes, methodologies, recommendations, best-practices, guidelines, benchmarks, or metrics to assess and subsequently improve:
    - environmental impacts of Cloud Native Technology including, but not limited to:
        - net zero GHG emissions
        - energy consumption and usage
        - performance (per unit of energy)
        - hardware utilization and longevity
    - organizational/technical/architectural maturity
    - detect and avoid greenwashing
- Community outreach on any topic within its scope including but not limited to:
    - Social media posts,
    - Conferences, meetups, and talks,
    - Podcasts and discussion formats.
- Collaborate with related efforts, organizations and foundations
-->

- Define users/personas/needs/customer demands in the power metrics/measurements/management
- Develop methodologies to assess organizational maturity and capability to implement improvements
- Identify areas of focus on performance per Watt, power savings, etc
- Identify, define, and develop procedures to improve environmental sustainability factors, benchmarks for the quantification of energy consumption of software, and recommended techniques to manage software such that the overall energy consumption and associated carbon are reduced. Formulate green/efficiency scoring methodology and procedures to evaluate CNCF projects.
- Evaluate architectures in regards to properties such as power measurement, and management, as well as performance gaps
- Create recommendations to help users tie improvements to carbon net zero goals
- Community outreach on any items within scope, for instance, blogs/twitter/conferences/podcasts/meetups et cetera
- Integrate common tooling into different projects, particularly where that tooling is a CNCF project
- Identify, define, and develop procedures to improve environmental sustainability factors, benchmarks for the quantification of energy consumption of software, and techniques to manage software such that the overall energy consumption and associated carbon is reduced.
- Identify, define, and develop procedures and technologies that can be used to create carbon "unit economics"
- Enhance energy efficiency and reduce the carbon footprint of CNCF projects both on-prem and Cloud services
- Define, prevent, and identify patterns of overt and inadvertent greenwashing
- Collaborate with existing efforts, especially from the standpoint of Cloud Native

### Out of scope
- Form an umbrella organization beyond the CNCF
- Establish a compliance and standards body beyond the CNCF
- Evaluate individual company infrastructures
- Focus outside of Cloud Native Technologies, according to the [CNCF Cloud Native definition](https://github.com/cncf/toc/blob/main/DEFINITION.md)

<!---
### Under Consideration 
Scope 1,2,3 support (operational and embeded), it it still complicated, but very important, wait for standardization
Scope 3 for hybrid architecture

Can we add, in here, also something reflecting that we are not responsible for calling out projects for greenwashing, but rather to help projects improve?
--->

## Deliverables to ToC
- framework document for the cloud-native carbon and energy metrics/measurements/management space
- landscape for the carbon and energy metrics/measurements/management savings
- recommendations for sandbox projects where exploration is needed
- recommendations for new CNCF projects where there are clear use cases
- scheduled regular reporting to ToC on ongoing and completed work
- reporting on carbon and energy saving/metrics/measurements/management projects for graduation and other events, summarizing the external power-related research, reviews, and additional relevant information
- help with regular health checks of projects in the category
- suggestions for improvements for CNCF internal processes, for example, education for sustainability

#### Audiences

- Education - audience is end users and developers
- Project intelligence - audience is TOC / TOC Community
- External collaboration - organizations with the same mindset

#### The issue of the Landscape(s)

- Being “deliberate” about what this (these) are for, and for whom?
- Main power landscape has become anti-pattern by slowing progress

#### Execution & Focus

- How do we spell out CNCF “work items” that can be executed by both CNCF staff and the TOC community
- Can the TOC ask questions of the SIGs?  “Go ruminate on this please”
- Make sure recommendations don’t over-determine users’ tech choices. For reference, the storage WG was successful because it provided genuine guidance about a *range* of approaches in a way that is transparent, unbiased, actionable

### Alignments

We aim to foster collaborations with other groups and initiatives to fulfill our goals by focusing on our engagement and being a responsive voice in the software sustainability space. We need to investigate which groups and initiatives we should approach first. The radar-shaped alignment diagram below should guide what this investigation could look like. 

<img src="https://i.imgur.com/SgWVcBV.png" width=70% style="display: block; margin: 0 auto">

* **Partnership**: We work closely and actively with other initiatives and teams outside TAG
* **Collaboration**: We are in close or loose contact with initiatives and teams, but do not work on joint projects
* **Orientation**: We know the initiatives and teams, but have only sporadic or no contact with them.

## Roles and Responsibilities

### TOC Liasons: 

Up to two CNCF TOC members are nominated to advise the chairs and technical committee, as well as review the status and progress of the TAG. 

<!-- this needs to be determined -->

### Co-Chairs:

The term of the chairs is inline with the best practices established by CNCF TAGs.

The three co-Chair team selection process is to following these criteria, among other best practices used by the CNCF community:
- Do the nominees have strong track records in community management and project maintenance, especially in sustainability and related areas? 
- Are the nominees committed to working with their best knowledge for the TAG and CNCF for the duration of their tenure (the term is in line with CNCF conventions)?
- Does the team represent a balance between research, development, and community management?

<!-- these need to be determined -->


### Technical Committee: 
The technical committee is to help the chairs in managing and developing projects and best practices, gather community input and conduct research. 

The committee consists of up to five members for six months terms.

<!-- these can be determined after the fact, but we can get a march by doing it beforehand. -->

## Acknowledgement
The format of this proposal is inspired from TAG security.
The initial doc was taken from the [Environmental WG charter](https://docs.google.com/document/d/1JaF7lSUmLQ2zmScmca6UF7PgbjMzSxjhhjx2LThThaY/edit#heading=h.x77xxicolnig) and modified by the community.

## Contributors
This proposal is contributed by (in alphabetical order):
- Cara Delia
- Chen Wang
- Debra Bernstein
- Eun Kyung Lee
- Frederick F. Kautz IV
- Huamin Chen
- Jiaju Zhang
- Jochen Joswig
- Jorge Palma
- Leonard Pahlke
- Mark Butcher
- Marlow Weston
- Max Körbächer
- Niki Manoledaki
- Parul Singh
- Scott Rigby
- Tony Mongkolsmai
- William Caban
- Wojtek Cichoń