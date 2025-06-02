```mermaid
graph TD
    A[Designer] --> B[Rara_GateRune (SO)]
    A --> C[RaRa_GateCombination (SO)]
    C --> D[GateController (State Machine)]
    D --> E[RunePlate (Plate Logic)]
    F[Player] --> G[RuneBlock (Rune Data)]
    G --> E
    E --> H[GateEventSystem (Event Bus)]
    H --> D
    D --> I[Gate (Door Logic)]
```
