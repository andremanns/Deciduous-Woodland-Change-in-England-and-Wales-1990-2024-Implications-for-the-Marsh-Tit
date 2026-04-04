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

### Loss
- In most areas, the proportion of DW loss was less than 2%.
- Areas declining by at least 8% were sparsely distributed through most of England and Wales, but clusters were present in the Northwest - particularly regions around the Peak District on the rural-urban fringes of Manchester, Sheffield and Leeds. The increase of urban land in these locations (see figure 4ai), suggests urban sprawl may have contributed to the decline. 
- High loss regions (≥8%) were also observed in the South East between London and Chichester, and in South Wales. In the South East, a reduction of DW was evident around smaller towns and villages, coinciding with an increase in urban developments (see figure 4aii). 
- While regions of ‘no change’ were prominent in the Fens, the North Pennines and Yorkshire Dales, the dominant land class in these regions has historically been arable or grassland (see figure 4aiii). For this reason, lower proportional gross losses would be expected.
- High loss areas (≥8%) were sparse in the East Midlands and East of England. Both regions coincide with extensive areas of arable land cover, limiting the potential for considerable DW loss. 
<p align='left'><image src='images/heatmap/loss_heatmap.png' width=900></p>

### Gain
- Most of the landscape exhibited low-moderate levels of DW gain (0 ≤ x < 4%). Moderate-high gain areas (≥6%) were generally less abundant but common in most regions; the exception would be large parts of the Northwest and the East Midlands where these areas were absent.
- High-gain clusters (≥8%) were evident in Western Leicestershire, South Wales and in the Northeast.
- In Leicestershire, despite an increase in urban area, significant regions of grassland and arable land were converted into DW (see figure x). A large part of this could be attributed to the Wood Pasture and Parkland Habitat Action Plan (WPPHAP), part of a regional effort to improve biodiversity in line with the UK Biodiversity Action Plan (BAP) [4]. Between 1998 and 2016 the scheme was responsible for the planting of more than 2473 ha of woodland [5].
- In South Wales, a large proportion of deciduous woodland was inherited from coniferous or arable land types (see figure x) – the result of multiple forest restoration schemes, such as the AFRP (Afan Forest Resource Plan) run by Natural Resources Wales (NRC), which aims to restore deciduous habitat on Planted Ancient Woodland Sites (PAWS) [6]. Additionally, disease-induced Larch felling, encouraged the restructuring of previously coniferous-dominant woodland [7].
<p align='left'><image src='images/heatmap/gain_heatmap.png' width=900></p>

### Net Change
Net change trends broadly reflected those observed in figures x and x, with the largest increases (>+10%) concentrating in the North East, South Wales and Western Leicestershire. Loss areas by comparison, were less abundant and lower in magnitude (-10% ≤ x < -2%) converging in parts of the North West and South East. Outside of these loss regions, DW cover predominantly remained constant or increased moderately (+2% ≤ x < +6%), indicating that afforestation processes were dominant overall.
<p align='left'><image src='images/heatmap/net_change_heatmap.png' width=900></p>

## 5. Regional Trends
Figures 5a to 5c illustrate the percentage change in DW area across ITL1 (International Territorial Level 1) regions in England and Wales between 1990 and 2024. Values were calculated relative to baseline levels of DW recorded in 1990.

### Loss
The distribution of regional gross losses could be categorised into 3 groups:
- The largest declines were observed in Wales and Northern regions of England (19.4-23.3%, mean=21.8%), with Yorkshire showing the greatest decrease (23.3%). This corresponds with clusters of high DW loss around Manchester, Sheffield, Leeds and South Wales (see figure x).
- The magnitude of decline was lowest in southeastern parts of England - specifically London, the South East and the East (13.5-14.1%, mean=13.8%). While the South East coincides with an area of large absolute loss (see figure x), in 1990 it was recorded as having the largest expanse of DW area in England and Wales (2411km²). This could explain why relative decline in the region was low. 
- The East Midlands, West Midlands and South West experienced moderate losses (15.1-17.6%, mean=16.4%), forming a transition zone from higher loss regions in Northern-England and Wales, to lower loss regions in the Southeast. 

### Gain
- Increases in DW exceeded losses on a regional level across all of England and Wales, with the largest gross gains evident in the North East (74.8%) and East Midlands (63.4%), supporting the cluster patterns observed in figure x. 
- Trends broadly mirrored regional loss patterns, with the lowest relative changes seen across Southern England - in the South West (+25.7%) and the Southeast (+39.0%). Misleadingly, these zones experienced the 2nd and 3rd largest increases in terms of absolute area (South West=712km², South East=621km²), but considerable expanses of baseline DW meant relative increases ranked poorly. 
- Variability was also higher on a regional level for DW gain (SD=12.6pp, range=49.1pp) compared to DW loss (SD=3.6pp, range=9.8pp). This may reflect differing levels of support among regional policy makers for biodiversity initiatives. Additionally, an increase in the number of National Parks, such as the South Downs (inaugurated in 2010) may have restricted urban development [8].
<p align='left'><image src='images/regional/regional_gain.png' width=1100></p>

### Net Change
A net increase was recorded across all regions, with the rank of the top three regions (North East, East Midlands and the East) consistent with those observed in the gross gains analysis (see figure x). Yorkshire (+18.0%), the South East (+11.9%) and the South West (+23.9%) delivered the lowest net increases. As previously mentioned, a low ranking in the latter two can be explained by their large baseline DW areas; Yorkshire on the other hand ranked 7th in terms of its baseline DW extent (811 km²). Poor overall performance in this region is likely linked to it losing nearly a quarter (23.3%) of its DW from 1990 (see figure x). Across the remaining regions, low to moderate net increases (+20 ≥ x > +40%) were evident. 

