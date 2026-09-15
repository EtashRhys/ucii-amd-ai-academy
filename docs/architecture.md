# Architecture

## Intended boundary

```text
AMD Developer Cloud / AMD GPU / ROCm workload
                    |
                    v
          Structured proposed action
                    |
                    v
              UCII public boundary
        identity / verification / authority
                    |
             ALLOW or DENY
                    |
                    v
        Deterministic consequential executor
                    |
                    v
             Provenance / evidence
```

## Authority model

AMD provides compute. The model provides reasoning/capability. Neither is an authority source.

The autonomous workload may propose an action, but consequential execution must depend on independently established UCII state.

The intended invariant is:

**AI proposes → UCII verifies and authorizes → deterministic executor enforces.**

## UCII integration discipline

- Use UCII through its public API/SDK boundary.
- Do not copy UCII core implementation into this repository.
- Keep identity verification separate from authorization.
- Keep authorization separate from execution.
- Keep payment/economic authority separate if introduced later.
- Preserve revocation as an independent authority-state transition.
- Record enough provenance to distinguish proposal, decision, and execution.

## AMD integration discipline

The final system must use AMD technology as a genuine execution substrate rather than decorative infrastructure. Experiments should identify and record the actual AMD GPU/runtime/framework surface used and how it affects the workload.

## Evolution rule

This architecture is a stable boundary, not a commitment to one model or one Academy challenge. The AMD workload can evolve as the program reveals better technical opportunities while the UCII authority separation remains intact.
