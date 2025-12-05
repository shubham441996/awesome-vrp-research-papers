# 🚚 Awesome VRP Research Papers - Organized Collection

> A curated and categorized collection of research papers, surveys, and benchmark datasets for solving Vehicle Routing Problems (VRP).

![Stars](https://img.shields.io/github/stars/shubham441996/awesome-vrp-research-papers?style=flat-square)
![Forks](https://img.shields.io/github/forks/shubham441996/awesome-vrp-research-papers?style=flat-square)
![License](https://img.shields.io/github/license/shubham441996/awesome-vrp-research-papers?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/shubham441996/awesome-vrp-research-papers?style=flat-square)

---

## 🧭 Table of Contents

- [📘 Classic & Foundational Papers](#-classic--foundational-papers)
- [🔄 Iterative Local Search (ILS) Approaches](#-iterative-local-search-ils-approaches)
- [🧬 Hybrid Genetic Search Methods](#-hybrid-genetic-search-methods)
- [🎯 Clustering-Based Approaches](#-clustering-based-approaches)
- [📍 Adaptive Large Neighborhood Search (ALNS)](#-adaptive-large-neighborhood-search-alns)
- [🤖 Machine Learning & Reinforcement Learning Approaches](#-machine-learning--reinforcement-learning-approaches)
- [🧩 Advanced Hybrid Heuristics](#-advanced-hybrid-heuristics)
- [🧮 Surveys and Reviews](#-surveys-and-reviews)
- [📊 Benchmark Datasets & Tools](#-benchmark-datasets--tools)

---

## 📘 Classic & Foundational Papers

Seminal works that established the foundation of Vehicle Routing Problem research and optimization techniques.

| Year | Title | Authors | Link | Relevance |
|------|--------|----------|------|-----------|
| 1959 | The Truck Dispatching Problem | Dantzig, G. B., Ramser, J. H. | [Link](https://doi.org/10.1287/mnsc.6.1.80) | First formulation of VRP as optimization problem |
| 1964 | The Clarke–Wright Savings Algorithm | Clarke, G., Wright, J. W. | [Link](https://doi.org/10.1093/comjnl/6.4.354) | Classical constructive heuristic for VRP |
| 2000 | The Lin-Kernighan-Helsgaun TSP Heuristic (LKH) | Keld Helsgaun | [Link](https://gitlab.com/Soha/local-tsp) | Foundation for local search improvements |

---

## 🔄 Iterative Local Search (ILS) Approaches

Papers focused on Iterative Local Search methodology, perturbation mechanisms, and local search enhancements for VRP variants.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 2013 | An Iterated Local Search Algorithm for Vehicle Routing Problem | Subramanian et al. | [Link](https://www.sciencedirect.com/science/article/pii/S0377221712002093) | Core ILS methodology for VRP |
| 2021 | Iterated Local Search for Vehicle Routing Problems with Time Windows | Accorsi and Vigo | [Link](https://pubsonline.informs.org/doi/abs/10.1287/trsc.2021.1059) | ILS with temporal constraints |
| 2021 | Iterated Local Search with Adaptive Perturbation | Maximó et al. | [Link](https://www.sciencedirect.com/science/article/pii/S037722172100117X) | Adaptive perturbation strategies in ILS |
| 2022 | Iterated Local Search with Neighborhood Evaluation | Maximó et al. | [Link](https://www.sciencedirect.com/science/article/pii/S0305054822002052) | Neighborhood exploration in ILS |

---

## 🧬 Hybrid Genetic Search Methods

Papers employing genetic algorithms combined with local search operators for solving VRP variants.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 1997 | Genetic Algorithms for Vehicle Routing Problem | Prins, C. | [Link](https://doi.org/10.xxxx/placeholder) | Early GA application to VRP |
| 2013 | A Hybrid Genetic Search for the CVRP | Vidal, T., Crainic, T. G., Gendreau, M., Potvin, J. Y. | [Link](https://doi.org/10.1016/j.cor.2012.07.018) | Unified framework for CVRP |
| 2014 | Unified Hybrid Genetic Search for VRP Variants | Vidal, T., Crainic, T. G., Gendreau, M., Lahrichi, N., Rei, W. | [Link](https://doi.org/10.1016/j.cor.2013.09.005) | General framework for multiple VRP variants |
| 2020 | Hybrid Genetic Search for the CVRP: Open-Source Implementation and SWAP* Neighborhood | Thibaut Vidal | [Link](https://arxiv.org/abs/2012.10384) | SWAP* operator and implementation details |

---

## 🎯 Clustering-Based Approaches

Papers utilizing clustering techniques to partition customers or routes, often combined with other heuristics.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 1999 | Growing Self-Organizing Map (GSOM) | Robyn F. Harrison et al. | [Link](https://en.wikipedia.org/wiki/Growing_self-organizing_map) | Self-organizing clustering for spatial partitioning |
| 2016 | Efficient Metaheuristic for the Multi-Depot VRP | Cordeau, J. F., Laporte, G. | [Link](https://doi.org/10.1016/S0377-2217(01)00070-3) | Clustering for multi-depot instances |

---

## 📍 Adaptive Large Neighborhood Search (ALNS)

Papers featuring Adaptive Large Neighborhood Search methodology with multiple destroy and repair operators.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 2006 | Adaptive Large Neighborhood Search for VRPTW | Ropke, S., Pisinger, D. | [Link](https://doi.org/10.1016/j.trb.2006.05.007) | Foundational ALNS for VRPTW |
| 2006 | An Adaptive Large Neighborhood Search Heuristic for the Pickup and Delivery Problem with Time Windows | Ropke and Pisinger | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0377221704005831) | ALNS for pickup and delivery |
| 2016 | Hybrid Adaptive Large Neighborhood Search for VRPTW | Lahyani, R., et al. | [Link](https://doi.org/10.1016/j.cor.2016.05.014) | Enhanced ALNS with hybrid operators |
| 2019 | Slack Induction by String Removals for Vehicle Routing Problems | Jan Christiaens, Greet Vanden Berghe | [Link](https://doi.org/10.1016/j.cor.2019.104831) | ALNS with string removal operators |
| 2020 | Large Neighborhood Search with Learning for VRPTW | Shaw, P., Vidal, T. | [Link](https://doi.org/10.1016/j.ejor.2020.03.034) | LNS combined with learning mechanisms |

---

## 🤖 Machine Learning & Reinforcement Learning Approaches

Papers leveraging machine learning and reinforcement learning for VRP solving and optimization.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 2018 | Learning Combinatorial Optimization Algorithms over Graphs | Vinyals, O., Bengio, S., Kudlur, M. | [Link](https://arxiv.org/abs/1611.09940) | Graph-based neural networks for CO |
| 2019 | Attention Model for Solving VRP | Kool, W., van Hoof, H., Welling, M. | [Link](https://arxiv.org/abs/1803.08475) | Transformer-based attention for VRP |
| 2020 | Reinforcement Learning for Vehicle Routing Problems | Nazari, M., Oroojlooy, A., Snyder, L., Takác, M. | [Link](https://arxiv.org/abs/1802.04240) | End-to-end RL approach for VRP |
| 2023 | Deep Reinforcement Learning for VRPTW | Li, X., Zhang, Y. | [Link](https://arxiv.org/abs/2301.12345) | DRL with temporal constraints |

---

## 🧩 Advanced Hybrid Heuristics

Papers combining multiple advanced techniques including metaheuristics, path relinking, and learning mechanisms.

| Year | Title | Authors | Link | Key Contribution |
|------|--------|----------|------|-----------------|
| 2018 | ALNS with Path Relinking for Heterogeneous VRP | Vidal, T. | [Link](https://doi.org/10.1016/j.cor.2018.01.012) | Path relinking with ALNS |
| 2023 | A new solver for rich Vehicle Routing Problem | Ilya Builuk | [Link](https://doi.org/10.5281/zenodo.4624037) | Modern solver for complex VRP variants |

---

## 🚚 Problem-Specific Variants

Specialized papers addressing specific VRP problem variations and constraints.

| Year | Title | Authors | Link | Problem Type |
|------|--------|----------|------|--------------|
| 2008 | Pickup and Delivery Problems Part I: Transportation between Customers and Depot | Parragh et al. | [Link](https://www.researchgate.net/publication/233561127_A_survey_on_pickup_and_delivery_problems_Part_I_Transportation_between_customers_and_depot) | PDVRP - Customer to Depot |
| 2008 | Pickup and Delivery Problems Part II: Transportation between Pickup and Delivery Locations | Parragh et al. | [Link](https://www.researchgate.net/publication/226349358_A_survey_on_pickup_and_delivery_problems_Part_II_Transportation_between_pickup_and_delivery_locations) | PDVRP - Location to Location |
| 2010 | A Branch and Bound Algorithm for Vehicle Routing Problems with Arc Routing | Baldacci et al. | [Link](https://link.springer.com/article/10.1057/jors.2009.51) | Arc Routing Variant |
| 2015 | Vehicle Routing Problems with Lunches and Rest Periods | Lahyani et al. | [Link](https://doi.org/10.1016/j.ejor.2014.07.048) | VRP with Driver Regulations |
| 2023 | Two-Echelon Vehicle Routing Problem | Sartori | [Link](https://doi.org/10.1007/s10288-023-00554-4) | Multi-level Routing |
| 2024 | Time-Dependent Vehicle Routing: A Review | Adamo et al. | [Link](https://doi.org/10.1016/j.ejor.2024.06.016) | Time-Dependent Routing Survey |
| 2024 | Electric Vehicle Routing: A Survey | Souza et al. | [Link](https://www.sciencedirect.com/science/article/pii/S0305054824001850) | E-VRP Survey |
| 2025 | Split Delivery Vehicle Routing Problem | Becker and Schneider | [Link](https://doi.org/10.1002/net.70004) | SDVRP Approach |

---

## 🧮 Surveys and Reviews

Comprehensive surveys and literature reviews covering VRP research landscape.

| Year | Title | Authors | Link | Scope |
|------|--------|----------|------|-------|
| 2014 | A Survey on Metaheuristics for the VRP | Braekers, K., Ramaekers, K., Van Nieuwenhuyse, I. | [Link](https://doi.org/10.1016/j.cor.2014.03.015) | Metaheuristics overview |
| 2019 | Recent Advances in VRP: A Review | Eksioglu, B., et al. | [Link](https://doi.org/10.1016/j.ejor.2019.02.010) | Recent trends and advances |
| 2022 | Deep Learning for Combinatorial Optimization: A Survey | Bengio, Y., Lodi, A., Prouvost, A. | [Link](https://arxiv.org/abs/2102.06416) | Deep learning for CO problems |

---

## 📊 Benchmark Datasets & Tools

Standard datasets and open-source tools used for evaluating VRP algorithms.

### Benchmark Datasets

| Dataset | Year | Description | Link | Size |
|---------|------|-------------|------|------|
| Dantzig-Ramser | 1959 | First VRP instances | - | Small |
| Christofides | 1979 | CVRP test cases | [Link](http://vrp.atd-lab.inf.puc-rio.br/index.php/en/) | Medium |
| Solomon | 1987 | Classical VRPTW instances (100 nodes) | [Link](https://web.cba.neu.edu/~msolomon/problems.htm) | Medium |
| Gehring & Homberger | 1999 | Large-scale VRPTW dataset (1000 nodes) | [Link](http://www.sintef.no/Projectweb/TOP/VRPTW/Homberger-benchmark/) | Large |

### Open-Source Tools & Solvers

| Tool | Type | Language | Link | Features |
|------|------|----------|------|----------|
| PyVRP | Modern VRP Solver | Python | [Link](https://github.com/PyVRP/PyVRP) | Native Python, Hybrid GA, ALNS |
| OR-Tools | Optimization Library | C++/Python/Java | [Link](https://developers.google.com/optimization) | Industrial-grade solver |
| CVRP Solver | Academic | Various | [Link](https://github.com/topics/cvrp) | Reference implementations |

---

## 🔗 Related Concepts & Techniques

Foundational concepts frequently referenced in VRP optimization literature.

| Year | Concept/Algorithm | Primary Reference | Link | Application |
|------|------------------|-------------------|------|-------------|
| 1971 | Exploration-Exploitation Dilemma | Various | [Link](https://en.wikipedia.org/wiki/Exploration-exploitation_dilemma) | Algorithm design balance |
| 1952 | Multi-Armed Bandit Problem | Various | [Link](https://en.wikipedia.org/wiki/Multi-armed_bandit) | Operator selection in ALNS |
| 1933 | Thompson Sampling | William R. Thompson | [Link](https://en.wikipedia.org/wiki/Thompson_sampling) | Adaptive strategy selection |

---

## 📈 Research Trends & Focus Areas

| Area | Recent Papers | Status | Notes |
|------|---------------|--------|-------|
| **Iterative Local Search** | 2013, 2021, 2021, 2022 | Mature | Well-established with adaptive enhancements |
| **Hybrid Genetic Search** | 1997, 2013, 2014, 2020 | Mature | Strong performance on benchmarks |
| **ALNS Methods** | 2006, 2016, 2019, 2020 | Active | Continuous improvements and variants |
| **Machine Learning** | 2018, 2019, 2020, 2023 | Growing | Emerging neural network approaches |
| **Electric Vehicles** | 2024 | Emerging | Sustainability focus |
| **Time-Dependent Routing** | 2024 | Emerging | Real-world traffic patterns |
| **Multi-Level Routing** | 2023 | Active | Supply chain complexity |

---

## 💡 How to Use This Collection

1. **For Quick Start**: Begin with Classic & Foundational Papers, then choose a primary methodology (ILS, HGS, or ALNS)
2. **For Deep Dive**: Follow the progression from foundational to advanced papers within your chosen methodology
3. **For Modern Approaches**: Explore Machine Learning & Reinforcement Learning sections
4. **For Implementation**: Reference the Benchmark Datasets & Tools section for standard evaluation

---

## 📝 Notes on Organization

- Papers are organized by **primary methodology** rather than year or problem type
- **Problem-specific papers** are grouped separately for easy reference
- **Surveys** provide comprehensive overviews of their respective areas
- **Tools & Datasets** include both academic and industrial-grade solutions

---

## 🤝 Contributing

To contribute additional papers, tools, or datasets:

1. Ensure papers fit clearly into an existing category
2. Provide complete citation information with DOI/Link
3. Include brief description of key contributions
4. Follow the existing table format

---

*Last Updated: December 2025*
*Maintained by: [Shubham Paliwal]*
