


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

Step 4: Send the File

Please send the final cookies.txt file to me. I will place it on the server, and then the bot will be able to download your restricted videos instantly.


