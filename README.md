# 🌐 NetScanner — TCP Port Scanner

> A minimal Python-based **TCP port scanner** for network recon and diagnostics.
> 
> Made by [Sandeep Prasad Chowdhury](https://github.com/chowdhurysandeep) | 🎓 Ethical Hacking Student

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Category](https://img.shields.io/badge/Category-Network%20Recon-red?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ⚠️ Legal Disclaimer

> This tool is intended for **educational purposes and authorized testing only**.  
> Only scan systems and networks you **own or have explicit permission** to test.  
> Unauthorized port scanning may be **illegal** in your jurisdiction.

---

## 📌 About

NetScanner is a lightweight alternative to Nmap for learning TCP scanning fundamentals. It's a great starting point for understanding how port scanning works under the hood — useful for CTFs, lab environments, and your own machines.

---

## ✨ Features

- 🔌 **TCP connect scanning** via `socket.connect_ex`
- 🎯 **Custom port ranges** — scan 1 port or all 65535
- 🌍 **Domain & IP support** — resolves hostnames automatically
- ⏱️ **1-second timeout** per port for speed
- ⚡ **Zero dependencies** — pure Python standard library

---

## 🚀 Usage

```bash
git clone https://github.com/chowdhurysandeep/NetScanner.git
cd NetScanner
python NetScanner.py
```

**Example:**

```
Enter target (IP or domain): scanme.nmap.org
Start port: 20
End port: 100

Scanning...

[+] Port 22 is OPEN
[+] Port 80 is OPEN

Scan complete.
```

---

## 🧪 Safe Test Targets

| Target | Notes |
|---|---|
| `127.0.0.1` | Your own machine |
| `scanme.nmap.org` | Authorized public test target by Nmap |
| Your lab VMs | TryHackMe / HackTheBox machines |

---

## 🛠️ Built With

- `Python 3`
- `socket` — TCP connection handling

---

## 🗺️ Roadmap

- [ ] Multi-threading for faster scans
- [ ] UDP scan support
- [ ] Service/banner grabbing
- [ ] Output to file (`.txt` / `.csv`)
- [ ] Nmap-style report formatting

---

## 👤 Author

**Sandeep Prasad Chowdhury**  
🔗 [LinkedIn](https://www.linkedin.com/in/sandeep-chowdhury-661a54397) · [GitHub](https://github.com/chowdhurysandeep)

---

## 📄 License

MIT License — free to use, modify, and distribute.
