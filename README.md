# DPDM2023
:heart_decoration: SC637802 : Data Pre Processing and Data Mining 
---
#### :love_letter: Repository for Data Mining and Data Processing, MSc in Applied Statistics, KKU

#### :love_letter: Wanissara Chongchai 665020059-1

| Work schedule | Score |
| ----------- | ----------- |
| Research project | 20% |
| Programming Assignment | 40% |
| Midterm Exam | 10% |
| Final Exam | 30% |
## :purple_heart: Grading
| คะแนน | เกรด |
| ----------- | ----------- |
|85% |  A  |
| 80% |  B+ |
| 70% |  B |
|<50% | F |
---
## :purple_heart: Table of Contents

เนื้อหาทั้งหมดที่เราได้เรียนจะประกอบไปด้วย 6 เรื่องได้แก่

| Chapter | Content |
| ----------- | ----------- |
| Chapter 1 | Introduction |
| Chapter 2 | Know the data |
| Chapter 3 | Data Preprocessing |
| Chapter 6 | Frequent Patterns(Association Rules) |
| Chapter 8 | Classification |
| Chapter 10 | Clustering |

---
## :file_folder: Chapter 1 : Introduction
เรียนรู้เกี่ยวกับ Python เบื้องต้น

:notebook: lecture part
  
- Introduction :arrow_forward: [Chapter 1: Introduction](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%201%20Introduction.pdf)

:computer: Coding part
  
