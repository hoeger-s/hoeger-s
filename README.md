![Stefan Höger - Fachinformatiker für Systemintegration](assets/banner.svg)

## 👤 Über mich

Hey, ich bin Stefan 👋

Ich begeistere mich für IT und neue Technologien, ganz besonders für Infrastruktur, IT-Security und KI. Mir reicht es nicht, dass etwas nur funktioniert, ich will verstehen, warum.
Deshalb probiere ich viel aus und teste so lange, bis ich die Dinge wirklich verstanden habe.

Genau daraus ist mein eigenes Homelab entstanden, und parallel dazu baue ich ARIA (Autonomous Responsive Intelligent Assistant), einen KI-Assistenten, der komplett lokal laufen soll.
Was ich dabei baue und lerne, dokumentiere ich hier.

**Kurz:**
- 🎓 Fachinformatiker für Systemintegration
- 🖥️ Betreibe ein eigenes Homelab mit Virtualisierung, Netzwerksegmentierung und Monitoring
- 🤖 Arbeite an meinem eigenen KI-Assistenten, komplett lokal und ohne Cloud
- 🔍 Suche einen Einstieg in Infrastruktur oder IT-Security


## 🚧 Projekte

### 🛡️ [Homelab](https://github.com/hoeger-s/homelab)

Meine private Infrastruktur im Dauerbetrieb und die Grundlage für eine Testumgebung, die schrittweise typische Enterprise-Infrastrukturen abbilden
und mir zum Ausprobieren und Testen dienen soll.

Aktuell laufen darauf mehrere Dienste, die ich täglich nutze. Alle Web-Dienste liegen hinter einem zentralen Reverse Proxy mit
Let's-Encrypt-Zertifikat. Betrieben wird das Ganze auf Proxmox in einem eigenen VLAN hinter zonenbasierter Firewall, überwacht mit Prometheus,
Grafana, Loki und Alertmanager. Sämtliche Konfigurationen liegen als Configuration as Code im Repo.

**[-> Zum Repository](https://github.com/hoeger-s/homelab)**

---

### 🎙️ [ARIA](https://github.com/hoeger-s/aria)

Ein lokal laufender KI-Companion mit Sprachein- und -ausgabe. Komplett auf eigener Hardware, ohne Cloud-Dienste.

Spracherkennung (faster-whisper), Sprachmodell (Ollama) und Sprachausgabe (Qwen3-TTS) laufen als getrennte Docker-Dienste, orchestriert von einem
FastAPI-Backend, mit einer Orb-Oberfläche in Three.js.

**[-> Zum Repository](https://github.com/hoeger-s/aria)**


## 🧭 Schwerpunkte

`Virtualisierung` · `Netzwerksegmentierung` · `Firewall & VPN` · `Monitoring & Logging` · `Alerting` · `Reverse Proxy & TLS` · `Linux-Administration` 
· `Self-Hosting` · `Containerisierung` · `Python` · `Lokale KI` · `Configuration as Code` · `Dokumentation`


## 🧰 Tech-Stack

**Infrastruktur & Netzwerk**<br>
![Proxmox](https://img.shields.io/badge/Proxmox-1f2937?style=flat-square&logo=proxmox&logoColor=E8E8E8) ![Debian](https://img.shields.io/badge/Debian-1f2937?style=flat-square&logo=debian&logoColor=E8E8E8) ![Docker](https://img.shields.io/badge/Docker-1f2937?style=flat-square&logo=docker&logoColor=E8E8E8) ![UniFi](https://img.shields.io/badge/UniFi-1f2937?style=flat-square&logo=ubiquiti&logoColor=E8E8E8) ![WireGuard](https://img.shields.io/badge/WireGuard-1f2937?style=flat-square&logo=wireguard&logoColor=E8E8E8) ![Caddy](https://img.shields.io/badge/Caddy-1f2937?style=flat-square&logo=caddy&logoColor=E8E8E8) ![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-1f2937?style=flat-square&logo=letsencrypt&logoColor=E8E8E8)

**Monitoring & Logging**<br>
![Prometheus](https://img.shields.io/badge/Prometheus-1f2937?style=flat-square&logo=prometheus&logoColor=E8E8E8) ![Grafana](https://img.shields.io/badge/Grafana-1f2937?style=flat-square&logo=grafana&logoColor=E8E8E8) ![Loki](https://img.shields.io/badge/Loki-1f2937?style=flat-square&logo=grafana&logoColor=E8E8E8) ![Alertmanager](https://img.shields.io/badge/Alertmanager-1f2937?style=flat-square&logo=prometheus&logoColor=E8E8E8)

**Skripting & Entwicklung**<br>
![Bash](https://img.shields.io/badge/Bash-1f2937?style=flat-square&logo=gnubash&logoColor=E8E8E8) ![Python](https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=E8E8E8) ![FastAPI](https://img.shields.io/badge/FastAPI-1f2937?style=flat-square&logo=fastapi&logoColor=E8E8E8) ![Ollama](https://img.shields.io/badge/Ollama-1f2937?style=flat-square&logo=ollama&logoColor=E8E8E8) ![Git](https://img.shields.io/badge/Git-1f2937?style=flat-square&logo=git&logoColor=E8E8E8)


## 📬 Kontakt

Fragen, Anregungen oder einfach Interesse an einem Gespräch? Ich freue mich über jede Nachricht.

[![E-Mail](https://img.shields.io/badge/E--Mail-1f2937?style=flat-square&logo=maildotru&logoColor=E8E8E8)](mailto:it@hoeger.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1f2937?style=flat-square&logo=linkedin&logoColor=E8E8E8)](https://www.linkedin.com/in/stefan-höger-5a375a339/)
[![XING](https://img.shields.io/badge/XING-1f2937?style=flat-square&logo=xing&logoColor=E8E8E8)](https://www.xing.com/profile/Stefan_Hoeger049861/web_profiles?nwt_nav=profile)
