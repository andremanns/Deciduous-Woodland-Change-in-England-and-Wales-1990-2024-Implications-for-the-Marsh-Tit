# Deciduous Woodland Change in England and Wales (1990-2024): Implications for the Marsh Tit
## 1. Project Background
### Context
Following its inclusion on the ‘Birds of Conservation Concern’ Red List in 2021, long term abundance trends for the Marsh tit have continued to decline, with a 48.3% decrease on 1995 levels reported in 2023 [1], [2]. For this reason, the UKDWC have partnered with ornithological charities, and UK government agencies, to produce a report highlighting population trends of the Marsh tit, and the likely environmental drivers. The report will be used to evidence future governmental environmental policy and guide ornithological charities on habitat restoration strategies. The UKDWC has agreed to focus primarily on the suspected environmental drivers including: climate change, invasive species, pollution and habitat loss. 
### The Goal
As a GIS analyst working for the UKDWC, the focus will be to provide insight into the long-term change of Marsh tit habitat cover in the UK using UKCEH land classification data. Key parameters for the study include, confining the analysis to deciduous woodland (DW) in England and Wales. This reflects the current populations spatial occupancy and preferred habitat [3]. 

An initial report is to be delivered to the Director of Environmental Analysis, detailing National and regional land classification changes between 1990 and 2024. The report will highlight the most significant areas of habitat change, detail the causes and explain if this is likely to have impacted Marsh tit population levels.  
### About the UKDWC
The UKDWC is a non-profit environmental research organisation, that monitors biodiversity and ecosystems in the UK, reporting its findings to various charities and central government. Since its founding in 1963, the company has gained a reputation for its excellent ecological and environmental modelling capabilities.

## 2. Data Sourcing and Data Structure
UKCEH (UK Centre for Ecology and Hydrology) 25m raster maps from 1990 and 2024 [3] were cleaned and analysed in QGIS to determine land classification changes relevant to Marsh tit habitat. Before the analysis, both datasets were clipped to England and Wales, and land classes were grouped for simplicity. Figure 2a illustrates how the data was prepared. 
<p align='left'><image src='images/data_sourcing/data_sourcing.png' width=900></p>

## 3. Executive Summary 
Despite net increases in Deciduous Woodland (DW) across England and Wales (+24.8%), significant gross losses were observed across all International Territorial Level 1 (ITL1) regions (13.5% to 23.3%). Yorkshire and the North West ranked highest for gross DW loss, with urban expansion highly prevalent in these regions. On a national scale, built-up areas were the largest contributor to net DW loss (-244.3 km²), accounting for 27.2% of all gross losses.
The Marsh tit’s preference for ancient DW means the loss of established habitat areas cannot be immediately reversed by replacing or increasing DW. For this reason, it is likely that species abundance has been heavily impacted in Yorkshire and the North West since 1990. Both regions have been marked as ‘critical’ and further research is recommended to determine the impact on the local populations. 

## 4. National Trends 
The heatmaps in figures 4a to 4c show the percentage loss, gain and net change of DW in England and Wales between 1990 and 2024. A 5.1x5.1km moving window was used to estimate proportional values, interspersed at 100m intervals. 

DW Loss

- In most areas, the proportion of DW loss was less than 2%.
- Areas declining by at least 8% were sparsely distributed through most of England and Wales, but clusters were present in the Northwest - particularly regions around the Peak District on the rural-urban fringes of Manchester, Sheffield and Leeds. The increase of urban land in these locations (see figure x), suggests urban sprawl may have contributed to the decline. 
- High loss regions (≥8%) were also observed in the South East between London and Chichester, and in South Wales. In the South East, a reduction of DW was evident around smaller towns and villages, coinciding with an increase in urban developments (see figure x). 
- While regions of ‘no change’ were prominent in the Fens, the North Pennines and Yorkshire Dales, the dominant land class in these regions has historically been arable or grassland (see figure x). For this reason, lower proportional gross losses would be expected.
- High loss areas (≥8%) were sparse in the East Midlands and East of England. Both regions coincide with extensive areas of arable land cover, limiting the potential for considerable DW loss (see figure x). 

