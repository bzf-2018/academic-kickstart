---


---

<center> <h1>Research - Civil Computing</h1> </center>

Dr Bao’s research interest is mainly on database management with a recent focus on big geo-spatial data. I propose the topic of **Civil Computing** and has made significant contributions in developing interactive visualized data exploration frameworks to bring big data back to a human scale, to **make big data empower everyone for optimal decision making**. These civil computing problems include:

- The budget-constrained facility deployment that benefits the optimal deployment of gas stations, electric charging stations and advertisement.

- The trajectory data exploration that benefits public transportation network optimization and traffic flow prediction.

- The one-size-fits-all point of interest (poi) and trajectory search engine that benefits personalized trip planning.

- The location-centred interactive visualized analytics that benefits real estate house seeking.

To solve the above civil problems, Dr Bao is the first of few developing **end-to-end** solutions that cross three disciplinaries: Data Management, Information Retrieval and Data Visualization. His inter-disciplinary methodology involves:

- design effective data usability modules in the front end.

- propose efficient evaluation algorithm in the mid end.

- provide efficient storage and indexing schemes in the back end.

Each end has mutual impact to the others in solution design, while it is usually assumed to be orthogonal to each other in single-discipline research. His proposed cross-disciplinary methodology is creative and highly endorsed by international peers, as evidenced by his publication in top venues of Information Retrieval such as WSDM, SIGIR, top venues of data management such as SIGMOD, ICDE, KDD, TKDE, VLDB Journal, and top venues of Data Visualization such as EUROVIS, JVLC.

<center> <h2>Ongoing Projects</h2> </center>

<center><h3>Research Project 1: Influential Facility Site Selection</h3> </center>

**Research Problem 1.1 - Trajectory-driven Influential Billboard Placement**: Given a set of billboards U (each with a location and a cost), a database of trajectories T and a budget L, find a set of billboards within the budget to influence the largest number of trajectories. One core challenge is to identify and reduce the overlap of the influence from different billboards to the same trajectories, while keeping the budget constraint into consideration. 

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/3eS1ac4KaHU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>


<center><h3>Research Project 2: Information Visulization and Data Analytics</h3> </center>

**Research Problem 2.1 - HomeSeeker - An Interactive & Visualized Personalized Exploration of the Real Estate Data**. ([Demo](http://115.146.89.158/))

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/aIO9Y-ebLBo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

**Research Problem 2.2 - Geo-located Multi-dimensional & Multi-granularity Data Visualization**: (1) Aggregation of results at different levels of detail for efficient visualization rendering (Data Sampling techniques, Approximate clustering); (2) Visualization Design of the Geo-located Multi-dimensional Data.

**Research Problem 2.3 - Spatial Keyword (Range) Search for Facility Seeking**: (1) Find house candidates which can reach all the facilities before further inspection/exploration - coles supermarkets (for food), good clinics or pathology center (for health), top-50 public schools (for education), train stations (for transportation), Bunnings (for house renovation), etc; (2) Find the smallest region that can cover all my expected facilities in this surburb.

**Research Problem 2.4 - Location-centered Data Integration & Cleaning**: Collect information centered around a property from different channels (besides the information of a real estate property itself), including but not limited to: (1) Regional Profile (age, sex, income, safety, density, etc.); (2) Transportational Profile (real time home-to-office travel time); (3)Education Profile (school zones, school rankings).

**Research Problem 2.5 - Selection of Objects For Visualization & Interactive User Exploration over the Map**: How to select the most representative k-size objects while they are not close to each other (which can maintain the visibility of all selected objects) at all levels of granularities when users want to see them in the map? How to maintain a seamless user experiences (i.e. keep selecting the up-to-date k-size objects) when users interact with the map by zooming and moving to keep changing their region of interest? Can we allow users to choose their own preferred similarity metrics and our approach is independent of that?

**Research Problem 2.6 - How to exploit the visualization techniques to strike a balance between structured query and ranked retrieval**: Structured query like SQL may give few or no results, while there is no one-size-fits-all ranking model to meet every individual buyer's requirement, not to mention the buyer's requirement may change w.r.t. the search result. What shall we do? Customer A wants to buy a house with a swimming pool under the budget of 1M; however, there is no such house, but there are few houses asking for 1.01M with swimming pools. We provide a visualized comparison for those "borderline" houses, for users to quickly identify which attributes of her interest do not meet her requirement. 

<center><h3>Research Project 3: Trajectory Data Exploration for Trip Planning</h3></center> 

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/5vB22ZR8kvk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center> 

**Research Problem 3.1 - Answering the Exemplar Trajectory Query (ICDE 2017) [17].**

**Research Problem 3.2 - A Unified Processing Paradigm for Interactive Location-based Web Search (WSDM 2018) [14].**

**Research Problem 3.3 - Distributed In-memory Trajectory Analytics (SIGMOD 2018) [16].**

**Research Problem 3.4 - A Search Engine for Trajectory Data on Road Networks (SIGIR 2018) [19].**

TISP is a Trip planning system by an Integrated Search Paradigm. TISP helps users (even those without any prior knowledge of the target city) interactively discover a city and incrementally plan a unique trip. Planning a trip usually involves a series of search processes, where users may issue several queries of the same type (with different settings), or even different types of queries, until the desired points of interest (POIs) and trajectories are found. In particular, for POI search, it involves the keyword query, k-Nearest Neighbor (kNN) query, Top-k Spatial Keyword (TkSK) query, Aggregate Nearest Neighbour (ANN) query, and Aggregate Textual Nearest Neighbour (ATNN) query. For trajectory search, it involves the k-Best-Connected-Trajectory (kBCT) query and Top-k Spatial-Textual Trajectory (TkSTT) query. 

At Data Management end, we  propose a general Top-k query called **Monotone Aggregate Spatial Keyword query** - MASK, which is able to cover all the above queries. Then we proposed a unified index and query processing paradigm to answer various types of location-based search queries on both spatial point data and spatial trajectory data. 

At Visualization end, we design an interactive visualized procedure to help users explore various data objects and plan their trips. On one hand, we propose a series of novel visual encoding designs to visualize the result of different types of queries. E.g., we design an enhanced transfer graph with careful retinal channel mapping of vertices and edges to visualize popular attractions and attraction pairs. On the other hand, we design user-friendly interactions upon multiple visualization views, which heuristically guide users to interact with the current visualization results, construct further **queries without inputting any text**, and gradually complete their planned trip.

Recently, We design a search engine called Torch for trajectory data and serve almost all metric and non-metric trajectory similarity computations. In particular, we first map the trajectories into the road network, then a trajectory can be represented by a set of road segment ids. Moreover, a road segment is also crossed by many trajectories. Hence, we can use the inverted index to organize all the trajectories crossing a same road. Compression techniques over trajectories and inverted lists will further reduce the space of dataset and index.

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