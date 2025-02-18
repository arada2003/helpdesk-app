# 📌 Help desk ticket Management System

## 🔍 เกี่ยวกับโปรเจกต์
โปรเจกต์นี้เป็น ระบบจัดการตั๋วสนับสนุน ที่สามารถทำการสร้างตั๋ว ทำการอัปเดตข้อมูลตั๋วและสถานะของตั๋ว สามารถกรองและเรียงข้อมูลตั๋วจากสถานะและวันที่อัปเดต

พัฒนาโดย นางสาวอารดา แว่นวงษ์ ซึ่งมีการพัฒนาระบบตั้งแต่การออกแบบและพัฒนาระบบทั้ง frontend และ backend รวมถึงการจัดการฐานข้อมูล

## 🛠 เทคโนโลยีที่ใช้  
- **Frontend:** React  
- **Backend:** Golang  
- **Database:** PostgreSql  
- **อื่น ๆ:** Docker

## 🚀 วิธีติดตั้งและใช้งาน 
#### 1. การติดตั้งและการใช้งาน Database
- ทำการ get database จาก [ticketdatabase](https://github.com/arada2003/ticketdatabase)
- จากนั้นทำการ run docker เพื่อสร้าง environment ของ database บนเครื่องของเรา
```bash
# คำสั่งรัน docker
docker-compose up -d
```
- จะเปิด URL: http://localhost:5050 เพื่อเปิด pgAdmin สำหรับจัดการฐานข้อมูล
- เข้าใช้งาน pgAdmin จาก environment ที่กำหนดไว้ในไฟล์ .env

#### 2. การติดตั้งและการใช้งาน Service API
