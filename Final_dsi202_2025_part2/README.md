รายงานนี้เป็นส่วนหนึ่งของรายวิชา Project DSI202: การพัฒนาซอฟต์แวร์ขั้นสมบูรณ์

# **PeddleCamp – Web Application ที่รวบรวมข้อมูลค่ายหลากหลายประเภท และพื้นที่สำหรับการประชาสัมพันธ์ค่าย**


**จัดทำโดย**: นางสาวภูษิตา สุนทรา  
**รหัสนักศึกษา**: 6624650088  
**นักศึกษาชั้นปีที่ 2** วิทยาลัยสหวิทยาการ สาขาวิทยาศาสตร์และนวัตกรรมข้อมูล มหาวิทยาลัยธรรมศาสตร์  

**วิดีโอประกอบการใช้งาน**: 


---

## **บทคัดย่อ**

ปัจจุบันมีจำนวนนักเรียนในระดับชั้นมัธยมศึกษาหลายคนที่ต้องเผชิญกับปัญหาหลายประการที่มีผลต่อการตัดสินใจและทิศทางในอนาคต อาทิเช่น การขาดความแน่ใจเกี่ยวกับเส้นทางการศึกษาและอาชีพที่ตนเองจะเลือกเดินต่อไป หรือแม้กระทั่งการไม่สามารถเข้าใจถึงความสนใจและความถนัดของตัวเองได้อย่างชัดเจน ทำให้การตัดสินใจเลือกเรียนหรือประกอบอาชีพเป็นเรื่องยาก นอกจากนี้ยังมีปัญหาด้านการเข้าถึงข้อมูลเกี่ยวกับกิจกรรมหรือค่ายต่าง ๆ ที่เปิดรับสมัคร ซึ่งมักจะมีการสื่อสารที่ล่าช้า ข้อมูลไม่ครบถ้วน หรือบางครั้งอาจไม่ได้รับการประชาสัมพันธ์อย่างทั่วถึง


ด้วยเหตุนี้ จึงเกิดความจำเป็นในการพัฒนาเครื่องมือที่สามารถช่วยนักเรียนทุกคนให้สามารถค้นหาข้อมูลเกี่ยวกับค่ายและกิจกรรมต่าง ๆ ที่ตรงกับความสนใจและความถนัดของตนเองได้อย่างรวดเร็วและมีประสิทธิภาพ ซึ่งจะช่วยให้พวกเขาสามารถตัดสินใจได้ดียิ่งขึ้น และสามารถเข้าร่วมกิจกรรมที่ช่วยเสริมทักษะและพัฒนาศักยภาพของตนได้อย่างเหมาะสม


เพื่อแก้ไขปัญหาเหล่านี้ เราจึงได้พัฒนา Web Application ที่มีชื่อว่า PeddleCamp แพลตฟอร์มที่รวบรวมข้อมูลเกี่ยวกับค่ายจากหลากหลายแหล่ง โดยเน้นให้ผู้ใช้สามารถค้นหาค่ายและกิจกรรมที่เปิดรับสมัครได้อย่างรวดเร็ว โดยระบบจะจัดเก็บข้อมูลจากค่ายต่าง ๆ รวมถึงช่วงเวลาการเปิดและปิดรับสมัคร ค่าใช้จ่าย สถานที่ที่จัดอย่างชัดเจน เพื่อให้ผู้ใช้งานสามารถเลือกสมัครได้ตามความต้องการ อีกทั้ง PeddleCamp ยังมีฟีเจอร์ที่ให้ผู้ใช้งานสามารถกรอกข้อมูลความสนใจและงานอดิเรกของตนเอง เพื่อให้ระบบสามารถแนะนำค่ายที่ตรงกับความสนใจและความถนัดได้อย่างแม่นยำ ซึ่งจะช่วยให้นักเรียนสามารถเลือกค่ายที่เหมาะสมกับตนเองได้มากที่สุด ระบบจะทำการคัดกรองและแนะนำค่ายที่ตรงกับข้อมูลที่นักเรียนกรอกไว้ในโปรไฟล์ รวมถึงให้ข้อมูลเกี่ยวกับกิจกรรมต่าง ๆ ที่เปิดรับสมัครในช่วงเวลาที่กำหนด นอกจากนี้ ผู้จัดค่ายหรือผู้ประชาสัมพันธ์กิจกรรมยังสามารถใช้เว็บไซต์นี้เป็นช่องทางในการประชาสัมพันธ์กิจกรรมของตนเองได้อย่างมีประสิทธิภาพ โดยสามารถเผยแพร่ข้อมูลเกี่ยวกับค่ายและกิจกรรมต่าง ๆ ที่ตนเองจัดขึ้นไปยังกลุ่มเป้าหมายที่ต้องการได้ง่ายขึ้น เนื่องจากผู้ใช้สามารถค้นหาข้อมูลได้ตามหมวดหมู่และความสนใจของตนเอง ทำให้การประชาสัมพันธ์นั้นมีความตรงกลุ่มและครอบคลุมมากขึ้น


