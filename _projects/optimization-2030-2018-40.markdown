---
layout: project
title:  "Optimization for 2030 based on 2018 with 40% emission reduction"
date:   2020-03-01 09:00:00
author: Julián Blanco, Javier Bonilla, Eduardo Zarza and Diego Alarcón

region: Spain
target: 2030
data: 2018
reduction: 40%
pv: 27.52
wind: 32.91
csp: 7.02
total_power: 131.03
renewable_power: 94.86 (72.40%)
cost: 5.48
demand: 286.50
generated: 288.71
exported: -1.90
imported: 0.01
dumped: 0.20
emissions: 38,719.39 (40.01 %)

results: 2030_(2018)_(40_%25)_batteries
remarks: <ul><li>Thermal power plants adapted to <b>store dumped electricity</b>.</li></ul>
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
- Cogeneration power reduced from 5.74 GW (2018) to **3.73 GW** (2030).
- New solar thermal power plants have **12-hour** thermal storage capacity with a **90%** of storage efficiency.
- Pumped hydropower increased from 3.3 GW (2018) to **6.8 GW** (2030).
- Pumped hydropower capacity increased from 14 GWh (2018) to **28.8 GWh** (2030) with a **76%** of storage efficiency.
- Electric batteries with **2.5 GW** of power and **10 GW** of capacity.
- **0.5%** annual demand increment (from 2018).
- **40%** emission reduction with respect to 1990.
