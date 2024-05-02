![license MIT](https://img.shields.io/github/license/kamal0013/PowNet) 
# PowNet: Unit Commitment / Economic Dispatch model in Python
PowNet is a least-cost optimization model for simulating the Unit Commitment and Economic Dispatch (UC/ED) of large-scale (regional to country) power systems. In PowNet, a power system is represented by a set of nodes that include power plants, high-voltage substations, and import/export stations (for cross-border systems). The model schedules and dispatches the electricity supply from power plant units to meet hourly electricity demand in substations at a minimum cost. It considers the techno-economic constraints of both generating units and high-voltage transmission network. The power flow calculation is based on a Direct Current (DC) network (with N-1 criterion), which provides a reasonable balance between modelling accuracy and data and computational requirements. PowNet can easily integrate information about variable renewable resources (e.g., hydro, wind, solar) into the UC/ED process. For example, it can be linked with models that estimate the electricity supply available from renewable resources as a function of the climatic conditions. In addition, PowNet has provision to account for the effect of droughts on the generation of dispatchable thermal units (e.g., coal, oil, gas-fired units) that depend on freshwater availability. These features facilitate the application of PowNet to problems in the water-energy nexus domain that investigate the impact of water availability on electricity supply and demand. 

# Read the PowNet Documentation here: https://pownet.readthedocs.io/en/latest


# Versions 
The latest and previous versions of PowNet are listed below. Please, check the [release notes](https://github.com/Critical-Infrastructure-Systems-Lab/PowNet/releases) for a list of modifications made in each version. Also, please note that the latest version (v2.0) features substantial changes w.r.t. to the v1.x versions, whose development is no longer supported.

### Current version
PowNet v2.0 <!--([GitHub]() | [Zenodo]())-->

### Previous versions
* PowNet v1.3 ([GitHub](https://github.com/kamal0013/PowNet/tree/v1.3) | [Zenodo](https://zenodo.org/record/4688309#.YHc5euhKguU))
* PowNet v1.2 ([GitHub](https://github.com/kamal0013/PowNet/tree/v1.2) | [Zenodo](https://zenodo.org/record/4020167#.X1hqrGhKguU))
* PowNet v1.1 ([GitHub](https://github.com/kamal0013/PowNet/tree/v1.1) | [Zenodo](https://zenodo.org/record/3756750))
