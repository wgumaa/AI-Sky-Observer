<p align="center">
  <img src="images/banner.png" alt="AI Sky Observer Banner">
</p>

# AI Sky Observer

> AI-powered local sky observation for Home Assistant using LLM Vision.

---

## Overview

AI Sky Observer transforms one or more outdoor cameras into intelligent local sky sensors for Home Assistant.

Instead of relying solely on internet weather forecasts, AI Sky Observer analyses the sky directly above your property using AI image analysis and creates reliable Home Assistant sensor entities that can be used in automations, dashboards, scripts and blueprints.

Whether you're protecting blinds from direct sunlight or building smarter weather-aware automations, AI Sky Observer provides observations based on what is happening **above your home right now**, not at the nearest weather station.

---

## Why Use AI Sky Observer?

Weather services provide regional forecasts.

AI Sky Observer provides **local observations**.

Using one or more outdoor cameras, it estimates:

- ☁️ Cloud Cover
- ☀️ Direct Sun Visibility
- 🎯 AI Confidence
- 📷 Per-camera Analysis

The result is more accurate automation based on the actual conditions at your property.

---

## Features

- ☁️ AI Cloud Cover Estimation
- ☀️ Direct Sun Detection
- 🎯 Confidence Scoring
- 📷 Multi-camera Support
- 🌞 Daylight-aware Analysis
- 🏡 Native Home Assistant Sensors
- 🤖 Compatible with any LLM Vision provider
- ⚡ Designed for Home Assistant automations

---

## Dashboard

<p align="center">
  <img src="images/dashboard.png" alt="AI Sky Observer Dashboard" width="900">
</p>

The included dashboard provides:

- Sky Condition
- Average Cloud Cover
- Per-camera Cloud Cover
- Sun Visibility
- Confidence Scores
- Last Analysis Time

---

## Sensors

The package creates the following Home Assistant entities:

| Entity | Description |
|---------|-------------|
| AI Sky Observer Cloud Cover | Average cloud cover across all configured cameras |
| AI Sky Observer Condition | AI-derived sky condition |
| Entry Cloud Cover | Cloud cover from the entry camera |
| Garden Cloud Cover | Cloud cover from the garden camera |
| Entry Confidence | AI confidence score |
| Garden Confidence | AI confidence score |
| Entry Sun Visible | Direct sun detected |
| Garden Sun Visible | Direct sun detected |

---

## Requirements

- Home Assistant
- LLM Vision
- One or more outdoor cameras
- Any supported LLM Vision provider

Compatible providers include:

- Google Gemini
- OpenAI
- Anthropic
- Ollama
- LocalAI
- and many more

---

## Works Well With

### Adaptive Cover Controller

AI Sky Observer was built to complement **Adaptive Cover Controller**.

Instead of relying solely on weather forecasts, Adaptive Cover Controller can use real-time AI observations of cloud cover and direct sun visibility from your own cameras for more accurate cover positioning.

➡️ https://github.com/wgumaa/Adaptive-Cover-Controller

---

## Documentation

Additional documentation can be found in the **docs** folder.

- 📖 Installation Guide
- 🖥 Dashboard Guide
- ❓ FAQ
- 🛣 Roadmap

---

## Project Status

🚧 **Active Development**

Current version:

**v0.1.0**

Suggestions, bug reports and feature requests are always welcome.

---

## Roadmap

### Weather Observation

- 🌤 Improved Sky Classification
- 📈 Sky Brightness Estimation
- 🌧 Rain Detection
- ❄️ Snow Detection
- 🌫 Fog Detection
- 🔥 Smoke Detection

### Camera Health

- 🕸 Spider Web Detection
- 🧼 Dirty Lens Detection
- 📷 Camera Health Monitoring

### Future

- Multiple Observation Zones
- Historical Sky Statistics
- Trend Analysis
- Additional AI Environmental Sensors

---

## Contributing

Contributions are welcome.

If you find a bug, have an idea for a new feature, or want to improve the project, feel free to open an Issue or submit a Pull Request.

---

## License

This project is released under the MIT License.