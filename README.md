# Thai Keyboard · แป้นพิมพ์ไทย

A web-based on-screen Thai keyboard built with a single HTML file. Type Thai (เกษมณี / Kedmanee TIS 820-2538) from any device — no installation, no extension, no dependency.

แป้นพิมพ์ไทยบนเว็บแบบไฟล์เดียว ใช้ผังเกษมณีตามมาตรฐาน TIS 820-2538 พิมพ์ภาษาไทยได้จากทุกอุปกรณ์ ไม่ต้องติดตั้ง ไม่ต้องใช้ส่วนเสริม

**Live demo / ทดลองใช้งาน:** https://3bbthailand.github.io/thai-keyboard-web/thai-keyboard_1.html

---

## English

### Features

- **TIS 820-2538 Kedmanee layout** — the official Thai keyboard standard
- **Click or type** — tap the on-screen keys, or use your real keyboard
- **Shift to reveal** — hold Shift to see the secondary Thai glyphs lit up in blue
- **Bilingual mode** — switch between Thai and English layouts on the fly
- **Toolbar actions** — Copy, Paste, Clear, and Done buttons built in
- **Adjustable font size** — make the output area larger or smaller
- **Hover hints** — hover an English letter to see its meaning
- **Dark theme** — modern, easy-on-the-eyes UI with glow accents
- **Zero dependencies** — single HTML file, no build step, no framework
- **Mobile friendly** — responsive layout that works on phones and tablets

### Getting started

1. Open the live demo link above, **or**
2. Clone this repo and open `thai-keyboard_1.html` directly in any modern browser:

   ```bash
   git clone https://github.com/3bbthailand/thai-keyboard-web.git
   cd thai-keyboard-web
   start thai-keyboard_1.html      # Windows
   open thai-keyboard_1.html       # macOS
   xdg-open thai-keyboard_1.html   # Linux
   ```

### How to use

| Action | What to do |
| --- | --- |
| Type a Thai letter | Click the key, or press the matching key on your real keyboard |
| Show shifted glyphs | Press / hold **Shift** to see secondary characters |
| Switch language | Click the **TH / EN** toggle in the toolbar |
| Copy your text | Click **Copy** — the output is placed in your clipboard |
| Paste into the editor | Click **Paste** |
| Clear everything | Click **Clear** |
| Resize text | Use the **A− / A+** controls |

### Tech

- Pure HTML, CSS, and JavaScript — no build tools, no npm
- Web fonts: **Inter** (UI) and **Noto Sans Thai** (Thai glyphs) loaded from Google Fonts
- Uses the standard Clipboard API for copy / paste

---

## ภาษาไทย

### คุณสมบัติ

- **ผังแป้นพิมพ์เกษมณี (TIS 820-2538)** — มาตรฐานแป้นพิมพ์ไทยอย่างเป็นทางการ
- **คลิกหรือพิมพ์ก็ได้** — ใช้เมาส์แตะปุ่มบนหน้าจอ หรือพิมพ์จากคีย์บอร์ดจริง
- **กด Shift เพื่อดูตัวอักษรซ้อน** — ตัวอักษรชั้นที่สองจะสว่างเป็นสีฟ้า
- **สลับภาษาไทย / อังกฤษ** ได้ทันทีในคลิกเดียว
- **แถบเครื่องมือครบ** — คัดลอก, วาง, ล้าง, และ เสร็จสิ้น
- **ปรับขนาดตัวอักษร** ในกล่องข้อความได้
- **ชี้เมาส์เพื่อดูคำแปล** ของตัวอักษรภาษาอังกฤษ
- **ธีมมืด (Dark Theme)** ดีไซน์สมัยใหม่ สบายตา
- **ไม่ต้องใช้ไลบรารีเสริม** — ไฟล์ HTML ไฟล์เดียวจบ
- **รองรับมือถือและแท็บเล็ต** — เลย์เอาต์ปรับขนาดอัตโนมัติ

### วิธีเริ่มต้น

1. เปิดลิงก์ Live demo ด้านบน **หรือ**
2. โคลนรีโปนี้ แล้วเปิดไฟล์ `thai-keyboard_1.html` ในเบราว์เซอร์:

   ```bash
   git clone https://github.com/3bbthailand/thai-keyboard-web.git
   cd thai-keyboard-web
   start thai-keyboard_1.html      # Windows
   open thai-keyboard_1.html       # macOS
   ```

### วิธีใช้งาน

| สิ่งที่ต้องการทำ | วิธีทำ |
| --- | --- |
| พิมพ์ตัวอักษรไทย | คลิกที่ปุ่ม หรือกดแป้นที่ตรงกันบนคีย์บอร์ดจริง |
| ดูตัวอักษรซ้อน (Shift) | กดปุ่ม **Shift** ค้างไว้ |
| สลับภาษา | คลิกที่ปุ่ม **TH / EN** ในแถบเครื่องมือ |
| คัดลอกข้อความ | คลิก **Copy** — ข้อความจะถูกบันทึกในคลิปบอร์ด |
| วางข้อความ | คลิก **Paste** |
| ล้างทั้งหมด | คลิก **Clear** |
| ปรับขนาดตัวอักษร | ใช้ปุ่ม **A− / A+** |

### เทคโนโลยีที่ใช้

- HTML, CSS, และ JavaScript ล้วน ๆ — ไม่ต้อง build, ไม่ต้องใช้ npm
- ฟอนต์: **Inter** (สำหรับ UI) และ **Noto Sans Thai** (สำหรับภาษาไทย) จาก Google Fonts
- ใช้ Clipboard API มาตรฐานในการคัดลอก / วาง

---

## License

Add your preferred license here (MIT recommended for open source projects).
ยังไม่ได้กำหนดสัญญาอนุญาต — แนะนำ MIT License สำหรับโครงการโอเพนซอร์ส
