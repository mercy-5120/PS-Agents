# ICS 3202: Artificial Intelligence — Practical Exercise 3
## Designing a Searching Agent

---

## Question 1: PEAS Framework and the 5 Definitions of Agent Environments

### PEAS Description of the Self-Driving Trailer Agent

| **Component** | **Description** |
| :--- | :--- |
| **P — Performance Measure** | Safety (no accidents or collisions), timely arrival at the destination, minimal fuel consumption, shortest travel distance, obedience to traffic rules, and smooth driving |
| **E — Environment** | Kenya's highway network covering the Nairobi, Central Highlands, Rift Valley, and Lake Victoria Basin regions — including roads, cities and towns, traffic conditions, weather, and other road users |
| **A — Actuators** | Steering wheel, accelerator and brake, gearbox, indicators, horn, and headlights |
| **S — Sensors** | GPS, cameras, LiDAR, radar, speedometer, accelerometer, fuel sensor, and rain sensor |

### The 5 Definitions of the Agent's Environment

1. **Partially Observable** — The agent cannot perceive the entire highway network at once. It cannot directly see distant traffic jams, sudden weather changes, or hazards beyond its sensor range, so it must operate on partial information.

2. **Stochastic** — The environment is not fully predictable. Traffic flow, weather conditions, and the behaviour of other drivers are uncertain, so the same action may not always produce the same outcome.

3. **Sequential** — The agent's current decision (for example, which route to take at Nakuru) affects all future states and the final arrival time. Decisions are linked rather than independent.

4. **Dynamic** — The environment changes while the agent is still deciding. Traffic moves, weather shifts, and other vehicles act, so the agent must continuously sense and react.

5. **Continuous** — Speed, position, and time are continuous variables rather than discrete values. The agent must handle a continuous state and action space.

---