# Smart English Lab 🐾
> **สื่อการเรียนรู้ภาษาอังกฤษ (ฟัง-พูด) พร้อมระบบตรวจจับสำเนียง สไตล์แก๊งเพื่อนสัตว์สุดน่ารัก**  
> *Smart English: Listening & Speaking Lab with Pronunciation & Accent Assessment*

[![Status](https://img.shields.io/badge/Status-100%25%20Verified-success.svg)](PROGRESS.md)
[![License](https://img.shields.io/badge/License-Copyright%202026-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20PWA%20%7C%20Mobile-orange.svg)](index.html)

---

## 🌟 ฟีเจอร์เด่น (Key Features)

1. **🎨 หน้า Landing Page ต้อนรับพร้อมแก๊งเพื่อนสัตว์ (Mascot Companions):**
   - มีมาสคอตสัตว์ 6 ตัวให้เลือก (🐱 เหมียวมีมี่, 🐶 ตูบบัดดี้, 🐼 แพนด้าโบ, 🦊 ฟ็อกซี่, 🐰 บันนี่, 🦉 พี่ฮูก)
   - มาสคอตจะเด้งดุ๊กดิ๊กและพูดคุยให้กำลังใจตามผลคะแนนจริงของผู้เรียน
2. **🎧 ฟังเสียงต้นแบบธรรมชาติ (Natural TTS with Dynamic Highlighting):**
   - อ่านออกเสียงเนื้อหาภาษาอังกฤษ ปรับระดับความเร็วได้ (`0.75x`, `1.0x`, `1.25x`)
   - ไฮไลต์คำศัพท์แบบเรียลไทม์ตามจังหวะการอ่าน
3. **🎙️ อัดเสียงตนเองและเปรียบเทียบเสียง (A/B Audio Comparison):**
   - อัดเสียงผ่านไมโครโฟน พร้อมแสดงกราฟคลื่นเสียงสด (Live Audio Waveform)
   - มีปุ่มสลับฟัง: `[🔊 เสียงคุณครู (ต้นแบบ)]` เทียบกับ `[🎙️ เสียงของหนูเอง]`
4. **🎯 ระบบประเมินการออกเสียง 4 มิติมาตรฐานสากล:**
   - **ความถูกต้อง (Accuracy Score):** คำนวณความคล้ายคลึงหน่วยเสียง (Phonetic Distance) ด้วย Levenshtein + Soundex
   - **ความคล่องแคล่ว (Fluency Score):** คำนวณความเร็ว WPM เทียบกับเกณฑ์มาตรฐาน
   - **ความครบถ้วน (Completeness Score):** ตรวจจับคำที่พูดตกหล่น (Omission) หรือพูดเกิน (Insertion)
   - **สำเนียงและจังหวะ (Prosody & Accent Score):** ประเมินท่วงทำนองและการลงน้ำหนักเสียง
5. **💡 คำแนะนำการวางรูปปากสำหรับคนไทยโดยเฉพาะ:**
   - แนะนำวิธีจัดวางลิ้น ฟัน และริมฝีปากสำหรับเสียงปราบเซียน (TH, R/L, V/W, Final -s, Final -ed)
6. **🧩 โหมดฝึกจัดเรียงประโยค (Interactive Sentence Scramble):**
   - แตะคำศัพท์เพื่อเรียงประโยคให้ถูกต้องตามไวยากรณ์ พร้อมปุ่มกดส่งไปฝึกพูดต่อทันที
7. **🎯 คลังคำผิดอัจฉริยะ (Spaced Repetition Mistake Bank):**
   - บันทึกคำที่ออกเสียงผิดอัตโนมัติ ปลดล็อกสถานะ "🌟 เชี่ยวชาญแล้ว" เมื่อพูดถูกติดต่อกัน 3 ครั้ง

---

## 🚀 วิธีเปิดใช้งานผ่าน GitHub Pages (ฟรีตลอดชีพ 100%)

1. Fork หรือสร้าง Repository บน GitHub
2. ไปที่แท็บ **Settings** ของ Repository
3. ที่เมนูด้านซ้าย เลือก **Pages**
4. ในส่วน **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
   - กด **Save**
5. รอ 30 วินาที จะได้ URL เว็บไซต์พร้อมใช้งานทันที เช่น:  
   `https://<username>.github.io/<repository-name>/`

---

## 💻 วิธีเปิดทดสอบในเครื่องคอมพิวเตอร์ (Local Offline)

```bash
# ดับเบิ้ลคลิกไฟล์ START.bat
# หรือรันคำสั่ง:
node server.js
```
เปิดเบราว์เซอร์ไปที่: `http://localhost:3000`

---

## 🧪 การตรวจสอบคุณภาพระบบ (Automated QA Pipeline)

```bash
# รันชุดทดสอบ 14 Unit Tests:
node --test test/*.test.js

# รันระบบตรวจสอบความสมบูรณ์ทั้งระบบ:
node verify.js
```

---

## 🔒 ลิขสิทธิ์ (Copyright)

**ลิขสิทธิ์ห้ามทำซ้ำหรือลอกเลียนแบบ 2026 • Smart English Lab 🐾 All Rights Reserved**
