# Kaggle Python Project

โปรเจ็กต์จาก Kaggle ถูกจัดระเบียบให้เหมาะกับ GitHub เพื่อการรีวิวโดย HR/ทีมเทคนิค

## สรุปจากโน้ตบุ๊ก
- หัวข้อหลัก (ตัวอย่าง):  


- ไลบรารีที่ตรวจพบ: datetime, matplotlib, missingno, numpy, pandas, seaborn
- ไฟล์ที่อ้างอิง:  
- `/kaggle/input/books-dataset/Books.csv`

## โครงสร้าง
```
kaggle-python-project/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ LICENSE
├─ notebooks/
│  └─ analyzing-book-with-python.ipynb
├─ src/
│  ├─ custom_functions.py
│  └─ main.py
├─ data/
│  └─ README.md
├─ reports/
│  └─ figures/
└─ models/
```

## การตั้งค่าและรัน
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/analyzing-book-with-python.ipynb   # เปิดโน้ตบุ๊ก
# หรือ
python src/main.py
```
