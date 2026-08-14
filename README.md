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

> این مخزن Private است. پیش از شروع، باید دعوت دسترسی را در حساب GitHub خود قبول کرده باشید.

### Windows

1. Git و Python 3 را نصب کنید.
2. **PowerShell** را باز کنید.
3. دستورهای زیر را اجرا کنید:

   ```powershell
   cd $HOME\Documents
   mkdir MachineLearning -ErrorAction SilentlyContinue
   cd MachineLearning
   git clone https://github.com/hadi-zarei/machine-learning-foundations.git
   cd machine-learning-foundations
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   python -m pip install -r 01-linear-regression/requirements.txt
   jupyter lab
   ```

   اگر اجرای اسکریپت فعال‌سازی مسدود شد، یک‌بار این دستور را در همان PowerShell اجرا کنید و سپس دستور فعال‌سازی را تکرار کنید:

   ```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   ```

### Linux

1. Terminal را باز کنید.
2. دستورهای زیر را اجرا کنید:

   ```bash
   mkdir -p ~/projects
   cd ~/projects
   git clone https://github.com/hadi-zarei/machine-learning-foundations.git
   cd machine-learning-foundations
   python3 -m venv .venv
   source .venv/bin/activate
   python -m pip install -r 01-linear-regression/requirements.txt
   jupyter lab
   ```

### دریافت بدون Git

اگر Git نصب نیست، از صفحهٔ مخزن روی **Code → Download ZIP** بزنید، فایل را Extract کنید و سپس از پوشهٔ پروژه، مراحل ساخت محیط مجازی و نصب وابستگیِ سیستم‌عامل خود را ادامه دهید.

## وابستگی‌ها و داده‌ها

هر بخش `requirements.txt` اختصاصی خود را دارد. فهرست دقیق فایل‌های دادهٔ موردنیاز در [`data/README.md`](data/README.md) نگهداری می‌شود.
