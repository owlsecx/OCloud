# ☁️ OCloud

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20Cloud%20Evidence-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-Optional%20(Pillow%2C%20exifread)-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OCloud** is a cloud evidence collector and forensic analyser. It processes Google Takeout ZIP archives, iCloud backups, photo folders with EXIF/GPS, and builds a unified chronological timeline from all extracted evidence.

---

## 📌 Overview

OCloud helps digital forensic investigators quickly extract and correlate evidence from cloud exports:
- Google Takeout (Location History, Search, YouTube, Chrome, Drive…)
- iCloud Backups (Contacts, Calls, SMS, Safari, Device Info…)
- Photo Evidence (EXIF metadata + GPS coordinates)
- Device Identifiers (IMEI, Serial, MAC, UUID, Emails…)

It automatically builds a **unified timeline** across all sources.

---

## 🖥️ Modules

| # | Module                    | Description |
|---|---------------------------|-------------|
| **[1]** | **Google Takeout**        | Analyse Google Takeout ZIP export |
| **[2]** | **iCloud Backup**         | Analyse iCloud / iTunes backup folder |
| **[3]** | **Photo Evidence**        | Extract EXIF + GPS from image folder |
| **[4]** | **Timeline Builder**      | Build unified chronological evidence timeline |
| **[5]** | **Device Profiler**       | Extract device identifiers (IMEI, MAC, UUID, emails…) |

---

## 📊 Key Features

- **Google Takeout Parsing** — Location points, search history, YouTube watch history, Chrome visits, Drive files, account email
- **iCloud Backup Support** — Contacts, call logs, SMS count, Safari history, device info from Manifest.plist
- **EXIF & GPS Extraction** — Camera model, timestamps, GPS coordinates (with Google Maps links)
- **Unified Timeline** — All events sorted chronologically with source tagging
- **Device Fingerprinting** — IMEI, Serial numbers, MAC addresses, UUIDs, Apple/Google IDs
- **Rich Reports** — JSON + TXT export with summaries and hashes
- **Optional Dependencies** — Works without Pillow/exifread (falls back to raw parsing)

---

## ⚙️ Requirements

- **Linux or Windows**
- **Optional**: `pip install Pillow exifread` (for better EXIF/GPS support)

---

## 🚀 Usage

```bash
./OCloud

📁 Output

Extracted Evidence — Location points, contacts, calls, URLs, photos with GPS
Unified Timeline — Chronological view of all events with timestamps
JSON & TXT Reports — Full forensic reports with summaries and hashes
Device Profile — All discovered identifiers (IMEI, MAC, UUID…)


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED FORENSIC ANALYSIS USE ONLY
