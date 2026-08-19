# Global Literacy Rate Analysis (1970–2024)

**Statistical Data Analysis Project | Multiple Linear Regression · Correlation Analysis · Python · RapidMiner**

## Project Overview

โครงงานนี้เป็นการวิเคราะห์ปัจจัยด้านการศึกษาและทรัพยากรทางการศึกษาที่เกี่ยวข้องกับ
**อัตราการรู้หนังสือ (Literacy Rate)** ของประชากรในระดับนานาชาติ โดยใช้ข้อมูลทุติยภูมิ
ในช่วงปี **1970–2024**

การวิเคราะห์มุ่งศึกษาความสัมพันธ์ระหว่างอัตราการรู้หนังสือกับตัวชี้วัดด้านการศึกษา
รวมถึงอัตราการสำเร็จการศึกษาระดับประถมศึกษา สัดส่วนครูที่ผ่านการอบรม
งบประมาณของรัฐบาลด้านการศึกษา และจำนวนเด็กที่ไม่ได้เข้าเรียนในระบบการศึกษา

ใช้กระบวนการวิเคราะห์ข้อมูลเชิงสถิติ ตั้งแต่การสำรวจและเตรียมข้อมูล
การวิเคราะห์ความสัมพันธ์ ไปจนถึงการสร้าง **Multiple Linear Regression Model**
เพื่อศึกษาปัจจัยที่สัมพันธ์กับอัตราการรู้หนังสือ

## Objectives

- ศึกษาลักษณะและการกระจายของข้อมูลด้านการศึกษา
- วิเคราะห์ความสัมพันธ์ระหว่างตัวแปรด้านการศึกษากับอัตราการรู้หนังสือ
- ศึกษาปัจจัยที่มีความสัมพันธ์กับ Literacy Rate ด้วย Multiple Linear Regression
- ประเมินความเหมาะสมของแบบจำลองทางสถิติ
- ฝึกประยุกต์ใช้กระบวนการวิเคราะห์ข้อมูลกับข้อมูลระดับนานาชาติ

## Data Sources

โครงงานใช้ข้อมูลทุติยภูมิ (Secondary Data) จากฐานข้อมูลระดับนานาชาติ ได้แก่

- World Development Indicators (WDI) — World Bank
- UNESCO Institute for Statistics (UIS)

ข้อมูลครอบคลุมตัวชี้วัดด้านการศึกษาและทรัพยากรทางการศึกษาในช่วงปี 1970–2024

## Variables

ตัวแปรตามที่ใช้ในการวิเคราะห์คือ

**Literacy Rate** — อัตราการรู้หนังสือของประชากร

ตัวแปรอิสระที่นำมาศึกษาประกอบด้วย

- Out-of-school Children — จำนวนเด็กที่ไม่ได้เข้าเรียนในระบบการศึกษา
- Primary Completion Rate — อัตราการสำเร็จการศึกษาระดับประถมศึกษา
- Trained Teachers in Primary Education — สัดส่วนครูที่ผ่านการอบรมระดับประถมศึกษา
- Trained Teachers in Secondary Education — สัดส่วนครูที่ผ่านการอบรมระดับมัธยมศึกษา
- Government Expenditure on Education — งบประมาณของรัฐบาลด้านการศึกษา

## Analysis Workflow

1. รวบรวมข้อมูลจากแหล่งข้อมูลทุติยภูมิ
2. ตรวจสอบและเตรียมข้อมูลก่อนการวิเคราะห์
3. สำรวจลักษณะและการกระจายของข้อมูล
4. ตรวจสอบค่าผิดปกติ (Outliers)
5. วิเคราะห์ความสัมพันธ์ระหว่างตัวแปร
6. สร้าง Multiple Linear Regression Model
7. ตรวจสอบและประเมินแบบจำลอง
8. ตีความและสรุปผลการวิเคราะห์

## Exploratory Data Analysis

ทำการสำรวจข้อมูลเบื้องต้นเพื่อศึกษาลักษณะของตัวแปร
รวมถึงค่ากลาง การกระจาย ความเบ้ และค่าผิดปกติ

ข้อมูลบางตัวแปรมีการกระจายค่อนข้างกว้างและมี Outliers
จึงต้องพิจารณาลักษณะของข้อมูลก่อนนำไปตีความผลการวิเคราะห์ทางสถิติ

