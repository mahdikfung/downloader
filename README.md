# GitHub Actions Workflow Collection



## چگونه از این مخزن استفاده کنم؟

1. اگر می‌خواهید این مخزن را در حساب خودتان داشته باشید، از صفحه‌ی `StellarOracle/downloader` روی دکمه‌ی `Fork` کلیک کنید.
2. به مخزن فورک شده‌ی خود بروید.
3. روی تب `Actions` کلیک کنید.
4. یکی از workflowها را انتخاب کنید:
   - `cleaner.yml`
   - `Downloder.yml`
5. روی دکمه‌ی `Run workflow` کلیک کنید.

## توضیحات هر workflow

- `cleaner.yml`
  - همه‌ی فایل‌های داخل `downloads` را حذف می‌کند.
  - دوباره پوشه‌ی `downloads` را می‌سازد.
  - یک فایل `downloads/README.md` جدید ایجاد می‌کند.

- `Downloder.yml`
  - برای دانلود فایل‌ها یا منابع استفاده می‌شود.
  - جزئیات دقیق‌تر را داخل خود فایل `Downloder.yml` ببینید.

> ⚠️ هشدار: قبل از اجرای `cleaner.yml` مطمئن شوید که از فایل‌های مهم داخل `downloads` نسخه پشتیبان دارید، چون همه چیز پاک می‌شود.
