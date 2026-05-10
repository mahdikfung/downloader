# 🌟 StellarOracle

دانلود خودکار فایل‌ها برای GitHub

---

## 📌 شروع

### 1️⃣ Fork پروژه
- دکمه **Fork** را کلیک کنید

### 2️⃣ آپلود فایل‌ها
- `Downloder.yml` و `cleaner.yml` را در `.github/workflows/` قرار دهید

### 3️⃣ استفاده
- روی **Actions** کلیک کنید
- Workflow را انتخاب کنید
- **Run** را کلیک کنید

---

## 🎯 مثال‌ها

**دانلود ساده:**
```
URL: https://example.com/file.zip
Mode: normal
```

**دانلود بزرگ:**
```
URL: https://example.com/large.iso
Mode: zip
Password: secure123
```

**چند فایل:**
```
URLs: link1 link2 link3
```

---

## ⚙️ Mode‌ها

| Mode | برای چه | تقسیم | رمز |
|------|---------|-------|-----|
| normal | فایل کوچک | ❌ | ❌ |
| zip | فایل بزرگ | ✅ | ✅ |

---

## ✅ نکات

- URL صحیح باشد
- رمز قوی انتخاب کنید
- مخزن را تمیز نگه دارید
