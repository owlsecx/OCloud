# 🦉 OCloud

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OCloud** — Cloud Evidence Collector

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OCloud is a cloud-evidence collector for digital forensics that parses exports from consumer cloud services. It analyses Google Takeout archives and iCloud backups, extracts EXIF metadata from photo folders, builds location timelines and enumerates linked devices. Parsed evidence, including WhatsApp chat exports, can be saved to a JSON report or exported as KML.

---

## ✨ Features

- Google Takeout ZIP analysis
- iCloud backup folder analysis
- EXIF metadata extraction from image folders
- Location timeline building and KML export
- WhatsApp chat-export parsing and linked-device enumeration
- Auto-detection of cloud export type and JSON report output

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OCloud -g takeout.zip
./OCloud -p ./photos/ -o report.json
./OCloud --detect ./export/
./OCloud --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
