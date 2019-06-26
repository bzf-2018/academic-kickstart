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

<center><h3>Research Project 4: Trajectory Data Exploration for Trip Planning</h3></center> 

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/5vB22ZR8kvk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center> 

**Research Problem 3.1 - Answering the Exemplar Trajectory Query (ICDE 2017) [17].**

**Research Problem 3.2 - A Unified Processing Paradigm for Interactive Location-based Web Search (WSDM 2018) [14].**

**Research Problem 3.3 - Distributed In-memory Trajectory Analytics (SIGMOD 2018) [16].**

**Research Problem 3.4 - A Search Engine for Trajectory Data on Road Networks (SIGIR 2018) [19].**

TISP is a Trip planning system by an Integrated Search Paradigm. TISP helps users (even those without any prior knowledge of the target city) interactively discover a city and incrementally plan a unique trip. Planning a trip usually involves a series of search processes, where users may issue several queries of the same type (with different settings), or even different types of queries, until the desired points of interest (POIs) and trajectories are found. In particular, for POI search, it involves the keyword query, k-Nearest Neighbor (kNN) query, Top-k Spatial Keyword (TkSK) query, Aggregate Nearest Neighbour (ANN) query, and Aggregate Textual Nearest Neighbour (ATNN) query. For trajectory search, it involves the k-Best-Connected-Trajectory (kBCT) query and Top-k Spatial-Textual Trajectory (TkSTT) query. 

At Data Management end, we  propose a general Top-k query called **Monotone Aggregate Spatial Keyword query** - MASK, which is able to cover all the above queries. Then we proposed a unified index and query processing paradigm to answer various types of location-based search queries on both spatial point data and spatial trajectory data. 

At Visualization end, we design an interactive visualized procedure to help users explore various data objects and plan their trips. On one hand, we propose a series of novel visual encoding designs to visualize the result of different types of queries. E.g., we design an enhanced transfer graph with careful retinal channel mapping of vertices and edges to visualize popular attractions and attraction pairs. On the other hand, we design user-friendly interactions upon multiple visualization views, which heuristically guide users to interact with the current visualization results, construct further **queries without inputting any text**, and gradually complete their planned trip.

Recently, We design a search engine called Torch for trajectory data and serve almost all metric and non-metric trajectory similarity computations. In particular, we first map the trajectories into the road network, then a trajectory can be represented by a set of road segment ids. Moreover, a road segment is also crossed by many trajectories. Hence, we can use the inverted index to organize all the trajectories crossing a same road. Compression techniques over trajectories and inverted lists will further reduce the space of dataset and index.