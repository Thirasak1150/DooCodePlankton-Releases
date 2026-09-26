# DooCodePlankton — ดาวน์โหลด

แอป desktop สำหรับจัดการบันทึกงาน สไลด์ และ Full Agent ที่สั่งงาน + ควบคุม browser ได้จากในแอป
(หน้านี้มีไว้เพื่อแจกตัวติดตั้งเท่านั้น — source code อยู่อีก repo)

## ดาวน์โหลด

| ไฟล์ | สำหรับใคร |
|---|---|
| [DooCodePlankton-Setup-1.3.74.exe](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.74/DooCodePlankton-Setup-1.3.74.exe) | ติดตั้งบน **Windows 10/11 (64-bit)** — รุ่นล่าสุด ปล่อยครั้งแรกบน Windows |
| [DooCodePlankton-1.3.6-arm64.dmg](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.6/DooCodePlankton-1.3.6-arm64.dmg) | ติดตั้งบน macOS Apple Silicon (M1/M2/M3/M4) — **แนะนำสำหรับ Mac** |
| [DooCodePlankton-1.3.6-arm64-mac.zip](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.6/DooCodePlankton-1.3.6-arm64-mac.zip) | ตัวแอป macOS แบบ ZIP (แตกแล้วใช้ได้เลย) |

> ไฟล์อื่นในหน้า Releases (`.blockmap`, `latest.yml`, `latest-mac.yml`) เป็นไฟล์ของระบบอัปเดตอัตโนมัติในแอป ไม่ต้องดาวน์โหลดเอง
> `Source code (zip/tar.gz)` เป็นไฟล์ที่ GitHub สร้างอัตโนมัติ ไม่ใช่ตัวแอป

## มีอะไรใหม่ใน 1.3.74 (Windows ครั้งแรก)

- **รองรับ Windows แล้ว** — ตัวติดตั้ง .exe พร้อม terminal จริงในตัว (ใช้งานได้ทันที ไม่ต้องตั้งค่าเพิ่ม)
- **แคปหน้าเว็บที่ AI กำลังคุมอยู่จริง** (`capture_browser_page`) — เห็นหน้า login/zoom/ผลคลิกล่าสุด ต่างจากแคปแบบเปิดหน้าใหม่
- หน้าต่าง **Test browser** ลอยแยก ให้ AI เปิด dev server แล้วคลิก/กรอก/แคป ในหน้าต่างนั้นได้
- ปุ่มกันหลับ (keep-awake), นาฬิกาหน้า Home, แถบวางข้อความบน webview
- เครื่องมือ "ทำความสะอาดข้อมูล" — สแกนแคชและ node_modules ให้เลือกลบทีละรายการ
- บอร์ดงาน + ปฏิทิน ที่ AI เพิ่มงาน/นัดหมายให้ได้จากในแอป

หมายเหตุ: เครื่องมือควบคุมหน้าจอ Mac (`capture_mac_screen` และชุดเมาส์/คีย์บอร์ด) ใช้ได้บน macOS เท่านั้น

## วิธีติดตั้ง — Windows

1. ดาวน์โหลด `DooCodePlankton-Setup-1.3.74.exe` แล้วดับเบิลคลิก
2. ถ้า SmartScreen เตือน (แอปยังไม่ได้ทำ code signing): กด **More info** → **Run anyway**
3. เลือกโฟลเดอร์ติดตั้งได้ตามต้องการ มี shortcut บน Desktop ให้อัตโนมัติ

## วิธีติดตั้ง — macOS

1. เปิดไฟล์ `.dmg` แล้วลากแอปไป `Applications`
2. เปิดครั้งแรกถ้า macOS ถามเรื่องความปลอดภัย: คลิกขวาที่แอป → **Open** → **Open**
3. ต้องใช้ macOS บนชิป Apple Silicon (arm64)

## อัปเดต

แอปตรวจอัปเดตอัตโนมัติจากหน้า Releases นี้ — กด "ตรวจอัปเดต" ในแอปได้เลย

---

## Download (English)

| File | For |
|---|---|
| [DooCodePlankton-Setup-1.3.74.exe](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.74/DooCodePlankton-Setup-1.3.74.exe) | Windows 10/11 (64-bit) installer — latest, first Windows release |
| [DooCodePlankton-1.3.6-arm64.dmg](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.6/DooCodePlankton-1.3.6-arm64.dmg) | macOS Apple Silicon installer (recommended for Mac) |
| [DooCodePlankton-1.3.6-arm64-mac.zip](https://github.com/Thirasak1150/DooCodePlankton-Releases/releases/download/v1.3.6/DooCodePlankton-1.3.6-arm64-mac.zip) | Zipped macOS app bundle |

## What's new in 1.3.74 (first Windows release)

- Windows support with a real built-in terminal that works out of the box
- Live page capture for the AI browser tools (`capture_browser_page`) — sees the logged-in, zoomed, last-clicked state instead of a fresh page load
- Floating Test browser windows the AI can open and drive
- Keep-awake blocker, home clock, webview paste bar, cache/node_modules cleanup tool
- Task board and work calendar the AI can add entries to

Note: Mac screen control tools (`capture_mac_screen` etc.) are macOS-only.

## Install — Windows

1. Run `DooCodePlankton-Setup-1.3.74.exe`
2. If SmartScreen warns (app is not code-signed): **More info** → **Run anyway**
3. Pick an install folder; a desktop shortcut is created automatically

## Install — macOS

1. Open the `.dmg` and drag the app to `Applications`
2. On first launch, right-click the app → **Open** → **Open**

Screenshots: coming soon.