- Introduction :arrow_forward: [Introduction](https://github.com/Jaomiew/DPDM2023/blob/main/Introduction.ipynb)

- Basic python :arrow_forward: [python101](https://github.com/Jaomiew/DPDM2023/blob/main/Python101.ipynb)
* คือการมาทำความรู้จักเกี่ยวกับการเขียนโค้ด python เบื้องต้น
  - ตัวอย่าง python
  - ข้อมูล string (ประเภทข้อความ)
  - ตัวแปร Variable คืออะไร
  - การใช้คำสั่ง print และ advance print
  - การคั่นกลาง (separator)
  - การขึ้นบรรทัดใหม่ (end)
  - ประเภทของตัวแปร
  - การเปลี่ยนแปลงชนิดตัวแปร
---
## :file_folder: Chapter 2 : Know the data
เป็นการทำความรู้จักข้อมูลต่างๆไม่ว่าจะเป็นในรูปแบบ เสียง ข้อความหรือภาพ เพื่อนำไปใช้งาน และในส่วนของ Python จะมีการใช้คำสั่งต่างๆในการสร้าง function รวมไปถึงการดูภาพรวมข้อมูลทั้งหมด รวมถึงการทำ Boxplot และการสร้างกราฟ

:notebook: lecture part  

- Know the data :arrow_forward: [Chapter 2: Know the data](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%202%20Data.pdf)

:computer: Coding part

- Data101 :arrow_forward: [Data101](https://github.com/Jaomiew/DPDM2023/blob/main/Data101_(Chapter2).ipynb)
  
  *เรียนเกียวกับการนำเข้าข้อมูลและ สิ่งที่ต้องใช้การในการหาด้วยวิธีการ loop หรือ ฟังก์ชัน
  - Data structure
  - loop ด้วยการใช้ for
  - nested loop
  - conditional if statment
  - Def หรือการสร้าง function
    
- Data102 :arrow_forward: [Data102](https://github.com/Jaomiew/DPDM2023/blob/main/Data102(Chapter2).ipynb)

  * เมื่อนำข้อมูลเข้ามา เราสามารถอธิบายการสร้างตารางใหม่รวมไปถึงการทำ boxplot และกราฟเพื่ออธิบายได้ว่าเกิดอะไรขึ้นที่นั้น
     - พานำข้อมูลเข้าด้วยการเชื่อมกับ Google Drive
     - Step 1 : พาดูข้อมูลว่ามีเท่าไร
     - Step 2 : Descriptive statistical
     - Step 3 : การทำ Boxplot
     - Step 4 : การทำกราฟ

---
## :file_folder: Chapter 3 : Preprocessing
เป็นการสอนวิธีการทำความสะอาดข้อมูลเพื่อนำไปใช้งาน รวมทั้งการรวมตาราง และการสร้างตารางขึ้นมาใหม่

:notebook: lecture part 

- Preprocessing :arrow_forward: [Chapter 3: Preprocessing](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%203%20Preprocessing.pdf)

:computer: Coding part  

- Preprocessing :arrow_forward: [Data Preprocessing](https://github.com/Jaomiew/DPDM2023/blob/main/preprocessing.ipynb)
  
  * ก่อนนำข้อมูลไปใช้งานเราจะทำการ Clean data ซึ่งก็มีหลายแบบ
     - เช็ค missing Value
     - การลบค่า missing value ด้วยการ .dropna()
     - การแทนค่า missing value โดยขึ้นกับตัวเราเองเช่น fill เป็น 0
     - การแทนค่า missing value ด้วย mean ของแต่ละกลุ่ม
     - การเชื่อมตาราง
     - สร้างตาราง dataframe

---
## :file_folder: Chapter 6 : Frequent Patterns
เป็นการทำความเข้าใจเกี่ยวกับแพทเทิร์นของข้อมูล ว่าทุกๆข้อมูลจะมีแพทเทิร์นอย่างนี้แล้วผลลัพธ์จะได้อะไร รวมไปถึงการเข้าใจเกี่ยวกับ Assiciation Rules

:notebook: lecture part

- Frequent Patterns :arrow_forward: [Chapter 6 : Frequent Patterns](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%206%20%20Frequent%20Patterns.pdf)

:computer: Coding part  

- Frequent Patterns :arrow_forward: [Frequent Patterns](https://github.com/Jaomiew/DPDM2023/blob/main/Frequent_Patterns_(Association_Rules).ipynb)

:sob: Quiz part 

- Quiz  :arrow_forward: [Quiz 5](https://github.com/Jaomiew/DPDM2023/blob/main/Q.pdf)

---
## :file_folder: Chapter 8 : Classification
เป็นการทำความเข้าใจเกี่ยวกับการจำแนกข้อมูลซึ่งเป็น Supervise learning เพื่อให้ข้อมูลในอนาคตที่เข้ามาสามารถทำนายได้อย่างแม่นยำ

:notebook: lecture part  

- Classification :arrow_forward: [Chapter 8 : Classification](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%208%20%20Classification.pdf)

- KNN Classification :arrow_forward: [KNN Classification](https://github.com/Jaomiew/DPDM2023/blob/main/KNN%20Classification.pdf)

:computer: Coding part
  
- Classification :arrow_forward: [Classification](https://github.com/Jaomiew/DPDM2023/blob/main/Classification.ipynb)

  * Classification เป็นวิธีที่ใช้สอนโมเดลคอมพิวเตอร์ให้สามารถแยกแยะวัตถุหรือข้อมูลออกเป็นกลุ่มหรือประเภทต่าง ๆ ตามลักษณะหรือคุณสมบัติที่กำหนดไว้ล่วงหน้า
     - Try Simple ML
     - Import
     - Define
     - Train 
     - Test
     - Set parameter

- K-nearest neighbor :arrow_forward: [KNN Classification](https://github.com/Jaomiew/DPDM2023/blob/main/HW4.ipynb)
  
  * KNN คือการแบ่งกลุ่ม (classification ) โดยวิธีการที่ว่า เมื่อมีข้อมูลใหม่มาเมื่อเทียบกับข้อมูลทั้งหมดเหมือนกลุ่มไหนมากที่สุด
    

:sob: Quiz part
  
- Quiz  :arrow_forward: [Quiz 6](https://github.com/Jaomiew/DPDM2023/blob/main/Q6.pdf)

---
## :file_folder: Chapter 10 : Clustering
เป็นการทำความเข้าใจเกี่ยวกับการแบ่งกลุ่มซึ่งเป็น Unsupervise learning เพื่อให้ข้อมูลที่มีอยู่สามารถแบ่งกลุ่มเพื่ออธิบายข้อมูลของแต่ละกลุ่ม

:notebook: lecture part 

- Clustering :arrow_forward: [Chapter 10 : Clustering](https://github.com/Jaomiew/DPDM2023/blob/main/Chapter%2010%20%20Clustering.pdf)

---
## :scream: Examination
การสอบแบ่งออกเป็น 2 ส่วน ได้แก่ การสอบกลางภาคและการสอบปลายภาค
  
:mortar_board: Mid-term Exam :arrow_forward: [Mid Term Exam](https://github.com/Jaomiew/DPDM2023/blob/main/midterm_dpdm2023.ipynb)

:mortar_board: Final Exam :arrow_forward: [Final Exam](https://github.com/Jaomiew/DPDM2023/blob/main/dpdm23_final.ipynb)

---
## :mag: Research project
Research project เป็นการหา paper ที่มีเนื้อหาเกี่ยวกับกับรายวิชานี้ นำมาทดลองและนำเสนอ ซึ่งในงานนี้ได้ศึกษาเกี่ยวกับแบบจำลองการทำเหมือนข้อมูลสำหรับการฟื้นฟูของผู้ป่วย
ที่ติดเชื้อโควิด-19 

- เนื้อหาใน Research project มีดังนี้
  
:newspaper: References :arrow_forward: [Paper](https://github.com/Jaomiew/DPDM2023/blob/main/Predictive%20Data%20Mining%20Models.pdf)

:information_desk_person: Presentation :arrow_forward: [PPT](https://github.com/Jaomiew/DPDM2023/blob/main/PPT_Research%20Project.pdf)

:computer: Coding Part  :arrow_forward: [Coding](https://github.com/Jaomiew/DPDM2023/blob/main/Research_project.ipynb)

---
## ขอบคุณค่ะ :pray: :purple_heart: :stuck_out_tongue_winking_eye: :kissing_heart: 
![people](รูปภาพ.jpg)
