# Frequently Asked Questions

## Why does Cloud Cover become unavailable at night?

AI Sky Observer only analyses images while the sun is above the horizon.

This reduces AI usage and prevents meaningless cloud estimates.

---

## Which cameras are supported?

Any Home Assistant camera entity supported by LLM Vision.

---

## Which AI providers work?

Any provider supported by LLM Vision.

---

## How often should analysis run?

The default is every five minutes.

---

## Why is confidence low?

Confidence decreases when:

- Sky visibility is limited.
- The lens is dirty.
- Lighting is poor.
- Heavy rain or fog obscures the image.