# Vendra — وضعیت پروژه v9
**تاریخ:** ۲۲ خرداد ۱۴۰۵

---

## ✅ چی تموم شد

- ثبت سفارش واقعی end-to-end
- فرم ثبت‌نام با موبایل
- لاگین دو حالته (نماینده/فروشگاه‌دار با موبایل، ادمین با ایمیل)
- پنل ادمین با تایید/رد کاربران و سفارش‌ها
- **قیمت‌گذاری بر اساس نقش — از Supabase** ✅

---

## ❌ مانده

- نمایش سفارش‌های تایید شده در پنل ادمین (فیلتر وضعیت)
- عکس محصول در کاتالوگ
- اعلان واتساپ/تلگرام برای سفارش جدید

---

## اطلاعات مهم

| آیتم | مقدار |
|------|-------|
| آدرس سایت | `raedir.github.io/vendra` |
| Supabase URL | `https://uorkgrinbbdcdtimagay.supabase.co` |
| Publishable Key | توی Bitwarden — Supabase - Publishable Key |
| Tenant ID | `00000000-0000-0000-0000-000000000001` |
| GitHub Repo | `https://github.com/raedir/vendra` |
| پوشه لوکال | `C:\Users\Ghavamian\Desktop\vendra` |
| ایمیل ادمین | `hraedgh@gmail.com` |
| پسورد ادمین | توی Bitwarden — Vendra Admin User |
| Branch | `main` |
| فرمت ایمیل کاربران | `09xxxxxxxxxx@vendra.app` |

---

## ابزارهای نصب شده

| ابزار | وضعیت |
|-------|--------|
| VS Code | ✅ |
| Node.js v24 | ✅ |
| Git v2.54 | ✅ |
| Claude Code Desktop | ✅ |
| Claude Code ترمینال | `cd C:\Users\Ghavamian\Desktop\vendra && claude --dangerously-skip-permissions` |

---

## جداول Supabase

| جدول | نکته مهم |
|------|----------|
| `product_prices` | کلید product_id در واقع category_id هست — foreign key حذف شده |
| `contact_types` | نماینده: `...000010` / فروشگاه: `...000020` |
| RLS | فقط `contact_types` و `tenants` فعال — بقیه غیرفعال |

---

## نکات مهم برای چت بعدی

1. این فایل رو توی Project Files آپلود کن (جای v8)
2. Claude Code رو با این دستور اجرا کن:
   `cd C:\Users\Ghavamian\Desktop\vendra && claude --dangerously-skip-permissions`
3. بگو: **"ادامه Vendra"**

---

## ایده‌های آینده

- **Soshia Content Agent** — اتصال به وردپرس سوشیاشاپ برای تولید مقاله، اینترلینک، لندینگ و باندل با AI
- مهاجرت از Supabase به لیارا (ایرانی، بدون ریسک تحریم)

---

*ساخته شده با Claude | پروژه Vendra*
