<p align="center"><a href="https://www.uvdesk.com/en/" target="_blank">
    <img src="https://s3-ap-southeast-1.amazonaws.com/cdn.uvdesk.com/uvdesk/bundles/webkuldefault/images/uvdesk-wide.svg">
</a></p>

<p align="center">
    <a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/v/stable.svg" alt="آخرین نسخه پایدار"></a>
    <a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/d/total.svg" alt="کل دانلودها"></a>
    <a href="#backers"><img src="https://opencollective.com/uvdesk/backers/badge.svg" alt="حامیان در Open Collective"></a>
    <a href="#sponsors"><img src="https://opencollective.com/uvdesk/sponsors/badge.svg" alt="حامیان مالی در Open Collective"></a>
    <a href="https://gitter.im/uvdesk/community"><img src="https://badges.gitter.im/uvdesk/community-skeleton.svg" alt="اتصال به گیتِر"></a>
    <a href="https://forums.uvdesk.com"><img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg" alt="بحث در انجمن uvdesk"></a>
    <a href="https://github.com/collections/made-in-india"><img src="https://badges.frapsoft.com/os/v3/open-source.png?v=103" alt="ما را در پروژه‌های متن‌باز هند دنبال کنید"></a>
</p>

<p align="center">
    <a href="https://twitter.com/intent/follow?screen_name=uvdesk"><img src="https://img.shields.io/twitter/follow/uvdesk?style=social"></a>
    <a href="https://www.youtube.com/channel/UCKKt4IOC7ynLwhJMP35uFeQ"><img src="https://img.shields.io/youtube/channel/subscribers/UCKKt4IOC7ynLwhJMP35uFeQ?style=social"></a>
</p>

<p align="center">
    ➡️ <a href="https://www.uvdesk.com/en/opensource/">وب‌سایت</a> | <a href="https://docs.uvdesk.com/">مستندات</a> | <a href="https://www.uvdesk.com/en/blog/open-source-helpdesk-installation-on-ubuntu-uvdesk/">راهنمای نصب</a> | <a href="https://forums.uvdesk.com/">انجمن‌ها</a> | <a href="https://www.facebook.com/uvdesk/">جامعه</a> ⬅️
</p>

<p align="center" style="display: inline;">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/ar.svg" alt="Arabic" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/de.svg" alt="German" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/us.svg" alt="English" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/es.svg" alt="Spanish" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/fr.svg" alt="French" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/it.svg" alt="Italian" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/dk.svg" alt="Danish" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/pl.svg" alt="Polish" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/tr.svg" alt="Turkish" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/cn.svg" alt="Chinese" width="24" height="24">
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/ir.svg" alt="Persian" width="24" height="24">

</p>

[میز کمک انجمن Uvdesk][1] اسکلت پروژه به همراه ابزارها و امکانات ضروری برای ساخت و سفارشی‌سازی راه‌حل‌های میز خدمت شما ارائه شده است.

برای مشاهده دمو به وبسایت رسمی ما مراجعه کنید [آن را در عمل ببینید!][15]

UVdesk را بررسی کنید **وب‌سایت رسمی سیمفونی** – [Symfony][24]

شروع به کار
-----------------

