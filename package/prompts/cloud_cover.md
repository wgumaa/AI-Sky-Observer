# Cloud Cover Prompt

Two outdoor security camera images are provided.

Image 1 shows the front of the property.

Image 2 shows the rear of the property.

Analyze each image independently.

Estimate:

- Cloud cover (%)
- Confidence (%)
- Sun visible (true/false)

Rules

- Analyze only the visible sky.
- Ignore buildings, trees, vehicles and the ground.
- Thin cirrus clouds count as cloud cover.
- Blue sky = 0%.
- Completely overcast = 100%.
- Return only valid JSON.