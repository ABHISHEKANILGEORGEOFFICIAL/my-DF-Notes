# 🛡️ VirusTotal Analysis Report — `LBpiy.exe` (inside `malware_sample.zip`)

> **Summary:**  
> 55/72 security vendors flagged this file as malicious.  
> Family tags reported by engines: **Kryptik / Taskun / SnakeStealer / Formbook variants**.

---

## 📁 File Information

- **Filename:** `LBpiy.exe`
- **Contained in:** `malware_sample.zip` (password-protected)
- **Size:** 902 KB
- **Hashes:**
  - **MD5:** `f1fd4cf59c5cfb5e4ab5fd8570889fdb`
  - **SHA1:** `48543fec63c090153308892c3cdfc411979c4b45`
  - **SHA256:** `ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1`

---

## 🧪 Detection Overview

- **Vendors Detected:** `56 / 72`  
- **Community Score:** **−12** (negative reputation)

---

### 📋 Vendor Detection Results

| **Engine** | **Detection** |
|---|---|
| AhnLab-V3 | Malware/Win.Kryptik.C5784104 |
| Alibaba | Trojan:MSIL/Taskun.cf3a01e2 |
| AliCloud | Trojan:MSIL/Egairtigado.Gen |
| ALYac | Trojan.GenericKDZ.112786 |
| Arcabit | Trojan.Generic.D1B892 |
| Arctic Wolf | Unsafe |
| Avast | Win32:MalwareX-gen [Pws] |
| AVG | Win32:MalwareX-gen [Pws] |
| Avira (no cloud) | TR/AD.SnakeStealer.lzrbr |
| BitDefender | Trojan.GenericKDZ.112786 |
| CrowdStrike Falcon | Win/malicious_confidence_100% (D) |
| CTX | Exe.trojan.msil |
| DeepInstinct | MALICIOUS |
| DrWeb | Trojan.Packed2.49940 |
| Elastic | Malicious (high Confidence) |
| Emsisoft | Trojan.GenericKDZ.112786 (B) |
| eScan | Trojan.GenericKDZ.112786 |
| ESET-NOD32 | A Variant Of MSIL/Kryptik.AOBM |
| Fortinet | MSIL/Formbook.HDZY!tr |
| GData | Trojan.GenericKDZ.112786 |
| Google | Detected |
| Gridinsoft | Trojan.Win32.Wacatac.sa |
| Huorong | TrojanSpy/MSIL.Stealer.js |
| Ikarus | Trojan.MSIL.Inject |
| K7AntiVirus | Trojan (005cb4e21) |
| K7GW | Trojan (005cb4e21) |
| Kaspersky | HEUR:Trojan.MSIL.Taskun.gen |
| Kingsoft | MSIL.Trojan.Taskun.gen |
| Lionic | Trojan.Win32.Taskun.4!c |
| Malwarebytes | Trojan.MalPack.PNG.Generic |
| MaxSecure | Trojan.Malware.407633379.susgen |
| McAfee Scanner | Ti!AE2A513B61FE |
| Microsoft | Trojan:Win32/Egairtigado!rfn |
| Palo Alto Networks | Generic.ml |
| Panda | Trj/Chgt.AD |
| QuickHeal | Trojan.MSIL |
| Rising | Malware.Obfus/MSIL@AI.100 |
| Sangfor Engine Zero | Infostealer.Msil.Taskun.Vb92 |
| SecureAge | Malicious |
| Skyhigh (SWG) | BehavesLike.Win32.Generic.dc |
| Sophos | Troj/Krypt-AQM |
| Symantec | Scr.Malcode!gdn34 |
| Tencent | Malware.Win32.Gencirc.1499b3e7 |
| Trapmine | Malicious.high.ml.score |
| Trellix ENS | Artemis!F1FD4CF59C5C |
| TrendMicro | TrojanSpy.Win32.NEGASTEAL.YXFG5Z |
| TrendMicro-HouseCall | TrojanSpy.Win32.NEGASTEAL.YXFG5Z |
| Varist | W32/MSIL_Kryptik.MNI.gen!Eldorado |
| VIPRE | Trojan.GenericKDZ.112786 |
| VirIT | Trojan.Win32.GenusT.FBKH |
| Webroot | Win.Trojan.Gen |
| WithSecure | Trojan.TR/AD.SnakeStealer.lzrbr |
| Yandex | Trojan.Igent.b4RFmo.2 |
| Zillya | Trojan.Kryptik.Win32.5445530 |
| ZoneAlarm | Troj/Krypt-AQM |



---

## 📡 Network Indicators

- Possible C2 overlaps with **Taskun** family and **Formbook** variants.  
- *Behavior tags: peexe, spreader, detect-debug-environment, clipboard, assembly, calls-wmi, long-sleeps.*

---

## 📊 Behavioral Summary

- **Evasion:** Anti-debugging, sandbox detection, long sleep delays  
- **Capabilities:** Clipboard access, WMI command execution, spreading via removable media/network shares  
- **Tags:** `peexe`, `spreader`, `detect-debug-environment`, `clipboard`, `assembly`, `calls-wmi`, `long-sleeps`

---

## 🗣️ Community Insight

- **Community Score:** 12 (Negative reputation). 
- Several community members classify as info-stealer Trojan.
---

## 🔐 Public Links

- **Main Report: Summary** [View on VirusTotal](https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1/summary)  
- **Detection Tab:** [Direct Link to Detection Results](https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1/detection)

---

## 🖼️ Screenshots

- **Detection Overview:**  
  ![VT Detection Screenshot](vt_detection.png)

- **Vendor List:**  
  ![VT Vendors Screenshot](vt_vendors.png)



