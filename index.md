---
layout: default
title: Getting Started
nav_order: 1
---

# Getting Started With ResStock
{: .fw-500 }

![](/assets/images/city-skyline-istock-1155981768.jpg)

## What Is ResStock?

The U.S. residential building sector stock energy model, ResStock™, is a highly granular, bottom-up model that uses multiple data sources, statistical sampling methods, and advanced building energy simulations of the residential building stock across the contiguous United States.

ResStock asks and answers two main types of questions: 1) How is energy used in the U.S. housing stock? and 2) What are the impacts of modifying the housing stock with different technologies?

ResStock, along with our partner model ComStock™, make up BuildStock. BuildStock allows for modeling of the U.S. residential and commercial building stock circa 2018.

{:refdef: style="text-align: center;"}
[Join Our Mailing List](https://www.nrel.gov/buildings/end-use-load-profiles#contact){: .btn .btn-blue .white-text}
{:refdef}

## Quick Links

### Access the Dataset
Visit the [Datsets page](https://resstock.nlr.gov/datasets) for access to the published datasets and details about the ways to access them.

Read the [technical reference documentation]({{  site.baseurl  }}{% link assets/trd/ResStockTechnicalReferenceGuide_2025_1.pdf %}) for the most recent baseline model inputs and assumptions.

Learn who is using the data and how with the in-depth [user summary snapshot]({{  site.baseurl  }}{% link assets/pdfs/NREL-Bldgs-BuildStock_infographic-FY25.pdf %}). A shorter version of this information is seen below.

![](/assets/images/BuildStock_Engagement_Highlight_Slide_1.svg)

## What Does ResStock Do?
ResStock enables a new approach to large-scale residential energy analysis across the United States by combining large public and private data sources, statistical sampling, detailed sub-hourly building simulations, and high-performance computing to create public datasets. ResStock is funded by the U.S. Department of Energy (DOE), and built by the National Laboratory of the Rockies (NLR).

ResStock is more than just a basic modeling tool for analyzing energy efficiency and consumption in residential buildings. It integrates a variety of features and capabilities that make it a comprehensive analytical platform. ResStock generates public datasets and downstream products like factsheets and dashboards. Here's a broader description of it's functionalities:

1. **Simulation Tool**: ResStock performs detailed simulations that can project the impact of various energy efficiency measures across millions of building prototypes, tailored to different climates, construction types, and demographics. This allows for a granular analysis of potential energy savings and efficiency improvements.

2. **Policy Analysis Instrument**: ResStock provides data and insights that can help inform state and local energy policies by illustrating the potential impacts of building code modifications, energy efficiency programs, and retrofit incentives.

3. **Decision Support System**: By offering robust datasets and modeling capabilities, ResStock aids decision-makers in prioritizing energy strategies that are most effective for specific regions or types of buildings.

4. **Research and Development Tool**: ResStock is used by researchers to study residential energy trends, assess energy needs, and evaluate the market potential of new energy technologies.

5. **Educational Resource**: ResStock also serves as an educational tool for professionals in the energy sector, helping them understand the complexities of residential energy use and the potential for energy efficiency gains.

In summary, ResStock could be aptly described as an **advanced energy analysis platform** that combines elements of simulation, policy analysis, decision support, research facilitation, and educational outreach. These elements are all focused on enhancing residential energy efficiency and understanding energy consumption patterns.

ResStock helps states, municipalities, utilities, and manufacturers understand the make up of their area's housing stock; identifying the energy or economic impacts of energy efficiency or retrofit measures; and exploring the impact of new technologies such as cold-climate heat pumps for both customers and the grid.

In the pursuit of understanding when and where energy consumption occurs, ResStock can be tailored to answer the core questions many people have (explained in the next section). The results are available in multiple formats and resolutions:

| Format | Resolution |
| --- | --- |
| Spatial | U.S., census division, climate zone, state, county, balancing authority, ISO/RTO, and Public Use Microdata Areas (PUMAs)|
| Temporal | 15 minutes to annual aggregations |
| Sectoral | All U.S. housing by Census and Residential Energy Consumption Survey (RECS) classifications |

To achieve energy objectives and enhance the alignment of building stock with the evolving power grid, a detailed analysis method is essential. This method must be able to evaluate the location, timing, and methods through which clusters of buildings use energy and identify potential energy savings. This tool is designed to aid professionals and researchers engaged in advancing these initiatives.

## What Questions Can and Cannot Be Answered With ResStock?
These are the type of questions that can be answered via data processing, distillation, and visualization of this dataset. This is not a complete list.

_Questions that can be answered with ResStock:_
1. Housing make up and current snapshot of energy consumption

    - How many homes are heated by electricity versus gas? How leaky or well insulated are these homes?

    - How are low-income and renter-occupied housing units different from other housing units?

    - What are the largest opportunities for energy efficiency?

2. Technology potentials and what-if scenarios

    - What is the range of energy consumption and utility bill savings per household if X, Y, or Z are implemented? What are the total expected savings for a program or community with X, Y, or Z?

    - What are the energy consumption and utility bill impacts of a home envelope upgrade versus an HVAC equipment upgrade?

3. Questions that can be addressed with timeseries and customization

    - What types of retrofits would shift a given region from summer peaking to winter peaking?

    - What is the total change in peak demand from energy efficiency?
    
    - How do higher efficiency equipment or envelope improvements affect peak demand?

_Questions that cannot be answered by ResStock alone:_
1. What is the potential for rooftop or community solar?
2. How many homes qualify for the Weatherization Assistance Program or other specific policies?
3. How might different income groups leverage financing mechanisms for their home upgrades?
4. What is the cost of installing a heat pump?
5. What is the energy savings potential for a specific home address?

## How To Use ResStock
ResStock provides access to results through many different forms, including a web data viewer, dashboards, and raw data available for download. Explanations, how-to guides, and tutorials are available in the [Resources section]({{  site.baseurl  }}{% link docs/resources/resources.md %}) to assist using the data for common use cases.

ResStock leverages and is deeply indebted to DOE's open source building energy modeling ecosystem of [Open Studio®](https://openstudio.net/) and [Energy Plus®](https://energyplus.net/). 