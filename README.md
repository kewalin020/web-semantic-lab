# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development

## รายละเอียด
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels

## คำสั่ง git
1. การเตรียมโปรเจค
    1. git clone https://github.com/kewalin020/web-semantic-lab
    2. แก ้ไขไฟล์Readme.md
        1. git add Readme.md
        2. git commit -m "แก้ไขไฟล์Readme.md”
        3. git push
2. สร้าง branch ชื่อ development
    1. git checkout -b development
    2. git add .
    3. git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น”
3. สร้าง branch feature/homepage
    1. git checkout -b feature/homepage
    2. git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค”
4. การพัฒนาหน้าหลักด ้วย Semantic HTML
    1. git commit -m "เพิ่ม header และ nav ในหน้าหลัก”
    2. git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก”
    3. git commit -m "เพิ่ม aside และ footer ในหน้าหลัก”
5. การสร้างฟอร์มติดต่อพร้อม Validation
    1. git checkout -b feature/contact
    2. git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ”
    3. git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ”
    4. git commit -m "เพิ่ม validation ในฟอร์มติดต่อ"
6. การเพิ่ม ARIA Labels
    1. git commit -m "เพิ่ม ARIA labels ในฟอร์ม”
    2. git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
7. การทดสอบและส่งงาน
8.  merge feature เขา branch development และ push
    1. เปลี่ยนกลับไปยัง branch development
        1. git checkout development
    2. merge feature/homepage และ feature/contact เข้า development
        1. git merge feature/homepage
        2. git merge feature/contact
    3. push ขึ้น GitHub เพื่ออัพโหลดการเปลี่ยนแปลงจาก branch development ในเครื่องของเราไปยัง remote repository
        1. git push origin development
    4. สร้าง Pull Request เข้า main branch บน GitHub ดําเนินการให้เสร็จสิ้น