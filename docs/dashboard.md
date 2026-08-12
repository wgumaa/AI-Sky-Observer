# 🖥 Dashboard

AI Sky Observer includes an optional Home Assistant dashboard to help you monitor AI observations at a glance.

The dashboard is provided as a YAML file and can be imported into any Home Assistant dashboard.

---

## Dashboard File

```text
dashboard/ai_sky_observer_dashboard.yaml
```

---

## Features

The dashboard displays:

- ☁️ Overall Sky Condition
- ☁️ Average Cloud Cover
- 📷 Camera 1 Cloud Cover
- 📷 Camera 2 Cloud Cover
- ☀️ Camera 1 Sun Visibility
- ☀️ Camera 2 Sun Visibility
- 🎯 Camera 1 Confidence
- 🎯 Camera 2 Confidence
- 🕒 Last Analysis Time
- ⚡ Observer Status

---

## Importing the Dashboard

1. Open Home Assistant.
2. Navigate to **Settings → Dashboards**.
3. Create a new dashboard or edit an existing one.
4. Open the **Raw Configuration Editor**.
5. Copy and paste the contents of:

```text
dashboard/ai_sky_observer_dashboard.yaml
```

6. Save the dashboard.

---

## Screenshot

<p align="center">
  <img src="../images/dashboard.png" alt="AI Sky Observer Dashboard">
</p>

---

## Customisation

The example dashboard is intended as a starting point.

Feel free to:

- Rename Camera 1 and Camera 2 to match your installation.
- Add the sensors to an existing dashboard.
- Combine AI Sky Observer with your own weather, cover or automation cards.
- Modify the layout to suit your Home Assistant theme.