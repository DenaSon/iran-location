# 🇮🇷 Iran Locations for Laravel 

[![Latest Version on Packagist](https://img.shields.io/packagist/v/denason/iran-location.svg?style=flat-square)](https://packagist.org/packages/denason/iran-location)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Laravel](https://img.shields.io/badge/Laravel-10.x-orange.svg?style=flat-square)](https://laravel.com)
[![Tests](https://img.shields.io/badge/tests-passing-brightgreen.svg?style=flat-square)](#)
[![Total Downloads](https://img.shields.io/packagist/dt/denason/iran-location.svg?style=flat-square)](https://packagist.org/packages/denason/iran-location)

---

## 🏞 اطلاعات موقعیت مکانی ایران (استان‌ها و شهرها)

این پکیج لاراول، لیست کامل **استان‌های ایران** و **شهرهای وابسته به هر استان** را فراهم می‌کند و برای هر پروژه‌ای که به اطلاعات موقعیت جغرافیایی داخلی ایران نیاز دارد، کاربردی است.


A professional and extendable Laravel package for accessing **all Iranian provinces and their cities**.
This package provides a clean and fluent API to retrieve **provinces and their related cities**, making it ideal for any project that needs structured Iranian location data — from address forms to geographical APIs.

✨ ویژگی‌ها
🗺 لیست کامل استان‌ها و شهرهای ایران
این پکیج شامل دیتابیس به‌روز شده‌ی تمام استان‌ها و شهرهای ایران است، بدون نیاز به API خارجی یا فایل اضافه.

🔗 رابطه‌ی یک‌به‌چند بین استان‌ها و شهرها
هر استان دارای چندین شهر است و شما می‌توانید به‌راحتی با استفاده از Eloquent به شهرهای وابسته به هر استان دسترسی داشته باشید.

⚡ فراخوانی ساده و سریع از طریق Facade و توابع Helper
نیازی به نوشتن Queryهای پیچیده نیست! با استفاده از IranLocation::getProvinces() یا تابع iran_provinces() می‌توانید اطلاعات مورد نظر را سریع دریافت کنید.

🔎 امکان دریافت لیست شهرها با شناسه یا مدل استان
فقط با ارسال ID یا شیء استان، می‌توانید لیست شهرهای مربوط به آن را دریافت کنید:

getCitiesByProvinceId($id)

getCitiesByProvince(Province $province)

🌐 پشتیبانی از نام فارسی (و در آینده: انگلیسی)
اطلاعات استان‌ها و شهرها به‌صورت فارسی ذخیره شده‌اند و به‌زودی نسخه‌ی انگلیسی نیز در دسترس قرار خواهد گرفت.

🧩 مناسب برای پروژه‌های فرم‌محور و کاربرمحور
این پکیج یک انتخاب عالی برای پروژه‌هایی است که نیاز به فرم ثبت‌نام، فرم ارسال آدرس، پنل مدیریت کاربران، فیلتر محصولات بر اساس موقعیت و... دارند.
