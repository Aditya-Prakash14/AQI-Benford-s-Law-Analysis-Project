# 🏙️ Air Quality Index (AQI) Analysis of Indian Cities using Benford's Law

This project analyzes air quality data from various Indian cities to assess whether the data follows **Benford’s Law**, a statistical principle that predicts the frequency distribution of digits in naturally occurring datasets. By doing so, we aim to explore the reliability and natural behavior of AQI data.

---

## 📌 Project Objectives

- Perform **data cleaning** and **exploratory analysis** on AQI data.
- Analyze the **distribution of first and second digits** in AQI values.
- Apply **Benford’s Law** to identify any deviations from expected digit patterns.
- Use **Chi-Square Goodness-of-Fit tests** to validate statistical findings.
- Generate visualizations to support the analysis.

---

## 📁 Dataset

- **File Name**: `air_quality_index_of_indian_cities.csv`
- **Description**: Contains AQI values for various Indian cities over a period of time.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📊 Key Analysis Steps

1. **Load and clean data**  
   - Handle missing or non-numeric AQI values.

2. **Visualize AQI distribution**  
   - Explore general trends in AQI values.

3. **First Digit Analysis**  
   - Extract the first digit of each AQI value.
   - Compare actual vs Benford's expected distribution.
   - Conduct Chi-Square test.

4. **Second Digit Analysis**  
   - Extract second digits.
   - Plot distribution and compare with expected probabilities.
   - Perform additional statistical checks.

---

## 📈 Results

- The **first-digit distribution** follows Benford's Law quite closely, indicating natural data distribution.
- The **second-digit distribution** shows some deviations, though not enough to indicate manipulation.
- Statistical tests confirm a reasonable fit to Benford's expectations.

---

## 👥 Team Members

- **Aditya Prakash** – aditya.prakash@adypu.edu.in  
- **Vipul** – vipul.k@adypu.edu.in  
- **Yashveer Singh** – yashveer.singh@adypu.edu.in  
- **Abhay Pratap Yadav** – abhaypratap.yadav@adypu.edu.in  

---

## 📌 Future Work

- Add **city-wise AQI trend analysis**.
- Build a **predictive model** to forecast AQI levels.
- Extend Benford analysis to other pollution metrics (PM2.5, PM10, NO2, etc.).

---

## 📜 License

This project is for educational purposes. Feel free to fork, use, and adapt with credit.

---

## 🤝 Contributions

Contributions are welcome! Please open issues or pull requests for improvements.

