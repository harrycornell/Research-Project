# Research Practicum 2019 – Research Plan 

> * Group Name: We Belong in a Museum
> * Group participants names: Cornell, Lincoln; Necaise, Aaron; Robkin, Jessica
> * Project Title: Towards a Model for Predicting Overland Trafficking Routes

## 1. Topic/Purpose Statement

This study addresses the viability of using computer simulations to identify the relationship between transportation networks and the smuggling of illicit antiquities. The intent of this line of work is to provide a tool for law enforcement agencies and cultural heritage workers to recover looted archaeological artifacts by identifying the most probable overland smuggling routes. 

## 2. General Introduction

Throughout the Middle East and North Africa (MENA) region, organized criminal gangs have taken advantage of political instability to loot archaeological sites for the purpose of selling illicit antiquities to fund political insurgency and terrorist organizations (Terrill, 2007). While looting in these areas is a centuries-old practice (Luke & Kersel, 2005), advances in technology and a growing demand for antiquities from this region has caused a dramatic increase in these activities (Terrill, 2007).  

<img src="images/DestructionofPalmyra2016_ArbreshInfo.jpg" width="360" > <img src="images/ISISPropoganda_DestructionofNimrud_BBCNews.jpg" width="485" > *ISIS destruction of the cultural heritage sites of  Palmyra, 2016 (left, Arbesh.info) and Nimrud, 2015 (right, BBC News).* 

During the insurgency of Syria and Iraq by the Islamic State of Iraq and Syria (ISIS) in 2014, the terrorist organization often televised the systematic destruction of what they termed “idolatrous” heritage. Using this as justification for the destruction of cultural heritage sites in the region, ISIS quietly looted these sites prior to their televised destruction, with the funds gained on the black market used to further support their effort (Terrill 2017). During this same time period, ISIS routinely issued permits to groups in the areas under their control, allowing for the looting of archaeological and cultural heritage sites, with the permit holders sharing a portion of the black-market profits with ISIS in exchange for the right to keep some of the profits for themselves. The looting of these sites and the subsequent improvements to domestic and household structures in the areas bordering the sites has been observed through analysis of satellite imagery of these locations (Casana, 2015; Parcak, 2013). In the intervening years, while the presence of ISIS in the region has been marginalized, the looting of archaeological sites continues in the destabilized region (Casana, 2015; Parcak et al., 2016; Terrill, 2017). Oftentimes, the looting of these resources is not known until months after the fact, often seen by satellite imagery or when locals discuss their activities with archaeologists returning to some of the affected areas to continue their research (Casana, 2015; Proulx, 2013). 

<img src="images/TellMardikh_Syria_2014.jpg" width="430" >  <img src="images/TellesSinn_Syria_2014.png" width="330" > *Satellite imagery of looting pits at Syrian archaeological sites Tell Mardikh (left) and Tell es-Sinn (right) (Cassana, 2015).*

The duel impact of the loss of cultural heritage and the monies gained from their sale are motivation to find methods to intercept stolen antiquities before they reach the black market. Understanding the methods of transportation that these groups utilize is essential to understanding how they are moving goods from the initial archaeological sites, through the countries, across the borders, and into safe houses where they could be held for decades before they are sold. 

Computer simulations present an intriguing avenue for this research. By first understanding the transportation options available to smugglers, simulations can be informed which can provide reliable insight on the routes that smugglers would select when transporting illicit antiquities away from looted archaeological sites. Research into transnational smuggling indicates that when transporting illicit goods, smugglers will often transport goods overland following two methods, by hiding in plain sight and/or by moving with stealth (Basu, 2013; Basu, 2014). Following the idea that smugglers will make rational informed decisions when selecting these overland routes (Basu, 2014; Medel, 2015), this project has several aims: first, to use computer simulations to identify viable routes traffickers would use based on previous literature and the application of graph theory; second, to use this data to construct two qualitative surveys designed to provide insight into the decisions participants will make when provided information on road conditions, route circuity, faction-control, crime rates, and population, as well as how they rank the importance of these factors; and finally, to use this data to inform a link-weighting system designed to produce the least-cost paths smugglers would likely select when faced with the same decisions. 

<img src="images/Medel2015_MXRoutes.jpg" width="350" >  <img src="images/types-of-graphs17.png" width="400" > *Examples of using least risk with shortest path theory applied to smuggling (left, Medel et al., 2015) and graph theory algorithm (left, Graph Theory Types of Graphs—Javatpoint, n.d.).*           

In an attempt to aid cultural heritage workers, international NGO's, and local stakeholders, this project addresses the problem of illicit antiquities trafficking by using computer simulations to illuminate the relationship between existing transportation infrastructures and the paths criminals use to transport stolen antiquities from archaeological sites. We believe this project will provide proof of concept that computer simulations can reliably identify routes that smugglers would select when moving illicit goods.  

### 2.1 Motivation

The looting of historical sites is both damaging to the cultural heritage of local communities and helps to  fund dangerous terrorist activity in the MENA region. While there has been a large amount of research focused on drug smuggling, little has addressed the issue of artifact smuggling. This research will address this gap in the literature and potentially have real-world impact on artifact smuggling.

### 2.2 Proposed Solution

The current project will utilize graph-theory to develop a series of routes within known smuggling networks. Our modeled smuggling network will take into account  factors like circuity and crime rates in order to generate routes with better validity than what can be achieved with shortest-path routing. A series of surveys and questionnaires will be used to gain additional insight about our model and smuggling behavior. The goal is for this model of smuggling to be extended to the MENA region where it can be used to predict artifact smuggling routes.

The shortest path routing will be based on risk, not distance.  Along the route, there will be assessments made for the amount of risk using several factors.  Once these risks have been identified and assigned, a short path based on the least risk will be found.  This will be assumed to be the most likely path that the smugglers will take.

### 2.3 Hypotheses:

#### H1:
Incorporating region specific variables that are related to criminal behavior (faction borders, distance, crime rates, and route exposure) will lead to improved prediction of smuggling routes compared to a standard shortest-path approach. 

>> H1 Rationale: Based off previous literature, it is reasonable to believe that smugglers will take actions that help them blend in with civilians in order to avoid detection by authorities. However, in countries that are dealing with major geopolitical conflicts, standard shortest-path routes generated by a program like Google maps are not applicable. It can be difficult to predict the routes in a country with unstable infrastructure. Further, smugglers are likely to be more concerned with the presence of border security or enemy faction control in the region than they are of police presence. From this standpoint, incorporating regional specific information--like the circuity of a route or the presence of border security-- into a graph model for routing may lead to improved prediction of smuggling routes.

#### H2:
When asked to rate the importance of regional variables that influence smuggling, enemy faction presence will serve as the strongest deterrent towards route selection.

>> H2 Rationale: A major challenge for the current project will be validating our model against historical data. Currently, there are some documented drug smuggling routes that have been made public throughout Central and North America. These routes will be used as validation data for our model. However, drug smuggling routes may differ from artifact smuggling routes, and the drug smuggling route data is limited to begin with. Our plan is to administer a survey in which participants are asked to rate and rank several variables that we have identified as important to drug smugglers based on previous literature. These ratings will include characteristics like distance, faction presence, or border control.  We hope to analyze the choices made by participants to understand the extent that these variables contribute to common sense routing decisions. 

#### H3:
Geopolitical conflict will influence region-specific routes. 

>> H3 Rationale: One assumption that we are operating under is that smugglers will generally behave like ordinary citizens in order to lower their visibility to law enforcement. A concern is that--in countries with political instability--law enforcement may not serve as a detriment to smugglers if police corruption is an issue. Countries in the MENA region are dealing with drastically different political realities compared to those in Central America. To better understand how regional instability may influence smuggling and law enforcement behavior, we plan to distribute a qualitative survey to participants who have live(d) in those regions. This exploratory survey will provide insight in how smugglers may operate in those countries. 

