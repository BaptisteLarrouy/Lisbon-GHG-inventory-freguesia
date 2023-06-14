# Implementing Lisbon GHG inventory in a GIS. Sector-based and consumption-based approaches.

This repository is the result of the work of Baptiste Larrouy for his master's thesis in Tecnico in Civil Engineering under the supervision of Manuel Duarte Pinheiro in June 2023.

## Executive Summary

Droughts, wildfires, floods, cyclones, food shortage, water stress, heat waves, wars: people are dying from global warming and its consequences.

As global greenhouse gas emissions rise, more and more people are also migrating to city. By 2050, around 70% of the world’s population will live in urban areas. Cities therefore play a crucial role in mitigating climate change by reducing direct emissions that occur within the city boundary (sector-based emissions) and those that result from the way city dwellers consume goods and services (consumption-based emissions).

This thesis lays the foundations for a freguesia-scale (neighbourhood-scale) GHG inventory for Lisbon in open data, both for sector-based and consumption-based emissions. Comprehensive and accurate GHG inventories at such a scale are extremely useful for better understanding the urban metabolism and identifying neighbourhoods with high GHG emissions. A clear map reflecting GHG emissions in the city will help planners, engineers and policy-makers to focus on the important parts of the city to transform and adapt in order to achieve a more sustainable urban system. In addition, having these maps available over time is a powerful tool for monitoring progress and assessing results after urban policies have been implemented.

In this thesis, sector-based GHG inventory was conducted using the BASIC methodology that takes into account three main sectors of emissions: stationary energy (scope 1&2), transportation (scope 1&2) and waste (scope 1&3). A bottom-up approach was performed using E-Redes electricity consumptions data to estimate stationary energy emissions per freguesia. Road transport emissions were estimated considering Lisbon’s Road network. This thesis also presents calculations to assess the carbon footprint of sea and air transport, which turns out to be twice as greats as that of Lisbon’s. Waste emissions were calculated on the basis of per capita waste production.

An initial calculation of Lisbon's consumption-based emissions was carried out by distributing Portugal's consumption-based emissions per capita between the freguesias, weighted by Lisbon's purchasing power and the freguesias' property prices. Consumption-based GHG emissions are higher than the sector-based one which leads to the conclusion that Lisbon is a “consumer city”.

Sector-based and consumption-based inventories are complementary, enabling us to build up a complete picture of Lisbon’s GHG emissions. By implementing them in an open-data GIS, this thesis provides an important tool for understanding the impact of cities on climate. One of the best outcomes of this thesis would be this tool to be used in the future to produce infographics, posters and communication on the effect of cities on climate changes, aimed at city dwellers as well as political decision-makers. 

Climate change is a complex topic. It's everyone's duty to communicate on this subject to improve understanding of the problems on a global scale. In that sense, all the resources are available on this repository and are free to use by anyone wishing to help humanity tackle the climate crisis (under the license mentionned in LICENSE.md)

## Sector-based inventory summary

