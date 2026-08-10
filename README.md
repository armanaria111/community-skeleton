<p align="center"><a href="https://www.uvdesk.com/en/" target="_blank">
    <img src="https://s3-ap-southeast-1.amazonaws.com/cdn.uvdesk.com/uvdesk/bundles/webkuldefault/images/uvdesk-wide.svg">
</a></p>

<p align="center">
    <a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/v/stable.svg" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/d/total.svg" alt="Total Downloads"></a>
    <a href="#backers"><img src="https://opencollective.com/uvdesk/backers/badge.svg" alt="Backers on Open Collective"></a>
    <a href="#sponsors"><img src="https://opencollective.com/uvdesk/sponsors/badge.svg" alt="Sponsors on Open Collective"></a>
    <a href="https://gitter.im/uvdesk/community"><img src="https://badges.gitter.im/uvdesk/community-skeleton.svg" alt="connect on gitter"></a>
    <a href="https://forums.uvdesk.com"><img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg" alt="discuss on uvdesk forum"></a>
    <a href="https://github.com/collections/made-in-india"><img src="https://badges.frapsoft.com/os/v3/open-source.png?v=103" alt="Checkout us on open source projects from India"></a>
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
    <img class="flag-img" src="https://flagicons.lipis.dev/flags/4x3/ir.svg" alt="Chinese" width="24" height="24">

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

About
-----------------