## Correlation Analysis

วิเคราะห์ความสัมพันธ์ระหว่าง Literacy Rate
และตัวแปรด้านการศึกษาต่าง ๆ เพื่อศึกษาทิศทางและระดับความสัมพันธ์
ก่อนนำตัวแปรเข้าสู่แบบจำลอง Multiple Linear Regression

## Multiple Linear Regression

ใช้ Multiple Linear Regression เพื่อศึกษาความสัมพันธ์ระหว่าง
Literacy Rate กับตัวแปรด้านทรัพยากรและผลลัพธ์ทางการศึกษาหลายตัวพร้อมกัน

การวิเคราะห์ช่วยให้สามารถพิจารณาผลของแต่ละตัวแปร
เมื่อควบคุมอิทธิพลของตัวแปรอื่นที่อยู่ในแบบจำลอง

## Key Findings

ผลการวิเคราะห์พบว่า

- **Primary Completion Rate** มีความสัมพันธ์เชิงบวกอย่างมีนัยสำคัญกับ Literacy Rate
- **Government Expenditure on Education** มีความสัมพันธ์เชิงบวกอย่างมีนัยสำคัญกับ Literacy Rate
- **Out-of-school Children** ไม่พบความสัมพันธ์อย่างมีนัยสำคัญทางสถิติที่ระดับ 0.05 ในแบบจำลอง
- แบบจำลองสามารถอธิบายความแปรปรวนของ Literacy Rate ได้ในระดับปานกลาง

ผลการวิเคราะห์สะท้อนให้เห็นถึงความสัมพันธ์ระหว่าง
ปัจจัยด้านการศึกษาและระดับการรู้หนังสือ อย่างไรก็ตาม
ผลลัพธ์ควรตีความภายใต้ขอบเขตและข้อจำกัดของข้อมูลที่ใช้ในการศึกษา

## Analysis Techniques

- Descriptive Statistics
- Exploratory Data Analysis
- Outlier Analysis
- Correlation Analysis
- Multiple Linear Regression
- Regression Model Evaluation
- Statistical Interpretation
- Data Visualization

## Tools & Technologies

- Python
- RapidMiner
- Statistical Analysis
- Data Preprocessing
- Data Visualization
- Multiple Linear Regression

## Project Activities

โปรเจกต์นี้เป็น **งานกลุ่มเชิงวิชาการ** โดยสมาชิกในกลุ่มร่วมกันดำเนินการวิเคราะห์
และจัดทำรายงาน ซึ่งครอบคลุมกิจกรรมดังนี้

- รวบรวมและเตรียมข้อมูลด้านการศึกษาสำหรับการวิเคราะห์
- ตรวจสอบและสำรวจลักษณะของข้อมูล
- วิเคราะห์ข้อมูลเชิงพรรณนาและความสัมพันธ์ระหว่างตัวแปร
- พัฒนา Multiple Linear Regression Model
- ประเมินและตีความผลของแบบจำลอง
- สร้าง Visualization เพื่อประกอบการวิเคราะห์
- สรุปผลและจัดทำรายงานโครงงาน

## Project Report

รายละเอียดเกี่ยวกับข้อมูล วิธีการวิเคราะห์ ผลการวิเคราะห์
และการอภิปรายผลสามารถดูได้จากรายงานฉบับเต็ม

[View Full Project Report](Global%20Literacy%20Rate%20Analysis%20%281970%E2%80%932024%29.pdf)

## Project Structure

```text
global-literacy-rate-analysis/
│
├── README.md
└── Global Literacy Rate Analysis (1970–2024).pdf
```

## Project Type

**Academic Team Project — Statistical Data Analysis & Multiple Linear Regression**

โครงงานนี้จัดทำขึ้นเพื่อประยุกต์ใช้กระบวนการวิเคราะห์ข้อมูลและเทคนิคทางสถิติ
กับข้อมูลด้านการศึกษาระดับนานาชาติ ตั้งแต่การเตรียมข้อมูล
การสำรวจข้อมูล การสร้างแบบจำลอง ไปจนถึงการตีความและนำเสนอผลการวิเคราะห์

> **Note:** Repository นี้จัดทำขึ้นเพื่อการศึกษาและการนำเสนอผลงานใน Portfolio
