# Analysis of Shill Bidding

This project analyzes fraudulent bidding behavior (specifically, **shill bidding**) in online auction platforms using Exploratory Data Analysis (EDA) techniques.

## 📁 Project Overview

Online auction platforms are increasingly susceptible to fraudulent bidding, where users artificially drive up prices. This project uses a public dataset to:

- Compare behaviors of legitimate vs shill bidders
- Analyze bidding patterns (early, late, aggressive)
- Visualize key auction dynamics
- Propose a foundation for fraud detection using ML

## 📊 Dataset

- **Source**: Publicly available CSV titled `Shill Bidding Dataset.csv`
- **Records**: 6,321
- **Features**: 11 numeric features
- **Target**: Binary classification (`Class` - 0: Legitimate, 1: Shill)

### Key Features:
- `Auction_Duration`
- `Auction_Bids`
- `Winning_Ratio`
- `Early_Bidding`
- `Last_Bidding`
- `Class` (target label)

## 🧪 EDA Highlights

- **Class Imbalance**: ~89% Legitimate, ~11% Shill Bidding
- **Bidding Behavior**:
  - Shill bidders place more bids on average
  - Higher early bidding concentration
  - Erratic or strategic avoidance of last-minute bids
- **Winning Ratio**:
  - Higher winning ratio in shorter auctions among shill bidders

## 📈 Tools Used

- Python
  - **NumPy**
  - **Pandas**
  - **Matplotlib**
  - **Seaborn**

## 🧠 Future Scope

- Machine learning classifiers (e.g., Random Forest, XGBoost)
- Real-time fraud detection pipelines
- Feature engineering from session patterns
- Behavioral profiling and anomaly detection

## 📚 References

- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)
- [Seaborn Documentation](https://seaborn.pydata.org/documentation.html)
- [LinkedIn Project Post](https://www.linkedin.com/posts/revanth-kaja-4ab19b2a2_dataanalysis-python-matplotlib-activity-7317210962938212352-tV-v)

## 🧑‍🎓 Author

**Kaja Revanth Sri Narasimha**  
Registration No: 12312200  
Lovely Professional University, Department of CSE/IT

---

📅 Project Semester: January–April 2025  
🎓 Course Code: INT375  
👩‍🏫 Guided by: Dr. Tanima Thakur
