# 🚀 Nexus Node Handler

Shell script otomatis untuk setup, monitoring, dan manajemen Node dari [app.nexus.xyz](https://app.nexus.xyz) menggunakan Docker dan log manager berbasis cron.

> ⚒ Dibuat oleh [@superti4r](https://github.com/superti4r) — cocok untuk dipakai di VPS Ubuntu/Linux secara praktis dan efisien.

---

## 🧰 Fitur Utama

- ⛏ **Install otomatis** Docker dan Cron
- 🐳 **Build Docker image** Nexus node
- 📡 **Jalankan node di background** via `screen`
- 📊 **Monitor status node** (CPU, Memori, Status container)
- 📁 **Log file terpusat** per node
- 🧹 **Pembersihan log otomatis** via cron
- ❌ **Uninstall node individual / massal**
- 💥 **Self-destruct**: hapus script & semua file otomatis

---

## 📦 Persyaratan

- VPS/Linux Ubuntu
- RAM minimal 16 GB
- Core v8
- Docker & cron (akan otomatis terinstal)

---

## 🚀 Instalasi & Menjalankan

1. **Clone repo atau download script**
   ```bash
   git clone https://github.com/superti4r/nexus-node-handler
   cd nexus-node-handler
   chmod +x run.sh
   ./run.sh