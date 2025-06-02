```mermaid
graph TD
    A[Designer] --> B[Rara_GateRune (SO)]
    A --> C[RaRa_GateCombination (SO)]
    C --> D[GateController (StateMachine)]
    D --> E[RunePlate (Logic)]
    F[Player] --> G[RuneBlock (Data)]
    G --> E
    E --> H[GateEventSystem (Events)]
    H --> D
    D --> I[Gate (Final Trigger)]
```
