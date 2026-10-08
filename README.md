# Simulation-Based Performance and Energy Efficiency Analysis of a Centrifugal Pump Using Aspen HYSYS

## Project Overview

This project presents a simulation-based performance analysis of a centrifugal pump using Aspen HYSYS 11. The study investigates the influence of operating conditions on pump performance and energy consumption through a series of sensitivity analyses.

A steady-state centrifugal pump model was developed using water as the working fluid. Various operating parameters including temperature, flow rate, discharge pressure, and pump efficiency were systematically varied to evaluate their effects on pump head, power consumption, and specific energy consumption. 

## Objectives

- Develop a centrifugal pump model in Aspen HYSYS 11.
- Establish a reference base case.
- Study the effect of fluid temperature on pump performance.
- Study the effect of flow rate on pump power consumption.
- Study the effect of discharge pressure on pump head and power requirements.
- Evaluate the influence of pump efficiency on energy consumption.
- Calculate specific energy consumption (SEC).
- Develop engineering recommendations based on simulation results. 

## Software Used

- Aspen HYSYS 11
- Microsoft Excel
- GitHub

## Base Case Conditions

| Parameter | Value |
|------------|---------|
| Fluid | Water |
| Flow Rate | 10,000 kg/h |
| Inlet Temperature | 30 °C |
| Inlet Pressure | 1 bar |
| Outlet Pressure | 5 bar |
| Pressure Rise | 4 bar |
| Pump Efficiency | 70 % |
| Pump Head | 40.64 m |
| Pump Power | 1.582 kW |



## Process Flowsheet

The simulation model consists of a water feed stream connected to a centrifugal pump with an associated energy stream for calculating power requirements.



Source: Simulation-Base Performance and Energy Efficiency Analysis of a Centrifugal Pump Under Varying Condition Using Aspen HYSYS.pdf. 

## Methodology

A one-variable-at-a-time sensitivity analysis approach was employed.

### Temperature Study
- Range: 20 °C to 60 °C

### Flow Rate Study
- Range: 5,000 kg/h to 20,000 kg/h

### Discharge Pressure Study
- Range: 3 bar to 7 bar

### Pump Efficiency Study
- Range: 50 % to 90 %

During each analysis, all other operating conditions were maintained constant. 

## Key Findings

### Effect of Temperature

- Pump power increased from 1.57 kW to 1.62 kW.
- Temperature showed a relatively small impact on power demand.



### Effect of Flow Rate

- Pump power increased from 0.7908 kW to 3.1633 kW.
- Pump head remained approximately constant at 40.64 m.



### Effect of Discharge Pressure

- Pump head increased from 20.32 m to 60.96 m.
- Pump power increased from 0.7908 kW to 2.3724 kW.

【1-5fc0ad】

### Effect of Pump Efficiency

- Increasing efficiency from 50 % to 90 % reduced power consumption from 2.2143 kW to 1.2301 kW.
- Specific energy consumption decreased by approximately 44.4%.



## Specific Energy Consumption

| Efficiency | Power (kW) | SEC (kWh/tonne) |
|------------|------------|-----------------|
| 50 % | 2.2143 | 0.22143 |
| 60 % | 1.8452 | 0.18452 |
| 70 % | 1.5820 | 0.15820 |
| 80 % | 1.3839 | 0.13839 |
| 90 % | 1.2301 | 0.12301 |



## Engineering Recommendations

- Operate pumps near their optimal efficiency range.
- Avoid excessive discharge pressure.
- Avoid unnecessary high flow rates.
- Monitor pump power and specific energy consumption regularly.
- Include manufacturer pump curves and NPSH analysis during actual pump selection.



## Project Outcomes

This study demonstrates how operating conditions and pump efficiency affect centrifugal pump performance and energy consumption. The project provides a practical simulation framework for preliminary pump analysis and energy optimization using Aspen HYSYS. 【1-5fc0ad】



Chemical Engineer

Institute of Chemical Engineering

Quaid-e-Awam University of Engineering, Science & Technology (QUEST), Nawabshah

Pakistan
