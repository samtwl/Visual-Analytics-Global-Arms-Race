# Visual-Analytics-Global-Arms-Race
This repository contains several exploratory data analysis on the global arms trade in R.

## Overview
The global arms trade has been a major concern as the international transfer of arms between states could lead to wars, crimes against humanity and contribute to serious violations of international human rights. The Stockholm International Peace Research Institute (SIPRI) conducts research on arms transfers between regions and states aimed at increasing the fundamental understanding of the impact of arms transfers and to support policymaking. SIPRI aims to contribute to greater transparency in the global arms trade to ensure responsible international arms transfers, hence helping to prevent violent conflict, alleviate tensions and warn about potentially destabilizing arms accumulations. Based on the latest publication by SIPRI in 2017, a rising trend is observed in the volume of international transfers of major weapons, with the highest volume of arm transfers recorded between 2013 to 2017, since 1990 [1]. Research conducted by SIPRI also shows that the global arms trade industry is continuing to export weapons into for deadly armed conflicts. [2]

## Motivation and Objectives
Based on the Global Peace Index 2018 published by the Institute for Economics and Peace, we have identified the countries with 'Low' and 'Very Low Peace' global peace index. [3]

Our project aims to identify the trends and patterns in the international arms transfers at the regional and country levels for these countries and we wish to explore the arms trade dependencies of these countries with other countries. We also aim to explore the major importers and exporters of arms weapons and to find out the relationships between the global arm importers and exporters. Our team is motivated to design a dynamic and interactive dashboard to provide students and policymakers a better understanding and holistic view of the global arms trade.

Through our analysis, we hope to address the following: 
1) To explore the arms imports at regional and country level 
We want to observe the trends in the global arms imports, find out the countries and regions with the highest arm imports and also identify if there are any unusual patterns in the global arm transfers over the years. 
2) To explore the arm trade dependencies between countries 
We would like to explore the chord diagram and network chart to find out the exchange of arms transfer between countries. 
3) Analyse the top exporters of arms 
For a particular region or country, we would like to find out which are the top exporters supplying arms and find out the trends in the arms suppliers across the years. 
4) Explore the arms imports with the economic and population indicators 
Our group wishes to find out if there is a relationship between the economic and population indicators with the arms imports of countries.

## Past Works
A number of applications exist for the visualization of arms trade data. SIPRI produced an interactive web platform using data in their published database but focused on military expenditure instead of arms trade flows (http://visuals.sipri.org/).

More prominently, Google produced an interactive platform visualizing the imports and exports of small arms and ammunition (http://armsglobe.chromeexperiments.com/).

These applications, while enhancing the interpretability of published data, often focus only on one aspect of the arms trade using a singular visualization technique. To value-add to this, we contribute an application featuring multiple visualizations, each providing a different aspect of exploration. The following sections describe our approach to the problem and how the application was designed and built.

## Data Sources
| Type | Description | Source |
| --- | --- | --- |
| Demographics | Detailed Listing of total trend-indicator value (TIV) of a country arms imports or exports, broken down by supplier, recipient | https://www.sipri.org/databases/armstransfers |
| Demographics | Detailed listing of World Economic and Population Indicators	| https://www.worldbank.org/ |
| Demographics | Detailed listing of Global Peace Index of Countries | http://economicsandpeace.org/ |

## Tools and Packages
• treemap
• d3treeR
• dplyr
• tidyverse
• tidyr
• ggplot2
• tidyr
• rsconnect
• htmltools
• htmlwidgets
• metricsgraphics
• RColorBrewer
• shiny
• flexdashboard
• networkD3
• visNetwork
• plotly
• janitor

## Design Framework
A detail description of the design principles used and data visualisation elements built

## Future Work
The Arms Trade visualization application has some areas of potential to be extended and enhanced further.

The application currently focuses on countries with Low and Very Low Peace index. It could to be enhanced to include more countries from the SIPRI arms imports database to provide a better coverage of the global arms imports trade. We could also include the military spending available in SIPRI database to explore the relationship between military spending and arms trade. Based on a research conducted by University of Warwick, a recent study showed the existence of a “local oil dependence”, which indicates that the amount of arms imported has a direct relationship with the amount of oil exported to the arms supplier. Speculatively, arms export to a specific country is affected by the degree of dependence on its supply of oil. Hence, it will be interesting area to explore will also be on energy dependency and arms trade.

## References
[1] Stockholm International Peace Research Institute. https://www.sipri.org/research/armament-and-disarmament/arms-transfers-and-military-spending/international-arms-transfers

[2] Amnesty International. https://www.amnesty.org/en/latest/campaigns/2017/09/killer-facts-the-scale-of-the-global-arms-trade/

[3] The Institute for Economics and Peace. http://visionofhumanity.org/indexes/global-peace-index/
