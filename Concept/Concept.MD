## Pillars of System Design


| Pillar          | Focus Area                          |
|-----------------|-------------------------------------|
| Scalability     | Growth in users/data/traffic        |
| Reliability     | Fault tolerance, redundancy         |
| Performance     | Latency, throughput, efficiency     |
| Maintainability | Ease of updates and debugging       |
| Availability    | Uptime and SLA guarantees           |
| Security        | Protecting data and access          |
| Cost Efficiency | Optimizing resources vs. expenses   |
| Flexibility     | Adapting to new requirements        |
| Observability   | Monitoring and troubleshooting      |
 -------------------------------------------------------

                          ┌───────────────────────────┐
                          │       Observability       │
                          │ (Monitoring, Logging, APM)│
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │        Security           │
                          │ (Auth, Encryption, Audit) │
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │     Availability          │
                          │   (Uptime, SLA, Failover) │
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │      Reliability          │
                          │ (Fault tolerance, Redund.)│
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │      Scalability          │
                          │ (Horizontal/Vertical grow)│
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │      Performance          │
                          │ (Latency, Throughput, QoS)│
                          └─────────────▲─────────────┘
                                        │
                          ┌─────────────┴─────────────┐
                          │     Maintainability       │
                          │ (Modularity, Extensibility│
                          │   Documentation, Testing) │
                          └───────────────────────────┘


🏛️## Explanation
   - Base Layer (Maintainability) → Without maintainability, systems become brittle and hard to evolve.
   - Performance & Scalability → Ensure the system can handle load efficiently and grow with demand.
   - Reliability & Availability → Keep the system functioning correctly and accessible even under failures.
   - Security → Protect data and access at every layer.
   - Observability → Provide visibility into system health and behavior for continuous improvement.
