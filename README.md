# Online Statistical Toolbox

این مخزن یک جعبه‌ابزار آماری آماده برای انتشار در GitHub/Colab است. شامل نوت‌بوک‌ها،
داده‌های نمونه، توضیحات و کدهای مستند برای روش‌های اصلی آماری.

## ساختار
```
statistical_toolbox/
├─ data/
│  ├─ demographics.csv
│  ├─ ab_test.csv
│  ├─ linear_regression.csv
│  └─ time_series_daily.csv
├─ notebooks/
│  ├─ 00_Index.ipynb
│  ├─ 01_Descriptive_Stats.ipynb
│  ├─ 02_Hypothesis_Tests.ipynb
│  ├─ 03_Regression.ipynb
│  ├─ 04_ANOVA_Nonparametric.ipynb
│  ├─ 05_Resampling_Power.ipynb
│  ├─ 06_Time_Series.ipynb
│  └─ 07_Interactive_Widgets.ipynb
└─ README.md
```

## اجرا
1. پوشه را در GitHub آپلود کنید یا در Colab باز کنید.
2. نیازمندی‌ها: `numpy`, `pandas`, `scipy`, `matplotlib` (و در صورت نیاز `statsmodels`, `ipywidgets`).
3. از نوت‌بوک `00_Index.ipynb` شروع کنید.

## لایسنس
MIT