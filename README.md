นพรัตน์ ภักดีรัตน์ เลขที่ 10 รหัส 45151

Food Truck Ordering System – OOAD + GitHub Project

บทนำ

ระบบนี้เป็น Web Application สำหรับการสั่งอาหารจาก Food Truck ในพื้นที่ใกล้เคียง โดยลูกค้าสามารถค้นหา เลือกเมนู สั่งอาหาร และชำระเงินได้ผ่านระบบออนไลน์ พัฒนาโดยใช้หลักการวิเคราะห์และออกแบบเชิงวัตถุ (OOAD)

 ฟีเจอร์ระบบ

ลูกค้า:
  - ค้นหา Food Truck ใกล้พื้นที่
  - เลือกเมนูและสั่งอาหาร
  - เลือกรับอาหารหน้ารถ หรือเดลิเวอรี่
  - ชำระเงินออนไลน์
  - ตรวจสอบสถานะการสั่งอาหาร

พนักงาน:
  - รับออเดอร์จากระบบ
  - เตรียมอาหารตามลำดับ
  - อัปเดตสถานะออเดอร์

ผู้จัดการระบบ:
  - เพิ่ม/แก้ไขข้อมูล Food Truck
  - จัดการเมนูของแต่ละคัน
  - ตรวจสอบรายงานยอดขาย

เทคโนโลยีที่ใช้
Frontend: React / HTML / Tailwind CSS  
Backend: Node.js + Express  
Database: MongoDB  
DevOps: GitHub + CI/CD (GitHub Actions)

Diagram ที่ใช้

 Use Case Diagram: ./docs/usecase-foodtruck.png
Sequence Diagram:./docs/sequence-order-foodtruck.png

Class Diagram: ./docs/class-foodtruck.png  
Activity Diagram: ./docs/activity-order-process.png
