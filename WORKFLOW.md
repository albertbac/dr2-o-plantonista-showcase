# Workflow

## High-level functional workflow
1. Start or open shift
2. Capture patient events
3. Review patient-centered summary
4. Prepare structured handoff
5. Close shift or continue care flow

```mermaid
    flowchart TD
        S1["Start or open shift"]
    S2["Capture patient events"]
    S3["Review patient-centered summary"]
    S4["Prepare structured handoff"]
    S5["Close shift or continue care flow"]
    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
