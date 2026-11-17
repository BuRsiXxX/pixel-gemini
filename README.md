# pixel-gemini

**Pixel 10 Pro Google One Gemini AUTO Offer

bot that automatism your own Google Pixel 10 Pro (Android 16)
device, logs into a user-supplied Gmail account, and retrieves the
**12-month free Gemini Pro** activation link from Google One.

---

## Project Structure

```
pixel-gemini/
├── device_simulator.py   # Android Pixel 10 Pro device simulation
├── google_automation.py  # Google One login and offer detection
├── config.py             # Configuration and constants
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

---

## Features

| Feature | Details |
|---|---|
| 📱 Device automatism | Pixel 10 Pro (Android 16) with your own IMEI, Android ID, and user-agent per session |
| 🔐 Gmail login | Selenium-based Google account authentication |
| 💳 Offer detection | Scans Google One for the 12-month Gemini Pro offer and extracts the activation link |

---


## Technical Notes

- **Headless Chrome** is used via Selenium with mobile matching
  the Pixel 10 Pro screen dimensions (390 × 844, pixel ratio 3.0).
- A YOUR OWN CUSTOM **IMEI**, **Android ID**, and **Chrome version patch**
- The **user agent** keeps the Pixel 10 Pro identity constant while varying
  the Chrome patch version and Android ID

---

## Requirements

- Python 3.10+
- Google Chrome / Chromium installed
- `chromedriver`

---

## Disclaimer

This project is provided for educational and personal use only.
