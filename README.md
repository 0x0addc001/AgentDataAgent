# AgentDataAgent

**An Agent that curates the data supply for an Agent-native engineering system.**

AgentDataAgent turns noisy multi-source material into versioned, verifiable training assets and routes evaluation failures back into the next collection cycle.

用 Agent 托管 Agent 全流程中的数据供给：将多源噪声转化为可验证、可追溯的训练资产，并把评测失败回流为下一轮数据修订。

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | Source inventory, collection plans, cleanup, synthesis, versioned release |
| Model | Coverage classifiers and quality critics |
| Training | Data selection policies learned from downstream results |
| Inference | Slice-aware quality scoring at pipeline speed |
| Harness | Source, license, privacy, deduplication, and rollback tools |
| Eval | Coverage, leakage, agreement, freshness, and downstream impact |

## System contract

- Every admitted sample carries provenance and an admission reason.
- Every release is reproducible, auditable, and reversible.
- Evaluation failures become targeted collection or repair tasks.

## Engineering principles

- Treat data quality as a slice-level property.
- Keep privacy and contamination gates deterministic.
- Optimize the dataset for downstream evidence, not raw volume.

