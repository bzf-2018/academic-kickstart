---
title: "Effective Travel Time Estimation: When Historical Trajectories over Road Networks Matter"
authors:
- Haitao Yuan
- Guoliang Li
- admin
- Ling Feng

publication_types: ["1"]
publication: In *the 2020 International Conference on Management of Data (SIGMOD)*
publication_short: In *SIGMOD*
publishDate: "2020-06-20"

abstract: In this paper, we study the problem of origin-destination (OD) travel time estimation where the OD input consists of an OD pair and a departure time. We propose a novel neural net- work based prediction model that fully exploits an important fact neglected by the literature – for a past OD trip its travel time is usually affiliated with the trajectory it travels along, whereas it does not exist during prediction. At the training phase, our goal is to design novel representations for the OD input and its affiliated trajectory, such that they are close to each other in the latent space. First, we match the OD pairs and their affiliated (historical) trajectories to road networks, and utilize road segment embeddings to represent their spa- tial properties. Later, we match the timestamps associated with trajectories to time slots and utilize time slot embed- dings to represent the temporal properties. Next, we build a temporal graph to capture the weekly and daily periodicity of time slot embeddings. Last, we design an effective encoding to represent the spatial and temporal properties of trajecto- ries. To bind each OD input to its affiliated trajectory, we also encode the OD input into a hidden representation, and make the hidden representation close to the spatio-temporal representation of the trajectory. At the prediction phase, we only use the OD input, get the hidden representation of the OD input, and use it to generate the travel time. Extensive experiments on real datasets show that our method achieves high effectiveness and outperforms existing methods.



#tags:
#- Source Themes
featured: true

links:
url_pdf: 'papers/sigmod20-deepod.pdf'


---