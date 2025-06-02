<pre><code class="language-mermaid">
graph TD
    A[Designer] --> B[Rara_GateRune<br/>(ScriptableObject)]
    A --> C[RaRa_GateCombination<br/>(ScriptableObject)]
    C --> D[GateController<br/>(State Machine)]
    D --> E[RunePlate<br/>(Plate Logic)]
    F[Player] --> G[RuneBlock<br/>(Rune Data)]
    G --> E
    E --> H[GateEventSystem<br/>(Event Bus)]
    H --> D
    D --> I[Gate<br/>(Door Logic)]
</code></pre>
