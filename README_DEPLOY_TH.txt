TU Drilling PWA V9

ไฟล์หลัก: index.html

ทดสอบในเครื่อง (ต้องใช้ localhost หรือ HTTPS):
  python -m http.server 8080
  เปิด http://localhost:8080

Deploy ด้วย Azure Static Web Apps:
1) อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้เข้า GitHub repository
2) Azure Portal > Create a resource > Static Web App
3) เชื่อม GitHub repository และ branch
4) Build Presets: Custom
5) App location: /
6) API location: เว้นว่าง
7) Output location: เว้นว่าง
8) หลัง deploy ให้เปิด URL ผ่าน HTTPS

ติดตั้งมือถือ:
- Android/Edge/Chrome: กดปุ่ม ติดตั้งแอป หรือเมนู Install app
- iPhone/iPad Safari: Share > Add to Home Screen

หมายเหตุ: Dashboard และข้อมูล snapshot ถูกคงไว้ใน index.html; Service Worker ทำให้เปิด shell ล่าสุดที่เคยโหลดได้เมื่อ offline