การใช้ PeddleCamp จึงไม่เพียงแต่ช่วยแก้ไขปัญหาการเข้าถึงข้อมูลที่ล่าช้าและไม่ทั่วถึง แต่ยังช่วยสนับสนุนการพัฒนาความสามารถและศักยภาพของนักเรียนให้เติบโตไปในทิศทางที่เหมาะสมกับตนเองมากยิ่งขึ้น โดยช่วยให้นักเรียนสามารถค้นพบค่ายและกิจกรรมที่สอดคล้องกับความสนใจและทักษะของตน รวมถึงเพิ่มโอกาสในการพัฒนาตนเองในด้านต่าง ๆ ที่เกี่ยวข้องกับการศึกษาและอาชีพในอนาคต


---

## **User Stories**


- **ในฐานะนักเรียน**

  
  **As a student**, I want to find information about portfolio-building workshops and camps, so that I can register camps that match my interests.


  *ในฐานะนักเรียน ฉันต้องการค้นหาข้อมูลเกี่ยวกับเวิร์กช็อปและค่ายสร้างพอร์ตโฟลิโอ เพื่อให้ฉันสามารถสมัครค่ายที่ตรงกับความสนใจได้*


- **ในฐานะผู้จัดค่าย/ผู้ประชาสัมพันธ์**
  

  **As an organizer**, I want to publish and promote my event information on the website, so that I can attract participants more easily.

  
  *ในฐานะผู้จัดค่าย ฉันต้องการประชาสัมพันธ์ข้อมูลกิจกรรมของฉัน เพื่อดึงดูดผู้เข้าร่วมได้มากและดียิ่งขึ้น*


- **ในฐานะผู้เข้าชมทั่วไป**

  
  **As a general visitor**, I want to access the website easily without needing to sign up, and I want to receive information about camps in categories I'm interested in, such as volunteer camps.

  
  *ในฐานะผู้เข้าชมทั่วไป ฉันต้องการเข้าถึงเว็บอย่างง่ายดาย โดยไม่ต้องมีการสมัครสมาชิก และต้องการรับข้อมูลค่ายประเภทที่สนใจ เช่น จิตอาสา*


---


## **ขั้นตอนการใช้งานตาม User Stories**


### **User Story ที่ 1: ในฐานะนักเรียน**


**ขั้นตอนการใช้งาน**:


1. เข้าสู่เว็บไซต์ **PeddleCamp** หน้า **Home** โดยไม่ต้องทำการเข้าสู่ระบบ/สมัครสมาชิก

   
2. เลือกดูค่ายประเภทต่าง ๆ ที่สนใจ พร้อมอ่านรายละเอียดค่าย วันที่จัดค่าย ค่าใช้จ่าย สถานที่จัดค่าย รายละเอียดตารางกำหนดการ วันสัมภาษณ์/ประกาศผลค่าย เป็นต้น

   
3. เมื่อเจอค่ายที่สนใจและต้องการสมัครเข้าร่วมค่าย ทำการสมัครโดยผ่านช่องทางฟอร์มที่ทางผู้จัดค่ายแนบไว้

   
4. รออีเมล หรือการติดต่อกลับจากผู้จัดค่ายโดยตรง

   
5. สำหรับผู้ใช้งานที่ยังไม่ได้ทำการสมัครสมาชิก:

   
   - คลิก **สมัครสมาชิก** โดยกรอกข้อมูลหรือเข้าสู่ระบบผ่าน Google
  
     
   - ระบุข้อมูลเพิ่มเติม เช่น ระดับชั้น ความสนใจ และงานอดิเรก
  
     
   - เข้าสู่หน้า **Profile** ระบบจะแนะนำค่ายที่เหมาะกับความสนใจของผู้กรอกข้อมูล
  
     
