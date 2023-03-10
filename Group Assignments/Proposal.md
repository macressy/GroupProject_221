# Race as Vulnerability: The Role of Police in Gentrification
## Proposal Update 13.02.2023

### Research Question:

To advance the [work of Ananya Roy](https://www.publicbooks.org/emergency-urbanism/#fn-39563-2) and [Brenden Beck](https://onlinelibrary.wiley.com/doi/abs/10.1111/cico.12473), we posit that gentrification is more than market-driven displacement. Dispossession and forced removal of working-class communities, particularly those of color, is a persistent feature of the American nationalist project. Nations are built on consolidation and assimilation in opposition to the racialized other. Home ownership, the middle class, hard-work, and citizenship are characteristics used to construct a shared American identity, without which we dissolve, as it were. Those existing outside the constructed identity, must be removed because they represent an insurgent threat to the national project. Gentrification is part of the through line of disappearing communities on the margins--it is among the machinations of racial banishment, carried out through state and private violence, control, and surveillance. Thus, we aim to geospatially demonstrate how economic redevelopment is co-constitutive of state-sanctioned removal. 

**What is the role of police power in the process of gentrification? How do arrests and low level policing fluctuate with demographic and economic shifts in neighborhoods?**

### Why? 

"Racism, specifically, is the state-sanctioned or extralegal production and exploitation of group-differentiated vulnerability to premature death" 
(Ruth Wilson Gilmore, [Golden Gulag Prisons, Surplus, Crisis, and Opposition in Globalizing, 1st ed. (University of California Press, 2007), 28.](https://cominsitu.files.wordpress.com/2018/08/gilmore-ruth-wilson-golden-gulag-2007.pdf))

Displacement is a spatial as well as economic and corporeal condition. When one’s community is gentrified, they lose their claim to space, and particularly property, which confers political power. They are pushed outside their home and made vulnerable to the streets. Vulnerability is compounded as low-level policing then haunts the displaced. We will be quantifying and visualizing communities’ vulnerability to gentrification and how police become agents of that displacement. This endeavor serves to build upon the methodology of the [Urban Displacement Project](https://www.urbandisplacement.org/maps/los-angeles-gentrification-and-displacement/) (UDP). 7 years ago, the project team at UCLA developed a neighborhood change database to identify areas that were vulnerable to gentrification. We will build upon their research and incorporate state violence into the analysis.

### Scope:

We will focus our analysis on the neighborhoods within the Greater Los Angeles area. Within these geographic parameters, we are specifically exploring vulnerability through the various inputs that lead to displacement like demographic shifts, building development, rent prices, and police presence. This may ultimately adjust as we come across new and more helpful data to build on our typology of gentrification-risk. Our intention is to understand the threat of removal faced by various communities within the Greater Los Angeles Area.

### Data Sources:

Gentrification (existing literature/research)
- [Urban Displacement Project typology](https://www.urbandisplacement.org/) - classifies census tracts by their susceptibility to displacement. 

Demographic/Housing:
- [Renter-occupied Households by Race | Census Data (5-Year ACS, 2021)](https://www.socialexplorer.com/tables/ACS2021_5yr/R13285209) SE:A03001B. Race (Renter-Occupied Housing Units)
- [Rent Burden | Census Data (5-Year ACS, 2021)](https://www.socialexplorer.com/tables/ACS2021_5yr/R13285211) - SE:A18002. Gross Rent as a Percentage of Household Income in the Past 12 Months (Dollars). 
Extracting the number of households that pay 30% or more of their monthly income toward rent serves as an approximate measure of rent burden.

Municipal/Administrative
- [Build permits](https://data.lacity.org/A-Prosperous-City/Building-Permits/nbyu-2ha9) - The Department of Building and Safety issues permits for the construction, remodeling, and repair of buildings and structures in the City of Los Angeles.

Police:
- [Police Score Card](https://policescorecard.org/)  - Assigns numerical “score” based on combined data for use of force incidents, citizen complaints, complaint typology, and funding per citizen.
- [LAPD Calls for Service](https://data.lacity.org/Public-Safety/LAPD-Calls-for-Service-2022/u6ri-98iw/data) - Data of calls to police based upon call typology and precincts.  
- [Neighborhood Data for Social Change (USC)](https://map.myneighborhooddata.org/) - various data, such as “public safety” metrics like arrests, visualized and cataloged at the neighborhood level.

### Analysis and Visualizations: 

At this stage, our analysis and visualizations are divided into two parts. In Part A, we have gathered race, rent, and building permit data by census tract to inform our working definition of gentrification. We cleaned this census and city level data and created various bar graphs and choropleth maps of shifts in neighborhoods over time by percent change. In Part B, we have explored UDP’s existing neighborhood change typology and mapped it to city level arrest data in the form of bar graphs and choropleth maps. 

In the next phase, the second half of the academic quarter, we plan to merge Part A and B into a single database, measurement system. We will also build out our own gentrification index with more inputs and develop a geo-statistical methodology for analysis and then visualization. 

### Conclusion:  

Geospatial measurements have the potential to effectively summarize structural violence, advance cultural discourse, and inform policy and community action. While we are striving to reach this potential, we acknowledge our limitations. We recognize the possible bounds of our research, as gentrification is defined and precipitated in myriad ways, some of which we may not be technically equipped to include in our analysis. As we continue to refine the project, we primarily aim to highlight a few of the spatial inputs that depict and quantify vulnerability to gentrification and simultaneously state violence. Additionally, we will try to predict the probability of forced displacement using spatial autocorrelation methods. Our work, like that of our entire cohort, can be part of a critical effort to preserve and empower communities. To quote [Sam Sinyangwe](https://twitter.com/samswey), a data scientist and co-founder of [Campaign Zero](https://campaignzero.org/) and [Mapping Police Violence](https://mappingpoliceviolence.org/), the work we’re all on a journey to do can save lives, and we should hold ourselves accountable to nothing less.

## Status report 07.02.2023

### Roles
**_John Parks_:** Lead Data Collector and Visualizer - identify and pull all viable data inputs, determine how they coalesce for visualization, and decide and execute the ultimate visualizing of our analysis. <br/>
**_Joshua Claxton_:** Police Violence Specialist - inform (maybe geostatistical) analysis, to be done on arrests, police beats, and incidents of escalated violence or fatal encounters, focusing on  the correlation to property values <br/>
**_Miles Cressy_:** Housing Specialist - clean and understand the data related to development, permitting, ownership vs. rent percentages, property values, etc. Conduct thorough analysis and provide visualizations of this housing data through the lens of race data. 

### Status update
We are in frequent communication with a few scheduled calls per week and text group to share updates and coordinate. We are aligned in our approach to the project and have been mutually supportive in the vicissitudes that take place in any group project. Most importantly, we have all been very amenable to modifications and feedback as we refine our topic, scope, and analysis. The only limitation right now is ambition, perhaps. We have entertained a variety of ideas with great excitement and have had to back away and acknowledge constraints of time and our own skill level. 

### Data update
We have located a lot of housing data on HUD Open Data Center and HCD Website and are working through thoughts of tying the data together, experimenting with layering and merging data sets. We have an abundance of various kinds of police data that all contain geo coordinates, but are struggling to find data directly from the Sheriff’s department. We are continuing to dive into various forms of housing data and overlaying it with various race data but are biggest challenge is defining a throughline between housing and policing that is succinct and achievable. Ideas are constantly being iterated upon and we are still in the process of determining what data will be in our final project.

A connection that is real and observed is the relationship between gentrification and policing but determining how to measure gentrification is an obstacle that we are currently facing. We had an idea to scrape Zillow listings, but that will require writing code that may be beyond our abilities at this stage. We also need to figure out how we will statistically analyze the relationship between policing and fluctuations in property values. We have discussed a hotspot analysis (based on the ArcGIS clustering toolset).   

**Housing Links:** 

[CDBG Block Areas](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::community-development-block-grant-grantee-areas/explore?location=6.227014%2C0.315564%2C1.44)

[HUD Location Affordability Index](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::location-affordability-index-v-1-0/explore)

[Low Poverty Index](https://hudgis-hud.opendata.arcgis.com/search?q=Location%20Affordability)

[HCD Affordable Opportunity Sites](https://cadgs.maps.arcgis.com/apps/webappviewer/index.html?id=392e5e687e9041bb8f20e3acc5b211c7)

[Mapping Inequality - Los Angeles](https://dsl.richmond.edu/panorama/redlining/#loc=10/34.015/-118.288&city=los-angeles-ca)

**Policing Links:**

[Fatal Encounters](https://fatalencounters.org/)

[Mapping Police Violence](https://mappingpoliceviolence.org/)

[Police Scorecard](https://policescorecard.org/ca)

[Neighborhood Data for Social Change](https://la.myneighborhooddata.org/)

[LA Public Safety](https://lahub.maps.arcgis.com/apps/instant/lookup/index.html?appid=e7405b41e6234e95bf4a63a4744c5923)

### Concerns

**Immediate:** 
We have a lot of data to pour through, but I think we have done a great job of honing in on the scope and our “inputs”:; housing and police violence.

**Major concerns:**
- We have not established any temporal for our data parameters.
- We do not have a specified geographic boundary (i.e. we have been referencing the greater Los Angeles area, but is that specific enough?).
- We need to figure out how to define gentrification through data.

**Minor concerns:**  
- Time (quarter feels accelerated so it is hard to logistically plan and execute everything we hope to).
- We have not defined the specifics of analysis (ie. geostatistics).

_______________________________________________________________________________________

## Visualizing and Indexing Structural Racism in Los Angeles
**Group Members:** John Parks, Joshua Claxton, Miles Cressy

### Research Question:

The United States (US) is a country of stark systemic inequality between racial groups. Communities of color have been subjected to and still experience exclusion, erasure, and negligence by US institutions. We will be investigating how these disparities geospatially persist in the Greater Los Angeles area. How can structural racism be quantified and visualized across Los Angeles neighborhoods through a multi-factor index?

### Why? 

"Racism, specifically, is the state-sanctioned or extralegal production and exploitation of group-differentiated vulnerability to premature death"- (p.28 _Golden Gulag Prisons, Surplus, Crisis, and Opposition in Globalizing_ , Ruth Wilson Gilmore)

We will measure vulnerability, as defined by Gilmore, across various communities that inhabit Los Angeles. Generally, the vulnerability that structural racism creates, and the restitution it necessitates, is accepted in the American political discourse. However, there remains a powerful contingent of media companies, politicians, and institutions that doubt our inequitable reality. Such denial functions as structural gaslighting to the narratives of communities of color, especially black folks given the persistent legacy of enslavement and exclusionary policies. We will be quantifying the experience of vulnerability through a geospatial index of Los Angeles, focusing on the dimensions of housing, pollution, police violence, and economic development. This endeavor serves to (a) bolster the community narratives that are too easily dismissed and (b) create helpful metrics for targeted public policy. In a cultural moment when truth and lived-experience is being invalidated, we believe our exploration and analysis to be of particular import. 

### Scope:

We will primarily focus our analysis on the neighborhoods within the Greater Los Angeles area. Within these geographic parameters, we are specifically exploring how vulnerability is distributed through property ownership, environmental risk, state violence, economic development, and rent burden. This may ultimately shift and adjust based on the availability of data that we can ascertain and is of particular interest but our intention is to understand the discrepancies between various communities within the Greater Los Angeles Area.

### Data Sources:

Demographic:

- [Renter-occupied Households by Race | Census Data (5-Year ACS, 2021) ](https://www.socialexplorer.com/tables/ACS2021_5yr/R13285209)SE:A03001B. Race (Renter-Occupied Housing Units)

Environmental:

- [Enviroscreen](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40) - CalEnviroScreen is a mapping tool that helps identify California communities that are most affected by many sources of pollution, and where people are often especially vulnerable to pollution’s effects.CalEnviroScreen uses environmental, health, and socioeconomic information to produce scores for every census tract in the state.

Police:

- [Map My Neighborhood](https://map.myneighborhooddata.org/) - various data visualized and cataloged at the neighborhood level.

- [Mapping Police Violence](https://mappingpoliceviolence.org/) (from https://campaignzero.org/campaigns/) - Tracks and catalogs any incident where a law enforcement officer (off-duty or on-duty) applies, on a civilian, lethal force resulting in the civilian being killed whether it is considered “justified” or “unjustified” by the U.S. Criminal Legal System.

- [Deputy-Involved Shootings](https://lasd.org/transparency/deputyinvolvedshootingprevious/) - Tracker provided by LA Sheriff’s Department

- [Arrest Data](https://data.lacity.org/Public-Safety/Arrest-Data-from-2010-to-2019/yru6-6re4) - Tracker regarding arrest data provided LA City.


Economic:

- [Listing of Active Businesses](https://data.lacity.org/Administration-Finance/Listing-of-Active-Businesses/6rrh-rzua) - Listing of all active businesses currently registered with the Office of Finance. An "active" business is defined as a registered business whose owner has not notified the Office of Finance of a cease of business operations. Analysis of business listings may help demonstrate what kind of businesses dominate at-risk and minority communities. 

- [SCAG Vulnerability Indicator](https://gisdata-scag.opendata.arcgis.com/datasets/SCAG::scag-covid19-vulnerability-indicator/explore?location=34.050425%2C-118.211269%2C10.00). SCAG COVID Vulnerability IndicatorShows a lot of pertinent information for the County and other areas regarding employment/rent burden/other items

- [COVID Rent Relief Applications](https://housing.ca.gov/covid_rr/dashboard.html) - Shows aid by city in LA County

Housing:

- [LAHD Affordable Housing Projects List](https://data.lacity.org/Housing-and-Real-Estate/LAHD-Affordable-Housing-Projects-List-2003-to-Pres/mymu-zi3s) LAHD financed projects since 2003 to present. These projects are financed with programs including Affordable Housing Managed Pipeline, Supportive Housing Program, Affordable Housing Bond Program, and the Proposition HHH Supportive Housing Loan Program. Enables us to visualize where affordable housing projects are being funded & developed and if they are being built in areas that require it.

- [Rent Burden | Census Data (5-Year ACS, 2021) ](https://www.socialexplorer.com/tables/ACS2021_5yr/R13285211)- SE:A18002. Gross Rent as a Percentage of Household Income in the Past 12 Months (Dollars). Extracting the number of households that pay 30% or more of their monthly income toward rent serves as an approximate measure of rent burden.

- [CTCAC Opportunity Areas](https://belonging.berkeley.edu/2023-ctcac-hcd-opportunity-map)  CTCAC Opportunity Map showing “High-Resource” to “High-Segregation/Poverty” Areas of lower opportunity can receive additional state funding

- [CA State AFFH Data](https://www.arcgis.com/apps/webappviewer/index.html?id=4d43b384957d4366b09aeeae3c5a1f60) AFFH Data Showing a bunch of different data regarding Affordable Housing/Subsidies/other

- **Will need CoStar Access for property sales

### Analysis and Visualizations: 

Our project will aggregate housing, transit, police, and environmental data sets, listed above, with the aim of presenting this information as a detailed choropleth map.  This map will assist in data interpretation and visualizing inequities between areas within Los Angeles. 

Additionally, we will conduct a Hot Spot Analysis of this data, and our visualization, in order to project likelihood of encountering any/all of our inputs (housing issues, police violence, or environmental risks).  The inclusion of a Hot Spot Analysis directly addresses a guiding principle of this work; to demonstrate likelihood of vulnerability and exposure to a premature death.  

Our group may attempt to Keyword scrape from property listing websites in order to capture biases / popular narratives about certain neighborhoods, issues of gentrification, etc. 

### Conclusion:  

Our hypothesis and impetus for the project is that geospatial measurements can be aggregated to highlight structural racism, advancing cultural discourse and refining public policy. For example, we hope to quantify the magnitude of difference between a black person’s exposure to violence, pollution, and rent burden, in comparison to a white person. We acknowledge the limitations of our research, as structural racism is, by definition, pervasive and cannot merely be quantified by a finite index. As we adjust our index, we hope to highlight the inputs that have the most influence on vulnerability. Ultimately, visualizing and quantifying where rectification is most needed.
