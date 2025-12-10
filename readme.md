# NYC Yellow Taxi – تحلیل پرترددترین مناطق و Hot Zones شهر نیویورک

این پروژه با استفاده از دیتاست معروف **NYC Yellow Taxi Trip Data** (از Kaggle) به شناسایی و تحلیل **پرترددترین مناطق pickup و dropoff** تاکسی‌های زرد نیویورک در بازهٔ زمانی ۲۰۱۵–۲۰۲۰۲ می‌پردازد.

هدف اصلی:
- پیدا کردن ۱۰–۲۰ منطقهٔ پرتردد شهر (Hot Zones)
- تحلیل الگوهای مکانی و زمانی سفرها
- نمایش بصری نتایج روی نقشهٔ تعاملی نیویورک

## دیتاست استفاده شده
** (دقیقاً همانی که شما دانلود کردید)
**نام دیتاست در Kaggle:**  
[NYC Yellow Taxi Trip Data](https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data)  
مالک: elemento  
حجم: حدود ۱۰۰ گیگابایت (فایل‌های پارکه ماهانه از ژانویه ۲۰۱۵ تا فوریه ۲۰۲۰ + چند ماه ۲۰۲۳–۲۰۲۴)

دانلود خودکار با kagglehub:
```python
import kagglehub
path = kagglehub.dataset_download("elemento/nyc-yellow-taxi-trip-data")
print("Path to dataset files:", path)

