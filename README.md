# Opera-tau-neutrino-electronic-detector

Overview:

The OPERA experiment was designed to discover ντ appearance in a νμ beam, a direct consequence of neutrino oscillations. Its primary objective was to detect the τ lepton produced in charged current (CC) ντ interactions and observe its decay under very low background conditions.
This dataset provides electronic detector hits for 10 tau neutrino candidate events.
•	Emulsion film information is not included here.
•	Electronic detector data alone is insufficient to fully classify decay products or reconstruct decay paths.
•	Some signatures (e.g., muon bending) are visible and allow partial interpretation.

Physics Context:

In ντ interactions with nucleons in the lead target, different hadrons are produced:
•	Shower hadrons
•	Nuclear fragments (from break-up and evaporation of the target nucleus)
According to the neutrino flavour, a corresponding lepton is produced. In the case of ντ:
•	The τ lepton is produced and travels ~1 mm before decaying.
•	τ decay channels:
o	Single hadron (49.5%)
o	Electron (17.8%)
o	Muon (17.7%)
o	Three hadrons (15.0%)


Analysis Performed:

•	3 out of 10 events were explored (electronic detector only).
•	Event 10 shows muon bending and the presence of a muon as a decay particle, supporting the evidence of τ lepton production in the target tracker.
•	While full classification requires emulsion data, this exploratory analysis demonstrates how electronic detector signals reflect tau neutrino interactions.

Methods & Tools:

1.	Preprocessing: event-wise filtering and normalization of detector hit data.
2.	Clustering:
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
HDBSCAN (Hierarchical DBSCAN for robust clustering)
3.	Dimensionality Reduction:
PCA (Principal Component Analysis) for 2D/3D event visualization
4.	Visualization:
Matplotlib for plotting detector hits and reconstructed tracks

References:
1.	CERN Open Data Portal – OPERA Tau Neutrino Dataset
2.	OPERA tau neutrino charged current interactions, N. Agafonova et al., Scientific Data 8 (2021) 218. DOI: 10.1038/s41597-021-00991-y
