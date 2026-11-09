# Nest Modules Collection 🚀

<div dir="rtl">

## درباره این مخزن

این مخزن (Repository) یک پروژه خاص یا محصول نرم‌افزاری یکپارچه **نیست**.

هدف اصلی این ریپازیتوری، جمع‌آوری و نگهداری **ماژول‌های گوناگون، مجزا و مستقل فریم‌ورک [NestJS](https://nestjs.com/)** است. ماژول‌های قرار گرفته در این مخزن ممکن است از لحاظ دامنه کاری (Domain)، نیازمندی و کاربرد، هیچ‌گونه ارتباطی با یکدیگر نداشته باشند و صرفاً به عنوان الگوهای طراحی، تست مفاهیم (PoC) یا بلوک‌های سازنده مستقل و قابل استفاده مجدد توسعه یافته‌اند.

### ویژگی‌ها و اهداف:
- **استقلال ماژول‌ها**: ماژول‌ها به‌گونه‌ای طراحی می‌شوند که کمترین وابستگی مستقیم را به یکدیگر داشته باشند تا در صورت نیاز بتوان هر کدام را به پروژه‌های مجزا منتقل کرد.
- **تنوع موضوعی**: پیاده‌سازی سناریوهای مختلف بک‌اند (مانند مدیریت هویت و احراز هویت، صف‌ها، ارتباطات و سرویس‌های عمومی).
- **تمرکز بر Best Practiceها**: رعایت ساختار استاندارد NestJS، تفکیک وظایف (Separation of Concerns) و کدهای تمیز.

### ساختار دایرکتوری

کدها و پیاده‌سازی‌ها در پوشه `nest-modules` نگهداری می‌شوند:

```text
Nest-Modules/
├── nest-modules/
│   ├── src/
│   │   ├── modules/       # ماژول‌های مستقل و گوناگون (مانند identity و ...)
│   │   ├── shared/        # قابلیت‌ها و ابزارهای مشترک
│   │   ├── core/          # کانفیگ‌ها و لایه‌های اصلی
│   │   └── ...
└── README.md              # معرفی کلی ریپازیتوری
```

---

</div>

## English Summary

### About This Repository
This repository is **not** a specific standalone application or a monolithic product.

It serves as a **curated collection and sandbox of diverse, independent [NestJS](https://nestjs.com/) modules**. The modules contained within this repository may have no functional relationship with one another and are created as architectural patterns, proof-of-concepts, or reusable building blocks that can be adapted into different NestJS applications.

### Key Highlights:
- **Decoupled Architecture**: Designed to keep modules isolated and easily extractable for other projects.
- **Diverse Domains**: Covers various standalone backend domains (e.g., identity & authentication, workers, utilities).
- **Best Practices**: Demonstrates idiomatic NestJS structure, separation of concerns, and clean coding principles.
