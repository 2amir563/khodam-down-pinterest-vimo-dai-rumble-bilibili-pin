


```
bash <(curl -s https://raw.githubusercontent.com/2amir563/khodam-down-pinterest-vimo-dai-rumble-bilibili-pin/main/install.sh)
```


این راهنما را می‌توانید به صورت مستقیم برای کاربرانی که با خطا مواجه می‌شوند، ارسال کنید.

Subject: Important! How to Download Restricted Videos (Pinterest, Bilibili, Private Content)

Hello,

The bot requires a file called cookies.txt to download videos from sites that require you to be logged in (like Pinterest, Bilibili, and some Vimeo/Streamable links). This is a mandatory security measure by those websites.

You must provide this file from your browser for the bot to work. Your login credentials (username/password) are NOT needed.

📝 4-Step Cookie Extraction Guide:
Step 1: Install the Extension

Install the browser extension 'Get cookies.txt' for your web browser (Chrome, Edge, or Firefox).

Step 2: Log In and Extract

Open your browser and navigate to the problematic website (e.g., Pinterest or Bilibili).

Make sure you are logged into your account and can view the video in the browser.

Click on the 'Get cookies.txt' extension icon.

A file named cookies.txt will be downloaded to your computer.

Step 3: Merge Cookies (If necessary)

If you need to download from multiple restricted sites (like both Pinterest AND Bilibili), you must extract a cookies.txt file from each site and combine their content into a single master cookies.txt file before sending it.

Step 4: Send the File

Please send the final cookies.txt file to me. I will place it on the server, and then the bot will be able to download your restricted videos instantly.


من دو اقدام فوری را پیشنهاد می‌کنم:

1. ⚙️ تأیید صحت نصب (اختیاری)
لطفاً یک بار دیگر، برای اطمینان از اینکه هیچ فایل کوکی‌ای وجود ندارد و تمام فایل‌ها در جای خود هستند، این دستورات را اجرا کنید:

بررسی وضعیت سرویس:

Bash

systemctl status telegram-media-bot
(باید وضعیت active (running) باشد.)

حذف هرگونه فایل کوکی تست قدیمی:

Bash

rm -f /opt/telegram-media-bot/cookies/cookies.txt
راه‌اندازی مجدد برای اعمال تنظیمات نهایی:

Bash

systemctl restart telegram-media-bot
2. 🍪 ارسال راهنمای کوکی به کاربر (اجباری)
لطفاً راهنمای انگلیسی زیر را برای کاربری که لینک‌ها را ارسال می‌کند، بفرستید تا فایل کوکی را برای شما تهیه و ارسال کند. تا زمانی که فایل کوکی برای سایت‌هایی مانند Pinterest و BiliBili در مسیر صحیح قرار نگیرد، دانلود از آن‌ها موفقیت‌آمیز نخواهد بود.

🇺🇸 English Cookie Guide (For the Bot User)
Subject: Important! How to Download Restricted Videos (Pinterest, Bilibili, Private Content)

Hello,

The bot requires a file called cookies.txt to download videos from sites that require you to be logged in (like Pinterest, Bilibili, and some Vimeo/Streamable links). This is a mandatory security measure by those websites.

You must provide this file from your browser for the bot to work. Your login credentials (username/password) are NOT needed.

📝 4-Step Cookie Extraction Guide:
Step 1: Install the Extension

Install the browser extension 'Get cookies.txt' for your web browser (Chrome, Edge, or Firefox).

Step 2: Log In and Extract

Open your browser and navigate to the problematic website (e.g., Pinterest or BiliBili).

Make sure you are logged into your account and can view the video in the browser.

Click on the 'Get cookies.txt' extension icon.

A file named cookies.txt will be downloaded to your computer.

Step 3: Merge Cookies (If necessary)

If you need to download from multiple restricted sites (like both Pinterest AND Bilibili), you must extract a cookies.txt file from each site and combine their content into a single master cookies.txt file before sending it.

این روش، بهترین راه برای حل خطاهای دسترسی (Access/Login Required) در سایت‌هایی مانند Pinterest، Vimeo و BiliBili است.

تهیه فایل cookies.txt یک فرآیند ساده است که باید در مرورگر رایانه شخصی یا لپ‌تاپ خود انجام دهید.

🍪 راهنمای گام به گام: تهیه فایل cookies.txt
1. 🌐 نصب افزونه مرورگر
شما به افزونه‌ای نیاز دارید که بتواند کوکی‌های فعال جلسه (Session) را از مرورگر استخراج کرده و در فرمت استاندارد cookies.txt ذخیره کند.

برای Chrome/Edge: افزونه "Get cookies.txt" را نصب کنید. *

برای Firefox: افزونه "Cookie Quick Manager" یا "Get cookies.txt" را نصب کنید.

2. 🔑 ورود به سایت و آماده‌سازی
مرورگر خود را باز کنید و به سایتی بروید که ربات در دانلود از آن مشکل دارد (مثلاً Pinterest یا BiliBili).

بسیار مهم: مطمئن شوید که با حساب کاربری خود وارد (Log in) شده‌اید و می‌توانید ویدیو یا محتوای مورد نظر را در مرورگر ببینید.

3. 💾 استخراج فایل کوکی
در صفحه‌ای که وارد حساب کاربری شده‌اید (مثلاً صفحه اصلی Pinterest)، روی آیکون افزونه‌ای که در مرحله ۱ نصب کردید، کلیک کنید.

گزینه "Export" یا "Download cookies.txt" را انتخاب کنید.

یک فایل به نام cookies.txt روی کامپیوتر شما دانلود می‌شود.

4. 🔗 ادغام فایل‌ها (اگر از چند سایت کوکی نیاز دارید)
اگر می‌خواهید مشکل دانلود از Pinterest و BiliBili را همزمان حل کنید، باید کوکی‌های هر دو سایت را در یک فایل واحد قرار دهید:

مراحل ۱ تا ۳ را برای Pinterest انجام دهید و فایل cookies.txt را ذخیره کنید.

مراحل ۱ تا ۳ را برای BiliBili انجام دهید و فایل cookies.txt را ذخیره کنید.

هر دو فایل را در یک ویرایشگر متن (مانند Notepad یا VS Code) باز کرده و محتویات یکی را کپی کرده و در انتهای دیگری Paste کنید.

فایل نهایی را با نام cookies.txt ذخیره کنید.

5. 📤 انتقال فایل به سرور (بخش شما)
در نهایت، فایل نهایی cookies.txt را باید در سرور خود، در مسیر مشخص شده قرار دهید:

Bash

/opt/telegram-media-bot/cookies/cookies.txt
پس از قرار دادن فایل، برای اینکه ربات بتواند از آن استفاده کند، حتماً سرویس را ری‌استارت کنید:

Bash

systemctl restart telegram-media-bot

Step 4: Send the File

Please send the final cookies.txt file to me. I will place it on the server, and then the bot will be able to download your restricted videos instantly.


