# Validation Notes

- Ответы Map AI ДОЛЖНЫ быть строго JSON по схеме из `map.yml`.
- `narration`: 1–2 предложения, понятный язык.
- `actions`: массив команд с `type` и `args`.
- `annotations`: `note|warn|tip`.
- `telemetry`: содержит `intent` и `confidence ∈ [0,1]`.
