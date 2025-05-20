<p align="center">
  <a href="https://wfcommons.org" target="_blank"><img src="https://wfcommons.org/images/wfcommons-horizontal.png" width="450" alt="WfCommons Project" /></a>
  <br />EMPOWERING SCIENTIFIC WORKFLOW RESEARCH
  <br /><br />
  <a href="https://badge.fury.io/py/wfcommons" target="_blank"><img src="https://badge.fury.io/py/wfcommons.svg" /></a>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/License-LGPL%20v3-blue.svg" />&nbsp;&nbsp;
  <img src="https://img.shields.io/github/contributors/wfcommons/wfcommons?style=flat" />&nbsp;&nbsp;
  <a href="https://pepy.tech/project/wfcommons" target="_blank"><img src="https://static.pepy.tech/personalized-badge/wfcommons?period=total&units=international_system&left_color=grey&right_color=yellowgreen&left_text=Downloads" /></a>
</p>

[WfCommons](https://wfcommons.org) is a collaborative framework for empowering 
scientific workflow research and development. WfCommons tools analyze workflow 
execution instances, generate synthetic yet realistic workflows, define 
benchmark specifications, and pioneer new techniques to optimize execution 
on complex distributed infrastructures.

<p align="center">
  <img src="https://wfcommons.org/images/wfcommons-concept.png" width="650" />
</p>

- **[WfFormat](https://github.com/wfcommons/WfFormat)**: A universal JSON format, ensuring seamless integration across simulators and frameworks supported by WfCommons

- **[WfInstances](https://github.com/wfcommons/wfinstances)**: Curated collection of open-access production workflow executions in the standardized WfFormat

- **[WfInstances browser](https://wfinstances.ics.hawaii.edu)**: A web app for browsing, selecting, visualizing, and simulating WfInstances workflow isntances

- **WfChef**: Automated creation of synthetic workflow generators by analyzing real workflows to uncover task patterns and performance characteristics

- **WfGen**: Automated generation of realistic synthetic workflows using recipes to create diverse instances for simulation or benchmark generation

- **WfBench**: Generate realistic workflow benchmarks with diverse performance characteristics and task dependencies for current workflow systems

- **WfSim**: Facilitate simulation for developing and evaluating scheduling algorithms and computing platforms, overcoming real-world limitations


## Citing WfCommons
When citing WfCommons, please use the following paper. You should also actually read 
that paper, as it provides a recent and general overview on the framework.

```
@article{wfcommons,
    title = {{WfCommons: A Framework for Enabling Scientific Workflow Research and Development}},
    author = {Coleman, Taina and Casanova, Henri and Pottier, Loic and Kaushik, Manav and Deelman, Ewa and Ferreira da Silva, Rafael},
    journal = {Future Generation Computer Systems},
    volume = {128},
    number = {},
    pages = {16--27},
    doi = {10.1016/j.future.2021.09.043},
    year = {2022},
}
```
