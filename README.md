# Lancaster Fire & EMS Incidents

<img width="640" height="480" alt="IMG_4164" src="https://github.com/user-attachments/assets/b8c6feb3-7d19-4d9b-9d45-e3195cc02e6d" />

<img width="640" height="480" alt="IMG_4170" src="https://github.com/user-attachments/assets/6c2a38f0-27ab-4c0e-8311-8f8af1ac9057" />

<img width="640" height="480" alt="IMG_4167" src="https://github.com/user-attachments/assets/3792fa94-a6cb-4704-958b-3671378e42b6" />

A minimal PlatformIO project for ESP32 with CYD display. ESP32-2432S028 V3 THIS IS THE CYD WITH DUAL USB

## Screenshots

Drop image files into `images/` and reference them here, e.g.:

```markdown
![Dashboard](images/dashboard.jpg)
![Unit Info popup](images/unit-info-popup.jpg)
![Incident map popup](images/county-map-popup.jpg)
```

## Build & Upload

- **Build**: `pio run -e esp32dev`
- **Upload**: `pio run --target upload -e esp32dev`
- **Monitor**: `pio device monitor`

## Adding Libraries

To add libraries later, update `platformio.ini` under `lib_deps`:

```ini
lib_deps =
    lovyan03/LovyanGFX @ ^1.1.16
    <new-library-name> @ ^<version>
```

Then rebuild.
