# ✈️ Predicting Customer Booking Behavior – British Airways

This project aims to predict whether a customer will complete a flight booking using behavioral and transactional data. The dataset includes over **50,000 records**, with various features such as travel lead time, stay duration, and service preferences.

---

## 📊 Project Goals

- Understand key factors that influence booking completion.
- Build a predictive model to identify booking behavior patterns.
- Provide business insights to improve marketing and customer targeting.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, Seaborn, Scikit-learn, Matplotlib)
- **Machine Learning**: Random Forest Classifier
- **Visualization**: Feature importance plots, confusion matrix
- **Data Preprocessing**: One-hot encoding, scaling

---

## 🔍 Key Insights

- **Target variable** was highly imbalanced (~85% No Bookings, ~15% Bookings)
- **Top predictors**: `purchase_lead`, `length_of_stay`, `flight_hour`
- Logistic Regression failed to converge effectively even after scaling
- Random Forest performed best with:
  - **Accuracy**: 85%
  - **ROC AUC Score**: 0.79

---

## 📁 Project Structure

```bash
BA_Customer_Booking_Project/
├── customer_booking.csv              # Dataset
├── BA_Prediction_Notebook.ipynb      # Full notebook analysis
├── Presentation_Slide.pptx           # Final single-slide summary
├── README.md                         # Project overview
---
```

## Author

**Mark-Daniels Tamakloe**  
- MSc Computer Science – Washington University in St. Louis
- MSc Mathematical Sciences – East Tennessee State University
  
[LinkedIn](https://www.linkedin.com/in/mark-daniels-tamakloe-934785a9)


---

## 🔗 Acknowledgement

This project was completed as part of the [British Airways Data Science Virtual Experience](https://www.theforage.com/simulations/british-airways/data-science-yqoz) on Forage.


