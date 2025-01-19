# PUBG Weapon Analysis 🔫🎯

## 📖 Overview
This project performs **Exploratory Data Analysis (EDA)** on PUBG weapons using the **PUBG Weapon Stats** dataset. The goal is to analyze weapon performance, bullet types, damage output, and other key statistics to gain insights into the best weapons in PUBG.

## 📂 Dataset
- **File:** `pubg-weapon-stats.csv`
- **Source:** PUBG weapon stats dataset
- **Columns Include:**
  - `Weapon Name` - Name of the weapon
  - `Weapon Type` - Assault Rifle, SMG, Sniper, etc.
  - `Bullet Type` - Caliber of bullet used (5.56mm, 7.62mm, etc.)
  - `Damage`, `Bullet Speed`, `Range`, `Fire Mode`
  - `Shots to Kill (Chest/Head)`, `Damage Per Second (DPS)`

## 📊 Analysis Performed
1. **Data Cleaning & Preprocessing**  
   - Handling missing values in bullet type, range, bullet speed, and damage stats.
   - Categorizing weapons into **Damage Ranges**:
     - **Low (0-30)**
     - **Medium (30-45)**
     - **High (45+)**

2. **Pivot Tables & Insights**  
   - **Weapon Type Distribution** → Number of weapons per category  
   - **Bullet Type Usage** → Which bullet types are most used  
   - **Average Damage Comparison** → Which weapon type has the highest damage  
   - **Bullet Speed vs. Damage** → Relationship between speed & damage  
   - **Fire Mode Distribution** → Single, Automatic, Burst  

3. **Interactive Excel Dashboard**  
   - Pivot Tables for weapon insights  
   - **Slicers for Filtering** → Filter by **Weapon Type, Bullet Type, Fire Mode, Damage Range**  
   - Charts for visualizing damage, fire rate, and bullet performance  

## 📈 Key Findings
- **7.62mm weapons** generally have higher damage but slower fire rates.  
- **5.56mm weapons** offer a balance of speed and damage.  
- **Snipers have the highest single-shot damage**, while **SMGs excel in close-range DPS**.  
- **Weapons like the Groza & M762** dominate in high damage with automatic fire modes.  

## 🛠️ Tools Used
- **Excel** → Data cleaning, Pivot Tables, Charts, and Dashboard  
- **Python (Pandas, NumPy)** → Data preprocessing (optional)  

## 📥 How to Use
1. Download the dataset: [`pubg-weapon-stats.csv`](link-to-dataset-if-public)  
2. Open `pubg_weapon_dashboard.xlsx` in Excel.  
3. Use **Pivot Tables & Slicers** to explore different weapons and stats.  

## 🚀 Future Improvements
- Add **weapon recoil analysis**.  
- Compare **real-game performance stats** with this dataset.  
- Build an **interactive Python dashboard using Streamlit or Power BI**.  

---

### 📢 **Contribute**
- Feel free to **fork the repo**, submit **pull requests**, or suggest new features!  
- If you find this useful, give it a ⭐ on GitHub!  

---
### 📌Contact
For inquiries or collaboration opportunities, please reach out to me:

**Name**: Malak Ismail  

**Email**: malakismail706@gmail.com 

**LinkedIn**: https://www.linkedin.com/in/malakismail0/ 

---

🚀 *Stay tuned for more PUBG data insights!*
