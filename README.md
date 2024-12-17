# HW1
ส่วนที่ 1: การเตรียมโปรเจค
git clone <your-repo-url>

ส่วนที่ 2: สร้าง branch สําหรับพัฒนา
git checkout -b development
git add .
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
git push --set-upstream origin development

ส่วนที่ 3: สร้าง branch สําหรับพัฒนา home page
git checkout -b feature/home-page
git add .
git commit -m "สร้างหน้า Home พื้นฐาน"
git add .
git commit -m "เพิ่มส่วนหัวของเว็บไซต์"
git add .
git commit -m "เพิ่มเมนูแฮมเบอร์เกอร์"
git add .
git commit -m "เพิ่มเมนูหลัก"
git add .
git commit -m "เพิ่มเมนูย่อยที่จะเปิดเมื่อคลิกเมนูแฮมเบอร์เกอร์"
git add .
git commit -m "เพิ่มเนื้อหาหลักของเว็บไซต์"
git add .
git commit -m "เพิ่มส่วนท้ายของเว็บไซต์"
git add .
git commit -m "เพิ่มส่วนสคริปต์ควบคุมเมนูแฮมเบอร์เกอร์"

ส่วนที่ 4: สร้าง branch สําหรับพัฒนา contact
git checkout -b feature/contact
git add .
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
git add .
git commit -m "เพิ่ม Hamburger Menu (☰) สำหรับเมนูในมือถือ"
git add .
git commit -m "เมนูหลักที่แสดงในหน้าคอมพิวเตอร์"
git add .
git commit -m "เมนูย่อยที่จะแสดงเมื่อคลิกที่ Hamburger Menu"
git add .
git commit -m "เพิ่มฟอร์มติดต่อ"
git add .
git commit -m "เพิ่มส่วนท้ายของเว็บไซต์"
git add .
git commit -m "เพิ่มส่วนสคริปต์ควบคุมเมนูแฮมเบอร์เกอร์"

ส่วนที่ 5: สร้าง branch สําหรับพัฒนา details
git checkout -b feature/details
git add .
git commit -m "สร้างโครงสร้างพื้นฐานหน้าสถานที่ท่องเที่ยว"
git add .
git commit -m "เพิ่ม Hamburger Menu (☰) สำหรับเมนูบนมือถือ"
git add .
git commit -m "เพิ่มเนื้อหาเมนูหลัก"
git add .
git commit -m "เพิ่มเมนูย่อยที่จะปรากฏเมื่อคลิกที่ Hamburger Menu"

ส่วนที่ 6: สร้าง Branch สำหรับพัฒนา CSS
1. สร้าง Branch ใหม่
git checkout -b feature/css
2. แก้ไขไฟล์ styles.css
เพิ่มหรือปรับแต่ง CSS ตามที่ต้องการ
3. Commit การเปลี่ยนแปลง
git add .
git commit -m "เพิ่มส่วนตกแต่ง"

ส่วนที่ 7: Merge Branch
1. เปลี่ยนกลับไปยัง Branch development
git checkout development
2. Merge Branch feature/home-page, feature/contact, feature/details และ feature/css เข้ากับ development
git merge feature/home-page
git merge feature/contact
git merge feature/details
git merge feature/css
3. Push ขึ้น GitHub
git push origin development
