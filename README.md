# 🌐 Recon CLI

Modular CLI tool for basic recon tasks: subdomain enumeration, port scanning, and service fingerprinting. Built for extensibility and speed.

---

## 🔧 Modules

| Module | Description |
|--------|-------------|
| `subdomain_scan.py` | Placeholder for DNS brute or API-based enumeration. |
| `port_scan.py` | TCP port scanner with timeout handling. |
| `service_fingerprint.py` | Banner grabbing and service ID logic. |

---

## 🚀 Usage

```bash
python3 auto_rec_main.py --target example.com
python3 modules/subdomain_scan.py example.com
python3 modules/port_scan.py example.com
