عنوان: 
طراحی و پیاده‌سازی مدار کنترل با کی‌پد ماتریسی و نمایش مقدار کلید فشرده شده بر روی سریال با استفاده از آردوینو
هدف آزمایش:
هدف اصلی این آزمایش، طراحی و پیاده‌سازی یک مدار ساده با استفاده از کی‌پد ماتریسی و برد آردوینو UNO است که قادر به تشخیص کلید فشرده شده بر روی کی‌پد بوده و مقدار آن را از طریق ارتباط سریال به کامپیوتر ارسال کند.
تئوری آزمایش:
•	برد آردوینو: UNO این برد یک میکروکنترلر است که می‌تواند ورودی‌ها را از طریق پین‌های خود دریافت کرده و خروجی‌ها را کنترل کند. در این آزمایش، از پین‌های دیجیتال آردوینو برای خواندن وضعیت ردیف‌ها و ستون‌های کی‌پد ماتریسی استفاده می‌شود.
•	کی‌پد ماتریسی 4  :4 x این کی‌پد شامل 16 کلید است که در یک آرایش ماتریسی از 4 ردیف و 4 ستون قرار گرفته‌اند. هر کلید در محل تقاطع یک ردیف و یک ستون قرار دارد. با فشردن یک کلید، اتصال الکتریکی بین ردیف و ستون مربوطه برقرار می‌شود. با اسکن کردن متوالی ردیف‌ها و خواندن وضعیت ستون‌ها، می‌توان تشخیص داد که کدام کلید فشرده شده است. برای استفاده از کی‌پد 4x4، معمولاً 8 پین از میکروکنترلر مورد نیاز است (4 پین برای ردیف‌ها و 4 پین برای ستون‌ها).
•	کتابخانه: Keypad برای سهولت در کار با کی‌پدهای ماتریسی در محیط آردوینو، کتابخانه‌های آماده‌ای وجود دارند که توابع لازم برای تشخیص کلید فشرده شده را فراهم می‌کنند. در این آزمایش، از کتابخانه Keypad.h استفاده می‌شود.
شرح مدار و قطعات مورد استفاده:
•	برد آردوینو UNO
•	1 عدد کی‌پد ماتریسی 44 x 
•	 سیم‌های مخابراتی 

روش انجام آزمایش:
1.	اتصالات سخت افزاری

•	کی‌پد ماتریسی را روی برد بورد قرار می‌دهیم.
•	پین‌های ردیف‌های کی‌پد (ROWS) را با استفاده از سیم‌های مخابراتی به پین‌های دیجیتال 9، 8، 7 و 6 برد آردوینو متصل می‌کنیم. (به ترتیب با سیم های سفید، نارنجی ، بنفش ،قرمز)
•	پین‌های ستون‌های کی‌پد (COLS) را با استفاده از سیم‌های مخابراتی به پین‌های دیجیتال 5، 4، 3 و 2 برد آردوینو متصل می‌کنیم. (به ترتیب با سیم های مشکی ، آبی ، زرد ، سبز)
•	ترتیب اتصال ردیف‌ها و ستون‌ها به پین‌های آردوینو باید با آرایه‌های rowPins و colPins در کد آردوینو مطابقت داشته باشد

نتیجه گیری:
نتیجه‌گیری کلی آزمایش: در این آزمایش، یک مدار برای تشخیص کلیدهای فشرده شده بر روی کی‌پد ماتریسی 4x4 با استفاده از برد آردوینو UNO با موفقیت طراحی و پیاده‌سازی شد. مقدار کلید فشرده شده به طور آنی از طریق ارتباط سریال به کامپیوتر ارسال و بر روی Serial Monitor نمایش داده شد. این آزمایش نشان می‌دهد که چگونه می‌توان از کی‌پدهای ماتریسی به عنوان یک رابط ورودی برای پروژه‌های آردوینو استفاده کرد و با استفاده از کتابخانه Keypad.h، فرآیند خواندن کلیدها به سادگی قابل انجام است. این روش می‌تواند در پروژه‌های مختلفی نظیر سیستم‌های ورود رمز، کنترل از راه دور و رابط‌های کاربری مورد استفاده قرار گیرد.




[keypad.pdf](https://github.com/user-attachments/files/20194155/keypad.pdf)
[keypad.docx](https://github.com/user-attachments/files/20194154/keypad.docx)
![photo18529385189](https://github.com/user-attachments/assets/b152edee-a824-4a79-9055-1a2f4863b9db)
![keypad](https://github.com/user-attachments/assets/f163022a-a94d-4d25-86eb-fa0b6a9d2c10)


https://github.com/user-attachments/assets/4dad5992-d2ac-4449-95ba-e8fb029786e5


