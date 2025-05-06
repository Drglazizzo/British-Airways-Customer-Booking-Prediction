

# British Airways - Task 2: Customer Booking Prediction

This is **Task 2** of the British Airways Virtual Internship by Forage. In this task, I used **machine learning** to predict whether a customer will complete a booking based on their behavior and preferences.

Using a dataset containing features such as:
- Days until travel (`purchase_lead`)
- Length of stay
- Preferred seat, extra baggage, in-flight meals
- Sales channel (Internet, Mobile)
- Route and origin

I trained a **Random Forest classifier** to identify key predictors of booking completion and interpreted feature importance to provide actionable insights.

---

## 🧾 Description

✅ Built a **machine learning model** to predict booking completion  
✅ Used **feature engineering** (e.g., `lead_to_stay_ratio`, `total_extra_services`)  
✅ Evaluated model using accuracy, precision, recall, and cross-validation  
✅ Visualized top predictive features  
✅ Created a **PowerPoint summary** for business stakeholders  

---

## 📁 Included Files

| File | Purpose |
|------|---------|
| `task2_booking_prediction.ipynb` | Jupyter Notebook with full analysis |
| `customer_booking.csv` | Dataset used for modeling |
| `top_feature_importances.png` | Feature importance chart |
| `BA_Booking_Prediction_Summary.pptx` | Summary slide for management |

---

## 🧰 Requirements

Install dependencies via:

```bash
pip install pandas scikit-learn matplotlib seaborn python-pptx
```

---

## 🚀 How to Run

1. Place `customer_booking.csv` in the same folder as the notebook
2. Open Jupyter Notebook
3. Run all cells to reproduce results

---

## 🔍 Key Insights

- Customers who request **extra services** (baggage, preferred seat, meals) are more likely to complete bookings  
- Top predictors include `purchase_lead`, `wants_extra_baggage`, and `sales_channel_Internet`  
- Model achieved decent accuracy and can be used to improve marketing targeting and conversion rates  

---

## ✈️ Goal

Provide data-driven insights that help British Airways understand what drives customers to complete or abandon bookings — enabling smarter marketing, improved user experience, and higher conversion rates.

