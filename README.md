# SGQ ตารางงานทีมช่าง — หน้าแอป (LIFF)

หน้าเว็บนิ่งสำหรับ LINE LIFF ของระบบตารางงานทีมช่าง SGQ Co., Ltd.
โฮสต์ที่ URL บนสุดเพื่อให้ LIFF ล็อกอินได้ (Apps Script แสดงหน้าใน iframe จึงล็อกอินไม่ได้)

- `index.html` คัดลอกมาจาก repo หลัก `SGQ-Fab` — **อย่าแก้ที่นี่โดยตรง** แก้ที่ repo หลักแล้วคัดลอกมา
- backend คือ Google Apps Script (`API_URL` ในไฟล์) เรียกผ่าน `fetch` แบบ POST
- ไม่มีข้อมูลลับในไฟล์นี้ (LIFF ID เป็นค่าสาธารณะ)

## ระบบบันทึกค่าใช้จ่าย (กำลังออกแบบ)

- `expense/CONCEPT.md` — คอนเซ็ปต์ระบบ: ดึงสลิปจากกลุ่ม LINE บัญชี → อ่านด้วย AI → Google Sheets → dashboard
- `expense/index.html` — หน้าตัวอย่าง dashboard (ข้อมูลสมมติ ไม่มี backend) เปิดดูได้ที่ `/expense/` บน GitHub Pages
