---
layout: project
title:  "Optimization for 2030 based on 2018 with 40% emission reduction"
date:   2020-03-01 09:00:00
author: Julián Blanco, Javier Bonilla, Eduardo Zarza and Diego Alarcón
region: Spain
target: 2030
data: 2018
reduction: 40%
pv: 21.57
wind: 41.04
csp: 5.12
total_power: 133.08
renewable_power: 94.90 (71.31%)
cost: 4.94
demand: 286.50
generated: 290.39
exported: -3.02
imported: 0.00
dumped: 0.88
emissions: 38,632 (40.14%)
results: 2030_(2018)_(40_%25)
variables: "New power of the following energy sources to be installed:
<ul>
<li>Photovoltaic power (PV).</li>
<li>Wind power.</li>
<li>Concentrating solar power (CSP).</li>
</ul>
"
goals: "Minimize the following criteria:
<ul>
<li>Average electricity generation cost.</li>
<li>Dumped energy.</li>
</ul>
"
restrictions: "
<ul>
<li>Electric demand must be at least matched.</li>
<li>Combined cycle power plants are used as much as possible but without exceeding the maximum allowed CO<sub>2</sub> emissions.</li>
</ul>
"
---
#### Overview
This document includes assumptions, results and interactive figures about the optimization for the Spanish energy mix in **2030** considering **2018** data with a **40%** of emission reduction.
<br>
<br>
#### Assumptions
- Shut down of **coal** power plants.
- Nuclear power reduced from 7.1 GW (2018) to **3.2 GW** (2030).
- New solar thermal power plants have **15-hour** thermal storage capacity with a **90%** of storage efficiency.
- Pumping turbidity power increased from 3.3 GW (2018) to **6.8 GW** (2030).
- Pumping turbidity capacity increased from 14 GWh (2018) to **28.8 GWh** (2030) with a **76%** of storage efficiency.
- Some coal power plants are adapted to **store dumped electricity** from photovoltaic and wind energy in molten salt tanks with a maximum capacity of **11.3 GWh** with a storage efficiency of **39%** and a nominal power of **2.3 GW**.
- **0.5%** annual demand increment (from 2018).
- **40%** emission reduction with respect to 1990.
