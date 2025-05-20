# CP372 Data Analytic Project: โครงงานวิเคราะห์อัตราการเติบโตของกำไรในบริษัทขายสินค้า

---

จัดทำโดย
1. นางสาวณัฐพร หยาง 65102010114
2. นางสาวปานชนก ขวัญสูงเนิน 65102010120

เสนอ : อาจารย์ ผศ.ดร.รัตน์ชัยนันท์ ธรรมสุจริต และ อาจารย์ ผศ.ดร.นุวีย์ วิวัฒนวัฒนา

---

โครงงานนี้จัดทำขึ้นในรายวิชา CP372: Data Analytics and Business Intelligence ชั้นปีที่ 3 มีเป้าหมายเพื่อศึกษาการวิเคราะห์ข้อมูลและการประยุกต์ใช้เครื่องมือด้าน Business Intelligence กับข้อมูลอัตราการเติบโตของกำไรในบริษัทขายสินค้า เพื่อสกัดข้อมูลเชิงลึกและนำเสนอข้อเสนอแนะที่เป็นประโยชน์ โดยใช้เครื่องมืออย่าง Excel และ Tableau ในการจัดการและแสดงผลข้อมูล 

คณะผู้จัดทำหวังว่าโครงงานนี้จะเป็นแนวทางให้กับผู้ที่สนใจด้าน Data Analytics และ Business Intelligence หากมีข้อผิดพลาดประการใดทางคณะผู้จัดทำ ขออภัยไว้ ณ ที่นี้ด้วย

---

## สารบัญ
  - [Overview](#Overview)
  - [Exploratory Data Analysis](#Exploratory-Data-Analysis)
  - [In-Depth Analysis](#In-Depth-Analysis)
  - [Insights & Recommendations](#Insights-&-Recommendations)
  - [Visualization](#Visualization)
  - [Public Dashboard Link](#Public-Dashboard-Link)

---
## Overview

เป้าหมายของโครงการนี้คือการนำความรู้ที่ได้จากการเรียนในรายวิชา CP372 มาปรับใช้เพื่อวิเคราะห์อัตราการเติบโตของกำไรในบริษัทขายสินค้า และหาแนวทางในการเพิ่มรายรับ โดยใช้ข้อมูลจริงมาช่วยในการวิเคราะห์ เพื่อให้ได้ข้อเสนอแนะที่เป็นประโยชน์ต่อการวางแผนและปรับปรุงธุรกิจในอนาคต

ข้อมูลที่ใช้ : .....................

เครื่องมือที่ใช้
  - Microsoft Excel
  - Tableau Public
  - Notepad
  - GitHub

---
## Exploratory Data Analysis

1. กราฟเส้นแสดงยอดขายและกำไรในแต่ละปี
![image](https://github.com/user-attachments/assets/94ae816e-a5fa-4b3f-a9b3-aebf956392b9)

2. แผนที่แสดงอัตรากำไรในแต่ละรัฐ สามารถเลือกดูตามปีได้
![image](https://github.com/user-attachments/assets/6e3119d7-dccc-4fa1-a907-198c8f21c99e)

3. กราฟแท่งแสดง 10 อันดับสินค้าที่มียอดขายมากที่สุด
![image](https://github.com/user-attachments/assets/a9bcf986-b116-400e-af18-a18dcb11d385)

4. กราฟแท่งและกราฟเส้นแสดงยอดขายและกำไรแบ่งตามกลุ่มลูกค้า
![image](https://github.com/user-attachments/assets/2f545920-694a-4b8d-8300-b7a57d2ecba4)

5. กราฟเส้นแสดงแนวโน้มของส่วนลดต่ออัตรากำไร
![image](https://github.com/user-attachments/assets/e933219d-1a3f-4e0e-9067-58347f0f5917)

---
## In-Depth Analysis

1 แนวโน้มของยอดขายในแต่ละปีเป็นอย่างไร

Ans: ตั้งแต่ปี 2013 บริษัทมีแนวโน้มของยอดขายสูงขึ้นทุกปี สังเกตได้จาก trendline ที่มีแนวโน้มสูงขึ้น
![image](https://github.com/user-attachments/assets/ba368965-903d-4cb4-89a5-ea4d7a7abdc4)

2 ส่วนลดมีผลต่ออัตรากำไรอย่างไร

Ans: ส่วนลดและกำไรมีความสัมพันธ์เป็นแบบ negative correlation คือเมื่อให้ส่วนลดมากขึ้น อัตรากำไรก็จะลดลง
![image](https://github.com/user-attachments/assets/8c2e865c-684d-49c5-afbe-5ab2fe54567f)

--- 
## Insights & Recommendations

1. ไตรมาสที่ 2 ของปี 2016 มีกำไรน้อยกว่าไตรมาสที่ 1 ต่างจาก 3 ปีที่ผ่านมาโดยที่ Sales และ Cost(ต้นทุน) ไม่ได้มีการเปลี่ยนแปลงมากนัก

2. ไตรมาสที่ 2 ของปี 2016 มีกำไรจากการขายสินค้าประเภท Technology ลดลงอย่างมากเมื่อเทียบกับปีก่อนหน้า

3. จำนวนคำสั่งซื้อของสินค้าประเภท Technology ในปี 2016 ของกลุ่มลูกค้า Consumer ลดลงจากปีก่อนไม่มากนัก แต่ราคาขายกลับลดลงถึงครึ่งหนึ่ง เมื่อเทียบเป็นอัตราส่วนราคาขายต่อ 1 คำสั่งซื้อแล้วพบว่าในปี 2016 ราคาสินค้าต่อ 1 คำสั่งซื้อเหลือเพียง 263.6$ เท่านั้นเมื่อเทียบกับปีก่อนหน้า เมื่อเจาะลึกลงไปพบว่าไม่มีลูกค้าประเภท Consumer และ Corporate สั่งซื้อเครื่องถ่ายเอกสารเลย ในขณะที่สินค้า Machines ก็มียอดสั่งซื้อลดลงอย่างมาก

![image](https://github.com/user-attachments/assets/35bc2eaf-0986-457a-8729-c4c4502c64be)
![image](https://github.com/user-attachments/assets/4b7d6410-8d17-4f77-b9ec-eb5b9b7d254a)
![image](https://github.com/user-attachments/assets/27880f78-a6b5-45ad-981e-b3e398fbfbaa)

---
## Visualization
![image](https://github.com/user-attachments/assets/9ae7cc85-7c7d-4f51-81e4-6e0a5b6e051b)

---
## Tableau Visualization Link

Dashboard : https://public.tableau.com/app/profile/pharnchanok.khwansungnuen/viz/CP372_Supermarket_Project_114_120/Dashboard1?publish=yes









