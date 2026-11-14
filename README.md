# WeatherScope — iPhone Weather Radar PWA

Play it at **https://oleksavr.github.io/weatherscope/**

## Install on iPhone

1. Open the HTTPS address above in **Safari** on your iPhone. A direct `file://` URL is not sufficient for iPhone GPS, service workers, or Home Screen PWA behavior.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Launch WeatherScope from your Home Screen. Tap **GPS** and grant location permission, or search for a city / US ZIP.

## Features

- OpenStreetMap base map with attribution
- RainViewer radar frames and animation when the public service is available
- Open-Meteo current weather, hourly and 7-day forecasts
- GPS, city and US ZIP lookup
- Local app-shell caching for limited offline launching; live data requires internet

## Limitations

- This is an installable web app, not an App Store IPA or native iOS binary.
- Requires HTTPS and internet for live radar/maps/forecasts; external Leaflet JS/CSS are served from CDN.
- RainViewer availability, tile paths, nowcast availability, and access policy can change. No guarantee of continuous radar coverage.
- No push warnings or official severe-weather alerts. Check weather.gov for urgent warnings.
- OpenStreetMap public tile servers have usage limits; this is for modest personal use, not high-volume distribution.
- No API key required for personal non-commercial use within provider policies.
