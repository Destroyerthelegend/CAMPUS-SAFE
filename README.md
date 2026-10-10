# CAMPUS-SAFE
Priority-Based Emergency Communication and Alert System
Using a Wireless Mesh Network.
 
## Objective
CAMPUS-SAFE simulates an emergency communication network where
critical SOS messages receive priority treatment and routing
adapts when network nodes or links fail.
 
## Main features
- Packet/message model with priority and TTL
- Wireless mesh topology with stateful links
- Dijkstra-based shortest-path routing
- AODV-inspired route invalidation and recomputation
- Priority queueing with finite buffers and aging
- Link delay and packet-loss simulation
- Node/link failure injection and alternate-route recovery
- ACK-based delivery measurement
- PDR, delay, hop count and throughput metrics
 
## Run
    python experiments/run_experiment.py
 
## Review 2 scope
The current implementation focuses on the network simulation core.
Dashboard, distributed UDP nodes, store-and-forward behaviour,
mobility and optional ESP32/LoRa integration are reserved for
Review 3.
 
## Team
- Kavin   (24BCE2722): topology, routing, failure recovery
- Prithvi (24BCE2778): queueing, channel model, metrics, experiments
