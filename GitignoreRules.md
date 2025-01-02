## **English Version:**  

# Gitignore Rules  

## Rules and Descriptions  
- `main.css`: Ignore a specific file named `main.css` in any directory.  
- `/main.css`: Ignore `main.css` only in the root directory.  
- `assets/`: Ignore all files inside the `assets` folder.  
- `assets/fonts/`: Ignore all files inside the `fonts` subfolder of `assets`.  
- `*.log`: Ignore all files with the `.log` extension.  
- `/*.config`: Ignore all `.config` files only in the root directory.  
- `!readme.md`: Exclude `readme.md` from being ignored even if it matches other patterns.  
- `index[a-z1-9].html`: Ignore HTML files matching the regex `index` followed by a lowercase letter or a number.  

## Useful Resource  
- Visit [gitignore.io](https://gitignore.io) to generate `.gitignore` files for your projects.  


---

<div dir="rtl">

## **نسخه فارسی:**  

# قوانین Gitignore  

## قوانین و توضیحات

- `main.css`: فایل خاصی به نام `main.css` را در هر دایرکتوری نادیده بگیرید.  
- `main.css/`: فقط فایل `main.css` را در دایرکتوری اصلی نادیده بگیرید.  
- `/assets`: تمام فایل‌های داخل پوشه `assets` را نادیده بگیرید.  
- `/assets/fonts`: تمام فایل‌های داخل پوشه `fonts` زیر `assets` را نادیده بگیرید.  
- `log.*`: تمام فایل‌هایی با پسوند `.log` را نادیده بگیرید.  
- `config.*/`: تمام فایل‌های `.config` را فقط در دایرکتوری اصلی نادیده بگیرید.  
- `readme.md!`: فایل `readme.md` را حتی اگر با الگوهای دیگر مطابقت داشته باشد، نادیده نگیرید.  
- `index[a-z1-9].html`: فایل‌های HTML مطابق با الگوی `index` به‌دنبال یک حرف کوچک یا عدد را نادیده بگیرید.  

## منبع مفید  
- به [gitignore.io](https://gitignore.io) مراجعه کنید تا فایل‌های `gitignore.` مناسب برای پروژه‌های خود ایجاد کنید.  

</div>