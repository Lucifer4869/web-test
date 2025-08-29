เว็บเป็นงานโปรเจคจบ งาน RFID มหาวิทยาลัยราชภัฏสวนสุนันทา สำหรับบัญฑิตจบรับปริญญา 
หากจะเปิดเว็บ โปรดinstallคำสั่งเหล่านี้ก่อน 
npm install concurrently 
pip install -r requirements.txt

ไฟล์ .env (สำหรับ frontend)
VITE_API_BASE=http://localhost:8001

VITE_USE_WEBSOCKET=false

ไฟล์ .env (สำหรับ backend)

SECRET_KEY='django-insecure-j=^xs4wja2)#p6%u#63(z2fd-ld0q80xp8jme%h0n6$a#w&7ri'
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost,sv.ssrurufi.com

DB_NAME=ssru_student_db
DB_USER=root
DB_PASSWORD=
DB_HOST=localhost
DB_PORT=3306

USE_CHANNEL=false

#ขอบพระคุณมากครับ
