# eBGP Peering Basics
## Introduction
eBGP or External BGP is peering with a BGP Speaker that is outside of the
Local BGP Speaker's Autonomous System. In other words, this is an
inter-AS peering between 2 BGP networks.

|  **BGP IP Address** | **ASN**  |
|:-------------------:|:--------:|
|    54.0.10.0.254    |   4500   |
|    54.0.10.0.253    |   25467  |

## Configuration for .254

    #!sh
    router bgp 4500
    neighbor 54.0.10.0.254 as 25467



Current GIS solution are mostly tackling big data related requirements in
terms of data volume or data velocity. In the era of cloud computing,
leveraging cloud-based resources is a widely adopted pattern. In addition,
with the advent of big data analytics, performing massively parallel
analytical tasks on large-scale data at rest or data in motion is as well
becoming a feasible approach shaping the design of today’s GIS. Although
scaling out enables GIS to tackle the aforementioned big data induced
requirements, there are still two major open issues. Firstly, dealing with
varying data types across multiple data sources (variety) lead to data and
schema heterogeneity, e.g., to describe locations such as addresses, relative
spatial relationships or different coordinates reference systems. Secondly,
modeling the inherent uncertainties in data (veracity), e.g., real-world
noise and erroneous values due to the nature of the data collecting process.
Both being crucial tasks in data management and analytics that directly
affect the information retrieval and decision-making quality and moreover
the generated knowledge on human-side (value). By leveraging the the
continuous refinement model, we present a holistic approach that explicitly
deals with all big data dimensions. By integrating the user in the
process, computers can learn from the cognitive and perceptive skills of
human analysis to create hidden connections between data and the problem
domain. This helps to decrease the noise and uncertainty and allows to
build up trust in the analysis results on user side which will eventually
lead to an increasing likelihood of relevant findings and generated
knowledge.

## Contact and Support

Role                      | Name                     | E-mail
--------------------------|--------------------------|---------------
**Contact person**        | Prof. Dr. Thomas Setzer  | setzer@fzi.de
**Project coordination**  | Dr. Viliam Simko         | simko@fzi.de
