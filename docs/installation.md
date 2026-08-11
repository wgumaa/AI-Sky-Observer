# Installation

## Requirements

Before installing AI Sky Observer you will need:

- Home Assistant
- LLM Vision
- At least one outdoor camera
- An LLM provider (OpenAI, Gemini, Ollama, etc.)

---

## Installation

1. Download the package.
2. Copy `ai_sky_observer.yaml` into:

```
config/packages/
```

3. Enable packages in `configuration.yaml`.

4. Restart Home Assistant.

5. Reload YAML.

---

## Dashboard

Import the example dashboard from:

```
examples/dashboard.yaml
```

---

## Enable the Observer

Turn on:

AI Sky Observer Enabled

---

## Verify Installation

You should now see:

- AI Sky Observer Cloud Cover
- AI Sky Observer Condition
- Entry Cloud Cover
- Garden Cloud Cover
- Entry Confidence
- Garden Confidence