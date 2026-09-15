# Project Concept

## Thesis

UCII AMD AI Academy Lab is a long-running environment for learning, experimenting, and producing evidence about UCII-governed autonomous AI on AMD infrastructure.

It is intentionally not limited to one final application idea. The Academy program gives us time to learn the AMD stack, test real workloads, participate in challenges, measure friction, and let evidence determine the strongest final submission.

## Core separation

**Capability ≠ Identity ≠ Authority ≠ Execution**

An AMD-backed model or agent may be highly capable. That capability does not establish who the actor is or whether it currently has permission to perform a consequential action.

UCII's role is to provide an independent cryptographic identity and authority boundary around the AI execution surface.

## Long-term canonical proof

A strong mature Academy artifact should be capable of demonstrating:

1. an autonomous workload executes on genuine AMD-backed infrastructure;
2. the actor is bound to a UCII identity;
3. a consequential action is proposed;
4. verified identity without matching authority fails closed;
5. a human establishes narrowly bounded delegated authority;
6. the same actor can execute only within that authority;
7. authority can be revoked independently of identity;
8. a fresh check denies the same action after revocation;
9. the complete sequence is attributable through provenance.

## Academy-specific value

Unlike the short ACT III build window, this repository should accumulate longitudinal evidence:

- AMD/ROCm learning outcomes;
- reproducible GPU experiments;
- model/runtime comparisons where useful;
- infrastructure setup and operational lessons;
- challenge participation;
- performance and reliability observations;
- authority/security experiments;
- product friction and feedback;
- reusable integration patterns for UCII.

## Non-goals

- Reimplement UCII in this repository.
- Treat AMD infrastructure as an authority source.
- Treat model reasoning as authorization.
- Copy the ACT III competition application into this project.
- Add SaaS dependencies merely to increase apparent complexity.
- Optimize for leaderboard points at the expense of technically meaningful work.
