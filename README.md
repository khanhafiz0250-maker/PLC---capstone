# Counter-Based Indicator Light Control Using PLC

## Project Overview

This project implements a counter-based indicator light control system using a Mitsubishi FX5U Programmable Logic Controller (PLC). The system turns the indicator light ON when the count reaches 5 and OFF when it reaches 10, then resets the counter automatically for the next cycle.

## Features

- Single-input pulse counting
- Automatic indicator light control
- ON threshold at count 5
- OFF threshold at count 10
- Automatic counter reset
- Manual reset push button
- Ladder logic programming
- PLC simulation and testing

## Technologies Used

- Mitsubishi FX5U PLC
- MELSOFT GX Works3
- GX Simulator3
- PLC Ladder Logic

## Input and Output Mapping

| Device | Function |
|---|---|
| X0 | Counting pulse input |
| X1 | Manual reset push button |
| D0 | Counter data register |
| M0 | Automatic reset flag |
| Y0 | Indicator light output |

## Working Principle

1. Each pulse received at input X0 increments the counter register D0.
2. When the count reaches 5, output Y0 turns ON.
3. The indicator remains ON for counts 5 through 9.
4. When the count reaches 10, the automatic reset sequence clears D0.
5. The indicator turns OFF, and a new counting cycle begins.
6. Input X1 allows the operator to reset the counter manually.

## Project Documentation

The project report includes the introduction, literature survey, feasibility study, project planning, system diagrams, ladder logic, simulation results, future scope and conclusion.

## Future Scope

- Adjustable counting thresholds
- Sensor-based counting
- HMI and SCADA integration
- Multi-stage indicator control
- Power-failure count retention

## Author and Team

Add your actual team members, enrollment numbers, project guide and department details here.

## References

Refer to the technical manuals and academic references listed in the project report.
