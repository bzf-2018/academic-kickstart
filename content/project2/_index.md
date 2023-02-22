---


---

<center> <h1>Completed Projects</h1> </center>

I proposed the topic of [**Civil Computing**](http://civilcomputing.co/) and has made significant contributions in developing interactive visualized data exploration frameworks to bring big data back to a human scale, to **make big data empower everyone for optimal decision making** and **facilitate people's everyday life**. These civil computing problems of my focus involve three domains: (1) [Site Selection](http://civilcomputing.co/sub-facility.html), (2) [House Seeking](http://civilcomputing.co/sub-houseseeking.html) (Point of Interest and Area of Interest), and (3) [Intelligent Transport](http://civilcomputing.co/sub-transport.html). 

* **House Seeking**
	- Map-based Visual exploration on location-centred multi-dimensional data (WSDM'19, EuroVIS'18, JVLC'18)
	- Map-based Spatial Object Recommendation with Explainability (SIGIR'20)
	- Representative Spatial Object Selection (SIGMOD'18)
	- Realtime Popular House (POI) and Area (AOI) Monitoring (ICDE'17)


User movement data generally behave in three forms: (i) Commuter Trajectory, (ii) Vehicle Trajectory, (iii) User Activity Trajectory. 
We utilize them in a comprehensive manner in the following projects.

* **Site Selection / Facility Deployment** 

	- Towards an Optimal City-wide Deployment of Advertisement (for Influcence Maximization) and Deployment of Gas stations, electric charging stations and any Facilities (for Doverage Maximization). 
	- Orthogonal to different choices of Coverage Measurement and Influence Measurement. 
		- When the Influence Overlaps Matter (KDD'18, TKDD'20)
		- When the Impression Counts Matter (KDD'19)
	- Optimal Site Selection for Retailer Store (VLDB'18)


* **Intelligent Transport**
- From the perspective of transport service provider, we exploit user movement data to: 

	- Monitor Network-wide Traffic via Vehicle Trajectory Clustering (PVLDB'20)
	- Bring People back to Public Transport via Reoptimizing the Bus Route Network (TKDE'19)
	- Ehance Passengers' Satisfaction via Optimizing the Network-wide Public Transport Time Schedule (TKDE'21)
	- Dynamic Ridesharing in **Peak Travel Periods** to Boost User Satisfaction (TKDE'20)
	
- From the perspective of individual user, we exploit user movement data to: 
	- Estimate the Origin-Destination Travel Time for a trip (SIGMOD'20)
	- Build an All-purpose POI and Trajectory Search Engine for Personalized Trip Planning (ICDE'17, SIGIR'18, WSDM'18)
	- Clean and Integrate Massive Trajectory Data (SIGMOD'18)


To solve the above civil problems, my team is the first of few developing **end-to-end** solutions that cross three disciplinaries: Data Management, Information Retrieval and Data Visualization. My inter-disciplinary methodology involves:

- design effective data usability modules in the front end.
- propose efficient evaluation algorithm in the mid end.
- provide efficient storage and indexing schemes in the back end.

Each end has mutual impact to the others in solution design, while it is usually assumed to be orthogonal to each other in single-discipline research. my team tried to propose cross-disciplinary methodology across the fields of data management, information retrieval, and visualization.

<center> <h2>A Breakdown of Completed Projects</h2> </center>

<center><h3>Research Project 1: Influential Facility Site Selection</h3> </center>

**Research Problem 1.1 - Trajectory-driven Influential Billboard Placement**: Given a set of billboards U (each with a location and a cost), a set T of user-movement records and a budget L, it aims to find a set of billboards within the budget to influence the largest number of trajectories. One core challenge is to identify and reduce the overlap of the influence from different billboards to the same trajectories, while keeping the budget constraint into consideration. 

<center><iframe width="480" height="320" src="https://www.youtube.com/embed/3eS1ac4KaHU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="480" height="320" src="https://www.youtube.com/embed/tE3dEbgHDUY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>


**Research Problem 1.2 - When Impression Counts Meet Influential Billboard Placement**: Given a set of billboards U (each with a location and a cost), a set T of user-movement records, an impression count threshold to trigger the influence of an individual user, a budget L, find a set of billboards within the budget to influence the largest number of trajectories. One core challenge is that different users can have different thresholds to be impressed by the same advertisement.




<center><h3>Research Project 2: Visualizaton, Retrieval and Analytics of Location-Centered Data </h3> </center>

**Research Problem 2.1 - HomeSeeker - An Interactive & Visualized Personalized Exploration of the Real Estate Data**. ([Demo1](http://47.75.79.142:8083/estatevis)) ([Demo2](http://47.75.79.142:8083/estatevis/ConcaveCubes/))

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/aIO9Y-ebLBo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

**Research Problem 2.2 - Geo-located Multi-dimensional & Multi-granularity Data Visualization**: (1) Aggregation of results at different levels of detail for efficient visualization rendering (Data Sampling techniques, Approximate clustering); (2) Visualization Design of the Geo-located Multi-dimensional Data.

**Research Problem 2.3 - Spatial Keyword (Range) Search for Facility Seeking**: (1) Find house candidates which can reach all the facilities before further inspection/exploration - coles supermarkets (for food), good clinics or pathology center (for health), top-50 public schools (for education), train stations (for transportation), Bunnings (for house renovation), etc; (2) Find the smallest region that can cover all my expected facilities in this surburb.

**Research Problem 2.4 - Location-centered Data Integration & Cleaning**: Collect information centered around a property from different channels (besides the information of a real estate property itself), including but not limited to: (1) Regional Profile (age, sex, income, safety, density, etc.); (2) Transportational Profile (real time home-to-office travel time); (3)Education Profile (school zones, school rankings).

**Research Problem 2.5 - Selection of Objects For Visualization & Interactive User Exploration over the Map**: How to select the most representative k-size objects while they are not close to each other (which can maintain the visibility of all selected objects) at all levels of granularities when users want to see them in the map? How to maintain a seamless user experiences (i.e. keep selecting the up-to-date k-size objects) when users interact with the map by zooming and moving to keep changing their region of interest? Can we allow users to choose their own preferred similarity metrics and our approach is independent of that?

**Research Problem 2.6 - Spatial object recommendation with Explainability: When spatial granularity matters**: What does a user expect when using a personalized map service for spatial object recommendation? We observe that the following questions may matter to cater for users’ intention: (1) what does the system recommend for users at different stages of data exploration when they zoom in or zoom out the map application? (2) why does the system recommend a particular spatial object to the users? In this project, we focus on the POI recommender system in a multi-level manner by involving spatial granularity information. To this end, we expect that users can be recommended effective POIs when they have personal requirements on spatial granularity, or even they do not provide any specific intentions on where to go. Our model can completely explore the intrinsic spatial containment relationship between a POI point and a suburb then provide recommendations for varying spatial granularity. Moreover, users will be acknowledged about additional hints on why such a recommendation is generated.


**Research Problem 2.7 - How to exploit the visualization techniques to strike a balance between structured query and ranked retrieval**: Structured query like SQL may give few or no results, while there is no one-size-fits-all ranking model to meet every individual buyer's requirement, not to mention the buyer's requirement may change w.r.t. the search result. What shall we do? Customer A wants to buy a house with a swimming pool under the budget of 1M; however, there is no such house, but there are few houses asking for 1.01M with swimming pools. We provide a visualized comparison for those "borderline" houses, for users to quickly identify which attributes of her interest do not meet her requirement. 


<center><h3>Research Project 3: Graph Data Analytics </h3></center> 

**Research Problem 3.1 - Representation Learning for Evolving Graph Data. (ICDE 2020)** 

Graph representation learning has been a very promising and popular research topic and it can outperform traditional methods under various applications. Despite significant progress, this topic is still quite open and many directions are worth exploring. In this project, we mainly focus on temporal information capture and graph similarity computation with machine learning, and explainability and interpretability of graph representation learning.

**Research Problem 3.2 - Viral Marketing over Evolving Social Networks. (ICDE 2019, VLDB 2023)**  

This project focuses on efficently and effectively finding the seed set users for spreading the advertising information in viral marketing. Due to various requirements, the seed set selection can be formulated as different problems such as Influence Maximization, Seed Set Minimization, Regret Minimization and Revenue Maximization. This project aims to propose novel solutions and business models for different versions of this problem with better practicalty, efficiency and effectiveness.

**Research Problem 3.3 - Mining High-Order Graph Information Mining. (ICDE 2021)**  

High-order graph information has been shown to be very useful for important tasks such as community detection and graph clutering. In this project, I mainly focus on revolving two bottlenecks of this topic: how to efficiently extract the high-order information, and determine what kinds of high-order information we should extract based on the specific context.



<center><h3>Research Project 4: Trajectory Data Exploration for Trip Planning</h3></center> 

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/5vB22ZR8kvk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center> 

**Research Problem 4.1 - Answering the Exemplar Trajectory Query (ICDE 2017).**

**Research Problem 4.2 - A Unified Processing Paradigm for Interactive Location-based Web Search (WSDM 2018).**

**Research Problem 4.3 - Distributed In-memory Trajectory Analytics (SIGMOD 2018).**

**Research Problem 4.4 - A Search Engine for Trajectory Data on Road Networks (SIGIR 2018).**

**Research Problem 4.5 - Effective Travel Time Estimation: When Historical Trajectories over Road Networks Matter (SIGMOD 2020).**

TISP is a Trip planning system by an Integrated Search Paradigm. TISP helps users (even those without any prior knowledge of the target city) interactively discover a city and incrementally plan a unique trip. Planning a trip usually involves a series of search processes, where users may issue several queries of the same type (with different settings), or even different types of queries, until the desired points of interest (POIs) and trajectories are found. In particular, for POI search, it involves the keyword query, k-Nearest Neighbor (kNN) query, Top-k Spatial Keyword (TkSK) query, Aggregate Nearest Neighbour (ANN) query, and Aggregate Textual Nearest Neighbour (ATNN) query. For trajectory search, it involves the k-Best-Connected-Trajectory (kBCT) query and Top-k Spatial-Textual Trajectory (TkSTT) query. 

At Data Management end, we propose a general Top-k query called **Monotone Aggregate Spatial Keyword query** - MASK, which is able to cover all the above queries. Then we proposed a unified index and query processing paradigm to answer various types of location-based search queries on both spatial point data and spatial trajectory data. 

At Visualization end, we design an interactive visualized procedure to help users explore various data objects and plan their trips. On one hand, we propose a series of novel visual encoding designs to visualize the result of different types of queries. E.g., we design an enhanced transfer graph with careful retinal channel mapping of vertices and edges to visualize popular attractions and attraction pairs. On the other hand, we design user-friendly interactions upon multiple visualization views, which heuristically guide users to interact with the current visualization results, construct further **queries without inputting any text**, and gradually complete their planned trip.

We design a search engine, Torch, for trajectory data and serve almost all metric and non-metric trajectory similarity computations. In particular, we first map the trajectories into the road network, then a trajectory can be represented by a set of road segment ids. Moreover, a road segment is also crossed by many trajectories. Hence, we can use the inverted index to organize all the trajectories crossing a same road. Compression techniques over trajectories and inverted lists will further reduce the space of dataset and index.


<center><h3>Research Project 5: Dynamic Ridesharing in Peak Travel Periods: One Stone, Two Birds </h3></center> 

Ridesharing service is an innovative transportation strategy in trip planning. Riders with similar itineraries and time schedules are encouraged to share their trips in order to save money, reduce traffic congestion and increase car seat utilization. However, the performance of ridesharing service under the peak hour scenario, where the number of riders is way larger than the number of vehicles, is critical in reality. Given a set of drivers and rider requests, this project tries to match drivers to each rider request by achieving two objectives: (i) **maximizing the served rate** and (ii) **minimizing the total additional travel distance**, subject to a series of spatio-temporal constraints dynamically. Interestingly, our problem can be distinguished from existing work in three aspects: (1) Previous work did not fully explore the impact of peak travel periods where the number of rider requests is much greater than the number of available drivers. (2) Existing solutions usually rely on single objective optimization techniques, such as minimizing the total travel cost. (3) When evaluating the overall system performance, the runtime spent on updating drivers' trip schedules as per incoming rider requests should be incorporated, while it is excluded by most existing solutions.