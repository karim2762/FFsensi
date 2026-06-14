# Kexer Extreme Sensi Engine

FFsensi is an advanced Free Fire Sensitivity Generator that creates optimized sensitivity settings based on your device's real performance. Instead of using random values from YouTube or websites, FFsensi analyzes your device and runs a live benchmark to generate the most suitable sensitivity for your phone.

The tool evaluates CPU performance, RAM speed, refresh rate, touch response, battery status, and system load to calculate accurate sensitivity values. This helps players achieve smoother gameplay, better drag control, improved recoil management, and more consistent headshots.

Whether you're on a budget phone or a flagship, FFsensi automatically adapts to your hardware and gives you a personalized sensitivity profile.

### âœ¨ Key Highlights

* ðŸ“± Real Device Detection
* âš¡ Live CPU & RAM Benchmarking
* ðŸŽ¯ Headshot Optimized Sensitivity
* ðŸ“Š Performance Based Calculations
* ðŸ“„ TXT & JSON Output Files
* ðŸš€ Quick Scan & Full Scan Modes
* ðŸ›  Performance Boost Script Generation
* ðŸ“² Android & Termux Compatible

Simply run the tool, wait for the scan, and apply the generated values inside Free Fire.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white">
  <img src="https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=termux&logoColor=white">
  <img src="https://img.shields.io/badge/Free_Fire-FF6A00?style=for-the-badge&logoColor=white">
</p>

---

## ðŸ“¥ Installation

<p align="center">
  <a href="https://f-droid.org/repo/com.termux_118.apk">
    <img src="https://img.shields.io/badge/ðŸ“±%20Download%20Termux-32CD32?style=for-the-badge">
  </a>
  <a href="https://github.com/karim2762/FFsensi/archive/refs/heads/main.zip">
    <img src="https://img.shields.io/badge/ðŸ“¦%20Download%20FFsensi%20ZIP-1E90FF?style=for-the-badge">
  </a>
</p>

---

### Method 1 â€” ZIP Download

**Step 1:** Setup Termux

```bash
termux-change-repo
pkg update && pkg upgrade -y
pkg install python
termux-setup-storage
```

> Allow storage permission when prompted.

**Step 2:** Open the FFsensi folder

```bash
cd storage/shared/Download/FFsensi-main
```

**Step 3:** Run

```bash
python3 get_sensi.py
```

---

### Method 2 â€” Git Clone (Easier)

```bash
pkg install git python
git clone https://github.com/karim2762/FFsensi.git
cd FFsensi
python get_sensi.py
```

---

## ðŸ“‚ File Structure

```
FFsensi/
â”‚
â”œâ”€â”€ README.md
â”œâ”€â”€ get_sensi.py              â† Main launcher
â”œâ”€â”€ i0x.sh                    â† Auto install & run script
â”‚
â”œâ”€â”€ x9k/
â”‚   â”œâ”€â”€ m7q.py                â† Device Detection Engine
â”‚   â”œâ”€â”€ p4r.py                â† Benchmark & Performance Engine
â”‚   â”œâ”€â”€ s2k.py                â† Sensitivity Generator
â”‚   â”œâ”€â”€ t8n.py                â† Boost Script Generator
â”‚   â”œâ”€â”€ v1u.py                â† Terminal UI & Colors
â”‚   â””â”€â”€ d8f.json              â† Device Tier Database
â”‚
â””â”€â”€ o0x/
    â”œâ”€â”€ x_device.txt          â† Generated Sensitivity
    â”œâ”€â”€ x_device.json         â† Detailed Scan Report
    â”œâ”€â”€ b0x.sh                â† Performance Boost Script
    â””â”€â”€ g0x.sh                â† Game Optimization Script
```

---

## ðŸš€ Available Commands

| Command | Description |
|---|---|
| `python3 get_sensi.py` | Full Device Scan & Generate Sensitivity |
| `python3 get_sensi.py --q` | Quick Scan Mode |
| `python3 get_sensi.py --i` | Show Device Information |
| `python3 get_sensi.py --qp` | Generate Performance Scripts |
| `python3 get_sensi.py --rn 5` | Run Benchmark 5 Times |
| `python3 get_sensi.py --rn 10` | Run Benchmark 10 Times |
| `python3 get_sensi.py --m DEVICE_NAME` | Manual Device Name |
| `bash i0x.sh` | Auto Setup & Run FFsensi |

---

## ðŸŒ Follow Us

<p align="center">
  <a href="https://t.me/Kexer_hub">
    <img src="https://img.shields.io/badge/@Kexer__hub-Telegram-blue?style=flat-square&logo=telegram">
  </a>
  <a href="https://youtube.com/@kexer144">
    <img src="https://img.shields.io/badge/@kexer144-YouTube-red?style=flat-square&logo=youtube">
  </a>
  <a href="https://instagram.com/kexer.vx">
    <img src="https://img.shields.io/badge/@kexer.vx-Instagram-purple?style=flat-square&logo=instagram">
  </a>
</p>

### ðŸ“¢ Stay Connected

* ðŸ’¬ Telegram â€” Community updates & support
* ðŸŽ¥ YouTube â€” Tutorial videos & guides
* ðŸ“¸ Instagram â€” Project updates & sneak peeks
* ðŸ”¥ Free Fire tools & resources

> Follow all platforms to get the latest updates, tutorials, and new releases.

---

<p align="center">
  <b>Made with â¤ï¸ for the Free Fire Community</b>
</p>