6. สำหรับผู้ใช้งานที่เคยสมัครสมาชิกแล้ว:

    
   - ทำการ **log in**

     
   - ระบบจะนำไปที่หน้า **Home**

     
   - เข้าหน้า **Profile** เพื่อดูค่ายที่ตรงกับข้อมูลที่ระบบทำการแนะนำแก่ผู้ใช้งาน

     
   - กด **แก้ไขข้อมูล** หากต้องการเปลี่ยนแปลงข้อมูล


### **User Story ที่ 2: ในฐานะผู้จัดค่าย/ผู้ประชาสัมพันธ์**


**ขั้นตอนการใช้งาน**:


1. เข้าสู่เว็บไซต์ **PeddleCamp** หน้า **Home** โดยไม่ต้องทำการเข้าสู่ระบบ


2. คลิกที่ **โปรโมทกิจกรรม**


3. กรอกข้อมูลเกี่ยวกับค่ายที่ต้องการประชาสัมพันธ์ เช่น รายละเอียดค่าย ประเภทของค่าย จำนวนผู้เข้าร่วม ค่าใช้จ่าย สถานที่จัดค่าย องค์กรผู้จัดค่าย วันที่ปิดรับสมัคร วันเริ่มกิจกรรม วันสิ้นสุดกิจกรรม ไฟล์ภาพค่าย ช่องทางการติดต่อของผู้จัด แบบฟอร์มสมัครเข้าร่วมค่าย เป็นต้น


4. เมื่อกรอกครบถ้วนแล้ว ทำการคลิก **ยืนยันการเพิ่มค่าย**


5. รอทางฝ่ายแอดมินพิจารณาตรวจสอบข้อมูลค่ายก่อนดำเนินการเผยแพร่


6. เผยแพร่ค่ายเรียบร้อย



### **User Story ที่ 3 : ในฐานะผู้เข้าชมทั่วไป**


**ขั้นตอนการใช้งาน**:


1. เข้าสู่เว็บไซต์ **PeddleCamp** หน้า **Home** โดยไม่ต้องทำการเข้าสู่ระบบ/สมัครสมาชิก


2. เลือกดูค่ายประเภทต่าง ๆ ที่สนใจ พร้อมอ่านรายละเอียดค่าย วันที่จัดค่าย ค่าใช้จ่าย สถานที่จัดค่าย รายละเอียดตารางกำหนดการ วันสัมภาษณ์/ประกาศผลค่าย เป็นต้น


3. เมื่อเจอค่ายที่สนใจและต้องการสมัครเข้าร่วมค่าย ทำการสมัครโดยผ่านช่องทางฟอร์มที่ทางผู้จัดค่ายแนบไว้



---

## **การติดตั้งและการใช้งาน**



### **ความต้องการเบื้องต้น**


- ทำการติดตั้ง **[Docker](https://www.docker.com/)**


- ทำการติดตั้ง **[Git](https://git-scm.com/downloads)**


### **ขั้นตอนการติดตั้ง**

1. **Clone โปรเจกต์จาก GitHub**:
   ```bash
   git clone https://github.com/bellochertam/dsi202_2025.git
   cd dsi202_2025


2. ทำการเพิ่ม code ในส่วนของ setting.py
```bash
SOCIALACCOUNT_PROVIDERS = {
    "google": {
        "SCOPE": ["profile", "email"],
        "AUTH_PARAMS": {"access_type": "online"},
        "APP": {
            "client_id": "Client ID ที่สร้างขึ้นมา",
            "secret": "Client secret ที่สร้างขึ้นมา",
            "key": "",
        },
    }
}




3. ทำการ Build Docker Container
```bash
 docker compose build


4. รัน Web Application
```bash
docker compose up 


5. เปิด Browser หน้าเว็บ ที่
http://localhost:8000/


##  **YOUTUBE VDO LINK  **









