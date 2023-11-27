# RTS-El-Paso

## Overview 

The following test system was developed in the [Powerful Lab](https://forum.ysang.org/) to simulate the operations of the electric grid of the city of El Paso, TX. 

The test system was used in [[1]](https://ieeexplore.ieee.org/document/10318590) to facilitate marginal emission tracking with the implementation of Distributed Flexible AC Transmission Systems (D-FACTS). As certain transmission network data was confidential, we generated an artificial system using publicly accessible information and the RTS-96 test system. This study's test system, partially derived from RTS-96, incorporates geographically representative locations mirroring actual bus and generator locations in El Paso. 

For additional details regarding the derivation and applications of the test system, it is advised to read the referenced paper.

## Contents

The repository includes data for the RTS-El-Paso test system, which is used to simulate the operations of the power system through optimization models such as unit commitment and economic dispatch. The proposed test system includes 25 buses and 40 transmission lines. In addition, the system was modified to include natural gas combined cycle (CC) and combustion turbine (CT) generators as well as solar energy facilities. Finally, the generators from the Palo Verde Nuclear Generating Station were also provided to serve the base load. The RTS-El-Paso data folder contains data in an open csv format.

## References

[1] E. Castillo, K. Santacruz, H. Caballero, and Y. Sang, “Reducing Marginal Emissions in Power Systems with Distributed Flexible AC Transmission Systems,” 2023 North Am. Power Symp., pp. 1–6, doi: 10.1109/NAPS58826.2023.10318590.

[2] Powerful Lab, RTS-El-Paso, Github repository (https://github.com/kenjisantacruz/RTS-El-Paso) , 2023.

## How to cite

* Article:
```
@article{ieeexplore,
  title={Reducing Marginal Emissions in Power Systems with Distributed Flexible AC Transmission Systems},
  author={Eduardo Castillo, Kenji Santacruz, Haveeair Caballero, and Yuanrui Sang},
  journal={2023 North American Power Symposium (NAPS)},
  year={2023},
  doi={10.1109/NAPS58826.2023.10318590},
}
```
* Repository:
```
@article{RTS-El-Paso,
author = {Powerful Lab},
journal = {GitHub repository (https://github.com/kenjisantacruz/RTS-El-Paso)},
title = {{RTS-El-Paso}},
url = {https://github.com/kenjisantacruz/RTS-El-Paso},
year = {2023}
}
```

## Contributors

* [Kenji Santacruz](https://orcid.org/0000-0002-5812-057X) - kenjisantacruz@gmail.com

If you are interested in contributing to this repository, feel free to send me an email.
