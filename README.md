# 🏠 IoT Home Hub

Open-source, self-hosted IoT home hub for ESP32, ESP8266, and Raspberry Pi.
Control devices via MQTT, automate rules, monitor sensors in real time, and manage everything from a local web dashboard.

---

## ✨ Features

* 🔌 MQTT-based device communication
* 📊 Real-time device & sensor monitoring
* ⚙️ Automation rules (if-this-then-that)
* 🕒 Scheduling & timers
* 🔐 Local-first, no cloud required
* 📱 Mobile-friendly web dashboard

---

## 🧱 Supported Hardware

* ESP32 / ESP8266
* Raspberry Pi
* Relays, LEDs, sensors (temp, motion, distance)
* Any MQTT-compatible device

---

## 🛠 Tech Stack

* **Backend:** Node.js (API + MQTT)
* **Frontend:** Web Dashboard
* **Protocol:** MQTT
* **Database:** SQLite (default)

---

## 📁 Project Structure

```
iot-home-hub/
├─ backend/
│  ├─ mqtt/
│  ├─ api/
│  └─ services/
├─ frontend/
│  ├─ components/
│  └─ pages/
├─ devices/
│  └─ esp32/
├─ docs/
└─ README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourname/iot-home-hub
cd iot-home-hub
npm install
npm run dev
```

> MQTT broker required (Mosquitto recommended)

---

## 🤝 Contributing

Contributions are welcome!
Check **Issues** for `good first issue` and `help wanted`.

---

## 📜 License

MIT
