# Ratatoskr Project: VHDL models of routers

This repo contains the 3D router model for the Ratatoskr project implemented in
VHDL and Python.

If you use this code, please cite:

```
@ARTICLE{8843870,
  author={J. M. {Joseph} and L. {Bamberg} and D. {Ermel} and B. R. {Perjikolaei} and A. {Drewes} and A. {García-Ortiz} and T. {Pionteck}},
  journal={IEEE Access},
  title={NoCs in Heterogeneous 3D SoCs: Co-Design of Routing Strategies and Microarchitectures},
  year={2019},
  volume={7},
  number={},
  pages={135145-135163},
  doi={10.1109/ACCESS.2019.2942129}}
```

Currently, we deliver two 3D-router models, to be found in the
corresponding folder:

- noc_heter: 3D NoC router with support for heterogeneous integration.
- noc_heter_with_pe: 3D NoC router and PEs for inject uniform random traffic
or from traces with support for heterogeneous integration.
- noc_heter_high_throughput: 3D NoC router with support for heterogeneous
integration and support for high-throughput links, see paper.
- noc_heter_high_throughput_with_pe: 3D NoC router with PE, see above.

For a complete documentation of all architectural details, please contact us
directly. (This is partly the result of the Master thesis "Technology-Aware On-Chip Router 
Architecture for High-Performance 3D SoCs" by Behnam Razi Perjikolaei, 
which cannot be made publicly available.) 

# Contributors

- Lennart Bamberg, GrAI Matter Labs, Eindhoven, The Netherlands
- Behnam Razi Perjikolaei, OFFIS, Oldenburg, Germany
- Jan Moritz Joseph, RWTH Aachen University, Germany
