# WT32-SC01 + LVGL + EEZ Studio (ESP-IDF)

A complete example demonstrating how to design a UI using **EEZ Studio**, generate **LVGL v8.x** code, and run it on the **WT32-SC01 (ESP32-S3)** using **ESP-IDF** and **LovyanGFX**.

This project includes:
- UI created visually in **EEZ Studio**
- Auto-generated LVGL UI files
- Working event callbacks (press, click, long press, pressing…)
- Touchscreen support via LovyanGFX
- Clean CMake integration

---
# **Projects**
- [Base code (Buttons + LogPrint)](https://github.com/ivvalachaitanya/WT32-SC01-LVGL8-ESP32-IDF-EEZ/tree/main/LVGL8-WT32-SC01-IDF-EZZ-Base)
- [Example with charts + Buttons + Bar + LogPrint](https://github.com/ivvalachaitanya/WT32-SC01-LVGL8-ESP32-IDF-EEZ/tree/main/LVGL8-WT32-SC01-IDF-EZZ-Charts)


---

## 🛠 Requirements

### Software
- ESP-IDF **5.5.1**
- EEZ Studio (UI design tool)
- LVGL 8.x component
- LovyanGFX (display + touch driver)

### Hardware
- WT32-SC01 (ESP32-S3 + ST7796(TFT) + FT6336U(Touch))
- USB-C cable

---

## ⚙️ Build & Flash

```sh
idf.py set-target esp32s3
idf.py fullclean
idf.py build
idf.py -p com8 flash monitor
```

---

## 📄 License
MIT License

---

## ❤️ Credits

- LVGL : https://lvgl.io
- EEZ Studio : UI designer
- LovyanGFX : Display/touch driver
- WT32-SC01 Community
- Special thanks to Sukesh(https://github.com/sukesh-ak/LVGL8-WT32-SC01-IDF) for getting started codes
