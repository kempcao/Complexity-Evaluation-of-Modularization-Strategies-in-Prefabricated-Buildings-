# Complexity Evaluation of Modularization Strategies in Prefabricated Buildings

This repository contains the project data, code, and documentation for a graph-based framework that evaluates the **structural complexity** of hybrid prefabricated buildings. The framework represents building configurations as graphs and assesses how different modularization strategies, combining **volumetric modules (VMs)** and **panelized walls (PWs)**, affect system-level structural complexity. 

## Overview

Hybrid prefabricated buildings can combine volumetric modules and panelized components within a single project. While such strategies may improve industrialization and design flexibility, they also alter the structural organization of the building system by changing component grouping, duplication, and interconnections. This repository provides a computational framework to model these alternative modularization strategies and quantify their structural complexity.

The framework integrates:

- **BIM-to-Graph transformation** from IFC-based building models  
- **Graph-based modularization modeling** for alternative VM/PW strategies  
- **Structural complexity computation** at component, connection, and topology levels  
- **Case-based evaluation** of modularization scenarios for prefabricated buildings  

## Research Objective

The goal of this project is to support the early-stage evaluation of modularization strategies in hybrid prefabricated buildings by providing a graph-based and computationally analyzable complexity assessment framework.

More specifically, the framework is designed to:

- represent building floor plans and modularized configurations as graphs,
- compute structural complexity based on wall, connection, module, and topology attributes,
- compare alternative modularization strategies quantitatively, and
- support design and decision-making in industrialized construction.

## Shared Data

This repository includes the data used in the case study presented in the research paper:

- **IFC Model**  
  The BIM model of the case project floor plan exported as an IFC file. This file contains the geometric and semantic information of the building elements used to generate the wall segment graph.

- **Wall Complexity Data**  
  A dataset describing the wall complexity features used in the complexity assessment model, including attributes such as wall length, openings, insulation requirements, MEP rough-ins, envelope layers, and structural roles.

- **Connection Complexity Data**  
  A dataset describing the connection complexity features between wall segments, including connection angles, structural requirements, and MEP connections.

These datasets support the graph generation process and the computation of structural complexity metrics for different modularization scenarios.

## Contact

Jianpeng Cao  
Department of Real Estate and Construction  
Faculty of Architecture, The University of Hong Kong  
Email: kempcao@hku.hk
