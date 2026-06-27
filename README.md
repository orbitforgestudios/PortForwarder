# <div align="center">

<img src="docs/Screenshots/icon.png" width="110" alt="Port Forwarder Logo"/>

# Port Forwarder

### Expose any local port to the internet with a single tap.

No login • No signup • No complex setup • HTTPS URL • QR Code • Open Source

[![Google Play](https://img.shields.io/badge/Google_Play-Download-green?style=for-the-badge\&logo=google-play)](https://play.google.com/store/apps/details?id=com.orbitforgestudios.portforwarder)
[![GitHub Release](https://img.shields.io/github/v/release/orbitforgestudios/PortForwarder?style=for-the-badge)](https://github.com/orbitforgestudios/PortForwarder/releases/latest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=for-the-badge)](LICENSE)
![Stars](https://img.shields.io/github/stars/orbitforgestudios/PortForwarder?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/orbitforgestudios/PortForwarder?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/orbitforgestudios/PortForwarder?style=for-the-badge)

</div>

---

## ⭐ Features

* 🚀 One-tap port forwarding
* 🌐 Instantly generate a public HTTPS URL
* 📱 Built-in QR code generation for easy sharing
* 🔒 Uses Cloudflare Quick Tunnels
* 📡 Forward any local TCP service
* 🔄 Runs as a foreground service while active
* 👤 No account or login required
* ⚡ Lightweight, fast and battery-friendly
* 🎨 Modern Material 3 UI
* 📖 Completely open source

---


## 📱 Screenshots

<p align="center">
  <img src="docs/Screenshots/SS_25.png" width="180" alt="Home Screen"/>
  <img src="docs/Screenshots/SS_26.png" width="180" alt="Enter Port"/>
  <img src="docs/Screenshots/SS_27.png" width="180" alt="Tunnel Created"/>
</p>

<p align="center">
  <img src="docs/Screenshots/SS_28.png" width="180" alt="QR Code"/>
  <img src="docs/Screenshots/SS_29.png" width="180" alt="Tunnel Details"/>
  <img src="docs/Screenshots/SS_30.png" width="180" alt="Settings"/>
</p>



---

## 🚀 Getting Started

1. Install the app.
2. Enter the local port you want to expose (for example `8080`).
3. Tap **Start Forwarding**.
4. Wait a few seconds while the tunnel is created.
5. Share the generated HTTPS URL or QR code.

Your local service is now securely accessible over the internet.

---

## ⚙️ Example Use Cases

Port Forwarder can expose virtually any service running on your device or local network.

* IP Cameras
* Development Servers
* Home Assistant
* NAS Dashboards
* Raspberry Pi Projects
* Local Web Applications
* IoT Devices
* REST APIs
* Media Servers
* Network Monitoring Dashboards

---

## 🛠 Tech Stack

* Kotlin
* Jetpack Compose
* Material 3
* Android Foreground Service
* Cloudflare Quick Tunnels
* Kotlin Coroutines
* MVVM Architecture
* QR Code Generation

---

## 📥 Download

### Google Play (Recommended)

Install the latest stable version directly from Google Play.

https://play.google.com/store/apps/details?id=com.orbitforgestudios.portforwarder

---

### GitHub Releases

Latest beta builds and APK files are available from GitHub Releases.

https://github.com/orbitforgestudios/PortForwarder/releases/latest

---

## 🔒 Privacy

Port Forwarder is designed with privacy in mind.

* No account required
* No signup
* No advertisements
* No analytics
* No user tracking
* No personal information collected

The app only establishes outbound connections required to create a Cloudflare Quick Tunnel.

---

## 🛡 Permissions

| Permission         | Purpose                                                    |
| ------------------ | ---------------------------------------------------------- |
| INTERNET           | Create secure outbound tunnel connections                  |
| FOREGROUND_SERVICE | Keep the tunnel alive while the app runs in the background |
| POST_NOTIFICATIONS | Display tunnel status notifications                        |

The app does **not** request access to:

* Camera
* Contacts
* Storage
* Location
* Microphone

No root access is required.

---

## 🔨 Build From Source

```bash
git clone https://github.com/orbitforgestudios/PortForwarder.git
cd PortForwarder
./gradlew assembleRelease
```

Debug build

```bash
./gradlew assembleDebug
```

---

## ❓ Frequently Asked Questions

### Does the app require root?

No.

---

### Do I need a Cloudflare account?

No. Cloudflare Quick Tunnels work anonymously.

---

### Can I expose any local service?

Yes.

Any service listening on a local TCP port can be forwarded.

---

### Does the app continue running in the background?

Yes.

While forwarding is active, the app runs as an Android foreground service.

---

### Is the project open source?

Yes.

Contributions are welcome.

---

## ⚠ Disclaimer

Exposing local services to the public internet carries security risks.

Only expose services you trust and ensure any sensitive applications are appropriately secured before making them publicly accessible.

---

## 🐞 Reporting Issues

Found a bug?

Please open an issue:

https://github.com/orbitforgestudios/PortForwarder/issues

---

## 💡 Feature Requests

Have an idea?

Start a discussion:

https://github.com/orbitforgestudios/PortForwarder/discussions

---

## 🤝 Contributing

Contributions of all kinds are welcome.

You can help by:

* Reporting bugs
* Improving documentation
* Suggesting features
* Submitting pull requests

Please ensure your changes are well-tested before submitting a pull request.

---

## ❤️ Support the Project

If you find Port Forwarder useful, consider supporting the project by:

* ⭐ Starring this repository
* 🍴 Forking the project
* 🐞 Reporting bugs
* 💬 Suggesting new features
* 📢 Sharing it with others

Every contribution helps improve the project.

---

## 📄 License

Licensed under the Apache License 2.0.

See the **LICENSE** file for details.

---

<div align="center">

Made with ❤️ by **Orbit Forge Studios**

</div>
