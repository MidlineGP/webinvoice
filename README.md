# برنامه حسابداری و فاکتور فروشگاهی تحت وب وبینویس
این اسکریپت رایگان و اوپن سورس به جهت کمک به فروشگاه های کوچک که امکان خرید برنامه های حساب داری گران قیمت را ندارند طراحی شده!

از جمله قابلیت های این اسکریپت میتوان به امکان ثبت و نگهداری لیست محصولات، ثبت و نگهداری لیست مشتری ها یا تامین کنندگان فروشگاه، ثبت و نگهداری فاکتور های خرید و فروش محصولات به همراه قابلیت پرینت و pdf، گزارش گیری محصولات، مشتری ها و خرید و فروش و .... اشاره کرد.
<br /><br />
## تصاویر برخی از صفحات :
| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|![login](https://github.com/user-attachments/assets/c6368846-e74a-44a0-afde-2e292d52d069) صفحه لاگین|![new-invoice](https://github.com/user-attachments/assets/00f85e4b-b1c8-4721-8b97-c973178e2594) ساخت فاکتور جدید|![reports](https://github.com/user-attachments/assets/ba87ad02-11d5-4a7d-967c-fefe53b69998) گزارش ها|
|![edit-prod](https://github.com/user-attachments/assets/36df31fc-e71a-4504-ab6b-88922f8a83be) ویرایش محصول|![dash](https://github.com/user-attachments/assets/67217f46-5bbb-4f72-9266-58cc4378fafe) داشبورد|![cus-info](https://github.com/user-attachments/assets/d23b86f0-cc05-4fe6-8040-a2215e502449) اطلاعات مشتری|

<br /><br />
## روش نصب :
1. آخرین نسخه فایل zip آپلود شده را از بخش release ها دانلود کنید. [[کلیک کنید]](https://github.com/MidlineGP/webinvoice/releases/latest/download/webinvoice.zip)
2. فایل را در هاست خود در پوشه مدنظر آپلود و از حالت فشرده خارج کنید.
3. در فایل config.php در بخش Admin Credentials نام کاربری و رمز عبور مدنظر خود را برای حساب ادمین وارد کنید (در [خط 17](https://github.com/MidlineGP/webinvoice/blob/main/config.php#L17) بجای عبارت admin نام کاربری و در [خط 18](https://github.com/MidlineGP/webinvoice/blob/main/config.php#L18) بجای عبارت admin رمز مدنظر قوی وارد کنید).
4. آدرس دامنه و پوشه ی نصب اسکریپت را باز کنید، به صفحه login.php هدایت خواهید شد و امکان ورود به حساب خود را خواهید داشت.
<br /><br />‌‌
## نکات مهم :
1. بعد از اینکه اولین بار سایت را باز کنید پوشه ی uploads و فایلی به نام store.sqlite در پوشه نصب ساخته خواهد شد، به این دو دست نزنید!
2. این اسکریپت نیازی به پایگاه داده mysql ندارد و از ماژول php به نام sqlite3 به عنوان پایگاه داده استفاده میکند و بدون آن کار نخواهد کرد.
3. این اسکریپت در نسخه php 8.2 تست شده و بدون مشکل کار میکند، توصیه میکنم نسخه ی php هاست خود را 8.2 و بالاتر انتخاب کنید.
4. این اسکریپت ممکن است بروزرسانی نشود، استفاده از آن بر عهده خودتان خواهد بود.
<br /><br /><br />
**وبینویس ، فاکتور نویسی با چاشنی اوپن سورس!**
