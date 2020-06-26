---
layout: project
title:  "Optimization for 2050 based on 2018 with 80% emission reduction"
date:   2020-03-03 09:00:00
author: Julián Blanco, Javier Bonilla, Eduardo Zarza and Diego Alarcón

region: Spain
target: 2050
data: 2018
reduction: 80%
pv: 57.07
wind: 80.37
csp: 17.02
total_power: 221.36
renewable_power: 192.53 (86.98%)
cost: 4.41
demand: 316.55
generated: 373.17
exported: -27.40
imported: 0.19
dumped: 29.42
emissions: 12,898.26 (80.01 %)

results: 2050_(2018)_(80_%25)_batteries
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
This document includes assumptions, results and interactive figures about the optimization for the Spanish energy mix in **2050** considering **2018** data with a **80%** of emission reduction.
<br>
<br>
#### Main assumptions for 2050 electric mix
- Shut down of **coal** power plants.
- Shut down of **nuclear** power plants.
- Cogeneration power reduced from 5.74 GW (2018) to **1.44 GW** (2050).
- Fuel & gas power reduced form 2.49 GW (2018) to **0.62 GW** (2050), a 75% reduction.
- New solar thermal power plants have **15-hour** thermal storage capacity with a **90%** of storage efficiency.
- Pumped hydropower increased from 3.3 GW (2018) to **10 GW** (2050).
- Pumped hydropower capacity increased from 14 GWh (2018) to **42.4 GWh** (2040) with a **76%** of storage efficiency.
- Electric batteries with **10 GW** of power and **40 GW** of capacity.
- **0.5%** annual demand increment from 2018 to 2030 and **1.5%** from 2030 to 2050.
- **80%** emission reduction with respect to 1990.
<br>
<br>
