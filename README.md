# EDCA-OS · Expression-Driven Cognitive Architecture

A next-generation AI operating framework for **deterministic, auditable, expression-driven intelligence**.

> This repository is the **public architecture anchor**, documentation hub, and ecosystem index for EDCA-OS.  
> All runtime implementations (SBE, SRP, SROE, ERB, ACL rules, semantic hashes, etc.) remain **proprietary**.

---

## Overview

Modern large language models (LLMs) are excellent **prediction engines**, but weak as **decision systems**:

- no behavioral stability  
- no determinism  
- no semantic-layer safety  
- no chain-of-thought auditability  
- no robust multi-step task consistency  

**EDCA-OS** (Expression-Driven Cognitive Architecture OS) is a framework that replaces prompt-driven randomness with:

- **structured expression control**
- **deterministic behavioral paths**
- **auditable reasoning and execution traces**

Instead of “prompting a model”, EDCA-OS treats **expression as behavior**:  
LLMs no longer *guess* intent — they *execute* an intent structure.

---

## Architecture at a Glance

High-level protocol stack (public-safe view):

```text
EDCA-OS
├── L0: Cold-Start Protocol (CSP)
├── L1: Alignment Core Protocol (ACP)
├── L2: Task Chain Protocol (TCEP)
├── L3: Micro-Task Protocols
├── L4: SROE – Structured Reasoning Override Engine
├── L5: Context Audit Layer (CAL)
└── Runtime Surface:
      ├── SBE – Structured Behavior Executor
      ├── SRP – Structured Retrieval Protocol
      ├── EMC – Externalized Memory Capsule
      └── GRS – Graph-Route Scheduler
