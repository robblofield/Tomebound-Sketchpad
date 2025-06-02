```mermaid
graph TD
    A[Designer] --> B[Rara_GateRune\n(ScriptableObject)]
    A --> C[RaRa_GateCombination\n(ScriptableObject)]
    C --> D[GateController\n(State Machine)]
    D --> E[RunePlate\n(Plate Logic)]
    F[Player] --> G[RuneBlock\n(Rune Data)]
    G --> E
    E --> H[GateEventSystem\n(Event Bus)]
    H --> D
    D --> I[Gate\n(Door Logic)]
```
