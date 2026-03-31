## การจำแนกการใช้ที่ดินในจังหวัดจันทบุรี
พื้นที่ศึกษา จังหวัดจันทบุรี

## ข้อมูลเบื้องต้นของการทำโมเดล

1.1 การแบ่งที่ดิน
แบ่งเป็น 5 คลาส ได้แก่
1. เกษตร
2. ป่า
3. เมือง
4. น้ำ
5. พื้นที่เบ็ดเตล็ด (อื่นๆ)

1.2 Training Samples

ใช้ข้อมูลจาก ESA World cover

1.3 Train/Validation

มีการทำ 80/20 แบบสุ่ม โดยนักศึกษาสุ่ม 1000 จุด ได้ Train size: 4055 และ Test size: 945

1.4 Feature ที่ใช้

1. NDVI (Normalized Difference Vegetation Index) ใช้วัดพื้นที่ที่มีพืช
2. NDBI (Normalized Difference Built-up Index) ใช้ตรวจจับพื้นที่เมือง/สิ่งปลูกสร้าง
3. NDWI (Normalized Difference Water Index) ใช้ตรวจจับน้ำหรือความชื้นบนพื้นผิว

## การเปรียบเทียบอัลกอริทึ่ม
