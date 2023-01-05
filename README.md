# DEMOS：clustering by pruning a density-boosting cluster tree of density mounts---DEnsity MOuntains Separation clustering algorithm

which is published in IEEE Transactions on Transactions on Knowledge and Data Engineering（TKDE）, 2023. Doi: ???


Most existing clustering algorithms require a preset cluster number and often fail to capture complex shapes. Herein, we propose a clustering algorithm by pruning a density-boosting cluster tree of density mounts—DEnsity MOuntains Separation clustering algorithm (DEMOS). We assume that a cluster is a density-connected area with multiple (or a single) density mounts (i.e., single-peak clusters) and a relatively large dis-connectivity from density-connected areas of higher densities. Based on the assumption, DEMOS can easily detect the number of clusters and robustly reconstruct their complex shapes. It first builds the dataset into a peak graph, where each density peak represents a density mount. A multi-valley-link-based connectivity estimation method is embedded to efficiently estimate the connectivity between density peaks during peak graph building. Then, by applying a new linkage metric designed based on our assumption, DEMOS builds density mounts into a reasonably density-boosting cluster tree. After obtaining a robust center detection in a clarity-enhancing decision graph, DEMOS prunes the cluster tree into final clusters to finish clustering. DEMOS is also suitable for large-scale data clustering. Experimental results on both synthetic and real datasets demonstrated the effectiveness of DEMOS.
