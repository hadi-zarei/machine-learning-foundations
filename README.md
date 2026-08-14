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

### Windows

<div dir="rtl" align="right">

۱. ابتدا Git و Python 3 را نصب کنید.

۲. سپس **PowerShell** را باز کنید.

۳. دستورهای زیر را اجرا کنید:

</div>

```powershell
mkdir projects-machine-learning
cd projects-machine-learning
git clone https://github.com/hadi-zarei/machine-learning-foundations.git
cd machine-learning-foundations
py -m venv .venv
.\.venv\Scripts\Activate.ps1
```

<div dir="rtl" align="right">

اگر اجرای اسکریپت فعال‌سازی مسدود شد، یک‌بار دستور زیر را در همان PowerShell اجرا کنید و سپس دستور فعال‌سازی را تکرار کنید:

</div>

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### Linux

1. Terminal را باز کنید.
2. دستورهای زیر را اجرا کنید:

   ```bash
   mkdir -p ~/projects-machine-learning
   cd ~/projects-machine-learning
   git clone https://github.com/hadi-zarei/machine-learning-foundations.git
   cd machine-learning-foundations
   python3 -m venv .venv
   source .venv/bin/activate
   ```

## نصب وابستگی‌ها

<div dir="rtl" align="right">

پس از ساخت و فعال‌سازی محیط مجازی، یکی از دو روش زیر را انتخاب کنید:

### نصب وابستگی‌های یک بخش

اگر فقط می‌خواهید یک بخش مشخص را اجرا کنید، وابستگی‌های همان پوشه را نصب کنید. نمونه برای بخش اول:

</div>

```bash
python -m pip install -r 01-linear-regression/requirements.txt
```

<div dir="rtl" align="right">

### نصب وابستگی‌های همهٔ بخش‌ها

اگر می‌خواهید تمام جلسات و پروژه‌ها را یک‌جا اجرا کنید، همهٔ وابستگی‌ها را از فایل ریشهٔ مخزن نصب کنید:

</div>

```bash
python -m pip install -r requirements.txt
```

### دریافت بدون Git

اگر Git نصب نیست، از صفحهٔ مخزن روی **Code → Download ZIP** بزنید، فایل را Extract کنید و سپس از پوشهٔ پروژه، مراحل ساخت محیط مجازی و نصب وابستگیِ سیستم‌عامل خود را ادامه دهید.

## وابستگی‌ها و داده‌ها

هر بخش `requirements.txt` اختصاصی خود را دارد. فهرست دقیق فایل‌های دادهٔ موردنیاز در [`data/README.md`](data/README.md) نگهداری می‌شود.
