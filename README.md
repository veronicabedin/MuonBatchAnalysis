# MuonBatchAnalysis
Final project of the Management and Analysis of Physics Datasets course

## Title
Batch analysis of cosmic rays using Drift Tubes detectors

## Introduction

The aim of the project is to analyse data of muon collisions in a drift tube detector, in order to reconstruct the tracks of the particles. The detector comprises of four chambers - each subdivided in four layers - and two scintillators, working in coincidence. Each layer consists of 8 "channels", which are physical cells containing the anode wire. The muons, passing through the channels, ionise the gas contained inside and the free electrons are collect by the wire and generate an electrical signal that indirectly indicate the passage of a particle.

The signals of the detector are digitised by the TDC and collected in 81 binary files.
We employ a cluster to parallelise the analysis operations and speed up the computations.

This was a group project, here the info of the people that worked on this and theyr general informations:


Professor in charge: Jacopo Pazzini
Students:

Bedin Veronica - 2097013 - veronica.bedin.1@studenti.unipd.it
⟶ VM Setup, Analysis on RSE, Global Fit, Refined Global fit
Marchetti Andrea - 2089216 - andrea.marchetti.5@studenti.unipd.it
⟶ VM Setup, Plot Displaying, Dataset Cleansing, Angular Resolution, Optimisation, Performances
Menti Luca - 2069534 - luca.menti@studenti.unipd.it
⟶ Data Preprocessing, Feature Enrichment, Local Fit, Performances
Merlin Giovanni - 2091186 - giovanni.merlin@studenti.unipd.it
⟶ Data Preprocessing, Feature Enrichment, Local Fit, Performances
