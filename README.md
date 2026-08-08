# Circular-Smart-MoBel-Plastic-Tree
Circular-Smart-MoBel-Plastic-Tree คือ website ที่ช่วยในการออกแบบผลิตภัณฑ์พลาสติกประเภทเครื่องใช้ที่เกี่ยวกับอาหารโดยเป็นมิตรต่อสิ่งแวดล้อม โดย สามารถนำโมเดลที่คุณออกแบบมาแล้วนำเข้า website และ มีระบบช่วยคำนวนคาร์บอนฟุตพริ้นท์ตามวัสดุและขนาดที่คุณเลือกออกแบบ และ ยังมีระบบช่วยคำนึง โดยเลือกวัสดุที่รีไซเคิลได้ง่าย หรือย่อยสลายได้ตามธรรมชาติ นอกจากนี้ คุณยังสามารถเข้าดูผลงานที่คุณออกแบบไว้ได้ในตัว website และยังสามารถเข้าดูตลาดของวัสดุตามที่คุณต้องการว่าคุ้มค่าตามราคาไหม โดย Website นี้ออกแบบมาเพื่อช่วยในการออกแบบผลิตภัณฑ์พลาสติกประเภทเครื่องใช้ที่เกี่ยวกับอาหาร โดยไม่กระทบต่อสิ่งแวดล้อม และ ช่วยลดต้นทุนได้
โดย Website นี้ออกแบบมาเพื่อช่วยในการออกแบบผลิตภัณฑ์พลาสติกประเภทเครื่องใช้ที่เกี่ยวกับอาหาร โดยไม่กระทบต่อสิ่งแวดล้อม และ ช่วยลดต้นทุนได้

นาย มัทธิว ขำดี 67160365
นายอิศรานุวัฒน์ จันทร์แก้ว 67160243

🌿 Circular Smart MoBel Plastic Tree
3D Eco-Packaging Design & Carbon Footprint Calculator

โปรเจกต์ระบบออกแบบบรรจุภัณฑ์อาหารรักษ์โลก (Food Grade) สำหรับกลุ่มธุรกิจ B2B (ร้านอาหาร, โรงงาน, Delivery) ที่มาพร้อมกับระบบสร้างโมเดล 3D Interactive บนหน้าเว็บไซต์ และสามารถคำนวณการลดคาร์บอนฟุตพริ้นท์ (Carbon Footprint) ได้แบบ Real-time เพื่อตอบโจทย์ธุรกิจสีเขียว (ESG)

🛠 เทคโนโลยีที่ใช้ (Tech Stack)
Front-end: HTML5, CSS3, JavaScript (ออกแบบ UI สไตล์ Minimal มินิมอล โทนสีพาสเทล)

Back-end: Node.js พร้อมเฟรมเวิร์ก Express.js สำหรับสร้าง RESTful API

Database: PostgreSQL สำหรับเก็บข้อมูลผู้ใช้งานและข้อมูลวัสดุ

Infrastructure: Docker และ Docker Compose สำหรับจัดการ Container

📁 โครงสร้างโปรเจกต์ (Project Structure)
Plaintext
circular-plastic-project/
│
├── frontend/                 # ส่วนของหน้าเว็บ (Front-end)
│   ├── index.html            # หน้าแรก และพื้นที่จำลองออกแบบ 3D
│   ├── login.html            # หน้าเข้าสู่ระบบ
│   └── register.html         # หน้าสมัครสมาชิก
│
├── backend/                  # ส่วนของ API (Back-end)
│   ├── src/
│   │   ├── index.js          # ไฟล์หลักของ API Server
│   │   └── package.json      # จัดการ Dependencies
│   ├── Dockerfile            # ตั้งค่า Docker Image สำหรับ Node.js
│   └── docker-compose.yml    # จัดการรัน API และ Database
│
└── README.md                 # ไฟล์อธิบายโปรเจกต์
🚀 วิธีการติดตั้งและรันระบบ (How to Run)
สิ่งที่ต้องมีเบื้องต้น (Prerequisites)
เครื่องคอมพิวเตอร์ของคุณจำเป็นต้องติดตั้งโปรแกรมต่อไปนี้:

Docker Desktop (หรือ Docker Engine + Docker Compose)

Web Browser (เช่น Chrome, Edge, Safari) สำหรับเปิดดูหน้าเว็บ

ขั้นตอนการรัน Back-end (API & Database)
เปิด Terminal / Command Prompt และเข้าไปที่โฟลเดอร์ backend/

พิมพ์คำสั่งรัน Docker Compose:

Bash
docker-compose up -d --build
รอให้ระบบดาวน์โหลดและสร้าง Container เมื่อเสร็จสิ้น:

REST API จะทำงานอยู่ที่: http://localhost:3000

Database (PostgreSQL) จะทำงานอยู่ที่ Port: 5432

หมายเหตุ: หากต้องการปิดการทำงานของ Server ให้ใช้คำสั่ง docker-compose down

ขั้นตอนการรัน Front-end (หน้าเว็บ)
เนื่องจากหน้าเว็บเป็น HTML/CSS/JS บริสุทธิ์ คุณสามารถใช้งานได้ง่ายๆ โดย:

เข้าไปที่โฟลเดอร์ frontend/

ดับเบิลคลิกไฟล์ index.html เพื่อเปิดผ่าน Web Browser ได้ทันที

(แนะนำ) หากใช้ VS Code สามารถติดตั้ง Extension ที่ชื่อว่า Live Server แล้วคลิกขวาที่ไฟล์ index.html เลือก "Open with Live Server" เพื่อให้หน้าเว็บรีเฟรชอัตโนมัติเมื่อมีการแก้ไขโค้ด

🔌 การใช้งาน REST API (API Endpoints)
คุณสามารถใช้โปรแกรมอย่าง Postman เพื่อทดสอบยิง API ได้ตามรายการด้านล่างนี้ (Base URL: http://localhost:3000)

1. Authentication (ระบบยืนยันตัวตน)

POST /register - สมัครสมาชิก

POST /login - เข้าสู่ระบบ

POST /logout - ออกจากระบบ

POST /change-password - เปลี่ยนรหัสผ่าน

2. User Management (จัดการข้อมูลผู้ใช้)

GET /me - ดึงข้อมูลโปรไฟล์ของตนเอง

GET /users - ดึงข้อมูลผู้ใช้งานทั้งหมด (มีระบบ Pagination)

GET /users/:id - ดึงข้อมูลผู้ใช้งานตาม ID ที่ระบุ

PUT /users/:id - แก้ไขข้อมูลผู้ใช้งาน

DELETE /users/:id - ลบผู้ใช้งาน

GET /check-username/:name - ตรวจสอบว่า Username นี้ว่างหรือไม่

💡 ฟีเจอร์ที่วางแผนพัฒนาต่อในอนาคต (Future Work)
เชื่อมต่อฟรอนต์เอนด์ index.html เข้ากับไลบรารี Three.js / WebGL เพื่อให้ผู้ใช้สามารถหมุนและปรับขนาดโมเดล 3D กล่องข้าวได้จริง

นำ API ที่เตรียมไว้ไปเชื่อมต่อกับฟังก์ชัน fetch() ในหน้า Front-end เพื่อให้ระบบ Login และ Register บันทึกข้อมูลลง PostgreSQL ได้สมบูรณ์

เพิ่มสูตรการคำนวณ Carbon Footprint ตามชนิดของเม็ดพลาสติก (เช่น PCR, Bioplastics)