* [درباره ما](#about)
* [ویژگی‌ها](#features)
* [مستندات](#documentation)
* [ماژول‌ها](#modules)
* [الزامات](#requirements)
* [نصب](#installation)
* [زمان اجرای داکر](#docker-runtime)
* [کانتینر پایدار داکر](#docker-persistent-container)
* [محیط مجازی Vagrant](#vagrant-virtual-environment)
* [مجوز](#license)
* [آسیب‌پذیری‌های امنیتی](#security-vulnerabilities)
* [بازخورد](#feedback)
* [مشارکت‌ها](#contributions)

درباره ما
-----------------

انجمن uvdesk که بر پایه [symfony](https://symfony.com/) و [backbone.js](https://backbonejs.org/) ساخته شده است، یک سیستم میز کمک متن‌باز توسعه‌پذیر، سرویس‌گرا و رویدادمحور است که می‌تواند توسط سازمان شما برای ارائه پشتیبانی کارآمد به مشتریانتان به راحتی و به هر روشی که تصور می‌کنید، مورد استفاده قرار گیرد.

توزیع استاندارد به همراه بسته‌های کمکی زیر ارائه می‌شود تا طیف وسیعی از موارد استفاده و الزامات را پوشش دهد:

  * [**چارچوب اصلی**][2] - در قلب سیستم پشتیبانی، چارچوب اصلی شامل تمام API های لازم مورد نیاز پروژه شما و بسته های وابسته برای اجرای روان امور است.

  * [**چارچوب الحاقی**][3] - پشتیبانی از ادغام و توسعه بسته‌های شخص ثالث را ارائه می‌دهد تا به راحتی بتوانید قابلیت‌های سیستم پشتیبانی خود را مطابق با نیازهایتان بسازید و گسترش دهید.

  * [**بسته اتوماسیون**][4] - پشتیبانی از گردش‌های کاری و پاسخ‌های آماده را برای خودکارسازی هرگونه عملیات خاص در سیستم پشتیبانی شما اضافه می‌کند.

  * [**کامپوننت صندوق پستی**][11] - تمام ایمیل‌های خود را تبدیل کرده و برای پشتیبانی از تیکت‌ها در UVDesk دریافت کنید و به راحتی درخواست‌های مشتری را مدیریت کنید.

  * [**بسته مرکز پشتیبانی**][5] - پورتال مرکز پشتیبانی که به راحتی قابل تنظیم است را ادغام می‌کند تا کاربران بتوانند به راحتی از طریق سیستم میز کمک شما با کارکنان پشتیبانی تعامل داشته باشند.

برای هرگونه سوال، نگرانی و بحث در مورد درخواست ویژگی‌ها، از طریق [گِیتِر چت][20] رسمی ما یا با عضویت در [انجمن][21] با ما در ارتباط باشید.

توسعه نسخه عمومی uvdesk توسط تیم [uvdesk][10] رهبری و توسط [Webkul][9] پشتیبانی می‌شود. برای کسب اطلاعات بیشتر در مورد سیستم پشتیبانی UVDesk، از [وب‌سایت][1] ما دیدن کنید.

ویژگی‌ها
----------------

* [پشتیبانی ترجمه (چندزبانه)][32]
* نمایندگان نامحدود، گروه، تیم، مشتریان، تیکت‌ها و غیره
* امتیازات نماینده
* بدون محدودیت در تعداد ادغام صندوق پستی/ایمیل
* پاسخ‌های ذخیره‌شده برای پرسش‌های رایج
* فیلتر بر اساس وضعیت تیکت، شناسه، نماینده، مشتری و غیره
* مسدود کردن هرزنامه
* [فعالیت نماینده][29]
* [اطلاعیه بازاریابی][30]
* [تمجید][31]
* گزینه reCAPTCHA
* گردش‌های کاری خودکار استاندارد
* یادداشت‌ها برای نمایندگان
* برندسازی سفارشی
* تغییر لوگو و فاویکون
* پیام پخش
* ارسال تیکت
* پاسخ آماده
* اعلان ایمیل
* جستجوی مؤثر
* نصب‌کننده وب کاربرپسند
* افزودن چندین پیوست
* پایگاه دانش/سوالات متداول قدرتمند (مقاله، دسته‌بندی و پوشه)
* انواع تیکت، برچسب‌های چندگانه
* قالب‌های ایمیل
* [API][16]-[Doc][25]
* ویرایش/حذف/پین کردن تیکت و موضوع
* اضافه کردن یک همکار و موارد دیگر.
* بررسی برنامه‌ها [اینجا][26]

مستندات
--------------

برای مطالعه مستندات رسمی ما و کسب اطلاعات بیشتر در مورد پروژه انجمن uvdesk، به [docs.uvdesk.com](https://docs.uvdesk.com/) مراجعه کنید.

ما از Jekyll برای توسعه و نگهداری مستندات خود استفاده می‌کنیم. با ارسال درخواست pull به پروژه ما، مشارکت خود را در نظر بگیرید. [jeykll repository](https://github.com/uvdesk/uvdesk.github.io).

الزامات
--------------

* **سیستم عامل**: اوبونتو ۱۶.۰۴ LTS یا بالاتر / ویندوز ۷ یا بالاتر (WAMP / XAMPP).
* **سرور**: Apache 2 or NGINX.
* **رم**: ۴ گیگابایت یا بالاتر.
* **PHP**: 8.1
* **Processor**: سیکل ساعت ۱ گیگاهرتز یا بالاتر.
* **برای کاربران MySQL**: ۵.۷.۲۳ یا بالاتر.
* **Composer**: ۲ یا بالاتر.
* **PHP IMAP** **&** **پی اچ پی میل پارسینگ** برای [اوبونتو][7], [ویندوز][23], [سنتوس][28], [مک][27].

نصب
--------------

مراحل نصب به دو مرحله مجزا تقسیم می‌شود:

* راه‌اندازی
* پیکربندی

### راه‌اندازی پروژه میز کمک شما

در این مرحله از فرآیند نصب، شما اسکلت پروژه helpdesk را دانلود کرده و تمام اجزای وابسته به آن را نصب خواهید کرد.

بسته به راحتی شما، می‌توانید از composer برای دانلود پروژه و نصب خودکار تمام وابستگی‌های آن استفاده کنید یا مستقیماً فایل فشرده پروژه را که از قبل با تمام وابستگی‌های پروژه نصب شده است، دانلود کنید.

ما توصیه می‌کنیم تا حد امکان از composer به جای دانلود مستقیم استفاده کنید. با این حال، اگر سیستم شما رم کافی برای اجرای صحیح عملیات composer را ندارد (به عنوان مثال: نصب روی یک هاست اشتراکی با منابع سیستم محدود)، پیشنهاد می‌کنیم برای کاهش این نوع مشکلات، از روش دانلود مستقیم استفاده کنید.

صرف نظر از روشی که استفاده می‌کنید، فرآیند پیکربندی میز کمک شما یکسان است.

#### Composer

شما می‌توانید با اجرای دستور زیر از ترمینال خود، از composer برای راه‌اندازی پروژه خود استفاده کنید:

```bash
$ composer create-project uvdesk/community-skeleton helpdesk-project
```

#### دانلود مستقیم

همچنین می‌توانید [فایل فشرده‌ی آخرین نسخه‌ی پایدار را دانلود کنید](https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip) و با اجرای دستورات زیر در ترمینال خود، محتوای آن را استخراج کنید:

```bash
$ wget "https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip" -P /var/www/
$ unzip -q /var/www/uvdesk-community-current-stable.zip -d /var/www/ \
```

### پیکربندی پروژه میز کمک شما

پس از دانلود و نصب تمام وابستگی‌های پروژه، می‌توانید نصب میز کمک خود را با استفاده از یکی از روش‌های زیر پیکربندی کنید:

#### استفاده از ترمینال

```bash
$ php bin/console uvdesk:configure-helpdesk
```

#### استفاده از ویزارد نصب تحت وب

##### در صورت دانلود فایل زیپ پروژه، محتویات فایل زیپ را استخراج کرده و پروژه را در مرورگر خود اجرا کنید:

~~~
http(s)://localhost/community-skeleton/public
~~~

##### در صورت ایجاد پروژه با استفاده از دستور، پروژه را در مرورگر خود اجرا کنید:

~~~
http(s)://localhost/helpdesk-project/public
~~~

یا

~~~
http(s)://example.com/public
~~~

پس از باز کردن پروژه خود در مرورگر وب، با نصب‌کننده وب مواجه خواهید شد که شما را در پیکربندی پروژه راهنمایی می‌کند.


##### اجرای پروژه روی لوکال هاست (حالت توسعه)
```bash
php bin/console server:run
```

**نحوه پاک کردن حافظه پنهان:**

```bash
php bin/console c:c
```

**نحوه ورود به سیستم به عنوان مدیر/نماینده:**

*در زیر آدرس اینترنتی پیش‌فرض برای ورود مدیر/نماینده آمده است، البته اگر تغییری در پیشوند /member ایجاد نکرده باشید.*

> *http(s)://example.com/en/member/login* 

**نحوه ورود به عنوان مشتری:**

*آدرس اینترنتی زیر، آدرس اینترنتی پیش‌فرض برای ورود مشتری است، البته اگر تغییری در پیشوند /customer ایجاد نکرده باشید.*

> *http(s)://example.com/en/customer/login*

زمان اجرای داکر
--------------

[پروژه پشتیبانی خود را داکر کنید][22]

کانتینر پایدار داکر
--------------

[همین حالا با استفاده از کانتینر دائمی داکر، کار با Uvdesk را شروع کنید][34]

محیط مجازی Vagrant
--------------

[همین حالا با استفاده از vagrant برای راه‌اندازی محیط مجازی، کار با uvdesk را شروع کنید.][33]

ماژول‌ها
--------------

[ماژول‌ها/اپلیکیشن‌های موجود](https://store.webkul.com/UVdesk/UVdesk-Open-Source.html)

به چیز دیگری نیاز دارید؟ به ما ایمیل بزنید به آدرس support@uvdesk.com

مجوز
--------------

تمام کتابخانه‌ها و بسته‌های موجود در نسخه عمومی UVDesk تحت مجوز [OSL-3.0 license][12] منتشر شده‌اند.

آسیب‌پذیری‌های امنیتی
--------------

لطفاً هیچ آسیب‌پذیری امنیتی را به‌صورت عمومی فاش نکنید. اگر هرگونه آسیب‌پذیری امنیتی در پلتفرم ما پیدا کردید، لطفاً برای ما به آدرس ایمیل زیر بنویسید. [support@uvdesk.com](mailto:support@uvdesk.com).

بازخورد
---------
#### بازخورد (با مطرح کردن بازخورد، از پروژه انجمن حمایت کنید)

* [تراست‌پایلوت][17]
* [کاپترا][18]
* [پیشنهاد نرم‌افزار][19]

مشارکت‌ها
--------------
این پروژه در [اوپن کالکتیو][13] میزبانی می‌شود و به لطف مشارکت‌کنندگان ما وجود دارد:

<a href="https://github.com/uvdesk/community-skeleton/graphs/contributors"><img src="https://opencollective.com/uvdesk/contributors.svg?width=890&button=false"/></a>

#### حامیان

از همه حامیانمون ممنونم! 🙏

<a href="https://opencollective.com/uvdesk#contributors" target="_blank"><img src="https://opencollective.com/uvdesk/backers.svg?width=890"></a>

#### حامیان مالی

با حمایت مالی از این پروژه، از آن حمایت کنید. لوگوی شما به همراه لینکی به وب‌سایتتان در اینجا نمایش داده خواهد شد.

<a href="https://opencollective.com/uvdesk/contribute/sponsor-7372/checkout" target="_blank"><img src="https://images.opencollective.com/static/images/become_sponsor.svg"></a>

[1]: https://www.uvdesk.com/
[2]: https://github.com/uvdesk/core-framework
[3]: https://github.com/uvdesk/extension-framework
[4]: https://github.com/uvdesk/automation-bundle
[5]: https://github.com/uvdesk/support-center-bundle
[6]: https://support.uvdesk.com/en/blog/prerequisites-ubuntu
[7]: https://support.uvdesk.com/en/blog/prerequisites-ubuntu
[8]: https://getcomposer.org/
[9]: https://webkul.com/
[10]: https://www.uvdesk.com/en/team/
[11]: https://github.com/uvdesk/mailbox-component
[12]: https://github.com/uvdesk/community-skeleton/blob/master/LICENSE.txt
[13]: https://opencollective.com/uvdesk
[14]: https://docs.uvdesk.com/
[15]: https://demo.uvdesk.com/
[16]: https://github.com/uvdesk/api-bundle
[17]: https://www.trustpilot.com/review/uvdesk.com
[18]: https://www.capterra.com/p/158346/UVdesk/
[19]: https://www.softwaresuggest.com/uvdesk
[20]: https://gitter.im/uvdesk/community
[21]: https://forums.uvdesk.com/
[22]: https://github.com/uvdesk/community-skeleton/wiki/dockerize-helpdesk-project
[23]: https://support.uvdesk.com/en/blog/prerequisites-windows
[24]: https://symfony.com/projects/uvdesk
[25]: https://github.com/uvdesk/api-bundle/wiki/Ticket-Related-APIs
[26]: https://store.webkul.com/UVdesk/UVdesk-Open-Source.html
[27]: https://support.uvdesk.com/en/blog/prerequisites-mac
[28]: https://support.uvdesk.com/en/blog/prerequisites-centos7
[29]: https://www.uvdesk.com/en/blog/uvdesk-agent-activity/
[30]: https://www.uvdesk.com/en/blog/uvdesk-marketing-announcement/
[31]: https://support.uvdesk.com/es/blog/uvdesk-what-is-kudos
[32]: https://www.uvdesk.com/en/blog/language-translation-in-uvdesk-open-source-helpdesk/
[33]: https://github.com/uvdesk/community-skeleton/wiki/Vagrant-Virtual-Machine-Environment
[34]: https://github.com/uvdesk/community-skeleton/wiki/Docker-Persistent-Container
