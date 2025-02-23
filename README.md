### Getting Started

# สื่งที่ต้องมีก่อนติดตั้ง
1. node.js version 20 (ลง [nvm](https://github.com/coreybutler/nvm-windows/releases) ด้วย ใน Assets ของ version ล่าสุดเลือก nvm-setup.exe )
2. android studio

# ติดตั้งโปรเจค
```sh
npm install
```

# เปิด emulator ใน android studio เตรียมไว้

# เช็คความพร้อมในการรันโปรเจค
```sh
npm react-native doctor
```
ถ้ามีไม่ครบจะไม่สามารถรันโปรเจคได้ สามารถถาม ChatGpt เพื่อติดตั้งได้

# รันโปรเจค
```sh
npm run android
```

- จะมี terminal เด้งขึ้นมาใช้สำหรับดูสถานะของแอพและรับคำสั่งจาก dev โดยคำสั่งพื้นฐาน
    - กดปุ่ม r จะรีแอพ เอาไว้ให้รีแอพตอนที่มี ui เปลี่ยน หรือแอพค้าง
    - กดปุ่ม j เปิด dev tool เหมือนของเว็บใช้อ่าน log และดู style

# ถ้าแอพ crash หรือแดง
ปิด terminal และปัดแอพทิ้ง พิมพ์คำสั่งรันใหม่ได้เลย