### 2.4 Contributions:

* Develop a methodology for predicting artifact smuggling routes that can be applied in the MENA region. 
* Gain insight into smuggling behavior, including information on routing decisions and understanding the influence of geopolitical conflict on smuggling.

## 3. Related Work / Literature Review

One obstacle for predicting the routes that looters take while transporting goods away from archaeological sites is understanding how the political or geographical conditions of a region could influence the routing decisions made by smugglers. While looting in the MENA region deserves unique considerations because of the activity’s relationship to terrorist groups, certain behaviors might hold true  across regions (Proulx, 2013).  From this perspective, understanding looting behavior at a global level could serve to inform our model for looting in the MENA region. 
  
There is some anecdotal evidence to suggest that looters often do not take precautions to avoid detection by archaeologists or law officials after they have stolen historical goods (Proulx, 2013). In this study on regional attitudes towards looting,  Proulx (2013) found that the majority of archaeological field-workers come into contact with looters while working. Further, nearly half of these field-workers have been solicited by looters to purchase back stolen goods. Data from this study was aggregated from historical sites located broadly throughout the world, which provides some insight on looting activity in MENA. However, this study does not help to explain routing behavior that is dependent on border customs and region-specific faction politics. 

Transporting illegal antiquities has its own unique set of complications (proper handling, packaging, packing), however the methods selected to transport these items over land shares many similarities with the trafficking of other illicit goods (Alderman, 2012; Basu; 2013, Basu, 2014). Understanding how these goods are moved over land is useful for informing our transportation models and selecting appropriate variables for study.  To further our understanding of how smugglers historically move illicit goods over land, a review of current research in the field of transnational smuggling was necessary. Transnational smugglers traditionally select two methods to move goods from destination to destination, moving either with stealth or blending in with traditional supply chain movements (Basu, 2013; Basu, 2014). Traffickers make these decisions in a rational way, looking to make the most profits with the fewest risks (Medel, Lu, & Chow, 2015). Medel et al. (2015) investigated the movement of drugs from Mexico into the United States, using crime data to inform transportation prediction models. For these models, an understanding of the mindset of the drug cartels was necessary. The movement of illicit goods requires planning and precision, with traffickers often making well-informed decisions about the routes they use, taking into consideration the political environments the goods must move through, the quality of available routes, and environmental concerns that may impact transport (Medel et al., 2015). Medel et al. (2015) use these factors in conjunction with socio-demographic and crime data to define their cost for moving drugs along the road networks in Mexico. This methodology will inform our own weighting criteria.
  
In finding the most likely path that smugglers may take, we are using graph theory to help predict the routes.  In graph theory, vertices are points (also referred to as nodes) defined with edges that connect the vertices to form a graph.  The edges can be unidirectional or bidirectional.  To use graph theory to help in predicting the shortest route, the graph is created to represent a geographic layout of a region.  The vertices represent the cities that are along the various routes that the smugglers could take.  The edges represent the paths between the cities which are the major roadways that connect the cities.  By defining the vertices and edges to represent geographic routes, a graph is created to help in determining the most likely route smugglers would take.
  
In order to find the most likely route using graph theory, the route with the smallest weighted path will be found.  To accomplish this, the edges (which represents the routes between the cities) will be given weights based on some attributes.  These attributes will include the following:

* Crime rate
* Distance
* Circuity
* Population
* Cartel controlled 

These attributes will define the weight given to each edge in the graph. These attributes have been selected both for their direct applicability, as well as their reliable history of use by other research, including Medel et al.'s 2015 study. 

With the graph constructed and weights applied to the edges, the shortest route can be found.  Although the shortest route can be found manually, there are algorithms that can also find the shortest path.  One such algorithm is Dijkstra’s Algorithm (Rodríguez-Puente & Lazo-Cortés, 2013) which will be used to determine the shortest path though the graph.  The Dijkstra’s Algorithm used with a graph tree simulation program can quickly determine the shortest path given the input.  The route determined by the Dijkstra’s Algorithm will represent the best route, not based on distance, but based on lowest risk to the smuggler.  
  
## 4. Research Method

As previously mentioned, the current project aims to address the lack of information surrounding smuggling routes in the MENA region by developing a model that can identify the most-likely long-distance pathways taken by smugglers. These pathways will consider attributes that are favorable for trafficking in addition to considering the standard least-distance/least-time approach. This will be the initial step in developing a more robust model that can be applied to the MENA region in future research. 
 
* First, using a similar approach as Medel et al. (2015), a graph model will be created that considers distance, faction presence, crime rate, and route circuity. Based on the drug smuggling literature,  these regional crime statistics likely contribute to the routing decisions made by organized criminal networks. 

* Next, we will attempt to gauge the extent that each of these variables influence travel-patterns in the real world.  For this topic, two qualitative surveys will be administered to human subjects. The data gathered will be used to inform our model inputs as well as inform any future attempts to apply this methodology to problem areas in the MENA region. 

Our organization of project workflow can be seen below, showing the steps and decisions that were taken and made throughout the project:

<img src="images/Work Flow.png" width="900" > *Project Work Flow*

### 4.1 Participants

We anticipate drawing from two separate participant populations: one sample from the general college population and the other from participants living in the MENA region. For the college student sample, 30 undergraduate students (age 18+) will be recruited using the University of Central Florida's SONA research system. These students will be asked to complete a short questionnaire on routing decisions.

From the MENA region, 30 adults (18+) who live (or who have lived) in the region will be recruited through Facebook advertisement. It is expected that a portion of these participants will be non-respondents due to the nature of the content on the survey. 

### 4.2 Materials

