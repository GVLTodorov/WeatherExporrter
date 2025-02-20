# WeatherExporrter

```
services:
  weather-exporter:
    image: ghcr.io/gvltodorov/weatherexporrter:beta
    container_name: weather-exporter
    ports:
      - 8080:8080
    environment:
      - LATITUDE=42.6975
      - LONGITUDE=23.3241
      - TIMEZONE=Europe/Sofia
      - WEATHER_FIELDS=temperature_2m,apparent_temperature
      - AIR_QUALITY_FIELDS=european_aqi,us_aqi,pm10,pm2_5
```
