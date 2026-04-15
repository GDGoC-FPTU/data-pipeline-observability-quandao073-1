[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23573953&assignment_repo_type=AssignmentRepo)
# Day 10 Lab: Data Pipeline & Data Observability

**Student Email:** anhquan7303qqq@email.com
**Name:** Đào Anh Quân

---

## Mo ta

Hoàn thành các hàm cho từng giai đoạn của ETL pipeline:
1. Extract:   Đọc dữ liệu từ file JSON
2. Validate:  Kiểm tra & loại bỏ dữ liệu không hợp lệ
3. Transform: Chuẩn hóa category + tính giá giảm 10%
4. Load:      Lưu kết quả ra file CSV

---

## Cach chay (How to Run)

### Prerequisites
```bash
pip install pandas
```

### Chay ETL Pipeline
```bash
python solution.py
```

### Chay Agent Simulation (Stress Test)
```bash
# Mo ta cach ban chay thi nghiem Clean vs Garbage data
```

---

## Cau truc thu muc

```
├── solution.py              # ETL Pipeline script
├── processed_data.csv       # Output cua pipeline
├── experiment_report.md     # Bao cao thi nghiem
└── README.md                # File nay
```

---

## Ket qua

Đã xử lý 5 records, trong đó 3 records hợp lệ và loại bỏ 2 records
