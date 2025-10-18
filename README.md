**Parking Occupancy Prediction using Machine Learning**

**A Smart Urban Management Approach**

Overview

This project focuses on predicting parking occupancy — whether a parking spot is occupied or available — using machine learning classification models.
It aims to support smart city management by helping urban planners and developers design intelligent parking systems that reduce time waste, fuel consumption, and air pollution.

**Models Used**

Two classification models were implemented and evaluated:

**Decision Tree Classifier** (with cross-validation and hyperparameter tuning)

**SGDClassifier** (no overfitting detected, cross-validation not required)

**Workflow**
1. Data preprocessing and feature selection
2. Model training and evaluation
3. Comparison of results using metrics such as:
  - Accuracy
  - Recall
  - Precision
  - F1-score
4. Confusion matrix visualization with Seaborn
5. Saving trained models using joblib.dump()

| Model         | Accuracy (Train/Test) | Overfitting | Notes                                |
| ------------- | --------------------- | ----------- | ------------------------------------ |
| Decision Tree | 1.00 / 0.53           | ✅ Yes       | Improved after hyperparameter tuning |
| SGDClassifier | 0.61 / 0.61           | ❌ No        | Stable and generalizable             |


_Requirements:_
numpy
pandas
scikit-learn
matplotlib
seaborn
joblib
jupyter

For better performance, use:
Google Colab: https://colab.research.google.com
or
Anaconda (Jupyter): https://www.anaconda.com

---------------------------------------------------------------------------------------------------
**پیش بینی اشغال پارکینگ با استفاده از یادگیری ماشین
رویکردی در جهت مدیریت هوشمند شهری
توضیح پروژه**

هدف این پروژه، پیش‌بینی وضعیت اشغال جای پارک (پر یا خالی بودن) با استفاده از الگوریتم‌های طبقه‌بندی یادگیری ماشین است.
این مدل می‌تواند در سامانه‌های مدیریت هوشمند پارکینگ و در راستای کاهش ترافیک، آلودگی هوا و اتلاف وقت شهروندان مورد استفاده قرار گیرد.
مدل‌های مورد استفاده

**درخت تصمیم (Decision Tree):** با اعتبارسنجی متقابل (Cross Validation) و تنظیم پارامترها

و **SGDClassifier**: بدون بروز بیش‌برازش (Overfitting)

*نتایج کلی*

مدل درخت تصمیم در داده‌های آموزشی بیش‌برازش نشان داد، اما با تنظیم پارامترها و Cross-Validation عملکرد آن بهبود یافت.
مدل SGDClassifier دقت پایداری حدود 61٪ داشت و بیش‌برازش در آن مشاهده نشد.
مدل‌های این پروژه می‌توانند در **سیستم‌های هوشمند شهری** برای:

پیش‌بینی تقاضای پارکینگ

کاهش ترافیک و جست‌وجوی جای پارک

 بهینه‌سازی مصرف سوخت و زمان شهروندان

به‌کار گرفته شوند.

Author: Fardin Vajdi
Email. f.vajdiurban@gmail.com
Date: October 2025
