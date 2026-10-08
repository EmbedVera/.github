# EmbedVera

**Evidence-driven CAN investigation for automotive and embedded engineers.**

EmbedVera is building a practical investigation workflow for real engineering issues:

```text
Problem report
    + CAN log
    + DBC
    + requirements / engineering context
        ↓
Hypotheses
        ↓
Deterministic checks
        ↓
Evidence
        ↓
Supported finding
        ↓
Unknowns + next investigation
```

The goal is not to guess a root cause. The goal is to help engineers move from a customer symptom to a traceable, evidence-backed investigation.

## Public engineering projects

### [can-log-toolkit](https://github.com/EmbedVera/can-log-toolkit)

Small, transparent utilities for deterministic CAN log inspection.

Current focus:

- ASC timing statistics;
- cycle-time anomalies;
- reproducible examples;
- deterministic analysis before generative reasoning.

### [can-debug-benchmark](https://github.com/EmbedVera/can-debug-benchmark)

Synthetic and redistributable CAN debugging cases for evaluating analysis tools and AI engineering agents.

The benchmark explicitly separates:

- observation;
- supported finding;
- requirement violation;
- unknown;
- root cause.

A tool should lose points for inventing a signal, requirement, or root cause that the evidence does not support.

## What stays private

Customer data and the core EmbedVera investigation runtime are not published here.

The public repositories focus on useful, reproducible engineering building blocks:

- tools;
- samples;
- benchmarks;
- evaluation cases;
- engineering methods.

## Product

For evidence-driven investigation of CAN issues using logs, DBCs, specifications, and engineering context:

**https://embedvera.com/**

---

## 中文

EmbedVera 面向汽车与嵌入式工程师，目标是把客户问题、CAN Log、DBC、功能规范和工程上下文组织成一条可追溯的工程调查链。

公开 GitHub 仓库主要提供可复现的基础工具、合成案例和 Benchmark（基准测试）；客户数据和 EmbedVera 核心调查运行时保持私有。
