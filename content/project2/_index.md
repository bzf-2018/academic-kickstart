---


---

<center> <h1>Research - Civil Computing</h1> </center>

My research interest is mainly on database management and data mining with a recent focus on massive Geo-Spatial data. I propose the topic of [**Civil Computing**](http://civilcomputing.co/) and has made significant contributions in developing interactive visualized data exploration frameworks to bring big data back to a human scale, to **make big data empower everyone for optimal decision making** and **facilitate people's everyday life**. These civil computing problems of my focus involve three domains: (1) [Site Selection](http://civilcomputing.co/sub-facility.html), (2) [House Seeking](http://civilcomputing.co/sub-houseseeking.html) (Point of Interest and Area of Interest), and (3) [Intelligent Transport](http://civilcomputing.co/sub-transport.html). 

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
	- Ehance Passengers' Satisfaction via Optimizing the Network-wide Public Transport Time Schedule (DASFAA'20 and more on the way)
	- Dynamic Ridesharing in **Peak Travel Periods** to Boost User Satisfaction (TKDE'20)
	
- From the perspective of individual user, we exploit user movement data to: 
	- Estimate the Origin-Destination Travel Time for a trip (SIGMOD'20)
	- Build an All-purpose POI and Trajectory Search Engine for Personalized Trip Planning (ICDE'17, SIGIR'18, WSDM'18)
	- Clean and Integrate Massive Trajectory Data (SIGMOD'18)


To solve the above civil problems, I am the first of few developing **end-to-end** solutions that cross three disciplinaries: Data Management, Information Retrieval and Data Visualization. My inter-disciplinary methodology involves:

- design effective data usability modules in the front end.
- propose efficient evaluation algorithm in the mid end.
- provide efficient storage and indexing schemes in the back end.

Each end has mutual impact to the others in solution design, while it is usually assumed to be orthogonal to each other in single-discipline research. His proposed cross-disciplinary methodology is creative and highly endorsed by international peers, as evidenced by his publication in top venues of Information Retrieval such as WSDM, SIGIR, top venues of data management such as SIGMOD, ICDE, KDD, TKDE, VLDB Journal, and top venues of Data Visualization such as EUROVIS, JVLC.

<center> <h2>Ongoing Projects</h2> </center>

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

**Research Problem 3.2 - Viral Marketing over Evolving Social Networks. (ICDE 2019, and more)**  

This project focus on efficently and effectively finding the seed set users for spreading the advertising information in viral marketing. Due to various requirements, the seed set selection can be formulated as different problems such as Influence Maximization, Seed Set Minimization, Regret Minimization and Revenue Maximization. This project aims to propose novel solutions and business models for different versions of this problem with better practicalty, efficiency and effectiveness.

**Research Problem 3.3 - Mining High-Order Graph Information Mining.**  

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


<center><h3>Past Projects</h3></center> 
**Past Project 1 - Social Networks (Search, Summarization and Management)**

Vision: have a general database to manage, search and analyze over the social network data.

- Database Design and Implementation: data modeling; query optimization; concurrency control.

- In-database Search: Personalized + RealTime Search search in your own "circles" and gets the latest results just published 1 second ago); In-database Social Network Analysis (SNA); link prediction.
  
This challenge requires a model for social network data, and graphs are the obvious candidate, but: sonSchema -- a social network is not a graph [10].

A graph is a static, syntactic model that does not capture the dynamics and semantics of a social network; this is evident from: sonLP -- social network link prediction by principal component regression [11].

We have designed a general search engine framework that is able to provide Personalized + Realtime Search in social networks [13].

Our ambition is to build a sonSchema-based open-source system that replaces MySQL as the default database management system for social network data: sonSQL -- an extensible relational DBMS for social network start-ups [12].

**Past Project 2 - Keyword search over spatial & textual data**

- a general support for various types of fuzzy type-ahead spatial keyword query

- one-size-fits-all index design for various types and degrees of relaxation

- maximization of query result reuse at different granularities

To make more data truly usable, keyword search is one important aspect I make continuous efforts, and my ultimate goal is to have a one-size-fits-all general framework to provide usability support for all these heterogeneous data. We are now developing various types of data exploration queries based on our previous experiences in keyword search, and we believe that **“The first step in leveraging big data is search and data exploration. Machine learning or other downstream advanced analytics will be effective only if search and data exploration get us the relevant data effectively and efficiently”** , quoted from Dr. Surajit Chaudhuri's keynote speech at ICDE 2015. 

Geo-textual data are generated in abundance. Recent study focused on the processing of spatial keyword queries which retrieve objects that match certain keywords within a spatial region. To ensure effective retrieval, various extensions were done including the allowance of errors in keyword matching and auto-completion using prefix matching. Our goal is to devise a unifying strategy for processing different variants of spatial keyword query. We adopt the auto-completion paradigm that generates the initial query as a prefix matching query. If there are few matching results, other variants are performed as a form of relaxation that reuses the processing done in the earlier phase. The types of relaxation include spatial region expansion and exact/approximate prefix/substring matching. Moreover, since the auto-completion paradigm allows appending characters after the initial query, we look at how query processing done for the initial query and relaxation can be reused in such instances. Compared to existing works which process variants of spatial keyword query as new queries over different indexes, we offer a more compelling way to efficient and effective spatial keyword search. Extensive experiments substantiate our claims.

**Past Project 3 - Data Quality (Integration & Tracking)**

- provenance data: storage, management and usability tracking

[9] studied the data quality problem, which is very important to extract, track unexpected result during studying the heterogeneous or uncertain data. Provenance information is vital in many application areas as it helps explain data lineage and derivation. Understanding the provenance of data has become exceedingly important due to the large number of sources, diversity of formats and sheer volume of data that current business and scientific applications have to deal with. For example, in scientific computing area, as in many other areas, provenance is vital to establish trust or correctness of results; in database environments it can help update views, explain unexpected results, and assist with data integration; in databases with uncertainty, it can be used to track correlation between probabilistic variables.

My research goal in this direction is to develop provenance data management frameworks that can be combined as part of the database management system. In particular, my concern is on: (1) the expressiveness of the provenance semantics designed, to interpret not only from which source data the result comes from, but also how the results come from the source data; (2) design novel data structures that minimize the storage cost of provenance data; (3) provide an efficient support on evaluating the provenance tracking query.

As a start, [9] focuses on designing a framework for storing fine-grained provenance data relating to data derived via database queries. While storage space is of little concern when dealing with high-level provenance, the requirements of storing fine-grained provenance data can be significant, with the size of provenance data often exceeding the size of the actual data. One way to deal with this is to compute provenance data only when requested, rather than storing it, but a drawback is that without good inverse functions this can be expensive, and it may require intermediate query results to be stored. Therefore, we first propose a provenance tree data structure which matches the query structure and thereby presents a possibility to avoid redundant storage of information regarding the derivation process. Then I investigate two approaches for reducing storage costs. The first provides a means of optimizing the selection of query tree nodes where provenance information should be stored. The second exploits logical query-rewriting, in particular join-reordering, which can be done after the query has already been computed, and thus does not impede the efficiency of query execution. The optimization algorithms run in polynomial time in the query size and linear in the size of the provenance information, thus enabling provenance tracking and optimization without incurring large overheads. Moreover, I built a relational query engine from scratch, supporting ASPJ operations required for executing SQL-style queries as well as provenance data construction during query execution.

**References**

[1] Z.F. Bao, T.W. Ling, B. Chen and J.H. Lu. Effective XML Keyword Search With Relevance Oriented Ranking. ICDE 2009, full paper. (Best Papers Award)

[2] Y. Zeng, Z.F. Bao, H.V. Jagadish, G.L. Li and T.W. Ling. Breaking out the Mismatch Trap. ICDE 2014, full paper.

[3] Z.F. Bao, J.H. Lu , T.W. Ling, and B. Chen. Towards an Effective XML Keyword Search. TKDE 2010.

[4] J.F. Zhou, Z.F. Bao, Z.Y. Chen and T.W. Ling. Fast Result Enumeration for Keyword Queries on XML Data. DASFAA 2012, full paper. (One of the Five Best Papers)

[5] J.F. Zhou, Z.F. Bao,W. Wang, J.J. Zhao and X.F. Meng. Efficient Query Processing for XML Keyword Queries based on the IDList Index. VLDB Journal, accepted in 2013.

[6] J.F. Zhou, Z.F. Bao, W. Wang, T.W. Ling, Z.Y. Chen, X.D. Lin and J.F. Guo. Fast SLCA and ELCA Computation for XML Keyword Queries based on Set Intersection. ICDE 2012, full paper.

[7] J.H. Lu, T.W. Ling, Z.F. Bao and C. Wang. Extended Tree Pattern Matching: Theories and Algorithms. TKDE 2010, regular paper.

[8] L. Xu, T.W. Ling, H.Y. Wu and Z.F. Bao. DDE: From Dewey to a Fully Dynamic XML Labeling. SIGMOD 2009, full paper.

[9] Z.F. Bao, H. Koehler, X.F. Zhou and S. Sadiq. Efficient Provenance Storage For Relational Queries. CIKM 2012, full paper.

[10] Z.F. Bao, Y.C. Tay and J.B. Zhou. sonSchema: A Conceptual Schema for Social Networks. ER 2013: 197-211

[11] Z.F. Bao, Y. Zeng and Y.C. Tay. sonLP: social network link prediction by principal component regression. ASONAM 2013: 364-371

[12] Z.F. Bao, J.B. Zhou and Y.C. Tay. sonSQL: An Extensible Relational DBMS for Social Network Start-Ups. ER 2013: 495-498

[13] Y.C. Li, Z.F. Bao, G.L. Li and K.L. Tan. Real Time Personalized Search over Social Networks. ICDE 2015: 639-650.

[14]  S. Wang, Z. Bao, S. Huang, R. Zhang. A Unified Processing Paradigm for Interactive Location-based Web Search. WSDM 2018.            

[15] M. Li, Z. Bao, F. Choudhury, T. Sellis. Supporting Large-scale Geographical Visualization in a Multi-granularity Way. WSDM 2018. 

[16] Z. Shang, G. Li, Z. Bao. DITA: Distributed In-Memory Trajectory Analytics. SIGMOD 2018.                                        

[17] T. Guo, K. Feng, G. Cong, Z. Bao. Efficient Selection of Geospatial Data on Maps for Interactive and Visualized Exploration.  SIGMOD  2018.   

[18] S. Wang, Z. Bao, J. Culpepper, T. Sellis, M. Sanderson, X. Qin. Answering Top-k Exemplar Trajectory Queries. ICDE 2017.

[19] S. Wang, Z. Bao, J. Culpepper, Z. Xie, Q. Liu, X. Qin. Torch: A Search Engine for Trajectory Data. SIGIR 2018.

**Recent System Prototypes**

[HomeSeeker](https://www.youtube.com/watch?v=uhp_a7_1mpY&feature=youtu.be): Visualization of the Real Estate Data ([version 0.1](http://www.google.com/url?q=http%3A%2F%2F115.146.89.158%2F&sa=D&sntz=1&usg=AFQjCNFZbSOiPj1A_-0MGWFLxbSoZkgwrA)).

[TORCH](http://47.75.79.142:8080/TTorchServer/): A Search Engine for Trajectory Data on Road Networks.

[TISP](http://43.240.96.219:8080/TripPlanning/index.html): Trip Planning by an Integrated Search Paradigm.