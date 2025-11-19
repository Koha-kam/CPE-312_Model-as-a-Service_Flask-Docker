# ML Service (Flask + Docker)
โฟลเดอร์นี้เป็นบริการโมเดลแมชชีนเลิร์นนิง โดยใช้ Flask เป็นเว็บเซอร์วิส และสามารถรันด้วย Docker ได้

## โครงสร้างโดยย่อ
- app.py – โค้ดหลักของ Flask แอป
- requirements.txt – รายการไลบรารีที่ใช้งาน
- Dockerfile – ไฟล์ที่ใช้สร้างอิมเมจ Docker

## วิธีใช้งาน
### 1. เตรียมเครื่อง
- ติดตั้ง Docker

### 2. สร้างอิมเมจ Docker
```
docker build -t ml-service:latest .
```

### 3. รันคอนเทนเนอร์
```
docker run -p 5000:5000 ml-service:latest
```

### 4. ทดสอบการใช้งาน
เปิดเบราเซอร์ไปที่ http://localhost:5000/

## สรุป
โหลดมาแล้ว build และ run ได้เลย
