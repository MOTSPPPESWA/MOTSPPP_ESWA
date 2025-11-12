# Mixed-integer linear programming model and algorithms for the multi-objective traveling salesman problem with profits and passengers 
**Exact, Heuristic, and Evolutionary Approaches**  

This repository contains the implementation, benchmark instances, and experimental data for the paper:  

> **"Mixed-integer linear programming model and algorithms for the multi-objective traveling salesman problem with profits and passengers"**  
> *Submitted to Expert System With Applications*  

## 📄 Abstract  

Ridesharing systems have emerged as effective mechanisms to enhance urban mobility by reducing costs, congestion, and environmental impacts. Despite the growing interest in optimization models for ridesharing, most of them are nonlinear and single-objective, focusing on minimizing travel costs while overlooking the conflicting relationships among cost, time, and bonus collection. This paper investigates the Multi-objective Traveling Salesman Problem with Profits and Passengers (MoTSPPP), an optimization problem that integrates passenger constraints with bonus collection mechanisms, capturing the trade-offs between minimizing route cost and travel time while maximizing collected bonuses. A multi-objective mixed-integer linear programming model is proposed, along with a proof of NP-hardness. Nine algorithms are investigated: an exact solver, three constructive heuristics, and five state-of-the-art metaheuristics (NSGA-II, MOEA/D, IBEA, SPEA2, MPLS). A comprehensive experimental study is conducted on 252 instances, comprising symmetric and asymmetric graphs with varying edge-weight correlations. Performance is assessed regarding processing time, solution quality, and solution diversity. Results supported by statistical tests confirm the computational difficulty of the MoTSPPP and demonstrate that metaheuristic approaches yield significantly better results than constructive heuristics.


## 📂 Repository Structure  
```
.
├── /Code/               # Source code (C/C++)
├── /Instances/          # Benchmark datasets
├── /results/            # Raw experimental and processed results
```

## 👥 Authors  
| Name | Affiliation | Contact |  
|------|-------------|---------|  
| **Juvenal B. A. Silva** | Federal University of Bahia, Institute of Computing | [juvenal.bruno@ufba.br](mailto:juvenal.bruno@ufba.br) |  
| **Tarcisio A. P. Brito** | Federal University of Bahia, Institute of Computing | [tarcisio.brito@ufba.br](mailto:tarcisio.brito@ufba.br) |  
| **Ricardo A. Rios** | Federal University of Bahia, Institute of Computing | [ricardoar@ufba.br](mailto:ricardoar@ufba.br) |  
| **Tatiane N. Rios** | Federal University of Bahia, Institute of Computing | [tatiane.nogueira@ufba.br](mailto:tatiane.nogueira@ufba.br) |  
| **Bilel Derbel** | University of Lille, CNRS, Centrale, Inria, UMR 9189 - CRIStAL, F-59000 Lille, France | [bilel.derbel@univ-lille.fr](mailto:bilel.derbel@univ-lille.fr) |  
| **Islame F. C. Fernandes** | Federal University of Bahia, Institute of Computing | [islame.felipe@ufba.br](mailto:islame.felipe@ufba.br) |  


## 📧 Contact  
For questions, contact the lead author: [juvenal.bruno@ufba.br](mailto:juvenal.bruno@ufba.br).  

---
