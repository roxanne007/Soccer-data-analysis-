# ⚽ FIFA Top 5% Player Analysis (2017–2021)

This project explores how various player attributes — including **preferred foot**, **nationality**, **age**, **acceleration**, **agility**, and **BMI** — affect **potential rating** and **wage** across the **top 5% of FIFA players** from 2017 to 2021.

---

## 🎯 Objective

To answer this question:
> “Are the top 5% of FIFA 21 players faster (in terms of acceleration and agility) than in FIFA 17?”

---

## 📊 Dataset

- **Source**: [Sofifa via Kaggle](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)
- **Years Covered**: FIFA 17 through FIFA 21
- **Top 5% Filter**: Players ranked in the top 5% by overall rating for each year
- **Features Used**:
  - `preferred_foot`
  - `nationality`
  - `age`
  - `acceleration`
  - `agility`
  - `height_cm`, `weight_kg` → converted to `BMI`
  - `potential`, `wage_eur`

---
---

## 📌 Key Findings

- **Preferred foot** has little to no effect on wage or potential.
- **Nationality** (e.g. Argentina, Brazil, Portugal) strongly influences both.
- **Age**: Players tend to peak in potential between **26–30 years**.
- **Acceleration & Agility**: Clear positive correlation with both **wage** and **potential**.
- **BMI**: Players with leaner body compositions trend toward higher earnings.

✅ **Hypothesis confirmed**:  
Top 5% FIFA 21 players are faster (higher acceleration & agility) than those in FIFA 17.

---

## 📄 Report

View the full analysis with graphs and conclusions:

👉 [**Download Full Report (PDF)**](./FIFA_Top5_Analysis.pdf)

Or explore the live code here:

🧪 [**View Notebook**](./FIFA_Top5_Analysis.ipynb)

---

## 💡 Author

**Roxanne-Mary Bell**  
- 🎓 Computer Science | 🧠 Data Analysis | ✨ Creative Thinker  
- 💼 [LinkedIn](https://www.linkedin.com/in/roxannemarybell) 

---

## 🤝 Contributions

Pull requests, feedback, or collaboration ideas are welcome!

---

## 📜 License

This project is for educational and demonstrational purposes.


## 📂 Project Structure

📁 Data/
├── players_17.csv
├── players_18.csv
├── players_19.csv
├── players_20.csv
└── players_21.csv

📄 FIFA_Top5_Analysis.ipynb
📄 FIFA_Top5_Analysis.pdf
📄 README.md
