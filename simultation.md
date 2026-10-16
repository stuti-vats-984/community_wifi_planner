# Dabba-style community WiFi planner

A working model of what Dabba is building: a network of home-hosted nodes that share the airwaves. Place nodes, see coverage, and compare standard sharing (OMA) with NOMA, which pairs a near and a far user on the same channel. Built by Stuti Vats.

Node transmit power NOMA power given to near user Target speed per home Colour homes by

Click empty space to place a node. Drag a node to move it. Double-click a node to remove it. Green homes meet the target speed, red ones don't.

Average speed, OMA

Average speed, NOMA

Outage, OMA (below target)

Outage, NOMA (below target)

## Outage probability

Monte Carlo over 300 rounds of Rayleigh fading. The vertical line is your target speed.

## Node health

## Fleet telemetry

Packet retry rate per node. A rolling z-score flags anything abnormal.

No alerts yet.

## Where my background fits

- **NOMA and outage analysis**My THz UAV relaying project derives outage probability. Here the same idea runs as a Monte Carlo simulation.
- **Embedded bring-up**At Cusmat I wrote C/C++ for microcontrollers and tested hardware. Each node here is that kind of device.
- **RISC-V and FPGA at the edge**My DIR-V design processes data on the device. Nodes could pre-filter telemetry the same way.
- **Monitoring and analytics**At Netradyne I analyse telematics at scale in Python and SQL. The panel above applies that to node health.

This is a simulation with simplified physics, not real firmware.