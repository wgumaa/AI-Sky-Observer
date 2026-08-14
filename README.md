<p align="center">
  <img src="images/banner.png" alt="AI Sky Observer">
</p>

# AI Sky Observer

> AI-powered local sky observation for Home Assistant using LLM Vision.

AI Sky Observer uses one or more outdoor cameras together with LLM Vision to estimate cloud cover and direct sun visibility from the sky above your home.

Unlike online weather services that report conditions across a wider region, AI Sky Observer creates Home Assistant entities based on what your cameras actually observe, allowing automations to react to local conditions rather than forecasts.

> [!NOTE]
> **AI-assisted development**
>
> This project was developed using AI as an engineering tool - not as a replacement for engineering.
>
> AI assisted with brainstorming, code reviews, documentation and iterative refinement, while all architectural decisions, implementation choices and real-world testing were carried out by the project author.

## Features

- AI cloud cover estimation
- Direct sun visibility detection
- Confidence scoring for each observation
- Multi-camera support
- Daylight-aware analysis
- Native Home Assistant entities
- Compatible with any LLM Vision provider
- Optional Home Assistant dashboard

## Dashboard

<p align="center">
  <img src="images/dashboard.png" alt="AI Sky Observer Dashboard" width="900">
</p>

An example dashboard is included with the project and provides an overview of the current observations.

It displays:

- Overall sky condition
- Average cloud cover
- Camera 1 cloud cover
- Camera 2 cloud cover
- Camera 1 sun visibility
- Camera 2 sun visibility
- Camera confidence scores
- Last analysis time
- Observer status

Dashboard YAML:

```text
dashboard/ai_sky_observer_dashboard.yaml
```

## Installation

Installation instructions are available in:

```text
docs/installation.md
```

## Requirements

Before installing AI Sky Observer you will need:

- Home Assistant
- LLM Vision
- One or more outdoor cameras
- Any LLM Vision supported provider

The project has been tested with:

- Google Gemini
- OpenAI
- Anthropic
- Ollama
- LocalAI

## Entities

The package creates the following Home Assistant entities.

| Entity | Description |
|---------|-------------|
| AI Sky Observer Cloud Cover | Average cloud cover across all configured cameras |
| AI Sky Observer Condition | Overall sky condition derived from AI observations |
| Camera 1 Cloud Cover | Cloud cover estimated from Camera 1 |
| Camera 2 Cloud Cover | Cloud cover estimated from Camera 2 |
| Camera 1 Confidence | Confidence score for Camera 1 |
| Camera 2 Confidence | Confidence score for Camera 2 |
| Camera 1 Sun Visible | Direct sun detected by Camera 1 |
| Camera 2 Sun Visible | Direct sun detected by Camera 2 |

## Motivation

AI Sky Observer was originally developed while building **Adaptive Cover Controller**.

During testing it became clear that regional weather forecasts were not always accurate enough for sunlight-based automations.

A weather service may report **20% cloud cover** while a cloud temporarily blocks the sun above your property. Likewise, it may report **80% cloud cover** while the sun is shining through a gap in the clouds.

For automations that react to direct sunlight, those local variations matter.

Rather than estimating conditions from a regional forecast, AI Sky Observer observes the visible sky directly from your own cameras and converts those observations into Home Assistant entities.

## Design Philosophy

AI Sky Observer follows one simple principle:

> **AI observes. Home Assistant decides.**

The project never controls devices directly.

Instead, it creates Home Assistant entities that can be used by automations, scripts, dashboards and blueprints, leaving all decision making inside Home Assistant.

## Integration with Adaptive Cover Controller

AI Sky Observer was designed to work alongside **Adaptive Cover Controller**.

By combining the sun's position with real-time observations from your own cameras, Adaptive Cover Controller can make more informed decisions about when blinds, curtains and shutters should move.

Adaptive Cover Controller:

https://github.com/wgumaa/Adaptive-Cover-Controller

## Documentation

Additional documentation is available in the `docs` directory.

- Installation Guide
- Dashboard Guide
- Frequently Asked Questions
- Roadmap

## Roadmap

Planned improvements include:

### Sky Observation

- Improved sky classification
- Sky brightness estimation
- Cloud density estimation
- Sunrise and sunset visibility

### Weather Observation

- Rain detection
- Snow detection
- Fog detection
- Smoke detection
- Storm detection

### Camera Health

- Spider web detection
- Dirty lens detection
- Camera health monitoring

### Platform

- Support for additional cameras
- Historical observations
- Observation trends
- Native Home Assistant integration

For additional detail, see:

```text
docs/roadmap.md
```

## Contributing

Bug reports, feature requests and pull requests are always welcome.

If you have ideas for improving the project, please open an issue or start a discussion.

## Project Status

AI Sky Observer is under active development.

Community feedback plays an important role in shaping future releases.

## License

Released under the MIT License.
