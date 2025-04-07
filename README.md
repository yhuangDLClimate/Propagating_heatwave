# Project Name: Part of the Methods Code from Article Evidence for preferred propagating terrestrial heatwave pathways due to Rossby wave activity

This document contains part of the methods code and their descriptions for demonstration and reference purposes.

## File Descriptions

### 1. `SAT_ES.m`
Calculates the Event Synchronization field for the Northern Hemisphere (20N-70N) based on SAT daily anomalies from 1959-2023. The calculation takes a long time and is for demonstration purposes only.

### 2. `network_divergence_compute.m`
Computes the network divergence of the ES network and plots the network divergence map (Northern Hemisphere), corresponding to **Figure 1** in the main text.

### 3. `find_path.m`
Uses the Local Searching algorithm to find the propagation path (using Asia as an example). The starting point of the path and the distance range between neighboring path points need to be determined. This corresponds to **Figure 1** in the main text.

### 4. `z500a_cluster.m`
Determines the 10-day movement trajectories of z500a following the onset of heatwaves at four initial pathway nodes using the Trajectory Tracking Algorithm and performs k-means clustering. Corresponds to **Figure 2** in the main text.

### 5. `SAT_spatiotemporal_evolutions.m`
Calculates the spatiotemporal evolutions of propagating and standing heatwaves. Corresponds to **Figure 3** in the main text.

### 6. `TNflux_compute.m`
Computes the horizontal TN-flux. Corresponds to **Figure 4** in the main text.

### 7. `RHO_compute.m`
Computes RHO, which represents the probability of heatwave occurrence at subsequent path nodes within the 7 days following a heatwave at the starting node. Corresponds to **Figure 5** in the main text.

### 8. `Rosediagram.m`
Calculates and plots the rose diagram (Asia), corresponding to Figure S7 in the supplementary materials.