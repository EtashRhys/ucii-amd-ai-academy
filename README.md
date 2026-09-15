# UCII AMD AI Academy Lab

A long-running AMD/ROCm learning and experimentation lab for UCII-governed autonomous AI.

The project explores how autonomous workloads running on AMD infrastructure can remain independently governed by UCII cryptographic identity, bounded delegated authority, revocation, provenance, and fail-closed execution controls.

## Core principle

**Capability ≠ Identity ≠ Authority ≠ Execution**

AMD provides the compute and AI execution surface. UCII provides the independent identity and authority boundary around consequential actions.

## Program context

This repository supports participation in the Lablab x AMD AI Academy Challenge as a solo `UCII Labs` project.

The repository is intentionally broader than a single final submission. It is the place to:

- complete AMD/ROCm learning work;
- run AMD Developer Cloud experiments;
- document setup, performance, and friction;
- participate in Academy challenges;
- prototype UCII-governed autonomous workloads;
- collect evidence and lessons that improve later UCII integrations;
- evolve toward a polished final Academy submission.

## Current status

**FOUNDATION READY — NO APPLICATION IMPLEMENTATION YET**

The immediate next step is to verify the current Academy challenge structure, infrastructure, points/rewards, deadlines, and submission rules before selecting the first implementation objective.

## Repository map

- `docs/challenge-requirements.md` — living Academy rules and compliance ledger
- `docs/project-concept.md` — project thesis and durable value
- `docs/architecture.md` — intended technical boundaries
- `docs/implementation-plan.md` — staged engineering plan
- `docs/academy-strategy.md` — learning, challenge, XP, and submission strategy
- `docs/infrastructure.md` — AMD cloud/ROCm infrastructure notes and cost controls
- `docs/friction-log.md` — product/setup friction observed during the program
- `docs/product-feedback.md` — structured AMD product feedback
- `docs/submission-checklist.md` — final submission readiness checklist

## Engineering cadence

Use the same bounded workflow throughout:

**inspect → reason → one bounded change → targeted verification → diff/review → commit → checkpoint**

Do not inflate the project with speculative features. Real AMD execution evidence and clean UCII authority boundaries matter more than surface complexity.
