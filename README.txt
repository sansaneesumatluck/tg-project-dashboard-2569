TG Project Dashboard 2569 - Web App

เวอร์ชันนี้ใช้สไตล์เดิม และเพิ่มความสามารถในการอัปโหลดไฟล์ Excel/CSV เพื่ออัปเดต Gantt Chart

ไฟล์หลัก
- index.html
- templates/Gantt_Update_Template.csv
- templates/MD_2569_Update_Template.csv

การอัปเดต Gantt Chart
1. เปิด Web App
2. กดปุ่ม “นำเข้าไฟล์”
3. เลือกไฟล์ .xlsx ที่มีชีทชื่อ “Gantt Chart” หรือไฟล์ .csv
4. ตรวจสอบ Preview
5. ถ้าต้องการแทนข้อมูลเดิมทั้งหมด ให้ติ๊ก “แทนที่ข้อมูล Gantt Chart เดิมทั้งหมด”
6. กด “อัปเดตข้อมูล”

คอลัมน์ที่รองรับสำหรับ Gantt Chart
WBS, Task / Activity, Deliverable, Owner, Start, End, Duration, Status, % Complete, Remark

หมายเหตุ
- ข้อมูลที่อัปเดตจะบันทึกใน Browser ของผู้ใช้เครื่องนั้น
- หากต้องการอัปเดตไฟล์เว็บไซต์บน GitHub ถาวร ให้ Export CSV แล้วนำไปปรับในไฟล์ต้นทางหรืออัปเดต data/default ในโค้ดภายหลัง
- GitHub Pages เป็น static hosting จึงไม่สามารถบันทึกข้อมูลกลับไปที่ repository อัตโนมัติได้
