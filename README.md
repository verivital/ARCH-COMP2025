# ARCH-COMP 2025
ARCH-COMP AINNCS Category 2025 Model Files

Event info: https://cps-vo.org/group/ARCH/FriendlyCompetition


## Benchmarks 

We are resuing the benchmarks from 2024:

| Benchmark | Instance | Specification | Network | Visualization | Comment |
|-----------|----------|---------------|-----------|---------------|---------|
| [ACC](./benchmarks/ACC) | safe-distance | default | relu | distance over time | - | 
| [Airplane](./benchmarks/Airplane) | continuous | t\in[0,20] | relu | [2,7] | - | 
| [Airplane](./benchmarks/Airplane) | discrete | t\in{0,1,...,20} | relu | [2,7] | - | 
| [Attitude Control](./benchmarks/Attitude-Control) | avoid | default | sigmoid | [1,2] | - | 
| [Balancing](./benchmarks/CartPole) | reach | default | tanh | [1,3] | new | 
| [Docking](./benchmarks/Docking) | constraint | default | tanh | [1,2] and [3,4] | - | 
| [Double Pendulum](./benchmarks/Double_Pendulum) | less-robust | Specification 1 | less robust | [3,4] | -| 
| [Double Pendulum](./benchmarks/Double_Pendulum) | more-robust | Specification 2 | more robust | [3,4] | - | 
| [NAV](./benchmarks/NAV) | standard | default | nn-nav-point | [1,2] | - | 
| [NAV](./benchmarks/NAV) | robust | default | nn-nav-set | [1,2] | - | 
| [QUAD](./benchmarks/QUAD) | reach | default | sigmoid | dim 3 over time | - | 
| [Single Pendulum](./benchmarks/Single_Pendulum) | reach | default | relu | 1 over time | - | 
| [TORA](./benchmarks/Benchmark9-Tora) | remain | Specification 1 | relu | [1,2] and [3,4] | - | 
| [TORA (Heterogeneous)](./benchmarks/Tora_Heterogeneous) | reach-sigmoid | Specification 2 | sigmoid | [1,2] | - | 
| [TORA (Heterogeneous)](./benchmarks/Tora_Heterogeneous) | reach-tanh | Specification 2 | tanh | [1,2] | - | 
| [Unicycle](./benchmarks/Benchmark10-Unicycle) | reach | default | relu | [1,2] | - | 
| [VCAS](./benchmarks/VCAS) | avoid | default | relu | vertical distance over time | - |


### Competition History

Prior year reports:
- 2024: https://easychair.org/publications/paper/WsgX
- 2023: https://easychair.org/publications/paper/Vfq4b
- 2022: https://easychair.org/publications/paper/C1J8
- 2021: https://easychair.org/publications/paper/Jq4h
- 2020: https://easychair.org/publications/paper/Jvwg
- 2019: https://easychair.org/publications/paper/BFKs

Repeatability archives: https://gitlab.com/goranf/ARCH-COMP/

