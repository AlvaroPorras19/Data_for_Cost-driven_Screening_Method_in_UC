## Data of 5-node and 2000-node Power Systems 🌇

## Goals 🚀

The aim of this repository is to provide the details of the power systems data set used in paper [[1]](https://arxiv.org/abs/2104.05746). This article have been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). I suggest you to visit the related links to know more about the research of the group 😉

## Contents 🌌

This repository includes the data about small-size system designed for illustrative purposes; and a power system in Texas which is extracted from a [repository of power grids](https://github.com/power-grid-lib/pglib-opf).
This data set contains net demands per node, and besides, information about generating units and transmission lines. 

- Five-node System:

  * [Generating Units](https://drive.google.com/file/d/1zK0Z3-HSOqBcE5sYITGDb7lc2nafjU1H/view?usp=sharing)
  * [Lines](https://drive.google.com/file/d/1gBbBxZc3kMpWyYcnq0jtnz8X2cAZaG5B/view?usp=sharing)
  * [Net Demands](https://drive.google.com/file/d/14gOCtA8oykLepH5K5C9BD_dYklPIB1il/view?usp=sharing)

- For the 2000-node system, net demand profiles for each node are synthetically derived from the nominal demand presented in the [repository](https://github.com/power-grid-lib/pglib-opf). It should be noted that the nominal parameters regarding the line
capacity and generating units have been conveniently modified. More details about these changes can be found in the paper [[1]](https://arxiv.org/abs/2104.05746). Each data file is linked below:

  * [Generating Units](https://drive.google.com/file/d/1r9t4zNWxOXvcKzbMiR1tLNv-IYkqvEz0/view?usp=sharing)
  * [Lines](https://drive.google.com/file/d/1OF4TTYkvnCPgjl3Cek-PzrgvEZuRXbfD/view?usp=sharing)
  * [Net Demands](https://drive.google.com/file/d/1Kz4c3jRrUNe8yiZ8fAJHwLmbCq9X5SqK/view?usp=sharing)
 
Additionally, we have included a section in the paper [[1]](https://ieeexplore.ieee.org/abstract/document/9736690) evaluating the performance of the proposed approach against topological changes in the 2000-node system. Each topological change considered consists of the disconnection of one of the corridor lines. The following file contains information about the identifier of the [corridor lines](https://drive.google.com/file/d/1OF4TTYkvnCPgjl3Cek-PzrgvEZuRXbfD/view?usp=sharing) and the ones we picked to run our experiments. More details in this regard can be found in Section III-B (Experiment 4) of [[1]](https://ieeexplore.ieee.org/abstract/document/9736690).
  
## References 📚
[1] Á. Porras, S. Pineda, J. M. Morales and A. Jiménez-Cordero, "Cost-driven Screening of Network Constraints for the Unit Commitment Problem," in IEEE Transactions on Power Systems, Early Access, 2022.

[2] OASYS, Data of 5-node and 2000-node Power Systems, Github repository (https://github.com/groupoasys/Cost-driven_Screening_Method_Data), 2022.

## How to cite the repository and the paper? 📝

If you want to cite the papers [[1]](https://arxiv.org/abs/2104.05746) or this repository, [[2]](https://github.com/groupoasys/Cost-driven_Screening_Method_Data
), please use the following bib entries:

* Article:
```
@article{porras2022cost,
  author={Porras, \'Alvaro and Pineda, Salvador and Morales, Juan Miguel and Jim\'enez-Cordero, Asuncion},
  journal={IEEE Transactions on Power Systems}, 
  title={Cost-driven Screening of Network Constraints for the Unit Commitment Problem}, 
  year={2022},
  doi={10.1109/TPWRS.2022.3160016}}
```

* Repository:
```
@article{Screenpowersystems2022,
author = {OASYS},
journal = {GitHub repository (https://github.com/groupoasys/Cost-driven{\_}Screening{\_}Method{\_}Data)},
title = {{Data of 5-node and 2000-node Power Systems}},
url = {https://github.com/groupoasys/Cost-driven{\_}Screening{\_}Method{\_}Data},
year = {2022}
}
```

## Do you want to contribute? 👨🏾‍🔬
 
 Please, do it ☺ Any feedback is welcome 🤩 so feel free to ask or comment anything you want via a Pull Request in this repo.
 If you need extra help, you can ask via email (alvaroporras19@gmail.com).

 
 ## Developed by 👨🏾‍💻
 * [Álvaro Porras](https://www.researchgate.net/profile/Alvaro-Porras-Cabrera) - alvaroporras19@gmail.com

 ## License 📝
 
    Copyright 2021 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
