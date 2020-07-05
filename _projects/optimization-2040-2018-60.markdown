---
layout: project
title:  "Optimization for 2040 based on 2018 with 60% emission reduction"
date:   2020-03-02 09:00:00
author: Julián Blanco, Javier Bonilla, Eduardo Zarza and Diego Alarcón

region: Spain
target: 2040
data: 2018
reduction: 60%
pv: 36.61
wind: 57.07
csp: 13.50
total_power: 169.14
renewable_power: 138.25 (81.74%)
cost: 5.05
demand: 301.15
generated: 316.77
exported: -10.24
imported: 0.15
dumped: 5.38
emissions: 25,804.35 (60.02 %)

results: 2040_(2018)_(60_%25)_batteries
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
This document includes assumptions, results and interactive figures about the optimization for the Spanish energy mix in **2040** considering **2018** data with a **60%** of emission reduction.
<br>
<br>
#### Main assumptions for 2040 electric mix
- Shut down of **coal** power plants.
- Shut down of **nuclear** power plants.
- Cogeneration power reduced from 5.74 GW (2018) to **2.87 GW** (2040).
- Fuel & gas power reduced form 2.49 GW (2018) to **1.25 GW** (2040), a 50% reduction.
- New solar thermal power plants have **12-hour** thermal storage capacity with a **90%** of storage efficiency.
- Pumped hydropower power increased from 3.3 GW (2018) to **8 GW** (2040).
- Pumped hydropower capacity increased from 14 GWh (2018) to **33.9 GWh** (2040) with a **76%** of storage efficiency.
- Electric batteries with **5 GW** of power and **20 GW** of capacity.
- **0.5%** annual demand increment from 2018 to 2030 and **1.5%** from 2030 to 2040.
- **60%** emission reduction with respect to 1990.
<br>
<br>
