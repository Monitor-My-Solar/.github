# MonitorMySolar

**MonitorMySolar** is a smart solar monitoring platform designed to track, analyze, and optimize energy performance across solar installations.

---

## ✨ Features

- Real-time energy monitoring
- Multi-region infrastructure (UK, US, and more)
- MQTT-based communication with solar dongles
- Custom dashboards and analytics
- Role-based access control for admins, companies, and installers
- API access for integrators and aggregators
- CI/CD pipeline with auto deployment and linting

---

## 🌐 Live Services

| Service        | Domain                    | Description              |
|----------------|---------------------------|--------------------------|
| Web Frontend   | `monitormy.solar`         | UK Region main UI       |
| MQTT Broker    | `mqtt.monitormy.solar`    | Data gateway for dongles |
| Monitoring     | `monitoring.monitormy.solar` | Device metrics UI       |
| Job Portal     | `jobs.monitomy.solar`     | Solar job listings       |

---

## 🧩 Integrations

- [Home Assistant Integration](https://github.com/MonitorMySolar/home-assistant-integration)

MonitorMySolar is compatible with Home Assistant to help visualize solar performance data directly from your dashboard.

---

## ⚙️ Tech Stack

- **Node.js** (Express, WebSocket, REST APIs)
- **Redis** (live data storage and message queues)
- **MySQL** (persistent storage)
- **EMQX** (MQTT Broker)
- **React / TailwindCSS** (Frontend)
- **React Native** (Mobile App)
- **HAProxy + Tailscale** (Access & Load Balancing)

---

## 🛠 Development Guidelines

- Create a branch for each feature or bugfix
- Follow [Husky commit conventions](https://github.com/MonitorMySolar/conventions)
- Run `npm run lint` before pushing
- Submit PRs into the `DEV` branch

---

## 📬 Support

If you need help or have questions, contact us at **[support@monitormy.solar](mailto:support@monitormy.solar)**.

---

## ✅ License

MIT License — see the [LICENSE](LICENSE) file for details.

---

_"Monitor smarter. Power brighter." — The MonitorMySolar Team_

