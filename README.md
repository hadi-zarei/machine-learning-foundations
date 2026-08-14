# مبانی یادگیری ماشین

مخزن آموزشی دورهٔ «مبانی یادگیری ماشین» شامل نوت‌بوک‌های جلسات، راهنمای هر بخش و وابستگی‌های جداگانهٔ آن است.

## نقشهٔ دوره

| بخش | موضوع | نوت‌بوک |
| --- | --- | --- |
| 01 | رگرسیون خطی | `chapter-2-linear-regression.ipynb` |
| 02 | رگرسیون خطی چندمتغیره | `week-3-multiple-linear-regression_1.ipynb` |
| 03 | رگرسیون غیرخطی | `week-4-nonlinear-linear-regression_1.ipynb` |
| 04 | انتخاب مدل | `week-5-model-selection.ipynb` |
| 05-A | پروژهٔ Titanic | `titanic.ipynb` |
| 05-B | مینی‌پروژهٔ Housing | `week-10-mini_project.ipynb` |

## شروع سریع

1. اگر Git نصب دارید، این دستورها را در ترمینال اجرا کنید:

   ```bash
   git clone https://github.com/hadi-zarei/machine-learning-foundations.git
   cd machine-learning-foundations
   ```

   اگر Git نصب ندارید، از **Code → Download ZIP** برای دریافت فایل‌ها استفاده کنید.
2. از ریشهٔ مخزن، وابستگیِ بخش موردنظر را نصب کنید. نمونه:

   ```bash
   pip install -r 01-linear-regression/requirements.txt
   ```

3. فایل‌های داده را در پوشهٔ ریشه‌ای [`data`](data/README.md) قرار دهید.
4. JupyterLab را از ریشهٔ مخزن اجرا کنید:

   ```bash
   jupyter lab
   ```

## وابستگی‌ها و داده‌ها

هر بخش `requirements.txt` اختصاصی خود را دارد. فهرست دقیق فایل‌های دادهٔ موردنیاز در [`data/README.md`](data/README.md) نگهداری می‌شود.
