# Fastfood Nutrition — Multiple Linear Regression

**Goal**  
วิเคราะห์ปัจจัยที่มีผลต่อปริมาณแคลอรีของอาหารฟาสต์ฟู้ด

**What I Did**  
- ใช้ Multiple Linear Regression (MLR)  
- ตรวจสมมติฐาน: Normality, Independence, Equality of error  
- ตรวจ multicollinearity ด้วย VIF  
- เลือกโมเดลที่เหมาะสมด้วย R², Adj-R², Mallows’ Cp

**Result**  
ได้สมการถดถอยที่ตีความได้ว่า คาร์โบไฮเดรต โปรตีน และคอเลสเตอรอล มีผลต่อแคลอรีอย่างมีนัยสำคัญ  
ผลการวิเคราะห์ช่วยให้เข้าใจโภชนาการของอาหารและปัจจัยที่ทำให้แคลอรีสูง

## Dataset
- Source: [Kaggle — Fastfood Nutrition](https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition)
- Sample file: [fastfood.csv](./fastfood.csv) 


**Outputs**  
- สมการ MLR + การตีความเชิงสัญญะ (ตัวเลขละเอียดอยู่ในไฟล์รายงาน)

📄 **รายงาน:** [Fastfood-Nutrition.pdf](./Fastfood-Nutrition.pdf)
