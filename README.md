# Lifeprajum PRODUCTION

เว็บไซต์ของ Lifeprajum PRODUCTION ทีมโปรดักชันงานภาพ วิดีโอ และงานตัดต่อ

เป็นเว็บแบบ static (HTML ล้วน) ไม่ต้อง build ใดๆ ขึ้น Vercel ได้ทันที

## โครงสร้าง
- `index.html` หน้าหลัก
- `photo.html` บริการภาพ
- `portrait.html` ภาพถ่ายพอร์ตเทรต (บุคคล / วันรับปริญญา)
- `street.html` ภาพ Street / Fashion
- `video.html` ผลงานวิดีโอ (ฝังจาก YouTube)
- `images/` ภาพผลงานในแกลเลอรี (webp)
- `media/hero/` คลิปและภาพในกล่องเลื่อนของหน้าหลัก
- `media/covers/` ภาพปกการ์ด
- `media/burst/` ภาพเล็กที่พุ่งออกมาตอนชี้คำตอบ

## เพิ่มภาพในแกลเลอรี
แปลงภาพเป็น webp กว้างไม่เกินราว 1500px แล้วเพิ่ม `<figure class="ph">` ในหน้านั้น โดยใส่ `data-w` / `data-h` ให้ตรงกับขนาดภาพ
