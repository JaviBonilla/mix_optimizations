---
layout: project
title:  "Optimization for 2040 based on 2018 with 60% emission reduction"
date:   2020-03-05 09:00:00
author: Julián Blanco, Javier Bonilla, Eduardo Zarza and Diego Alarcón

region: Spain
target: 2040
data: 2018
reduction: 75%
pv: 34.11
wind: 86.77
csp: 11.62
total_power: 192.40
renewable_power: 163.57 (85.02%)
cost: 4.58
demand: 301.15
generated: 346.62
exported: -27.86
imported: 0.09
dumped: 17.70
emissions: 16,125.73 (75.01 %)

results: 2040_(2018)_(75_%25)_batteries
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
This document includes assumptions, results and interactive figures about the optimization for the Spanish energy mix in **2040** considering **2018** data with a **75%** of emission reduction.
<br>
<br>
#### Main assumptions for 2040 electric mix
- Shut down of **coal** power plants.
- Shut down of **nuclear** power plants.
- Cogeneration power reduced from 5.74 GW (2018) to **1.44 GW** (2040), a 75% reduction.
- Fuel & gas power reduced form 2.49 GW (2018) to **0.62 GW** (2040), a 75% reduction.
- New solar thermal power plants have **12-hour** thermal storage capacity with a **90%** of storage efficiency.
- Pumped hydropower increased from 3.3 GW (2018) to **8 GW** (2040).
- Pumped hydropower capacity increased from 14 GWh (2018) to **33.9 GWh** (2040) with a **76%** of storage efficiency.
- Electric batteries with **5 GW** of power and **20 GW** of capacity.
- **0.5%** annual demand increment from 2018 to 2030 and **1.5%** from 2030 to 2040.
- **75%** emission reduction with respect to 1990.
<br>
<br>
