# Grain

Locus works with the grain of the host platform.

1. Common code owns application semantics, not pixels.
2. Native toolkits own native presentation.
3. Platform divergence is permitted when platform convention demands it.
4. State transitions are deterministic and single-writer.
5. External work crosses the application boundary as typed effects.
6. Effect results return as typed actions.
7. Platform capabilities are explicit dependencies.
8. Shared renderers are not a portability mechanism.
9. Fixtures consume public framework surfaces; local compatibility shims are forbidden.
10. Abstractions are introduced only after concrete implementations demand them.
