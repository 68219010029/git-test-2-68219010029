# gittest2.1
ห้อง 1-2

1. สร้าง Repository ใหม่บน GitHub ของตนเองชื่อ git-test-2-รหัสประจำตัวนร(รหัสเต็ม)
2. ตั้งค่าชื่อ git ในเครื่องเป็น ชื่อจริง_นามสกุล และอีเมลเป็น อีเมลของวิทยาลัย
3. Clone Git URL มาไว้ที่เครื่อง
4. สร้างไฟล์ index.txt พิมพ์ข้อความบรรทัดแรกว่า "Version 1.0" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Add index.txt for V.1"
5. สร้าง Branch ใหม่ชื่อ hotfix1 และสลับไปทำงานที่ Branch นี้
6. เปิดไฟล์ index.txt ขึ้นมา แก้ไขบรรทัดที่ 1 จาก "Version 1.0" เป็น "Version 2.0 (Hotfix)" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Update version to 2.0"
7. สลับกลับมาที่ Branch หลัก (main หรือ master)
8. ใน Branch หลัก ให้เปิดไฟล์ index.txt ขึ้นมาอีกครั้ง แล้วแก้บรรทัดที่ 1 จาก "Version 1.0" เป็น "Version 1.5 (Main)" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Update version to 1.5 by team"
9. สร้าง Branch ใหม่ชื่อ hotfix2 และสลับไปทำงานที่ Branch นี้
10. เปิดไฟล์ index.txt ขึ้นมา และเพิ่มข้อความบรรทัดใหม่ว่า "edit by [ชื่อจริงของนักเรียน]" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Add edit by [ชื่อนร.]"
11. เปลี่ยนชื่อ Branch hotfix2 เป็น hotfix
12. ทำการลบ Branch hotfix1 ทิ้ง
13. สลับกลับมาที่ Branch หลัก (main หรือ master) จากนั้นให้พิมพ์คำสั่งนี้เพื่อดึงประวัติการทำงานแทนการแคปหน้าจอ:
     git log --all --oneline --graph > my-history.txt
14. ทำการ Add และ Commit ไฟล์ my-history.txt บน Branch หลัก
15. ทำการ Push โค้ด ทั้ง Branch หลัก และ Branch hotfix ขึ้น GitHub ของตนเอง
