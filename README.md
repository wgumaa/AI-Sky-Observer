<p align="center">
  <img src="images/banner.png" alt="AI Sky Observer Banner">
</p>

<h1 align="center">☁️ AI Sky Observer</h1>

<p align="center">
AI-powered local sky observation for Home Assistant using LLM Vision.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v0.1.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Home%20Assistant-Compatible-41BDF5.svg" alt="Home Assistant">
</p>

---

## Overview

AI Sky Observer transforms one or more outdoor cameras into intelligent local weather sensors.

Instead of relying solely on internet weather forecasts, AI Sky Observer analyses the sky directly above your property using AI image analysis, providing real-time environmental observations that Home Assistant can use for automations.

---

## Features

- ☁️ AI Cloud Cover Estimation
- ☀️ Direct Sun Visibility Detection
- 🎯 Analysis Confidence Score
- 📷 Multi-camera Support
- 🌞 Daylight-only AI Analysis
- 🏡 Native Home Assistant Sensors
- 🤖 Compatible with any LLM Vision provider

---

## Dashboard

<p align="center">
  <img src="images/dashboard.png" alt="Dashboard Screenshot" width="850">
</p>

The included dashboard provides:

- Sky Condition
- Overall Cloud Cover
- Per-camera Cloud Cover
- Sun Visibility
- Confidence Scores
- Last Analysis Time

---

## Design Philosophy

AI Sky Observer follows one simple principle.

> **AI observes. Home Assistant decides.**

The AI never controls devices directly.

Instead, it creates reliable Home Assistant sensors that can be used by automations, scripts, dashboards and blueprints.

---

## Available Sensors

The package creates sensors including:

- AI Sky Observer Cloud Cover
- AI Sky Observer Condition
- Entry Cloud Cover
- Garden Cloud Cover
- Entry Confidence
- Garden Confidence
- Entry Sun Visible
- Garden Sun Visible

---

## Requirements

- Home Assistant
- LLM Vision
- At least one outdoor camera
- Any LLM Vision compatible provider
  - Google Gemini
  - OpenAI
  - Ollama
  - Anthropic
  - LocalAI
  - ...and others

---

## Documentation

- 📖 Installation Guide
- 🖥 Dashboard
- ❓ Frequently Asked Questions
- 🛣 Roadmap

---

## Project Status

🚧 **Active Development**

Current release:

**v0.1.0**

---

## Roadmap

Planned features include:

- 🌤 Sky Condition Classification
- 📈 Sky Brightness Estimation
- 🌧 Rain Detection
- ❄️ Snow Detection
- 🌫 Fog Detection
- 🔥 Smoke Detection
- 🕸 Spider Web Detection
- 🧼 Dirty Lens Detection
- 🚧 Camera Health Monitoring

---

## License

Released under the MIT License.