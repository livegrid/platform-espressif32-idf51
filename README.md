# Frozen Mirror: Espressif 32 PlatformIO Platform (IDF 5.1.6 / Arduino 3.0.x)

Frozen preservation mirror of `Jason2866/platform-espressif32` branch `Arduino/IDF5` at commit `f889376` (`2025.03.10`), archived because the upstream `Arduino/IDF5` branch was removed.

Release `v2025.03.10` hosts the required upstream package zips (`framework-arduinoespressif32-all-release_v5.1-7e10045.zip` and `esptool.zip`) so builds remain self-contained and reproducible.

```ini
platform = https://github.com/livegrid/platform-espressif32-idf51.git#v2025.03.10
```

---

[![Build_special_firmware](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)


# Tasmota Espressif 32: development platform for [PlatformIO](http://platformio.org)

[![Examples](https://github.com/Jason2866/platform-espressif32/actions/workflows/examples.yml/badge.svg)](https://github.com/Jason2866/platform-espressif32/actions/workflows/examples.yml)[![GitHub Releases](https://img.shields.io/github/downloads/tasmota/platform-espressif32/total?label=downloads)](https://github.com/tasmota/platform-espressif32/releases/latest)

Espressif Systems is a privately held fabless semiconductor company. They provide wireless communications and Wi-Fi chips which are widely used in mobile devices and the Internet of Things applications.

* [Home](http://platformio.org/platforms/espressif32) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/espressif32.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

### Development build Arduino 3.0.5+ and IDF 5.1.4+ (build from development branches)
Support for the ESP32/ESP32solo1, ESP32C2, ESP32C3, ESP32C6, ESP32S2, ESP32S3 and ESP32-H2
```                  
[platformio]
platform = https://github.com/Jason2866/platform-espressif32.git#Arduino/IDF5
framework = arduino
```
to use the ESP32 Solo1 Arduino framework add in your env
```
[env:esp32solo1]
board = esp32-solo1
build_flags = -DFRAMEWORK_ARDUINO_SOLO1
```
The released frameworks can be downloaded [here](https://github.com/tasmota/arduino-esp32/releases)

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/espressif32.html).
