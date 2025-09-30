# ✈️ Passenger Satisfaction in Air Travel

## 📌 Project Overview

This project explores key drivers of passenger satisfaction in the air travel industry using a publicly available airline passenger dataset. Through exploratory data analysis, statistical testing, and predictive modeling, the project investigates which features most significantly influence satisfaction and how airlines might use these insights to improve the passenger experience.

**Note:** The dataset used may be synthetic or simulated. While this allowed for large-scale analysis, it may also have introduced artificial patterns or significance not typically found in real-world data. This limitation is acknowledged in the interpretation of findings.

This project was submitted as the final requirement for **Data Tools and Algorithms CISC 3225** at **Brooklyn College, New York**.

---

## 🎯 Project Goals

- Understand the main factors contributing to airline passenger satisfaction.
- Use statistical and machine learning techniques to analyze and model satisfaction outcomes.
- Explore how features such as booking ease, flight delays, seat comfort, and service impact satisfaction.
- Make data-driven recommendations for improving airline operations and customer experience.

---

## 🔍 Key Insights & Methodology Notes

### 📱 Online Booking Satisfaction
- Investigated whether ease of online booking is associated with higher overall satisfaction.
- A **t-test** was the appropriate choice for this analysis given that satisfaction is a binary variable.
- Although a linear regression was briefly attempted, results were ultimately interpreted in the context of the t-test findings.

### 💺 Seat Comfort Across Classes
- Visualized seat comfort scores across different travel classes.
- While the t-test indicated a statistically significant difference, the distributions were **nearly identical**.
- This suggests that the large dataset size may have produced **statistical significance without practical significance**—a common issue in big data analysis.

### ⏱️ Satisfaction & Flight Delays
- Explored the relationship between satisfaction and flight delays.
- **Methodology Note:** Delay status was inferred by comparing actual departure/arrival times to scheduled times. Further discussion of this logic has been added to the project notebook.
- The absence of detailed time data limited the precision of this analysis.

---

## 📊 Tools & Technologies

- **Python 3**
- **Google Colab**
- **Pandas / NumPy** – data manipulation
- **Matplotlib / Seaborn** – visualizations
- **Scikit-learn** – modeling and evaluation
- **VS Code** – local file inspection and documentation

---

## 📁 Project Structure
├── data/ # Raw and cleaned datasets
├── notebooks/ # Colab/Notebook files
├── visuals/ # Graphs and plots
├── models/ # Trained models (if any)
├── README.md # Project documentation
└── requirements.txt # Python dependencies (if running locally)



This is a final project that was created for my Data Tools and Algorithms class created in spring of 2025 
