---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<p align="center">
  <img src="mimic_logo.jpg" width="450" height="230"/>
</p>

I am involved in the [MiMiC project](https://mimic-project.org/en/latest/) together with [Dr. Jógvan Magnus Haugaard Olsen](https://orbit.dtu.dk/en/persons/jógvan-magnus-haugaard-olsen) and [Prof. Ursula Röthilsberger](https://www.epfl.ch/labs/lcbc/roethlisberger/). The MiMiC framework is an open-source, general platform that enables the implementation of multiscale computational chemistry simulation methods through coupling of multiple external programs, designed for massively parallel applications with a multiple-programs multiple-data model. The program is written in a combination of Fortran and C++, and parallelization implmented with hybrid MPI/OpenMP. Currently, MiMiC couple the CPMD and GROMACS code to perform highly scalable QM/MM biomolecular simulations on HPCs. 

I am the lead developer of [MiMiCPy](https://mimic-project.org/en/latest/mimicpy/overview.html), a python toolkit as a companion to MiMiC. The code greatly simplifies the preparation and debugging of MiMiC-based QM/MM input files via a user-friendly interface. It provides an extensive list of command-line tools with an easy-to-use selection language to pick out the QM region. Plugins for PyMOL and VMD allows the selection of complex QM regions visually. MiMiCPy can also be used as a Python library, allowing one to develop complex workflows to set up MiMiC-based QM/MM simulations. The package has been designed with a modular and object-oriented approach. This allows one (i) to easily support new topology and coordinate file formats from different programs, when they become available in MiMiC; (ii) to develop new tools as MiMiC expands its functionalities.

I was involved in early efforts to couple MiMiC-QM/MM simulations with machine learning-based force fields. This was carried out as part of the Helmholtz GPU Hackathon 2020 in collaboration with Andrea Rizzi, Florian Schakerth and Viacheslav Bolynkh. I designed a MiMiC data reader for the [PiNN library](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00994), and contributed to parallelization efforts of the tensorflow-based atomic neural network on multiple GPUs. I also contribute to testing, documentation and communication activities related to MiMiC. I spearheaded training activities at the [CECAM Flagship School on MiMiC](https://www.cecam.org/workshop-details/1119) held at the École Polytechnique Fédérale de Lausanne (EPFL) on 18 to 22 July 2022 and the [Simulate with EBRAINS](https://flagship.kip.uni-heidelberg.de/jss/HBPm?m=showAgenda&meetingID=242) event held by the Human Brian Project on 10th Nov 2022.

<p align="center">
  <img src="hepp.png" width="430" height="200"/>
</p>

My Doctral thesis is conducted within the Helmholtz European Partnering Project between Forschungszentrum Juelich and Italian Institute of Technology. The main goal is computational drug design against neuroloigcal diseases and glioma by targeting the protein Isocitrate Dehydrogenase.

My contributions:

- To do
- To do

Skills demonstrated:
- Clustering..
- To do
