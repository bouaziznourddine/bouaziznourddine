## 👋 Hi, I'm Nourddine Bouaziz

- 🎓 **PhD in Computer Science** — Arts et Métiers, 2025 | Production Scheduling | Simulation | Operations Research
- 🔬 Postdoctoral researcher at **CESI LINEACT**, Rouen — scheduling a robotic machining cell (OPTIMAN, with Maugars Industrie)
- 🏭 Five years of **Odoo ERP** development in industry before research: port maintenance, manufacturing, point of sale
- 📦 Main author of **[Netlogopy](https://github.com/Bouaziz19/netlogopy)**, an open-source Python–NetLogo library (MIT)
- 📄 **5 publications**, including *International Journal of Production Economics* (2024)

### 🛠️ Technologies I work with

- **Optimisation:** MILP, MINLP, genetic algorithms, NSGA-II · Gurobi, SCIP, CPLEX, LINGO, OpenSolver, OR-Tools
- **Simulation:** NetLogo, Netlogopy, Arena, FlexSim · Markov chains · simulation–optimisation coupling
- **Programming:** Python (Flask, Django, pandas, Pyomo, Pymoo), Julia, Java, SQL, JavaScript
- **ERP:** Odoo v9 to v16 — ORM, QWeb views, APIs, custom business modules
- **Data & methods:** PostgreSQL, MERISE/UML, shop-floor data collection (QR, multi-camera video, JSON)

📫 **[Portfolio](https://bouaziznourddine.github.io/portfolio/)** ·
[Google Scholar](https://scholar.google.fr/citations?user=P_OKvKwAAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/nourddine-bouaziz-b58224350/) ·
[ResearchGate](https://www.researchgate.net/profile/Nourddine-Bouaziz)

---

### 🔎 What I actually work on

Most scheduling models treat operators like machines: always present, always at the same pace. A real shop floor does not work that way.

My PhD modelled operator punctuality with **Markov chains estimated from observed transitions**, extended those profiles with fatigue, learning and forgetting, then coupled an **agent-based simulator** with a **mixed-integer non-linear optimisation model** that assigns operators to workstations to maximise throughput. A simulation–optimisation loop triggers rescheduling when execution drifts from the plan.

Today, on **OPTIMAN**, I work on a robotic machining cell: two CNC machines, a shared handling robot, pallets, fixtures and operator calendars. A free machine is not enough to start a part — the right fixture must be available, and the first part of each phase needs an operator on site.

### 📦 Netlogopy

NetLogo is excellent for agent-based simulation but cut off from the Python ecosystem. Existing bridges run a simulation and collect results; **Netlogopy lets you create agents, change their properties at runtime and reuse existing models**, so optimisation and data analysis become available to agent-based modelling.

MIT licence · [PyPI](https://pypi.org/project/netlogopy/) · [Code](https://github.com/Bouaziz19/netlogopy) · [Paper, SW25](https://doi.org/10.36819/SW25.019)

### 📄 Publications

- **Incorporating uncertain human behavior in production scheduling for enhanced productivity in Industry 5.0 context** — *Int. J. of Production Economics*, 274, 109311, 2024 · [doi](https://doi.org/10.1016/j.ijpe.2024.109311)
- **Netlogopy: Unlocking Advanced Simulation and Integration for NetLogo Using Python** — *Simulation Workshop 2025*, Exeter · [doi](https://doi.org/10.36819/SW25.019)
- **Modeling and simulation of worker profiles based on punctuality, fatigue, and experience** — *IEEE ICTMOD 2024*, Sharjah
- **Modeling and simulation of human behavior impact on production throughput** — *IFAC-PapersOnLine*, 55(10), 1740–1745, 2022 · [doi](https://doi.org/10.1016/j.ifacol.2022.09.649)
- **Ordonnancement d'atelier de production flexible sous incertitude du comportement humain** — *SAGIP 2024*, Villeurbanne · [HAL](https://hal.science/hal-04627782)

---

📍 Rouen, France — open to discussions on operations optimisation, simulation and industrial software.
