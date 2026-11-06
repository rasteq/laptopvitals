<div align="center">

# L A P T O P &nbsp; V I T A L S &nbsp; P R O
### *The Lightweight, Zero-Dependency Telemetry & Hardware Diagnostics Utility*

[![Live Showcase](https://img.shields.io/badge/LIVE_SHOWCASE-rasteq.github.io%2Flaptopvitals-ED2024?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rasteq.github.io/laptopvitals/)
[![GitHub Repo](https://img.shields.io/badge/REPO-laptopvitals-0ea5e9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rasteq/laptopvitals)
[![Download](https://img.shields.io/badge/DOWNLOAD-v1.0.0_PORTABLE-2563eb?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/rasteq/laptopvitals/releases/latest/download/LaptopVitals-v1.0.0.exe)
[![License](https://img.shields.io/badge/LICENSE-MIT-10b981?style=for-the-badge)](LICENSE)
[![Privacy](https://img.shields.io/badge/PRIVACY-100%25_OFFLINE-a855f7?style=for-the-badge)](https://rasteq.github.io/laptopvitals/)

<br/>

> **"Engineered for clarity, speed, and accuracy. The single-binary telemetry companion built for Windows laptops and workstations."**

<br/>

[**Launch Web Showcase**](https://rasteq.github.io/laptopvitals/) &nbsp;•&nbsp; [**Download Portable Binary (.exe)**](https://github.com/rasteq/laptopvitals/releases/latest/download/LaptopVitals-v1.0.0.exe)

<br/>

<p align="center">
  <img src="assets/preview_02.png" alt="Laptop Vitals Pro Native Dark Interface" width="100%" style="border-radius: 8px; border: 1px solid #1f2430;">
</p>

</div>

<br/>

### Description

**Laptop Vitals Pro** is an ultra-fast, zero-bloat system health and hardware diagnostics tool engineered specifically for Windows laptops and workstations.

Packaging real-time hardware introspection, event-log-derived screen time analytics, battery degradation forensics, NVMe SMART telemetry, Wi-Fi security audits, and junk cleaning into a single ~343 KB portable binary, Laptop Vitals Pro runs instantly on vanilla Windows without requiring any runtimes, installers, or third-party packages.

<br/>

### Key Capabilities

- **Battery Health & Wear Forensics:** Inspect factory design capacity vs. full charge capacity in mWh, exact wear percentage, real hardware cycle counts, and 24-hour charge/discharge history.
- **Screen Time Analytics:** Accurate active display time and continuous session breakdowns derived directly from Windows Kernel sleep/wake event logs (Events 42, 107, 1, 41).
- **Storage SMART & Temperatures:** Real-time health status, NVMe and SATA SSD operational temperatures, read/write reliability indicators, and partition volume meters.
- **Real-Time Performance Graphs:** Low-overhead live SVG polyline graphs tracking CPU, RAM, Disk I/O, and Network throughput, along with active memory consumers and startup items.
- **Network & Wi-Fi Audits:** Radio protocols (802.11ax/ac/n), band, channel, link speeds, round-trip DNS ping latency test, and a secure offline viewer for saved Wi-Fi keys.
- **Security & Kernel Forensics:** Real-time Windows Defender status, Secure Boot, TPM 2.0 readiness, and 30-day BSOD BugCheck crash logs.
- **Safe Storage Cleaner:** One-click scanning and purging of Windows temporary directories, thumbnail caches, and Windows Update cache to safely reclaim disk space.
- **Executive Diagnostic Certificate:** Generates a sanitized, one-page offline verification report saved directly to the Desktop.

<br/>

### Quick Start

1. Download **`LaptopVitals-v1.0.0.exe`** from the latest release or from the **`release/`** folder.
2. Double-click to launch (zero installation or runtime dependencies required).
3. *(Optional)* Click **"Run as Administrator"** for low-level kernel, battery cycle inspection, and storage SMART sensors.

<br/>

### File Verification (SHA-256)

Verify binary integrity in Windows PowerShell:

```powershell
Get-FileHash release\LaptopVitals-v1.0.0.exe
# SHA-256: 63B545B811CC743B3798DF54EC764339B9103B6DF963554B944113B6703046FD
```

<br/>

---

<div align="center">

### Crafted with intention by [Shahariar Ahammed (@rasteq)](https://github.com/rasteq)

*Designed & engineered with precision for Windows laptops and workstations.*

[![Star on GitHub](https://img.shields.io/badge/Star_this_Project-laptopvitals-f59e0b?style=flat-square&logo=github)](https://github.com/rasteq/laptopvitals)

</div>
