# 🦉 OCupsX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OCupsX** — CUPS Printing-Service Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

CUPS printing-service configuration security auditor

---

## ✨ Features

- Stdlib CUPS directive / <Block> parser (Location, Policy, Limit, Printer, Class, Subscription) with line tracking
- cupsd — Listen / Port 631 exposure, ServerAlias *, Location / Order / Allow ACL evaluation, remote admin, Policy / Limit operation authorisation, AuthType, DefaultEncryption, SSLOptions, Browsing, logging, limits
- cups-files — FileDevice, SystemGroup, User / Group, RemoteRoot, Sandboxing, file / log perms, spool dirs, ServerKeychain private keys
- printers.conf — shared queues, DeviceURI credentials (masked), file: devices, plaintext backends, OpPolicy
- client.conf — Encryption, ValidateCerts, AllowAnyRoot, AllowExpiredCerts, TrustOnFirstUse, legacy SSL
- cups-browsed — remote 'cups' protocol (CVE-2024-47176 chain), BrowseAllow, auto-created / re-shared queues
- Secrets masked; --root discovery; CWE + MITRE; A+..F
- TXT / MD / JSON / CSV / SARIF; --demo; --fail-on

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OCupsX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
