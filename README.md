# 🌍 TheIPLocalizator

**TheIPLocalizator** is a lightweight, client-side web tool that displays the **approximate geographic location of an IP address** using public GeoIP services.

It can:
- Locate a manually entered IP address
- Locate your own public IP
- Display an approximate location on an interactive map
- Show the visitor’s real IPv4 and IPv6 addresses
- Provide clear privacy and security recommendations

This project is intended for **educational, informational, and demonstration purposes**.

---

## 🚀 Features

- 🔎 IP address lookup (manual or automatic)
- 🗺️ Interactive map (OpenStreetMap via Leaflet)
- 📍 Approximate location (city, region, country)
- 🌐 Displays **your real IPv4 and IPv6** (always the visitor’s)
- 🔐 Built-in security and privacy recommendations
- 📦 Single-file project (HTML + CSS + JavaScript)
- ❌ No backend required
- ❌ No data storage
- ❌ No tracking

---

## 🧠 How It Works

TheIPLocalizator uses a public GeoIP API to estimate location data based on an IP address.

Important notes:
- The location is **approximate**, not exact
- It does **not** use GPS
- Results may be inaccurate when using VPNs, proxies, or Tor
- Mobile networks often return less precise locations

The visitor’s IPv4 and IPv6 addresses are always obtained separately and **never depend on the entered IP**.

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- OpenStreetMap
- Leaflet.js
- Public GeoIP API (ipapi)

---

## 🔐 Security & Privacy Recommendations

When browsing the Internet, your IP address is exposed and can be used to obtain approximate information about your location or Internet service provider. In the wrong hands, this data may pose a risk to your privacy.

For this reason, we recommend:
- Avoiding websites of questionable or untrusted origin
- Taking additional privacy measures, such as using a **trusted VPN**
- Using privacy-focused browsers like **Tor Browser**, which help hide your real IP address and improve online anonymity

---

## ⚖️ Legal Notice

This project is **legal** and compliant with privacy regulations because:

- It only uses publicly available technical data
- It does not identify individuals
- It does not store, log, or transmit personal data
- All processing happens client-side in the user’s browser
- The displayed location is clearly stated as approximate

TheIPLocalizator does **not** perform tracking, surveillance, or data collection.

---

## 📄 Disclaimer

TheIPLocalizator provides **approximate location data only**.  
Accuracy is not guaranteed and may vary depending on network conditions, ISP routing, or privacy tools.

This tool should not be used for surveillance, identification, or legal enforcement purposes.

---

## 📜 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it, provided the original copyright notice is included.

---

## ⭐ Contributing

Contributions, improvements, and suggestions are welcome.  
Feel free to open an issue or submit a pull request.

---
