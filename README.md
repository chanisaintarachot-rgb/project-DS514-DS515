# project-DS514-515
project final DS514-515

โครงงานนี้เป็นส่วนหนึ่งของรายวิชา DS514/DS515 Data Science จากข้อมูลชุดนี้เป็นข้อมูลการขายสินค้า/บริการของบริษัทแห่งหนึ่ง โดยมีวัตถุประสงค์หลักในวิเคราะห์หรือทำนายช่องทางการขายที่เหมาะสม เพื่อช่วยให้ทีมขายเลือกช่องทางได้ตรงกับประเภทสินค้าและราคาที่เสนอได้

**Data Preprocessing**
เปลี่ยนประเภทของข้อมูล
ลบช่องว่างของข้อมูล
เพิ่มคอลัมน์อายุ
ตัดข้อมูลที่ไม่ถูกต้องออก (ผู้ที่อายุน้อยกว่า 14 ปี)

**Imbalance Data and Encoding**
จัดการข้อมูล Imbalance โดยการสุ่มข้อมูล (เลือกจำนวนข้อมูลจากจำนวนกลุ่มที่น้อยที่สุด)
Encode ข้อมูลที่เป็น Category

**Target and Feature Selection **
Target : Sales_Channel
Feature : 
Package_Type
Price_After_Discount
Price
Subscription_Type
Package_Group
Age

**Model และ การปรับ Hyperparameters**
K-Nearest Neighbors
Logistic Regression    
ตัวอย่างโมเดล
