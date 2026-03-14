---
name: detect_suspicious_listing
description: Detect suspicious or risky used-car listings
---

# Risk Signals
Flag listings if:
- price far below market
- vague description
- missing key information
- contradictory details
- duplicate listings
- suspicious seller behavior

# Risk Levels
- low
- medium
- high

# Output
Provide:
- risk_level
- risk_reason