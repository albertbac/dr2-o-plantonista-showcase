# Workflow

## High-level functional workflow
1. Start or open shift
2. Capture patient events
3. Review patient-centered summary
4. Prepare structured handoff
5. Close shift or continue care flow

```mermaid
    flowchart TD
        W1["Start or open shift"]
    W2["Capture patient events"]
    W3["Review patient-centered summary"]
    W4["Prepare structured handoff"]
    W5["Close shift or continue care flow"]
    W1 --> W2
    W2 --> W3
    W3 --> W4
    W4 --> W5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
