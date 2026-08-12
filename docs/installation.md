# 📖 Installation

This guide explains how to install **AI Sky Observer** into Home Assistant.

---

# Requirements

Before installing AI Sky Observer, ensure you have:

- Home Assistant
- LLM Vision installed and configured
- At least one outdoor camera with a view of the sky
- A supported LLM provider (Google Gemini, OpenAI, Anthropic, Ollama, LocalAI, etc.)

---

# Install the Package

1. Download or clone this repository.

2. Copy the package file:

```text
package/ai_sky_observer.yaml
```

to your Home Assistant packages directory:

```text
config/packages/
```

3. If you are not already using packages, enable them in your `configuration.yaml`:

```yaml
homeassistant:
  packages: !include_dir_named packages
```

4. Restart Home Assistant.

---

# Configure AI Sky Observer

Open the package and update the **User Configuration** section.

Replace:

- `YOUR_PROVIDER_ID`
- `camera.camera_1`
- `camera.camera_2`

with your own LLM Vision provider ID and outdoor camera entities.

No other changes should be required.

---

# Import the Optional Dashboard

An example dashboard is included with the project.

Dashboard file:

```text
dashboard/ai_sky_observer_dashboard.yaml
```

Open the Home Assistant Dashboard editor, switch to the **Raw Configuration Editor**, and paste the contents of the dashboard file.

---

# Enable the Observer

Turn on:

```
AI Sky Observer Enabled
```

The automation will begin analysing your cameras every five minutes during daylight hours.

---

# Verify the Installation

After Home Assistant has restarted, you should see entities similar to:

- AI Sky Observer Cloud Cover
- AI Sky Observer Condition
- Camera 1 Cloud Cover
- Camera 2 Cloud Cover
- Camera 1 Confidence
- Camera 2 Confidence
- Camera 1 Sun Visible
- Camera 2 Sun Visible

---

# Next Steps

You're now ready to start using AI Sky Observer in your own automations.

It works particularly well with projects such as **Adaptive Cover Controller**, where real-time AI observations can be used instead of relying solely on weather forecasts.