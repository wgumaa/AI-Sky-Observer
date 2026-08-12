# ❓ Frequently Asked Questions

## Why does AI Sky Observer stop analysing at night?

AI Sky Observer only performs image analysis while the sun is above the horizon.

At night, cloud cover cannot be estimated reliably from standard outdoor cameras, so analysis is suspended to reduce unnecessary AI usage and API costs.

---

## Which cameras are supported?

Any Home Assistant camera entity that is supported by LLM Vision can be used.

For best results, use outdoor cameras with a clear view of the sky.

---

## Which AI providers are supported?

AI Sky Observer works with any provider supported by LLM Vision, including:

- Google Gemini
- OpenAI
- Anthropic
- Ollama
- LocalAI

and many others.

---

## How often should analysis run?

The default schedule analyses the cameras every **five minutes** during daylight hours.

You can adjust the schedule to suit your own requirements, but more frequent analysis will increase AI usage.

---

## Why is the confidence score low?

The AI reports a confidence score for each camera observation.

Confidence may decrease when:

- Only a small portion of the sky is visible.
- Lighting conditions are poor.
- The camera lens is dirty.
- Rain, snow or condensation obscures the image.
- Heavy fog or haze reduces visibility.
- Motion blur is present.

A lower confidence score simply indicates that the AI is less certain about its cloud cover estimate.

---

## Does AI Sky Observer control any devices?

No.

AI Sky Observer is an observation system only.

It creates Home Assistant sensor entities that can be used by your own automations, scripts, dashboards and blueprints.

This follows the project's design philosophy:

> **AI observes. Home Assistant decides.**

---

## Can I use more than two cameras?

The initial release is designed for two cameras.

Support for additional cameras is planned for a future release.

---

## Can I use AI Sky Observer with Adaptive Cover Controller?

Yes.

AI Sky Observer was designed to complement Adaptive Cover Controller by providing real-time local observations of cloud cover and direct sun visibility, allowing cover automations to react to the actual conditions at your property instead of relying solely on weather forecasts.

---

## Does AI Sky Observer require an internet connection?

That depends on your AI provider.

Cloud-based providers such as Google Gemini and OpenAI require internet access.

If you use a local provider such as Ollama or LocalAI, AI Sky Observer can operate entirely within your local network.