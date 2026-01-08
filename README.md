# Engineering Notes & Articles

A curated collection of my backend engineering articles, notes, and hands-on learnings.
This repository serves as a living index of my writing and technical growth.

---

## English Articles

- [From Junior to Senior: Understanding Challenges in Large Projects](#from-junior-to-senior-understanding-challenges-in-large-projects)
- [Getting Started with CI/CD and Azure DevOps Pipelines](#getting-started-with-cicd-and-azure-devops-pipelines)

---
## مقالات فارسی

- [مسیریابی در Razor Pages: از مفاهیم پایه تا پیاده‌سازی](#مسیریابی-در-razor-pages-از-مفاهیم-پایه-تا-پیاده‌سازی)
- [Repository Pattern در لایهٔ Infrastructure](#repository-pattern-در-لایهٔ-infrastructure)
- [تفاوت API و REST API](#تفاوت-api-و-rest-api)
- [Clean Code: چرا کد تمیز اهمیت دارد](#clean-code-چرا-کد-تمیز-اهمیت-دارد)
- [مسیردهی در API](#مسیردهی-در-API)
- [ تفاوت فایروال‌های Stateful و Stateless](#تفاوت-فایروال‌های-Stateful-و-Stateless)

---

### مسیریابی در Razor Pages: از مفاهیم پایه تا پیاده‌سازی

**توضیح کوتاه**  
در این مقاله به مفهوم مسیریابی در Razor Pages پرداخته‌ام و توضیح داده‌ام که چگونه یک URL
از لحظه‌ی ورود توسط کاربر، به صفحه‌ی درست و منطق مناسب در سمت سرور هدایت می‌شود.
تمرکز مقاله بر درک ذهنی مسیریابی، ارتباط آن با ساختار پوشه‌ها، و نقش آن در طراحی
قابل‌نگهداری برنامه‌های وب است.

**وبسایت**  
نیک‌آموز

**لینک مقاله**  
🔗 https://nikamooz.com/url-routing-to-razor-pages/

---

### Repository Pattern در لایهٔ Infrastructure

**توضیح کوتاه**  
این مقاله به بررسی کاربرد Repository و Unit of Work در لایهٔ Infrastructure می‌پردازد.
در برنامه‌های مقیاس کوچک، دسترسی به دیتابیس معمولاً مستقیم در سرویس‌ها انجام می‌شود، که مشکلاتی مانند تست‌پذیری سخت و پیچیدگی نگهداری ایجاد می‌کند. مقاله توضیح می‌دهد چگونه الگوهای Repository و Unit of Work این مشکلات را حل می‌کنند.

**وبسایت**  
نیک‌آموز

**لینک مقاله**  
🔗 https://nikamooz.com/repository-unit-of-work-infrastructure-layer/

---

### تفاوت API و REST API

**توضیح کوتاه**  
این مقاله به زبان ساده تفاوت میان API و REST API را توضیح می‌دهد. API نقش مترجم بین نرم‌افزارها را دارد و REST API نوع خاصی از آن با قوانین مشخص است. مقاله با مثال‌های کاربردی نشان می‌دهد چگونه درخواست‌ها بین کلاینت و سرور منتقل و پردازش می‌شوند.

**وبسایت**  
نیک‌آموز

**لینک مقاله**  
🔗 https://nikamooz.com/difference-between-api-and-rest-api/

---

### Clean Code: چرا کد تمیز اهمیت دارد

**توضیح کوتاه**  
این مقاله بررسی می‌کند چرا برخی پروژه‌ها با گذشت زمان پرهزینه و پرخطر می‌شوند. تمرکز بر طرز فکر و هنجارهای رفتاری کدنویسی است و چارچوبی بر اساس اصول 5S ژاپنی ارائه می‌دهد که نشان می‌دهد کیفیت کد محصول یک سیستم ساختاریافته و منظم است.

**وبسایت**  
نیک‌آموز

**لینک مقاله**  
🔗 https://nikamooz.com/clean-code/

---

### مسیردهی در API

توضیح کوتاه
مسیر‌دهی (Routing) در طراحی API یکی از مهم‌ترین بخش‌هاست که تأثیر مستقیمی بر خوانایی، استفاده‌پذیری و نگهداری سیستم دارد. در این مقاله توضیح داده‌ام چرا استفاده از مسیرهایی مانند
/api/getAllProducts یا /api/deleteProductById در نگاه اول ساده اما در عمل مشکل‌ساز است. تمرکز مقاله بر طراحی مسیرهای معنادار، سازگار با اصول REST، و قابل‌درک برای تیم‌های فرانت‌اند و موبایل است تا توسعه و نگهداری API در بلندمدت ساده‌تر شود.

وبسایت
نیک‌آموز

لینک مقاله
🔗 https://nikamooz.com/routing-in-api/

---

## تفاوت فایروال‌های Stateful و Stateless

توضیح کوتاه
در طراحی امنیت شبکه، انتخاب بین فایروال‌های Stateful و Stateless تصمیمی صرفاً فنی نیست، بلکه مستقیماً بر مقیاس‌پذیری، مصرف منابع و سطح امنیت سیستم اثر می‌گذارد. در این مقاله با استفاده از یک مثال ملموس (کافی‌شاپ)، توضیح داده‌ام که چگونه فایروال‌های Stateful با نگه‌داشتن وضعیت ارتباط‌ها می‌توانند تصمیم‌های هوشمندتری بگیرند، اما در مقابل هزینه‌ی پردازشی و پیچیدگی بیشتری دارند. در مقابل، فایروال‌های Stateless هر درخواست را به‌صورت مستقل بررسی می‌کنند؛ رویکردی ساده‌تر و سبک‌تر که با ذات پروتکل HTTP نیز هم‌راستاست. تمرکز مقاله بر درک مفهومی این تفاوت‌ها و کاربرد آن‌ها در معماری سیستم‌های مدرن است.

وبسایت
نیک‌آموز

لینک مقاله
🔗 https://nikamooz.com/stateful-vs-stateless/
---

### From Junior to Senior: Understanding Challenges in Large Projects

**Context**  
Junior engineers entering a large software team or a project with an extensive legacy codebase often face overwhelming complexity. They encounter confusion and uncertainty, and key skills are underdeveloped. Small changes can ripple across the system unexpectedly. This stage highlights the gap between hands-on experience and understanding the system as a whole, emphasizing learning and system-awareness.

**Website**  
Substack

**Link**  
🔗 https://rezatajari.substack.com/p/from-junior-to-senior

---

### Getting Started with CI/CD and Azure DevOps Pipelines

**Context**  
Writing code alone is no longer sufficient in modern software development. CI/CD pipelines automate build, test, and deployment processes, improving reliability, visibility, and team coordination. This article explains how Azure DevOps Pipelines enable teams to deliver code with confidence, replacing error-prone manual workflows.

**Website**  
Substack

**Link**  
🔗 https://rezatajari.substack.com/p/getting-started-with-cicd-and-pipelines

---

### Subscribe to my Weekly Newsletter

For regular insights on backend development, system thinking, and software engineering, you can subscribe to my newsletter:

🔗 https://rezatajari.substack.com/