Build on top of [symfony](https://symfony.com/) and [backbone.js](https://backbonejs.org/), uvdesk community is a service oriented, event driven extensible opensource helpdesk system that can be used by your organization to provide efficient support to your clients effortlessly whichever way you imagine.

The standard distribution comes packaged along with the following helpdesk packages to cover a wide range of use-cases and requirements:

  * [**Core Framework**][2] - در قلب سیستم پشتیبانی، چارچوب اصلی شامل تمام API های لازم مورد نیاز پروژه شما و بسته های وابسته برای اجرای روان امور است.

  * [**Extension Framework**][3] - پشتیبانی از ادغام و توسعه بسته‌های شخص ثالث را ارائه می‌دهد تا به راحتی بتوانید قابلیت‌های سیستم پشتیبانی خود را مطابق با نیازهایتان بسازید و گسترش دهید.

  * [**Automation Bundle**][4] - پشتیبانی از گردش‌های کاری و پاسخ‌های آماده را برای خودکارسازی هرگونه عملیات خاص در سیستم پشتیبانی شما اضافه می‌کند.

  * [**Mailbox Component**][11] - تمام ایمیل‌های خود را تبدیل کرده و برای پشتیبانی از تیکت‌ها در UVDesk دریافت کنید و به راحتی درخواست‌های مشتری را مدیریت کنید.

  * [**Support Center Bundle**][5] - پورتال مرکز پشتیبانی که به راحتی قابل تنظیم است را ادغام می‌کند تا کاربران بتوانند به راحتی از طریق سیستم میز کمک شما با کارکنان پشتیبانی تعامل داشته باشند.

Reach out to us at our official [gitter chat][20] or by joining [forum][21] for any queries, concerns and feature request discussions.

The development of the uvdesk community edition is led by the [uvdesk][10] team and backed by [Webkul][9]. Visit our [website][1] to learn more about the UVDesk Helpdesk System.

ویژگی‌ها
----------------

* [پشتیبانی ترجمه (چندزبانه)][32]
* نمایندگان نامحدود، گروه، تیم، مشتریان، تیکت‌ها و غیره
* امتیازات نماینده
* بدون محدودیت در تعداد ادغام صندوق پستی/ایمیل
* Saved Replies for common queries
* Filter based on ticket status, Id, agent, customer, etc
* Block Spam
* [Agent Activity][29]
* [Marketing Announcement][30]
* [Kudos][31]
* reCAPTCHA option
* Standard automated workflows
* Notes for agents
* Custom branding
* Change logo & favicon
* Broadcasting message
* Ticket Forwarding
* Prepared Response
* Email Notification
* Effective search
* User Friendly Web Installer
* Add multiple attachments
* Powerful Knowledgebase/Faq (article, category & folder)
* Ticket types, Multiple Tags
* Email Templates
* [API][16]-[Doc][25]
* Edit/delete/pinned ticket and thread
* Add a collaborator and much more.
* Check Apps [here.][26]

Documentation
--------------

Visit [docs.uvdesk.com](https://docs.uvdesk.com/) to read our official documentation and learn more about the uvdesk community project.

We use Jekyll to develop and maintain our documentations. Consider contributing by submitting a pull request to our project's [jeykll repository](https://github.com/uvdesk/uvdesk.github.io).

الزامات
--------------

* **OS**: Ubuntu 16.04 LTS or higher / Windows 7 or Higher (WAMP / XAMPP).
* **SERVER**: Apache 2 or NGINX.
* **RAM**: 4 GB or higher.
* **PHP**: 8.1
* **Processor**: Clock Cycle 1 Ghz or higher.
* **For MySQL users**: 5.7.23 or higher.
* **Composer**: 2 or higher.
* **PHP IMAP** **&** **PHP Mailparse** for [Ubuntu][7], [Windows][23], [Centos][28], [Mac][27].

نصب
--------------

مراحل نصب به دو مرحله مجزا تقسیم می‌شود:

* راه‌اندازی
* پیکربندی

### Setting up your helpdesk project

در این مرحله از فرآیند نصب، شما اسکلت پروژه helpdesk را دانلود کرده و تمام اجزای وابسته به آن را نصب خواهید کرد.

بسته به راحتی شما، می‌توانید از composer برای دانلود پروژه و نصب خودکار تمام وابستگی‌های آن استفاده کنید یا مستقیماً فایل فشرده پروژه را که از قبل با تمام وابستگی‌های پروژه نصب شده است، دانلود کنید.

ما توصیه می‌کنیم تا حد امکان از composer به جای دانلود مستقیم استفاده کنید. با این حال، اگر سیستم شما رم کافی برای اجرای صحیح عملیات composer را ندارد (به عنوان مثال: نصب روی یک هاست اشتراکی با منابع سیستم محدود)، پیشنهاد می‌کنیم برای کاهش این نوع مشکلات، از روش دانلود مستقیم استفاده کنید.

صرف نظر از روشی که استفاده می‌کنید، فرآیند پیکربندی میز کمک شما یکسان است.

#### Composer

شما می‌توانید با اجرای دستور زیر از ترمینال خود، از composer برای راه‌اندازی پروژه خود استفاده کنید:

```bash
$ composer create-project uvdesk/community-skeleton helpdesk-project
```

#### Direct Download

Alternatively, you can also [download the zip archive](https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip) of the latest stable release and extract its content by running the following commands from your terminal:

```bash
$ wget "https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip" -P /var/www/
$ unzip -q /var/www/uvdesk-community-current-stable.zip -d /var/www/ \
```

### Configuring your helpdesk project

پس از دانلود و نصب تمام وابستگی‌های پروژه، می‌توانید نصب میز کمک خود را با استفاده از یکی از روش‌های زیر پیکربندی کنید:

#### Using Terminal

```bash
$ php bin/console uvdesk:configure-helpdesk
```

#### Using Web Installer Wizard

##### Extract the contents of zip and execute the project in your browser in case of project zip download:

~~~
http(s)://localhost/community-skeleton/public
~~~

##### In case of created project using command, execute the project in your browser:

~~~
http(s)://localhost/helpdesk-project/public
~~~

or

~~~
http(s)://example.com/public
~~~

پس از باز کردن پروژه خود در مرورگر وب، با نصب‌کننده وب مواجه خواهید شد که شما را در پیکربندی پروژه راهنمایی می‌کند.


##### Run project on localhost (dev mode)
```bash
php bin/console server:run
```

**How to clear cache:**

```bash
php bin/console c:c
```

**How to log in as admin/agent:**

*Below url is the default url for admin/agent login if you have not made any changes for /member prefix.*

> *http(s)://example.com/en/member/login* 

**How to log in as customer:**

*Below url is the default url for customer login if you have not made any changes for /customer prefix.*

> *http(s)://example.com/en/customer/login*

Docker Runtime
--------------

[Dockerize your helpdesk project][22]

کانتینر پایدار داکر
--------------

[Get started with Uvdesk now by using docker persistent container][34]

محیط مجازی Vagrant
--------------

[Get started with uvdesk now by using vagrant to setup virtual environment][33]

ماژول‌ها
--------------

[Available Modules/Apps](https://store.webkul.com/UVdesk/UVdesk-Open-Source.html)

Need something else ? email us at support@uvdesk.com

مجوز
--------------

All libraries and bundles included in the UVDesk Community Edition are released under the [OSL-3.0 license][12] license.

Security Vulnerabilities
--------------

Please don't disclose any security vulnerabilities publicly. If you find any security vulnerability in our platform then please write us at [support@uvdesk.com](mailto:support@uvdesk.com).

بازخورد
---------
#### Feedback (Support Community project by raising feedback)

* [Trustpilot][17]
* [Capterra][18]
* [Software suggest][19]

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