At current, two questionnaires have been developed to address [hypothesis 2](######h2:) and [hypothesis 3](######h3:):

The first, the Route Decision Questionnaire (RDQ), is composed of two major sections. In the first section, participants will be provided a brief historical context on the project and the issue of smuggling. Then, they will be asked to take on the perspective of a smuggler to rate the importance of our variables of interest (crime rate, faction presence, circuity, and distance traveled). The second section of the survey will ask the participant to rank the importance of the five variables relative to each other.  

The second questionnaire, titled the Regional Influence Questionnaire (RIQ), will be distributed to participants in the MENA region. This survey was developed to probe topics related to corruption and smuggling as they relate to our routing model. The survey consists of structured-interview style questions with multiple choice response. 

## 5. Study Plan and Procedure 

### 5.1 Routing Model
While the basis of this project is for use in MENA to combat illicit antiquities smuggling, due to unreliable and unavailable data from this region, we will run our initial models using information from Mexico, including cartel presence and internal transportation networks. This will allow an initial form of validation using previous research, as well as the ability to run the models due to having access to available data. 

Drawing from the methods developed by Medel et al. (2015), our graph model will be developed using a high-level overview of Central America. In the graph, nodes will represent major way-points located throughout the region. These way-points will consist of several dozen major cities, towns, and highway entrances. Using a qualitative approach, historical data will be gathered on the crime rate and criminal faction presence of that node's surrounding area. This data will be systematically applied to that node’s edges.

Links between nodes will represent the pathway between major way-points. As a base, these links will be given a value that corresponds to the distance between nodes. Then, this distance will be weighted by population, route complexity, crime rate and faction presence of connected nodes. Once this network has been established, routing will be completed using Dijkstra's shortest path algorithm. Because the distance between nodes was weighed by our regional variables, this model will represent the path of least-risk.

<img src="images/MX_NodesLinks_Alpha.jpg" width="600" > *Map of links and nodes overlaid on map of Mexico (created using ESRI ArcGIS 10.7).*

### 5.2 Surveys

As previously mentioned, two surveys have been developed for the current study (the RDQ and the RIQ). The RDQ survey will be distributed to UCF undergraduate students. The purpose of this survey was to collect data on our routing variables in order to aggregate them into a single 'risk' score. The RIQ was designed to collect cultural information from participants who live in MENA. This information was not included in the current project, but this data will be used to further understand smuggling in MENA. 

#### 5.2.1 IRB Plan

RHP-255 forms for both questionnaires will be submitted for review by UCF’s IRB Review Board. As neither questionnaire collects nor retains personal data, we believe the board will provide an exemption for both surveys. While the Route Decision Questionnaire is conducted anonymously, there is an in-person element, and as such, we will keep a completed RHP-254 Explanation of Research form on file, should the review board have need of it. 

#### 5.2.2 Route Decision Questionnaire

Participants recruited through SONA will be asked to fill out the questionnaire in a face-to-face session. The function of an in-person meeting is to ensure that any questions from the participant concerning this nuanced cultural issue can be fully addressed be researchers. After receiving a thorough briefing on the topic, participants will be allowed to complete the paper-based form in private. This questionnaire is not expected to take more than 15 minutes to complete. 

<img src="images/RD_pg1.JPG" width="400" >   <img src="images/RD_pg2.JPG" width="400" >

*Route Decision Questionnaire*

#### 5.2.3 Regional Influence Questionnaire

Participants will be recruited through Facebook and social media. Respondents who choose to participate will receive a link to fill out the survey through Google Forms. Study's completed in this manner are both convenient and anonymous. Survey completion will take no more than 10 minutes. 

### 5.3 Define Routes

A set of routes were taken from previous studies, mainly the Medel et al. (2015) study which showed the routes that were predicted along a path from a cartel-controlled area to the US-Mexico border as shown below. The Medel et al. (2015) study included many factors to come up with the least risk route that the traffickers may take while traveling. Using the study as a reference, our project focused on finding the most likely path from the Mexican city of Zihuatanejo on the Pacific coast to Nuevo Laredo, which shares the border with Laredo, TX.

<img src="images/MedelRoutes.png" width="400">

*Possible drug smuggling routes, created using shortest path models (Medel et al., 2015).* 


A map was studied showing the major road networks between Zihuatanejo to Nuevo Laredo.  Major population cities along the path were picked out to form the road network and cities that the smugglers would have to travel though.  The cities were plotted into Google Earth along with the linear routes between the cities that matched the road networks that connect the cities.  The result is shown below.

<img src="images/RoutesKMZ.png" width="300">

*Mexican cities and roads selected for graph theory model.*


### 5.4 Route and City Information

With the cities defined, information was gathered about each city to start to form the attributes that will be applied to the routes when generating the various weights.  It was decided to use the destination city's information to apply to the route's attributes when calculating the weights.  

City information of crime rate and population was found using crime data that reported the crime rate and population for each city (“Mexico Crime Map,” n.d.).  Cartel information was gathered showing which cartels control different areas (Reed, 2015).  This map was overlaid onto the route maps to allow us to determine which cartels control the different areas for each city.

<img src="images/RoutesWithCartel.png" width="800"> 
<img src="images/CartelMXLegend.png" width="500" > 

*Georectified map of Mexican cartel control with selected cities and roads overlaid (base map by Reed, 2015).*


In total, the following information was collected for the 34 cities selected: 

| City | Crime Rate | Population | Cartel | 
| --- | --- | --- | --- | 
| Aguascalientes | 6.8 | 905908 | Tierra Caliente | 
| Celaya | 38.2 | 513690 | Tierra Caliente | 
| Ciudad Valles | 19.5 | 184262 | Tamaulipas | 
| Ciudad Victoria | 29.3 | 368317 | Tamaulipas | 
| Fresnillo | 42.3 | 231904 | Tamaulipas | 
| Guadalajara | 22.5 | 1538374 | Shared | 
| Huetamo | 28.6 | 49031 | Tierra Caliente | 
| Irapuato | 53.7 | 584276 | Tierra Caliente | 
| La Piedad | 22.3 | 107696 | Tierra Caliente | 
| León | 26.5 | 1575400 | Tierra Caliente | 
| Linares | 0.0 | 89441 | Tamaulipas | 
| Matehuala | 21.4 | 102579 | Tamaulipas | 
| Monclova | 6.7 | 240033 | Tamaulipas | 
| Monterrey | 17.1 | 1226064 | Shared | 
| Morelia | 41.2 | 786782 | Tierra Caliente | 
| Nueva Ciudad Guerrero | 0.0 | 5371 | Tamaulipas | 
| Nueva Italia de Ruiz | 4.7 | 42605 | Tierra Caliente | 
| Nuevo Laredo | 15.2 | 432926 | Tamaulipas | 
| Pátzcuaro | 14.7 | 95335 | Tierra Caliente | 
| Piedras Negras | 7.1 | 168297 | Tamaulipas | 
| Reynosa | 30.9 | 718857 | Tamaulipas | 
| Rioverde | 10.0 | 100293 | Tamaulipas | 
| Sabinas | 2.9 | 69718 | Tamaulipas | 
| Sabinas Hidalgo | 10.3 | 38888 | Tamaulipas | 
| Saltillo | 3.2 | 825244 | Tamaulipas | 
| San Juan de los Lagos | 13.3 | 74932 | Tierra Caliente | 
| San Juan del Río | 13.5 | 280960 | Tierra Caliente | 
| San Luis Potosí | 20.4 | 854014 | Tamaulipas | 
| San Tiburcio | 0.0 | 548 | Tamaulipas | 
| Torreón | 11.1 | 723100 | Sinaloa | 
| Uruapan | 74.6 | 348643 | Tierra Caliente | 
| Zacatecas | 36.3 | 148752 | Tamaulipas | 
| Zamora | 62.9 | 200205 | Tierra Caliente | 
| Zihuatanejo | 103.8 | 132894 | Tierra Caliente | 

The routes were defined next using the maps that were generated.  Each of the 67 defined routes was given the name of a 'from' and 'to' city.  The routes linear distance was measured using Google Earth.  The routes road distance was calculated using Google Maps.  These two attributes were used to calculate the circuity of the route by dividing the route distance by the linear distance.  The destination city's crime rate and population was also tabulated for the routes.

| Route | Linear Distance (mi) | Path Distance (mi) | Circuity | Destination City Crime Rate | Destination Population |
| --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 75.9 | 162.0 | 2.1 | 28.6 | 49031 |
| Zihuatanejo to Nueva Italia de Ruiz | 97.4 | 125.0 | 1.3 | 4.7 | 42605 |
| Nueva Italia de Ruiz to Uruapan | 25.3 | 36.2 | 1.4 | 74.6 | 348643 |
| Huetamo to Morelia | 74.2 | 128.0 | 1.7 | 41.2 | 786782 |
| Uruapan to Pátzcuaro | 26.9 | 35.5 | 1.3 | 14.7 | 95335 |
| Pátzcuaro to Morelia | 27.6 | 33.7 | 1.2 | 41.2 | 786782 |
| Morelia to San Juan del Río | 85.6 | 151.0 | 1.8 | 13.5 | 280960 |
| Morelia to Celaya | 57.3 | 90.4 | 1.6 | 38.2 | 513690 |
| Morelia to Irapuato | 65.8 | 86.6 | 1.3 | 53.7 | 584276 |
| Celaya to Irapuato | 34.1 | 42.2 | 1.2 | 53.7 | 584276 |
| Irapuato to Celaya | 34.1 | 42.2 | 1.2 | 38.2 | 513690 |
| San Juan del Río to Celaya | 49.9 | 65.6 | 1.3 | 38.2 | 513690 |
| Celaya to San Juan del Río | 49.9 | 65.6 | 1.3 | 13.5 | 280960 |
| Pátzcuaro to La Piedad | 58.4 | 132.0 | 2.3 | 22.3 | 107696 |
| Uruapan to Zamora | 40.9 | 64.9 | 1.6 | 62.9 | 200205 |
| Zamora to La Piedad | 25.6 | 32.7 | 1.3 | 22.3 | 107696 |
| La Piedad to Irapuato | 46.9 | 61.5 | 1.3 | 53.7 | 584276 |
| Zamora to Guadalajara | 82.0 | 104.0 | 1.3 | 22.5 | 1538374 |
| La Piedad to Guadalajara | 83.8 | 103.0 | 1.2 | 22.5 | 1538374 |
| La Piedad to León | 56.4 | 69.6 | 1.2 | 26.5 | 1575400 |
| Irapuato to León | 38.8 | 43.1 | 1.1 | 26.5 | 1575400 |
| San Juan del Río to San Luis Potosí | 134.0 | 159.0 | 1.2 | 20.4 | 854014 |
| Celaya to San Luis Potosí | 105.0 | 160.0 | 1.5 | 20.4 | 854014 |
| Irapuato to San Luis Potosí | 101.0 | 128.0 | 1.3 | 20.4 | 854014 |
| León to San Luis Potosí | 82.4 | 112.0 | 1.4 | 20.4 | 854014 |
| Guadalajara to San Juan de los Lagos | 70.3 | 89.2 | 1.3 | 13.3 | 74932 |
| San Juan de los Lagos to San Luis Potosí | 102.0 | 119.0 | 1.2 | 20.4 | 854014 |
| León to San Juan de los Lagos | 38.5 | 50.6 | 1.3 | 13.3 | 74932 |
| San Juan de los Lagos to León | 38.5 | 50.6 | 1.3 | 26.5 | 1575400 |
| San Juan del Río to Rioverde | 105.0 | 255.0 | 2.4 | 10.0 | 100293 |
| Rioverde to San Luis Potosí | 62.6 | 109.0 | 1.7 | 20.4 | 854014 |
| San Luis Potosí to Rioverde | 62.6 | 109.0 | 1.7 | 10.0 | 100293 |
| San Juan del Río to Ciudad Valles | 121.0 | 231.0 | 1.9 | 19.5 | 184262 |
| Rioverde to Ciudad Valles | 61.3 | 75.8 | 1.2 | 19.5 | 184262 |
| Ciudad Valles to Rioverde | 61.3 | 75.8 | 1.2 | 10.0 | 100293 |
| Ciudad Valles to Matehuala | 152.0 | 166.0 | 1.1 | 21.4 | 102579 |
| San Luis Potosí to Matehuala | 101.0 | 121.0 | 1.2 | 21.4 | 102579 |
| Ciudad Valles to Ciudad Victoria | 117.0 | 143.0 | 1.2 | 29.3 | 368317 |
| Ciudad Victoria to Linares | 80.2 | 96.7 | 1.2 | 0.0 | 89441 |
| Matehuala to Linares | 104.0 | 142.0 | 1.4 | 0.0 | 89441 |
| Linares to Monterrey | 72.7 | 80.9 | 1.1 | 17.1 | 1226064 |
| Monterrey to Sabinas Hidalgo | 48.0 | 64.8 | 1.4 | 10.3 | 38888 |
| Sabinas Hidalgo to Nuevo Laredo | 77.7 | 81.7 | 1.1 | 15.2 | 432926 |
| Monterrey to Nueva Ciudad Guerrero | 86.0 | 108.0 | 1.3 | 0.0 | 5371 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 66.1 | 78.1 | 1.2 | 15.2 | 432926 |
| Monterrey to Reynosa | 125.0 | 136.0 | 1.1 | 30.9 | 718857 |
| Reynosa to Nueva Ciudad Guerrero | 62.7 | 81.7 | 1.3 | 0.0 | 5371 |
| Guadalajara to Aguascalientes | 103.0 | 138.0 | 1.3 | 6.8 | 905908 |
| San Juan de los Lagos to Aguascalientes | 41.9 | 50.8 | 1.2 | 6.8 | 905908 |
| Aguascalientes to Zacatecas | 57.2 | 73.2 | 1.3 | 36.3 | 148752 |
| Guadalajara to Zacatecas | 149.0 | 199.0 | 1.3 | 36.3 | 148752 |
| San Luis Potosí to Zacatecas | 107.0 | 120.0 | 1.1 | 36.3 | 148752 |
| Guadalajara to Fresnillo | 172.0 | 217.0 | 1.3 | 42.3 | 231904 |
| Zacatecas to Fresnillo | 29.5 | 37.8 | 1.3 | 42.3 | 231904 |
| Zacatecas to San Tiburcio | 113.0 | 127.0 | 1.1 | 0.0 | 548 |
| Matehuala to San Tiburcio | 63.6 | 73.9 | 1.2 | 0.0 | 548 |
| San Tiburcio to Saltillo | 92.3 | 108.0 | 1.2 | 3.2 | 825244 |
| Matehuala to Saltillo | 121.0 | 158.0 | 1.3 | 3.2 | 825244 |
| Saltillo to Monterrey | 43.7 | 54.2 | 1.2 | 17.1 | 1226064 |
| Fresnillo to Torreón | 166.0 | 205.0 | 1.2 | 11.1 | 723100 |
| Saltillo to Torreón | 149.0 | 157.0 | 1.1 | 11.1 | 723100 |
| Torreón to Saltillo | 149.0 | 157.0 | 1.1 | 3.2 | 825244 |
| Torreón to Monclova | 153.0 | 229.0 | 1.5 | 6.7 | 240033 |
| Saltillo to Monclova | 106.0 | 123.0 | 1.2 | 6.7 | 240033 |
| Monterrey to Monclova | 105.0 | 121.0 | 1.2 | 6.7 | 240033 |
| Monclova to Sabinas | 67.0 | 71.4 | 1.1 | 2.9 | 69718 |
| Sabinas to Piedras Negras | 63.8 | 75.6 | 1.2 | 7.1 | 168297 |
| Piedras Negras to Nuevo Laredo | 103.0 | 110.0 | 1.1 | 15.2 | 432926 |

## 6. Results

### 6.1 Route Decision Questionnaire Responses

The results for the questionnaire were gathered from a pilot study using the class as subjects.  The different route attributes had their respective Score and Ranking attributes averaged.  The Low/High value for each attribute was taken by using the value that had the majority of the responses.  The averaged information is shown below.  A higher Score attribute value showed that the attribute was more important.  A lower Ranking for the attribute showed that the attribute was more important when compared to the other attributes. As can be seen below, the presence of competeing gangs was ranked with the highest importance, lending support to Hypothesis 2. 

| Attribute | Score | Low/High | Ranking |
| --- | --- | --- | --- |
| Presence of Competing Gangs | 4.71 | Low | 1.86 |
| Distance to Next Destination | 3.86 | Low | 2.43 |
| Crime Rate | 3.14 | High | 3.14 |
| Population Density | 2.86 | Low | 3.71 |
| Complexity of the Route | 2.86 | Low | 3.86 |

### 6.2 Regional Influence Questionnaire Response
Given the nature of this survey, the pilot study was used as an opportunity to receive feedback on question structure and organization. The Regional Influence Questionnaire will be used in future work, as discussed in section 8.2.  

### 6.3 Calculating Attribute Weights

To apply the weights of the different attributes, scales were applied to each attribute.  The scale was based on the Score and Ranking attribute that was derived from the Route Decision Questionnaire.  These scales will be used against each route's attributes to determine the final weighting of the route.  The scales were calculated using the following formula to allow for the more risky attribute to have a higher value.  The Score were based on a scale of 1 - 5, where 5 was set to be the most risky. The Ranking were based on a scale of 1 - 5, where 1 was set to be the most risky.  For the Composite calculation, the Ranking was reversed to allow the Score and Ranking to use a scale of 1 - 5 with 5 being the most risky.  This formula for calculating the Composite score is shown below there the Ranking was reversed, then the Score and the Ranking was averaged.

Composite = Average(Score, 5.00 - Ranking)  

With the above formula, the Composite value was calculated for each attribute.

| Attribute | Composite |
| --- | --- |
| Presence of Competing Gangs | 3.93 |
| Distance to Next Destination | 3.21 |
| Crime Rate | 2.50 |
| Population Density | 2.07 |
| Complexity of the Route | 2.00 |

Each destination city was assigned a cartel that controlled the particular area.  For this project, it was assumed that the beginning city of Zihuatanejo was the control cartel, with a weighting of 0 (least risky).  If a city was in a rival cartel area, then the cartel weighting was set to 1 (most risky).  If the city had shared or multiple controls from cartels, it was given a partial weighting of 0.33 since there were three cartels in the study.

| Cartel | Weighting |
| --- | --- |
| Shared | 0.33 |
| Sinaloa | 1.00 |
| Tamaulipas | 1.00 |
| Tierra Caliente | 0.00 |

Each of the route attributes were normalized to range from 0 to 1.  The normalization was done by calculating the value over the range of the minimum and maximum for each attribute using the following formula.

Normalized Attribute = (Attribute Value - Min Attribute Value) / (Max Attribute Value - Min Attribute Value)

The ascending or descending order was based on the Low/High response from the Route Decision Questionnaire results.

Each attribute for the route was then scaled by the attribute Composite value and summed together.  The formula is shown below that was used to calculate the route weight.

Route Weight = (Distance * Distance to Next Destination Composite) + (Circuity * Complexity of the Route Composite) + (Crime * Crime Rate Composite) + (Population * Population Density Composite) + (Cartel * Presence of Competing Gangs Composite)

The results for each route is shown below:

| Route | Distance | Circuity | Crime | Population | Cartel | Route Weight |
| --- | --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 0.42 | 0.21 | 0.38 | 0.97 | 0.00 | 4.74 |
| Zihuatanejo to Nueva Italia de Ruiz | 0.58 | 0.83 | 0.06 | 0.97 | 0.00 | 5.72 |
| Nueva Italia de Ruiz to Uruapan | 0.98 | 0.72 | 1.00 | 0.78 | 0.00 | 8.73 |
| Huetamo to Morelia | 0.57 | 0.51 | 0.55 | 0.50 | 0.00 | 5.28 |
| Uruapan to Pátzcuaro | 0.99 | 0.81 | 0.20 | 0.94 | 0.00 | 7.22 |
| Pátzcuaro to Morelia | 1.00 | 0.88 | 0.55 | 0.50 | 0.00 | 7.37 |
| Morelia to San Juan del Río | 0.47 | 0.48 | 0.18 | 0.82 | 0.00 | 4.62 |
| Morelia to Celaya | 0.74 | 0.62 | 0.51 | 0.67 | 0.00 | 6.29 |
| Morelia to Irapuato | 0.76 | 0.81 | 0.72 | 0.63 | 0.00 | 7.15 |
| Celaya to Irapuato | 0.96 | 0.86 | 0.72 | 0.63 | 0.00 | 7.91 |
| Irapuato to Celaya | 0.96 | 0.86 | 0.51 | 0.67 | 0.00 | 7.48 |
| San Juan del Río to Celaya | 0.85 | 0.81 | 0.51 | 0.67 | 0.00 | 7.03 |
| Celaya to San Juan del Río | 0.85 | 0.81 | 0.18 | 0.82 | 0.00 | 6.51 |
| Pátzcuaro to La Piedad | 0.55 | 0.12 | 0.30 | 0.93 | 0.00 | 4.70 |
| Uruapan to Zamora | 0.86 | 0.61 | 0.84 | 0.87 | 0.00 | 7.89 |
| Zamora to La Piedad | 1.00 | 0.84 | 0.30 | 0.93 | 0.00 | 7.56 |
| La Piedad to Irapuato | 0.87 | 0.81 | 0.72 | 0.63 | 0.00 | 7.52 |
| Zamora to Guadalajara | 0.68 | 0.84 | 0.30 | 0.02 | 0.67 | 7.30 |
| La Piedad to Guadalajara | 0.68 | 0.87 | 0.30 | 0.02 | 0.67 | 7.37 |
| La Piedad to León | 0.83 | 0.87 | 0.36 | 0.00 | 0.00 | 5.30 |
| Irapuato to León | 0.95 | 0.96 | 0.36 | 0.00 | 0.00 | 5.87 |
| San Juan del Río to San Luis Potosí | 0.43 | 0.90 | 0.27 | 0.46 | 1.00 | 8.75 |
| Celaya to San Luis Potosí | 0.43 | 0.66 | 0.27 | 0.46 | 1.00 | 8.25 |
| Irapuato to San Luis Potosí | 0.57 | 0.84 | 0.27 | 0.46 | 1.00 | 9.08 |
| León to San Luis Potosí | 0.64 | 0.78 | 0.27 | 0.46 | 1.00 | 9.18 |
| Guadalajara to San Juan de los Lagos | 0.75 | 0.84 | 0.18 | 0.95 | 0.00 | 6.50 |
| San Juan de los Lagos to San Luis Potosí | 0.61 | 0.92 | 0.27 | 0.46 | 1.00 | 9.36 |
| León to San Juan de los Lagos | 0.92 | 0.81 | 0.18 | 0.95 | 0.00 | 6.99 |
| San Juan de los Lagos to León | 0.92 | 0.81 | 0.36 | 0.00 | 0.00 | 5.46 |
| San Juan del Río to Rioverde | 0.00 | 0.00 | 0.13 | 0.94 | 1.00 | 6.20 |
| Rioverde to San Luis Potosí | 0.66 | 0.50 | 0.27 | 0.46 | 1.00 | 8.67 |
| San Luis Potosí to Rioverde | 0.66 | 0.50 | 0.13 | 0.94 | 1.00 | 9.31 |
| San Juan del Río to Ciudad Valles | 0.11 | 0.38 | 0.26 | 0.88 | 1.00 | 7.51 |
| Rioverde to Ciudad Valles | 0.81 | 0.87 | 0.26 | 0.88 | 1.00 | 10.73 |
| Ciudad Valles to Rioverde | 0.81 | 0.87 | 0.13 | 0.94 | 1.00 | 10.53 |
| Ciudad Valles to Matehuala | 0.40 | 0.97 | 0.29 | 0.94 | 1.00 | 9.81 |
| San Luis Potosí to Matehuala | 0.60 | 0.89 | 0.29 | 0.94 | 1.00 | 10.31 |
| Ciudad Valles to Ciudad Victoria | 0.50 | 0.88 | 0.39 | 0.77 | 1.00 | 9.87 |
| Ciudad Victoria to Linares | 0.71 | 0.89 | 0.00 | 0.94 | 1.00 | 9.95 |
| Matehuala to Linares | 0.51 | 0.77 | 0.00 | 0.94 | 1.00 | 9.06 |
| Linares to Monterrey | 0.78 | 0.96 | 0.23 | 0.22 | 0.67 | 8.09 |
| Monterrey to Sabinas Hidalgo | 0.86 | 0.78 | 0.14 | 0.98 | 1.00 | 10.61 |
| Sabinas Hidalgo to Nuevo Laredo | 0.78 | 1.00 | 0.20 | 0.73 | 1.00 | 10.45 |
| Monterrey to Nueva Ciudad Guerrero | 0.66 | 0.85 | 0.00 | 1.00 | 1.00 | 9.82 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 0.80 | 0.91 | 0.20 | 0.73 | 1.00 | 10.31 |
| Monterrey to Reynosa | 0.54 | 0.97 | 0.41 | 0.54 | 1.00 | 9.76 |
| Reynosa to Nueva Ciudad Guerrero | 0.78 | 0.82 | 0.00 | 1.00 | 1.00 | 10.13 |
| Guadalajara to Aguascalientes | 0.53 | 0.79 | 0.09 | 0.43 | 0.00 | 4.38 |
| San Juan de los Lagos to Aguascalientes | 0.92 | 0.88 | 0.09 | 0.43 | 0.00 | 5.83 |
| Aguascalientes to Zacatecas | 0.82 | 0.83 | 0.49 | 0.91 | 1.00 | 11.32 |
| Guadalajara to Zacatecas | 0.25 | 0.79 | 0.49 | 0.91 | 1.00 | 9.42 |
| San Luis Potosí to Zacatecas | 0.61 | 0.95 | 0.49 | 0.91 | 1.00 | 10.87 |
| Guadalajara to Fresnillo | 0.17 | 0.85 | 0.57 | 0.85 | 1.00 | 9.36 |
| Zacatecas to Fresnillo | 0.98 | 0.83 | 0.57 | 0.85 | 1.00 | 11.92 |
| Zacatecas to San Tiburcio | 0.58 | 0.95 | 0.00 | 1.00 | 1.00 | 9.75 |
| Matehuala to San Tiburcio | 0.81 | 0.92 | 0.00 | 1.00 | 1.00 | 10.46 |
| San Tiburcio to Saltillo | 0.66 | 0.91 | 0.04 | 0.48 | 1.00 | 8.98 |
| Matehuala to Saltillo | 0.44 | 0.82 | 0.04 | 0.48 | 1.00 | 8.06 |
| Saltillo to Monterrey | 0.90 | 0.86 | 0.23 | 0.22 | 0.67 | 8.29 |
| Fresnillo to Torreón | 0.22 | 0.87 | 0.15 | 0.54 | 1.00 | 7.88 |
| Saltillo to Torreón | 0.44 | 1.00 | 0.15 | 0.54 | 1.00 | 8.84 |
| Torreón to Saltillo | 0.44 | 1.00 | 0.04 | 0.48 | 1.00 | 8.44 |
| Torreón to Monclova | 0.12 | 0.68 | 0.09 | 0.85 | 1.00 | 7.64 |
| Saltillo to Monclova | 0.59 | 0.92 | 0.09 | 0.85 | 1.00 | 9.66 |
| Monterrey to Monclova | 0.60 | 0.93 | 0.09 | 0.85 | 1.00 | 9.70 |
| Monclova to Sabinas | 0.83 | 0.99 | 0.04 | 0.96 | 1.00 | 10.64 |
| Sabinas to Piedras Negras | 0.81 | 0.90 | 0.10 | 0.89 | 1.00 | 10.42 |
| Piedras Negras to Nuevo Laredo | 0.65 | 0.99 | 0.20 | 0.73 | 1.00 | 10.01 |

### 6.4 Graph Theory Results

Graph Tea is an application that can take a graph and apply different algorithms to the graphs. Graph Tea was used with Dijkstra's algorithm to calculate the route with the least risk calculated on based on the routes attributes and survey results. The cities were loaded into Graph Tea in their respective geographical locations. The city's latitude and longitude was used to place the city node for Graph Tea in the program screen space coordinates. This allowed for an accurate geospatial representation of the city's location within Graph Tea.

The routes were defined using city to city routes, with the weights being defined from the results of each route’s attributes and the weighting determined by the Route Decision Questionnaire results. The route weight that was calculated for each route represents the amount of risk associated with that route. The input into Graph Tea is show below:

<img src="images/GraphTeaInput.png" width="400"> 
 

Graph Tea was run with the input of the cities, routes, and weights to find the least risk path between the source city and the destination city. For this, the Dijkstra algorithm was run. Within the program, the route with the smallest weights was calculated, which represents the route with the least amount of risk. The results are shown in the below image and a video link to the Dijkstra algorithm being run.

<img src="images/MexicoRoutes.png" width="400"> *Graph Tea results with five attributes.* 


The video will go to a link that can download the mp4 file for playback:

[![Graph Tea](images/MexicoRoutes85.png)](https://github.com/harrycornell/Research-Project/blob/master/images/MexicoRoutes.mp4)

The routes generated using the Graph Tea program contained nine total stops and traveled a distance of 1236 miles: 

| Route | Linear Distance (mi) | Path Distance (mi) | Circuity | Destination City Crime Rate | Destination Population |
| --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 75.9 | 162.0 | 2.1 | 28.6 | 49031 |
| Huetamo to Morelia | 74.2 | 128.0 | 1.7 | 41.2 | 786782 |
| Morelia to San Juan del Río | 85.6 | 151.0 | 1.8 | 13.5 | 280960 |
| San Juan del Río to Ciudad Valles | 121.0 | 231.0 | 1.9 | 19.5 | 184262 |
| Ciudad Valles to Matehuala | 152.0 | 166.0 | 1.1 | 21.4 | 102579 |
| Matehuala to Saltillo | 121.0 | 158.0 | 1.3 | 3.2 | 825244 |
| Saltillo to Monterrey | 43.7 | 54.2 | 1.2 | 17.1 | 1226064 |
| Monterrey to Nueva Ciudad Guerrero | 86.0 | 108.0 | 1.3 | 0.0 | 5371 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 66.1 | 78.1 | 1.2 | 15.2 | 432926 |

The route weights were as follows: 

| Route | Distance | Circuity | Crime | Population | Cartel | Route Weight |
| --- | --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 0.42 | 0.21 | 0.38 | 0.97 | 0.00 | 4.74 |
| Huetamo to Morelia | 0.57 | 0.51 | 0.55 | 0.50 | 0.00 | 5.28 |
| Morelia to San Juan del Río | 0.47 | 0.48 | 0.18 | 0.82 | 0.00 | 4.62 |
| San Juan del Río to Ciudad Valles | 0.11 | 0.38 | 0.26 | 0.88 | 1.00 | 7.51 |
| Ciudad Valles to Matehuala | 0.40 | 0.97 | 0.29 | 0.94 | 1.00 | 9.81 |
| Matehuala to Saltillo | 0.44 | 0.82 | 0.04 | 0.48 | 1.00 | 8.06 |
| Saltillo to Monterrey | 0.90 | 0.86 | 0.23 | 0.22 | 0.67 | 8.29 |
| Monterrey to Nueva Ciudad Guerrero | 0.66 | 0.85 | 0.00 | 1.00 | 1.00 | 9.82 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 0.80 | 0.91 | 0.20 | 0.73 | 1.00 | 10.31 |

### 6.5 Sensitivity Analyses

For completeness, a sensitivity analysis was conducted. When one of the attributes was removed and the route was generated using only four attributes, the simulation produced the same route for each attribute combination as it had when it was run with all five attributes, with the exception of the model that was generated without the Population attribute. 

| Attributes | Results |
| --- | --- |
| Circuity, Crime, Population, Cartel | <img src="images/MexicoRoutes_Cir_Cr_Pop_Cart_PS.png" width="400"> |
| Distance, Circuity, Crime, Population | <img src="images/MexicoRoutes_Dis_Cir_Cr_Pop_PS.png" width="400"> |
| Distance, Circuity, Population, Cartel | <img src="images/MexicoRoutes_Dis_Cir_Pop_Cart_PS.png" width="400"> |
| Distance, Crime, Population, Cartel | <img src="images/MexicoRoutes_Dis_Cr_Pop_Cart_PS.png" width="400"> |
| Distance, Circuity, Crime, Cartel |  <img src="images/MexicoRoutes_Dis_Cir_Cr_Cart_PS.png" width="400"> |

Additionally, a second analysis was conducted using only one attribute, instead of all five, the results can be seen below:

| Attribute | Results |
| --- | --- |
| Cartel | <img src="images/MexicoRoutesCartel.png" width="400"> |
| Circuity | <img src="images/MexicoRoutesCircuity.png" width="400"> |
| Crime | <img src="images/MexicoRoutesCrime.png" width="400"> |
| Distance | <img src="images/MexicoRoutesDistance.png" width="400"> |
| Population |  <img src="images/MexicoRoutesPopulation.png" width="400"> |

When running the simulation using only one attribute, instead of considering all five, there was variation in the routes. When using only one attribute, the routes generated for population, distance, and cartel varied slightly. Interestingly, however, the routes generated for both crime and circuity both matched each other and were the same as the route generated using all five attributes. Also interesting, none of the routes match the recommended route from Google Maps, which also uses graph theory to generate routes, though uses different attributes to define weights. Both of these analyses speak to the usefulness of this method. The simulation is not just generating a traditional route, but by taking into considerations the factors that have proven to be of importance to smugglers, it is producing viable alternative options that could prove useful to law enforcement.

<img src="images/GoogleMaps.png" width="400"> *Google Maps generated route from Zihuatanejo to Nuevo Laredo.*


<img src="images/MexicoGoogleMapsRoutes.png" width="400"> *Google Maps generated route overlaid on Graph Tea route map.*


## 7. Conclusion

### 7.1 Compare to Other Studies Results

The current study serves as a proof of concept for using graph theory to the predict routes used by artifact smugglers when traveling over land. As seen above, the routes generated here appear to be reasonable in that they do not take illogical or random deviations from the fastest routes provided by standard software like Google Maps. Instead, deviations from the most obvious route reflect the unique considerations that might be taken by individual criminal organizations. Similarly, the routes that our graph model predicted share a general directionality to those routes predicted by Medel et al. who employed a surface cost analysis (Medel et al., 2015). Similarity among these approaches provides increased confidence that our routes represent reasonable pathways from Southern to Northern Mexico. The primary difference between the current model and the routes provided by Medel et al. (2015) and Google Maps is that the current model operates at a low resolution. Instead of predicting the exact roads or highway networks used by smugglers, the current project predicts the cities that smugglers might pass through during their trips in the country. 

Attempting to predict routes using graph theory provides several strengths and weaknesses compared to other methods. The most obvious benefit is that graph models are highly customizable and scalable. It would be possible to scale our city-based approach up to a much higher resolution by treating each individual stoplight or crossway as a node in the model. This operation would be more computationally heavy, but it would provide insight about the favorable smuggling roads within a city's infrastructure. Additionally, this model is highly specific allowing for users to adjust model weights and inputs depending on the particular criminal organization or smuggling operation being assessed. For the MENA region, it would be relatively easy to adjust our model to take into account cultural or infrastructural differences in those countries.

The major drawback to this approach is that it requires a more robust process in order to calculate the weights that are used as model inputs. The current project administered a survey to a small group of human subjects in order to assess the relative importance of the some of the variables that smugglers consider when making routing decisions. While the weight of these inputs were objectively calculated using data from a sample of college students, the quality of this data could have been improved by using a more informed population group. This inherently raises the question as to whether the weights that are calculated from a graduate study are valid approximates to the logic used by smugglers. However, this is an issue that could be improved upon in the future with better data. 
 
A good indication that our predictions represent reasonable routing logic is that the suggested routes do not to appear to be highly sensitive to changes in input variables. As demonstrated in section 6.5, after iteratively excluding a single variable from the model, the suggested route did not change. This suggests that our model is stable and that perhaps there are not many viable routes to begin with. 

## 8. Future Work

As previously mentioned, this project serves as a foundation for future efforts combating smuggling in the MENA region. From here, there is a need to address several major concerns. First, it is necessary to scale the model to have a higher resolution. It would be beneficial for efforts of intercepting smugglers to have routing information at the country, city, and local levels. Many of these smuggling networks operate at a transcontinental scale; stealing artifacts from MENA and selling them across the globe. It is reasonable to combine results from our model at different scales to get a better idea of the least-risk path of overland smuggling. 

Additionally, the current project focused on drug smuggling within Mexico. The decision to use data from Mexico was mainly made because of resource limitations. However, the goal of this work is to address the looting of archaeological sites within the MENA region. As such, the next phase of the project aims apply these methods to the MENA region. It would be during this phase of the project that the Regional Questionnaire would be distributed to participants in the affected countries. Further, to increase applicability to the MENA region, we intend on reassessing our model inputs to better address artifact smuggling and infrastructure challenges within MENA. For example, some attributes would need to be more heavily weighted and the cartel relationships we modeled here would need to be replaced with faction dynamics present the Middle East.

With more time to develop our method it is also important for us to further validate our results. There appears to be some agreeance among our graph model and previous works. However, we intend on collecting data on the locations that smugglers have been caught with goods and collect first-hand experiences that we can test our model against. This was simply out of the scope of the current project. 

With the use of graph theory, the model should have the results analyzed to validate and verify the results. During the project, there were some sensitivity tests ran along with routes using just one attribute. Although Dijkstra's algorithm found the path with the least risk, a more detailed study of the results should be done to determine why other routes were not used by the algorithm. This will give an understanding to the verification of the routes and attributes to ensure that the initial setup was not flawed or biased.

See below for the Regional Influence Survey:

<img src="images/Reg_Infl_Survey_pg1.JPG" width="400" > <img src="images/Reg_Infl_Survey_pg2.JPG" width="400" >


## References

Alderman, K. L. (n.d.). Honor Amongst Thieves: Organized Crime and the Illicit Antiquities Trade. Indiana Law Review, 45, 27.

Barker, A. (2018a, June 5). Tracking the smugglers’ trail of priceless Islamic State loot to art markets in the West. Retrieved    September 27, 2019, from ABC News (Australian Broadcasting Corporation website: https://www.abc.net.au/news/2018-06-06/priceless- antiques-looted-by-is-smuggled-into-western-markets/9833554 

Barker, A. (2018b, June 6). A one-ton mosaic likely stolen from Syria turns up in the West. It’s the “tip of the iceberg” [Text]. Retrieved September 27, 2019, from ABC News website: https://www.abc.net.au/news/2018-06-06/priceless-antiques-looted-by-is-smuggled-into-western-markets/9833554

Barthélemy, J., & Carletti, T. (2017). An adaptive agent-based approach to traffic simulation. Transportation Research Procedia, 25, 1238–1248. https://doi.org/10.1016/j.trpro.2017.05.142

Barzoukas, G., & Institute for Security Studies (Paris, F. (2017). Drug trafficking in the MENA: The economics and the politics. Retrieved from http://dx.publications.europa.eu/10.2815/972478

Basu, G. (2013). The role of transnational smuggling operations in illicit supply chains. Journal of Transportation Security, 6(4), 315–328. https://doi.org/10.1007/s12198-013-0118-y

Basu, G. (2014). The strategic attributes of transnational smuggling: Logistics flexibility and operational stealth in the facilitation of illicit trade. Journal of Transportation Security, 7(2), 99–113. https://doi.org/10.1007/s12198-013-0132-0

Beittel, J. (n.d.). Mexico: Organized Crime and Drug Trafficking Organizations, Version 35. Congressional Research Service. 

Blannin, P. (2017). Islamic State’s Financing: Sources, Methods and Utilisation. Counter Terrorist Trends and Analyses, 9(5), 11.

Blythe Bowman Proulx. (2013). Archaeological Site Looting in “Glocal” Perspective: Nature, Scope, and Frequency. American Journal of Archaeology, 117(1), 111. https://doi.org/10.3764/aja.117.1.0111

Brodie, N., & Mackenzie, S. (2014). Trafficking Cultural Objects: Introduction. European Journal on Criminal Policy and Research, 20(4), 421–426. https://doi.org/10.1007/s10610-014-9256-4

Brodie, N., & Renfrew, C. (2005). Looting and The World’s Archaeological Heritage: The Inadequate Response. Annual Review of Anthropology, 34(1), 343–361. https://doi.org/10.1146/annurev.anthro.34.081804.120551

Broek, A. C. van den, Schoemaker, R. M., & Dekker, R. J. (2014). Land Border Permeability and Irregular Migration Using Geospatial Intelligence from Satellite Data. 2014 IEEE Joint Intelligence and Security Informatics Conference, 208–211. https://doi.org/10.1109/JISIC.2014.38

Brunsdon, C., & Singleton, A. (2015). Geocomputation: A Practical Primer. Thousand Oaks, CA: SAGE Publications. https://doi.org/10.4135/9781473916432

Campbell, P. B. (2013). The Illicit Antiquities Trade as a Transnational Criminal Network: Characterizing and Anticipating Trafficking of Cultural Heritage. International Journal of Cultural Property, 20(2), 113–153. https://doi.org/10.1017/S0940739113000015

Casana, J. (2015). Satellite imagery-based analysis of archaeological looting in Syria. Near Eastern Archaeology, 78(3), 142–152.

Casana, & Panahipour. (2014). Satellite-Based Monitoring of Looting and Damage to Archaeological Sites in Syria. Journal of Eastern Mediterranean Archaeology & Heritage Studies, 2(2), 128. https://doi.org/10.5325/jeasmedarcherstu.2.2.0128

Danese, M., Masini, N., Biscione, M., & Lasaponara, R. (2014). Predictive modeling for preventive Archaeology: Overview and case study. Open Geosciences, 6(1). https://doi.org/10.2478/s13533-012-0160-5

Felner, A. (2011). Position Paper: Dijkstra’s Algorithm versus Uniform Cost Search or a Case Against Dijkstra’s Algorithm. In The Fourth International Symposium on Combinatorial Search.

Graph Theory Types of Graphs—Javatpoint. (n.d.). Retrieved December 8, 2019, from Www.javatpoint.com website: https://www.javatpoint.com/graph-theory-types-of-graphs

Grayson, G. W. (2014). The Evolution of Los Zetas in Mexico and Central America: Sadism as an Instrument of Cartel Warfare. Strategic Studies Institute: Army War College (U.S.) https://doi.org/10.21236/ADA599872

Greenland, F. (2019). Introduction: New Insights into the Antiquities Market. International Journal of Cultural Property, 26(3), 211–225. https://doi.org/10.1017/S0940739119000237

Hall, R. (2019). Inside the hunt for Iraq’s looted treasures. Retrieved September 27, 2019, from The Independent website: https://www.independent.co.uk/news/world/middle-east/iraq-archaeology-museum-antiquities-looting-a8996676.html

Jenkins, J. L., Marquardson, J., Proudfoot, J. G., Valacich, J. S., Golob, E., & Nunamaker, J. F. (2013). The Checkpoint Simulation: A Tool for Informing Border Patrol Checkpoint Design and Resource Allocation. 2013 European Intelligence and Security Informatics Conference, 252–255. https://doi.org/10.1109/EISIC.2013.65

Jordan, C. (2016, December 17). New leads on looted Middle Eastern antiquities. Retrieved September 27, 2019, from TheHill website: https://thehill.com/blogs/congress-blog/foreign-policy/310831-new-leads-on-looted-middle-eastern-antiquities

Latek, M. M., Rizi, S. M. M., Crooks, A., & Fraser, M. (2012). Social Simulations for Border Security. 2012 European Intelligence and Security Informatics Conference, 340–345. https://doi.org/10.1109/EISIC.2012.50

Luke, C., & Kersel, M. (2005). A Retrospective and a Look Forward. Journal of Field Archaeology, 30(2), 191–200. https://doi.org/10.1179/009346905791072323

Madella, M., Rondelli, B., Lancelotti, C., Balbo, A., Zurro, D., Campillo, X. R., & Stride, S. (2014). Introduction to Simulating the Past. Journal of Archaeological Method and Theory, 21(2), 251–257. https://doi.org/10.1007/s10816-014-9209-8

Medel, M., Lu, Y., & Chow, E. (2015). Mexico’s drug networks: Modeling the smuggling routes towards the United States. Applied Geography, 60, 240–247. https://doi.org/10.1016/j.apgeog.2014.10.018

Parcak, S., Gathings, D., Childs, C., Mumford, G., & Cline, E. (2016). Satellite evidence of archaeological site looting in Egypt: 2002–2013. Antiquity, 90(349), 188–205. https://doi.org/10.15184/aqy.2016.1

Parks, S., Mcanany, P. A., & Murata, S. (2006). The Conservation of Maya Cultural Heritage: Searching for Solutions in a Troubled Region. Journal of Field Archaeology, 31(4), 425–432. https://doi.org/10.1179/009346906791071846

Rodríguez-Puente, R., & Lazo-Cortés, M. S. (2013). Algorithm for shortest path search in Geographic Information Systems by using reduced graphs. SpringerPlus, 2(1), 291. https://doi.org/10.1186/2193-1801-2-291

Rose-Greenland, F. (2014). Looters, collectors and a passion for antiquities at the margins of Italian society. Journal of Modern Italian Studies, 19(5), 570–582. https://doi.org/10.1080/1354571X.2014.962256

Samuel, S. (2018, March 19). It’s Disturbingly Easy to Buy Iraq’s Archeological Treasures. Retrieved September 27, 2019, from The Atlantic website: https://www.theatlantic.com/international/archive/2018/03/iraq-war-archeology-invasion/555200/

Sellers, W. I., Hill, R. A., & Logan, B. S. (2007). An agent-based model of group decision making in baboons. Philosophical Transactions of the Royal Society B: Biological Sciences, 362(1485), 1699–1710. https://doi.org/10.1098/rstb.2007.2064

Sørensen, M. L. S., & Viejo-Rose, D. (Eds.). (2015). War and Cultural Heritage: Biographies of Place. New York, NY: Cambridge University Press.

Dennehy, J. (2014). Stealing from history: The looting and destruction of Iraqi and Syrian heritage concern us all. Retrieved April 2, 2019, from The National website: https://www.thenational.ae/arts-culture/stealing-from-history-the-looting-and-destruction-of-iraqi-and-syrian-heritage-concern-us-all-1.308011

Sullivan, B. L. (2003). Stolen artifacts finding way into the world’s art markets. Retrieved September 27, 2019, from Baltimoresun.com website: https://www.baltimoresun.com/bal-te.fbi22apr22-story.html

Swann, S. (2019, May 2). “Loot-to-order” antiquities sold on Facebook. BBC News. Retrieved from https://www.bbc.com/news/world-middle-east-47628369

Wang, X. Z. (2018). The Comparison of Three Algorithms in Shortest Path Issue. Journal of Physics: Conference Series, 1087, 022011. https://doi.org/10.1088/1742-6596/1087/2/022011

Xue, G., Li, Z., Zhu, H., & Liu, Y. (2009). Traffic-Known Urban Vehicular Route Prediction Based on Partial Mobility Patterns. 2009 15th International Conference on Parallel and Distributed Systems, 369–375. https://doi.org/10.1109/ICPADS.2009.129
