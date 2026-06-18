TG Data Governance Project Control — Web App

ไฟล์หลัก:
- index.html เปิดใช้งานด้วย Web Browser ได้ทันที
- templates/Gantt_Update_Template.csv
- templates/MD_2569_Update_Template.csv

ข้อมูลที่แสดง:
1) Gantt Chart — ข้อมูลจากชีท Gantt Chart
2) MD 2569 — แผนและการใช้ Man-Day พร้อมหน้าบันทึกรายการ

การบันทึก:
ข้อมูลที่เพิ่มหรือแก้ไขจะเก็บใน Local Storage ของ Browser เครื่องนั้น
ควร Export CSV เป็นระยะเพื่อสำรองและใช้ย้ายข้อมูลระหว่างเครื่อง

การนำเข้า CSV:
- Gantt: อัปเดต/เพิ่มรายการโดยใช้ WBS เป็นรหัสหลัก
- Man-Day: อัปเดต/เพิ่มรายการโดยใช้ ID หรือ Date + Person + Task
ไฟล์ควรบันทึกเป็น UTF-8 CSV

ลิงก์เอกสาร:
- TG มหิดล: https://drive.google.com/drive/folders/0AM0MHyArwN95Uk9PVA
- TG ฝั่ง TG: https://thaiairways365.sharepoint.com/sites/THAIProjectCenter/TGDG/Forms/AllItems.aspx
