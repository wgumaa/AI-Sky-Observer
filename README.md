<p align="center">
  <img src="images/banner.png" alt="AI Sky Observer Banner">
</p>

<h1 align="center">AI Sky Observer</h1>

<p align="center">
AI-powered local sky observation for Home Assistant using LLM Vision.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v0.1.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Home%20Assistant-Compatible-41BDF5.svg" alt="Home Assistant">
  <img src="https://img.shields.io/badge/LLM%20Vision-Supported-purple.svg" alt="LLM Vision">
  <img src="https://img.shields.io/badge/AI-Powered-orange.svg" alt="AI Powered">
</p>

---

# Overview

AI Sky Observer transforms one or more outdoor cameras into intelligent local sky sensors for Home Assistant.

Instead of relying solely on internet weather forecasts, AI Sky Observer analyses the sky directly above your property using AI image analysis. It creates reliable Home Assistant sensor entities that can be used by automations, scripts, dashboards and blueprints.

Whether you're protecting blinds from direct sunlight, monitoring changing weather conditions or building smarter automations, AI Sky Observer provides observations based on what is happening **above your home right now**, not at the nearest weather station.

---

# Why AI Sky Observer?

Traditional weather services provide regional forecasts.

AI Sky Observer provides **local observations**.

Using AI image analysis, your cameras become intelligent sky sensors capable of estimating:

- ☁️ Cloud Cover
- ☀️ Direct Sun Visibility
- 🎯 AI Confidence Scores
- 📷 Per-Camera Analysis

This makes AI Sky Observer ideal for automations that depend on the actual conditions at your property.

---

# Features

- ☁️ AI Cloud Cover Estimation
- ☀️ Direct Sun Detection
- 🎯 AI Confidence Scoring
- 📷 Multi-Camera Analysis
- 🌞 Daylight-Aware Operation
- 🏡 Native Home Assistant Sensors
- 🤖 Compatible with any LLM Vision provider
- ⚡ Designed for Home Assistant automations and blueprints

---

# Dashboard

<p align="center">
  <img src="images/dashboard.png" alt="Dashboard Screenshot" width="900">
</p>

The included dashboard displays:

- Current Sky Condition
- Average Cloud Cover
- Per-Camera Cloud Cover
- Sun Visibility
- AI Confidence Scores
- Last Analysis Time

---

# Design Philosophy

AI Sky Observer follows one simple principle:

> **Observe locally. Automate intelligently.**

The AI never controls your home.

Instead, it creates reliable Home Assistant sensor entities that your automations can use to make better decisions.

In short:

> **AI observes. Home Assistant decides.**

---

# Available Sensors

| Sensor | Description |
|---------|-------------|
| AI Sky Observer Cloud Cover | Average cloud cover across all configured cameras |
| AI Sky Observer Condition | Current AI-derived sky condition |
| Entry Cloud Cover | Cloud cover estimated from the entry camera |
| Garden Cloud Cover | Cloud cover estimated from the garden camera |
| Entry Confidence | Confidence score for the entry camera |
| Garden Confidence | Confidence score for the garden camera |
| Entry Sun Visible | Direct sun detected by the entry camera |
| Garden Sun Visible | Direct sun detected by the garden camera |

---

# Requirements

- Home Assistant
- LLM Vision
- One or more outdoor cameras
- Any supported LLM Vision provider

Supported providers include:

- Google Gemini
- OpenAI
- Anthropic
- Ollama
- LocalAI
- ...and many more

---

# Works Great With

## Adaptive Cover Controller

AI Sky Observer was designed to complement **Adaptive Cover Controller**.

Instead of relying solely on weather forecasts, Adaptive Cover Controller can use real-time AI observations of cloud cover and direct sun visibility from your own cameras, allowing cover movements to better reflect the actual conditions at your property.

Learn more:

https://github.com/wgumaa/Adaptive-Cover-Controller

---

# Documentation

Complete documentation is available in the **docs** folder.

- 📖 Installation Guide
- 🖥 Dashboard Guide
- ❓ Frequently Asked Questions
- 🛣 Roadmap

---

# Project Status

🚧 **Active Development**

Current Release:

**v0.1.0**

Feedback, feature requests and contributions are always welcome.

---

# Roadmap

## Weather Intelligence

- 🌤 Improved Sky Classification
- 📈 Sky Brightness Estimation
- 🌧 Rain Detection
- ❄️ Snow Detection
- 🌫 Fog Detection
- 🔥 Smoke Detection

## Camera Health

- 🕸 Spider Web Detection
- 🧼 Dirty Lens Detection
- 📷 Camera Health Monitoring

## Future Ideas

- Multiple Observation Zones
- Historical Sky Statistics
- Trend Analysis
- Environmental AI Sensors

---

# Contributing

Bug reports, feature requests and pull requests are welcome.

If you have an idea that would make AI Sky Observer even better, feel free to open an Issue or start a Discussion.

---

# License

This project is released under the MIT License.