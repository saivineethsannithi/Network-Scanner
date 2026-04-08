# 🔍 Network Scanner Suite (Python + Web Dashboard)

A professional **network discovery tool** built for cybersecurity learning and SOC analysis.
This project includes **two implementations**:

* 🖥️ **Python-based CLI Scanner**
* 🌐 **Web-based Interactive Dashboard**

It identifies active devices on a local network using **ARP, ICMP, and DNS resolution**.

---

## 💼 Project Type

**Blue Team | SOC Analyst | Network Security Project**

---

## 🚀 Features

### 🖥️ Python Scanner

* Multi-threaded network scanning
* ICMP-based host discovery (Ping)
* ARP-based MAC address resolution
* Reverse DNS hostname lookup
* Fast scanning using threading
* Clean tabular CLI output

### 🌐 Web Dashboard

* Interactive UI for network scanning simulation
* Real-time progress bar and logs
* Device filtering (Resolved / Unknown)
* Search functionality (IP / MAC / Hostname)
* Metrics dashboard (Hosts scanned, Devices found, Time)
* Responsive and modern design

---

## 🛠️ Tech Stack

| Component       | Technology                         |
| --------------- | ---------------------------------- |
| Backend Scanner | Python                             |
| Networking      | ARP, ICMP, DNS                     |
| Library         | Scapy                              |
| Frontend        | HTML, CSS, JavaScript              |
| Concepts        | Multi-threading, Network Discovery |

---

## 📂 Project Structure

```
network-scanner/
│
├── network_scanner.py        # Python CLI Scanner :contentReference[oaicite:0]{index=0}
├── dashboard.html           # Web Dashboard UI :contentReference[oaicite:1]{index=1}
├── requirements.txt         # Dependencies :contentReference[oaicite:2]{index=2}
├── README.md
└── screenshots/
    └── demo.png
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/network-scanner-suite.git
cd network-scanner-suite
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### 🖥️ Run Python Scanner

```bash
python network_scanner.py
```

Enter CIDR range:

```
192.168.1.0/24
```

📌 Requirements:

* Run as **Administrator (Windows)**
* Run with **sudo (Linux/Mac)**

---

### 🌐 Run Web Dashboard

Simply open:

```bash
dashboard.html
```

in your browser.

👉 No server required (runs locally)

---

## 📸 Demo - web-based scanner 

<img width="1884" height="926" alt="Screenshot 2026-04-08 122758" src="https://github.com/user-attachments/assets/279902a7-628c-48ee-a429-640bef653d28" />

<img width="1898" height="870" alt="Screenshot 2026-04-08 122812" src="https://github.com/user-attachments/assets/fa9c4f4a-29fa-46f0-8552-10283b19b49e" />

## 📸 Demo - python code-based scanner 




<img width="935" height="795" alt="Screenshot 2026-04-08 122605" src="https://github.com/user-attachments/assets/b717b4c8-eeca-42fb-a54d-eb0409de7e15" />



## 🧠 How It Works

### Python Scanner

1. Takes network range (CIDR)
2. Pings each host (ICMP)
3. Sends ARP requests for MAC address
4. Resolves hostname via DNS
5. Displays results in structured table

### Web Dashboard

* Simulates scanning process
* Visualizes results with metrics and logs
* Allows filtering and searching devices

---

## 🎯 Use Cases

* Network reconnaissance
* SOC analyst lab practice
* Internal asset discovery
* Cybersecurity portfolio project
* Learning ARP & ICMP protocols

---

## ⚠️ Limitations

* May not work on restricted networks (ICMP/ARP blocked)
* Requires admin privileges
* Web version is a simulation (not real scanning)

---

## 📌 Future Improvements

* 🔍 Port scanning (Nmap integration)
* 🌍 Live backend API integration
* 📊 Export results (CSV / JSON)
* 🛡️ Intrusion detection features
* 🖥️ Full-stack web app version

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork and improve the project.

---

## ⭐ Support

If you found this project helpful:

👉 Give it a **star on GitHub**
👉 Share it with others

---

## 👨‍💻 Author

Built as part of a **Cybersecurity / SOC Analyst learning project**

---

## 📜 License

This project is open-source and available under the MIT License.
