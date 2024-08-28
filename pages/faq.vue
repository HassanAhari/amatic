<script setup>

</script>

<template>
    <div>
        <h3 class="serif my-6">جستجوی پیشرفته سوالات متداول</h3>
        <div class="flex flex-col gap-2 relative w-full">
            <div class="w-full flex items-center justify-between px-3 rounded bg-basic-1">
                <img class="right-label w-5 h-5" alt=""
                    src="data:image/svg+xml;base64,PHN2ZyBpZD0idnVlc2F4X2xpbmVhcl9zZWFyY2gtbm9ybWFsIiBkYXRhLW5hbWU9InZ1ZXNheC9saW5lYXIvc2VhcmNoLW5vcm1hbCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMTguMjM1IiBoZWlnaHQ9IjE4LjIzNSIgdmlld0JveD0iMCAwIDE4LjIzNSAxOC4yMzUiPgogICAgPGcgaWQ9InNlYXJjaC1ub3JtYWwiPgogICAgICAgIDxwYXRoIGlkPSJWZWN0b3IiIGQ9Ik0xNC40MzYsNy4yMThBNy4yMTgsNy4yMTgsMCwxLDEsNy4yMTgsMCw3LjIxOCw3LjIxOCwwLDAsMSwxNC40MzYsNy4yMThaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxLjUyIDEuNTIpIiBmaWxsPSJub25lIiBzdHJva2U9IiNhYWEiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIxIi8+CiAgICAgICAgPHBhdGggaWQ9IlZlY3Rvci0yIiBkYXRhLW5hbWU9IlZlY3RvciIgZD0iTTEuNTIsMS41MiwwLDAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE1LjE5NiAxNS4xOTYpIiBmaWxsPSJub25lIiBzdHJva2U9IiNhYWEiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIxIi8+CiAgICAgICAgPHBhdGggaWQ9IlZlY3Rvci0zIiBkYXRhLW5hbWU9IlZlY3RvciIgZD0iTTAsMEgxOC4yMzVWMTguMjM1SDBaIiBmaWxsPSJub25lIiBvcGFjaXR5PSIwIi8+CiAgICA8L2c+Cjwvc3ZnPgoK">
                <div class="w-full py-3">
                    <input placeholder="" id="search" oninput="searchQ()" type="text"
                        class="w-full outline-none focus:outline-none flex-grow bg-transparent px-2 appearance-none text-right"
                        style="direction: rtl; padding-right: 20px;">
                </div>
            </div>
            <div class="w-full border-b h-8 border-gray-200"></div>
        </div>
        <div class="flex flex-col" id="dataContainer">
            <div class="flex flex-col">
                <div class="flex gap-4 pt-8 pb-2 items-center">
                    <img src="https://cdn.ok-ex.io/asset/svg/okex.svg" class="w-8 h-8" alt="">
                    <h2 class="font-semibold ">حساب کاربری</h2>
                </div>

                <div class="flex flex-col">
                    <h3 class="font-semibold py-6">احراز هویت</h3>

                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623065c882b01a14d04eacda')">
                            <h4 class="header-color leading-12 text-primary">چرا احراز هویت نیاز است؟</h4>
                            <img id="toggle623065c882b01a14d04eacda" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623065c882b01a14d04eacda"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به دلیل ارائه خدمات ارزهای دیجیتال در اوکی اکسچنج و ماهیت خاص این بازار که می تواند برای
                            جرایم زیادی مورد استفاده قرار گیرد و همچنین عدم سواستفاده کلاهبرداران اینترنتی که اقدام به
                            دزدیدن اطلاعات کارت ها می کنند، نیاز است که هر فرد تنها با هویت و کارت بانکی خود اقدام به
                            معامله، واریز و برداشت نماید تا از این گونه مشکلات جلوگیری شود.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('65912762d407f91a10060cdf')">
                            <h4 class="header-color leading-12 text-primary">پروسه احراز هویت چقدر زمان میرد؟</h4>
                            <img id="toggle65912762d407f91a10060cdf" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="65912762d407f91a10060cdf"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            تائید هویت در ساعات کاری سایت انجام می شود و معمولا کمتر از ۱ ساعت احراز هویت خواهید شد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f1f8582b01a14d04ea52b')">
                            <h4 class="header-color leading-12 text-primary">به چه علت احراز هویت شما رد شده است؟</h4>
                            <img id="toggle622f1f8582b01a14d04ea52b" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f1f8582b01a14d04ea52b"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            1) عدم همخوانی اطلاعات هویتی واردشده در وب سایت با استعلام از ثبت احوال
                            2) عدم ارسال عکس مطابق با الگو پیش فرض، عکس باید از چهره خودتان به همراه کارت ملی یا
                            شناسنامه جدید یا کارت پایان خدمت جدید و یا گواهینامه رانندگی، در دست شما به صورتی که اطلاعات
                            هویتی روی کارت و چهره شما کاملا واضح و شفاف باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f1f9082b01a14d04ea531')">
                            <h4 class="header-color leading-12 text-primary">محدودیت سنی برای احراز هویت چگونه است؟</h4>
                            <img id="toggle622f1f9082b01a14d04ea531" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f1f9082b01a14d04ea531"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            متولدین کمتر از 18 سال و بالاتر از 60 سال با توجه به قوانین و مقررات پلتفرم اوکی اکسچنج،
                            مجاز به ثبت نام نیستند.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('65a516f66df1c3788267eaef')">
                            <h4 class="header-color leading-12 text-primary">چگونه ثبت نام من کامل می شود؟</h4>
                            <img id="toggle65a516f66df1c3788267eaef" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="65a516f66df1c3788267eaef"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            ابتدا با انتخاب گزینه ثبت نام با جیمیل یا شماره همراه، حساب کاربری را ایجاد کنید .
                            پس از تایید جیمیل یا شماره همراه، می توانید اطلاعات کاربری خود را ( اطلاعات کارت ملی ) تکمیل
                            کنید.
                            تمامی اطلاعات هویتی خود را دقیقا مطابق با شناسنامه و کارت ملی وارد کنید. زمانی که مدارک
                            هویتی (اطلاعات اولیه) از طرف کارشناسان ما تایید شود شما به سطح 2 رسیده و می توانید واریز،
                            خرید و فروش داشته باشید.
                            اخرین سطح کاربری ارسال عکس می باشد. برای ارسال تصویر مطمئن شوید که تمام استانداردهای‌ لازم
                            مطابق الگو رعایت شده باشد.(لطفا عکس از چهره خودتان به همراه یکی از مدارک: کارت ملی،شناسنامه
                            جدید،کارت پایان خدمت و یا گواهینامه در دست شما به صورتی که کاملا واضح و شفاف باشد آپلود کنید
                            و منتظر تایید کارشناسان بمانید.)

                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('667184b6068b37c8ef1cba2a')">
                            <h4 class="header-color leading-12 text-primary">چگونه وارد حساب کاربری خود شوم؟</h4>
                            <img id="toggle667184b6068b37c8ef1cba2a" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="667184b6068b37c8ef1cba2a"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            می توانید از بخش ورود از طریق شماره همراه یا ایمیل وارد حساب کاربری خود شوید. درصورتی که
                            اطلاعات را درست وارد کنید، وارد حساب کاربری خود خواهید شد. در صورت درخواست کد دومرحله ای ،
                            باید کد را از اپلیکیشن Authenticator گرفته و در قسمت اعلام شده وارد نمایید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('6671855c068b37735a1cba35')">
                            <h4 class="header-color leading-12 text-primary">در صورتی که رمز خود را فراموش کرده باشیم چه
                                کنیم؟</h4>
                            <img id="toggle6671855c068b37735a1cba35" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="6671855c068b37735a1cba35"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به صفحه ورود به حساب خود در اوکی اکسچنج بروید و روی گزینه "فراموشی رمز عبور" کلیک کنید سپس
                            آدرس ایمیل یا شماره تلفن خود را وارد کنید، کد شش رقمی دریافت شده از ایمیل یا شماره همراه را
                            داخل فیلد مربوطه وارد کنید. صفحه ای بعد از وارد کردن کد برای شما باز می شود که رمز عبور جدید
                            و تکرار آن را باید ثبت کنید. توجه داشته باشید هیچگونه برداشتی تا 24 ساعت پس از تغییر رمز
                            عبور امکان پذیر نمی باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623067a282b01a14d04eaceb')">
                            <h4 class="header-color leading-12 text-primary">چرا در زمان وارد کردن ایمیل در قسمت ثبت نام
                                خطای عدم پشتیبانی از سرویس دهنده ایمیل نمایش داده می شود؟</h4>
                            <img id="toggle623067a282b01a14d04eaceb" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623067a282b01a14d04eaceb"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به این دلیل که ایمیل به درستی وارد نشده است یا از سرویس دهنده ایمیل پشتیبانی نمی شود ، لطفا
                            از سرویس ایمیل های ذکر شده استفاده کنید: yahoo.com , gmail.com
                        </div>
                    </div>
                </div>

                <div class="flex flex-col">
                    <h3 class="font-semibold py-6">کد دومرحله ای</h3>

                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62306aae82b01a14d04eacfd')">
                            <h4 class="header-color leading-12 text-primary">ورود دو مرحله برای چه استفاده می شود؟</h4>
                            <img id="toggle62306aae82b01a14d04eacfd" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62306aae82b01a14d04eacfd"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            تایید دو مرحله ای گوگل یکی از لایه های امنیتی است که باعث می شود ورود به حساب کاربری برای
                            افراد غیرمجاز دشوار گردد.اگر کد دومرحله ای فعال گردد، فردی که به ایمیل و گذرواژه ی حساب
                            کاربری دسترسی داشته باشد برای ورود به حساب کاربری همواره کد دیگری (کد احراز کننده گوگل) را
                            نیاز خواهد داشت.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('667185c1068b376af81cba39')">
                            <h4 class="header-color leading-12 text-primary">کد تایید گوگل در کدام قسمت ها استفاده می
                                شود؟</h4>
                            <img id="toggle667185c1068b376af81cba39" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="667185c1068b376af81cba39"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            شما پس از فعال سازی آن در هر بار ورود به حساب کاربری نیاز به استفاده از آن را خواهید داشت؛
                            همچنین به جهت امنیت برداشت، حتما باید آن را فعال نمایید و در هر بار درخواست برداشت، از آن
                            استفاده نمایید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('6591298cd407f95910060d0d')">
                            <h4 class="header-color leading-12 text-primary">چگونه میتوان آن را غیر فعال کرد؟</h4>
                            <img id="toggle6591298cd407f95910060d0d" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="6591298cd407f95910060d0d"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            شما می‌توانید از بخش حساب کاربری/تنظیمات نسبت به غیر فعال سازی کددومرحله ای خود اقدام نمایید
                            (داشتن کد دومرحله ای گوگل برای غیرفعال سازی الزامی است).
                            توجه داشته باشید در صورت غیرفعال سازی به مدت ۲۴ ساعت، نمی توانید برداشت ارزی و ریالی داشته
                            باشید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f203782b01a14d04ea560')">
                            <h4 class="header-color leading-12 text-primary">گوشی خود را گم کردید یا دسترسی ندارید؟</h4>
                            <img id="toggle622f203782b01a14d04ea560" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f203782b01a14d04ea560"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            شما در زمان فعال سازی، یک کد بکاپ دریافت می کنید که باید حتما آن را جایی غیر از گوشی خود
                            یادداشت و نگهداری کنید تا در صورت بروز چنین مشکلاتی بتوانید به راحتی اقدام به بازیابی کد
                            دومرحله ای نمایید و مجدد به حساب کاربری خود دسترسی داشته باشید. جهت این کار تنها کافی است با
                            نصب مجدد نرم افزار و ورود به آن، از بخش add نسبت به اضافه کردن کد بکاپ اقدام کنید که در بخش
                            اول از شما درخواست یک نام می شود که می توانید نام وب سایت را وارد کنید و سپس کد بکاپ خود را
                            وارد کنید و مجددا آن را فعال نمایید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66718707068b37bbe01cba46')">
                            <h4 class="header-color leading-12 text-primary">کد پشتیبان یا بکاپ ورود دو مرحله ای گوگل را
                                گم کرده اید و به آن دسترسی ندارید؟</h4>
                            <img id="toggle66718707068b37bbe01cba46" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66718707068b37bbe01cba46"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            در صورت گم شدن کد بکاپ و پاک شدن اپلیکیشن authenticator، برای بازیابی و ورود به حساب خود،
                            باید با شماره همراه تایید شده در حساب کاربریتان با پشتیبانی اوکی اکسچنج تماس بگیرید.پس از
                            مراحل مجدد احراز هویت, پروسه غیرفعالسازی کد دومرحله ای که ممکن است تا ۷ روز زمان بر باشد
                            آغاز می شود.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f204f82b01a14d04ea56c')">
                            <h4 class="header-color leading-12 text-primary"> اطمینان دارید که کد وارد شده صحیح است اما
                                سیستم به شما پیغام خطا نمایش می دهد؟</h4>
                            <img id="toggle622f204f82b01a14d04ea56c" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f204f82b01a14d04ea56c"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            برای رفع این مشکل ساعت گوشی خود را در حالت اتوماتیک قرار دهید و مجدد یک بار دیگر وارد نرم
                            افزار شوید. از بخش تنظیمات اقدام به بروز رسانی مجدد یا Sync نمایید.
                            در صورت لزوم، یک بار گوشی خود را خاموش روشن نمایید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('659129e5d407f95873060d1f')">
                            <h4 class="header-color leading-12 text-primary">به غیر از فعالسازی کد دومرحله ای روش دیگری
                                برای تایید برداشت وجود دارد؟</h4>
                            <img id="toggle659129e5d407f95873060d1f" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="659129e5d407f95873060d1f"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            در صورتی که کد دومرحله ای گوگل شما فعال باشد ابتدا باید از بخش تنظیمات حساب کاربری نسبت به
                            غیرفعالسازی کد گوگل خود اقدام کنید تا هنگام برداشت به شماره همراه شما پیامک تایید برداشت
                            ارسال شود.
                            در صورتی هم که کد دومرحله ای گوگل شما فعال نباشد هنگام برداشت کد 6 رقمی به شماره موبایل ثبت
                            شده شما در وبسایت، ارسال می شود.

                        </div>
                    </div>
                </div>

            </div>

            <div class="flex flex-col">
                <div class="flex gap-4 pt-8 pb-2 items-center">
                    <img src="https://cdn.ok-ex.io/asset/svg/okex.svg" class="w-8 h-8" alt="">
                    <h2 class="font-semibold ">اوکی اکسچنج</h2>
                </div>

                <div class="flex flex-col">
                    <h3 class="font-semibold py-6">تبادل سریع</h3>

                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f511e82b01a14d04ea900')">
                            <h4 class="header-color leading-12 text-primary">اوکی اکسچنج چیست ؟</h4>
                            <img id="toggle622f511e82b01a14d04ea900" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f511e82b01a14d04ea900"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            اوکی اکسچنج پلتفرم خرید و فروش کوین با قیمت لحظه ای و به صورت آنی با وب سایت است که تمامی
                            قیمت ها در آن مشخص می باشد. در این قسمت نیازی به انتظار برای قبول سفارش توسط یک مشتری دیگر
                            نمی باشد و شما مستقیما با خود سایت معامله می کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f43d482b01a14d04ea877')">
                            <h4 class="header-color leading-12 text-primary">چگونه در اوکی اکسچنج، از سایت خرید کنم؟
                            </h4>
                            <img id="toggle622f43d482b01a14d04ea877" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f43d482b01a14d04ea877"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            جهت خرید از وب سایت، اطلاعات هویتی شما باید تایید شده باشد. سپس کیف پول ریالی خود را شارژ
                            کنید و از منو تبادل ارز با تعیین کوین خود، مراحل خرید را به آسانی پیش بروید و پس از آن مقدار
                            خریداری شده را در کیف پول داخلی دریافت کنید. مدت زمان ارسال کوین ها به کیف پول داخلی شما ،
                            به صورت آنی و پس از خرید می باشد.توجه داشته باشید اگر قصد برداشت کوین دارید باید حتما احراز
                            هویت خود را تکمیل کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66718789cf7461f53de9d7d8')">
                            <h4 class="header-color leading-12 text-primary">حداقل مبلغ خرید و فروش از سایت چقدر است؟
                            </h4>
                            <img id="toggle66718789cf7461f53de9d7d8" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66718789cf7461f53de9d7d8"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            حداقل مبلغ خرید و فروش از بخش تبادل سریع معادل 10 هزار تومان می باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('65912a5ad407f9a30c060d26')">
                            <h4 class="header-color leading-12 text-primary">روش پرداخت جهت خرید چگونه است؟</h4>
                            <img id="toggle65912a5ad407f9a30c060d26" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="65912a5ad407f9a30c060d26"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            شما می توانید از طریق درگاه بانکی یا واریز با شناسه، کیف پول ریالی خود را شارژ کنید تا
                            بتوانید از قسمت تبادل ارز یا بازار اقدام به خرید کنید. همچنین از فروش ارزی می توانید موجودی
                            ریالی کیف پول خود را افزایش دهید و از این طریق نسبت به خرید اقدام کنید.

                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623ea98282b01a14d04ebea8')">
                            <h4 class="header-color leading-12 text-primary">چگونه میتوانم در مورد کوین ها اطلاعات کسب
                                کنم؟</h4>
                            <img id="toggle623ea98282b01a14d04ebea8" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623ea98282b01a14d04ebea8"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            بهترین راه های کسب اطلاعات جدید درباره به روز ترین اخبار، آموزش ها و تحلیل ها، بخش بلاگ سایت
                            اوکی اکسچنج است.
                            همچنین شما میتوانید شبکه های اجتماعی ما (تلگرام-اینستاگرام) را نیز دنبال کنید و از اخبار
                            لحظه ای مطلع شوید.


                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66718b24068b3798ef1cba64')">
                            <h4 class="header-color leading-12 text-primary">نحوه فروش از بخش تبادل سریع چگونه است؟</h4>
                            <img id="toggle66718b24068b3798ef1cba64" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66718b24068b3798ef1cba64"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            جهت فروش ابتدا باید اطلاعات هویتی شما تایید شده باشد. سپس وارد بخش تبادل سریع شوید و گزینه
                            فروش را انتخاب کنید. در بخش جستجو کوین، رمزارزی که می خواهید معامله کنید را انتخاب کنید .در
                            قسمت مقدار، می توانید مقداری رمزارزی که تمایل به معامله آن را دارید وارد نمایید ، در صورتیکه
                            می خواهید کل موجودی تومانی یا ارزی کیف پولتان را معامله کنید گزینه max را انتخاب کرده و
                            تراکنش خود را تکمیل کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('622f243782b01a14d04ea60d')">
                            <h4 class="header-color leading-12 text-primary">آیا امکان لغو فروش پس از ارسال کوین به کیف
                                پول شما برای فروش میسراست؟</h4>
                            <img id="toggle622f243782b01a14d04ea60d" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="622f243782b01a14d04ea60d"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به دلیل اینکه تمامی کوین ها در قسمت فروش بلافاصله به دلار تبدیل می شوند امکان لغو تراکنش
                            میسر نیست.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66718e50cf7461d584e9d816')">
                            <h4 class="header-color leading-12 text-primary"> کارمزد خرید در بخش تبادل سریع چه مقدار
                                است؟</h4>
                            <img id="toggle66718e50cf7461d584e9d816" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66718e50cf7461d584e9d816"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            کارمزد خرید در اوکی اکسچنج با توجه به خدمات و امنیتی که ارائه می‌دهیم و ریسک معاملاتی محاسبه
                            می شود. همچنین با توجه به نوع ارز، حجم معامله و نوسانات بازار کارمزد متغیر است.توجه داشته
                            باشید مقدار دقیق کارمزد پس از انجام معامله در فاکتور شما نمایش داده می شود.همچنین بخشی از
                            کارمزد معاملاتی که توسط کاربران پرداخت می شود به صندوق بیمه اوکی اکسچنج منتقل شده که با وجود
                            این صندوق بیمه، پشتیبانی امن برای سرمایه کاربران در شرایط غیر قابل پیش بینی ایجاد می شود و
                            دارایی کاربران کاملا امن و محفوظ می ماند.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66718cc1068b37fee81cba70')">
                            <h4 class="header-color leading-12 text-primary">کارمزد فروش در بخش تبادل است چقدر است؟</h4>
                            <img id="toggle66718cc1068b37fee81cba70" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66718cc1068b37fee81cba70"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            کارمزد فروش در بخش تبادل سریع صفر است.
                        </div>
                    </div>
                </div>

            </div>

            <div class="flex flex-col">
                <div class="flex gap-4 pt-8 pb-2 items-center">
                    <img src="https://cdn.ok-ex.io/asset/svg/okex.svg" class="w-8 h-8" alt="">
                    <h2 class="font-semibold ">اوکی اکسچنج تریدر</h2>
                </div>

                <div class="flex flex-col">
                    <h3 class="font-semibold py-6">بازار و معاملات </h3>

                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('65913aedd407f976f8060f0a')">
                            <h4 class="header-color leading-12 text-primary">بازار حرفه ای (تریدر ) چیست و چگونه کار می
                                کند؟</h4>
                            <img id="toggle65913aedd407f976f8060f0a" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="65913aedd407f976f8060f0a"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            اوکی اکسچنج تریدر یک پلتفرم معاملاتی شخص به شخص است که به شما این امکان را می دهد، با دیگر
                            خریداران و فروشندگان ارزهای دیجیتال به معامله بپردازید؛ به نوعی این پلتفرم به عنوان واسطه
                            میان خریدار و فروشنده است و نقش مستقل و مجزایی در خرید و فروش ها ندارد. توجه داشته باشید در
                            این بخش با 3 روش (قیمت ثابت - فوری - مدیریت ضرر) می توانید معامله خود را ثبت کنید. معامله در
                            بخش بازار فقط با تتر انجام می شود همچنین با در نظر گرفتن کارمزد بسیار پائین این بخش ،معامله
                            در این بخش بسیار بصرفه و مناسب می باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e12b1758a134a144eb43bd')">
                            <h4 class="header-color leading-12 text-primary">چگونه یک معامله باز کنم؟</h4>
                            <img id="toggle62e12b1758a134a144eb43bd" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e12b1758a134a144eb43bd"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            معامله در تریدر به صورت معامله با قیمت ثابت بر مبنا تتر است و می توانید از قسمت قیمت ثابت
                            نسبت به سفارش گزاری از نوع لیمیت اقدام کنید. توجه داشته باشید در سفارش لیمیت (حد) شما یک
                            محدوده قیمتی برای سفارش خرید و یا فروش خود ثبت می کنید و برای شروع یک معامله نیاز به یک
                            دارایی اولیه دارید، یعنی باید از کیف پول اصلی نسبت به واریز کوین یا ریال اقدام کنید و موجودی
                            خود را به بخش تریدر منتقل کنید ، سپس از مشتریانی که فروشنده و خریدار ارز دیجیتال هستند نسبت
                            به خرید و فروش ارز اقدام نمایید . همچنین شما می توانید برای خرید یا فروش، معامله ای را با
                            قیمت پیشنهادی خود ثبت کنید تا در زمان رسیدن به قیمت پیشنهادی، فروشنده یا خریدار آن را قبول
                            کرده و معامله شما انجام شود. سفارش شما پس از تکمیل مقادیر اولیه(قیمت،مقدار و مجموع سفارش)
                            وارد قسمت لیست سفارشات موجود برای خریداران و یا فروشندگان می شود و زمانی که سفارش مقابل و
                            مشابه مقادیر سفارش شما وجود داشته باشد ،سفارش شما در جهت تکمیل پیشروی خواهد کرد .
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e1166c58a134a144eb4350')">
                            <h4 class="header-color leading-12 text-primary">آیا در این بخش می توانیم با ریال معاملات
                                خود را ثبت کنیم؟</h4>
                            <img id="toggle62e1166c58a134a144eb4350" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e1166c58a134a144eb4350"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            امکان معامله با ریال فقط برای رمز ارز تتر فعال می باشد و برای سایر رمز ارزها باید معاملات
                            خود را براساس تتر انجام دهید.به این معنی که برای خرید هر رمز ارز باید تتر داشته باشید تا
                            بتوانید معامله کنید همچنین در ازای فروش رمزارز خود، تتر دریافت می کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e1168558a134a144eb4353')">
                            <h4 class="header-color leading-12 text-primary">چطور از بخش بازار (تریدر) موجودی خود را
                                برداشت بزنیم؟</h4>
                            <img id="toggle62e1168558a134a144eb4353" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e1168558a134a144eb4353"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            برای برداشت در این بخش باید به کیف پول تریدر مراجعه کرده و از بخش انتقال، موجودی خود را به
                            کیف پول اصلی انتقال دهید سپس از کیف پول اصلی نسبت به برداشت ریالی یا ارزی اقدام کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e116a058a134a144eb4357')">
                            <h4 class="header-color leading-12 text-primary">کارمزد بخش تریدر چگونه محاسبه می شود؟</h4>
                            <img id="toggle62e116a058a134a144eb4357" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e116a058a134a144eb4357"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            0.3 % کارمزد برای سفارش گذار (کاربری که تراکنش جدیدی ثبت می کند)
                            0.36 % کارمزد برای جمع کننده سفارش ( کاربری که از لیست معاملات کاربران دیگر تراکنشی را قبول
                            می کند)


                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e116b258a134a144eb435a')">
                            <h4 class="header-color leading-12 text-primary">سود صرافی از کجاست؟</h4>
                            <img id="toggle62e116b258a134a144eb435a" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e116b258a134a144eb435a"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            سود صرافی از انجام یک معامله دریافت می شود، ثبت و حذف سفارش شامل دریافت کارمزد نمی شود.
                        </div>
                    </div>
                </div>

            </div>

            <div class="flex flex-col">
                <div class="flex gap-4 pt-8 pb-2 items-center">
                    <img src="https://cdn.ok-ex.io/asset/svg/okex.svg" class="w-8 h-8" alt="">
                    <h2 class="font-semibold ">کیف پول </h2>
                </div>

                <div class="flex flex-col">
                    <h3 class="font-semibold py-6">کیف پول </h3>

                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('667193b7068b37a0091cba91')">
                            <h4 class="header-color leading-12 text-primary">کیف پول چیست؟</h4>
                            <img id="toggle667193b7068b37a0091cba91" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="667193b7068b37a0091cba91"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به صورت کلی شما در اوکی اکسچنج دارای دو نوع کیف پول مجزا (کیف پول اصلی - کیف پول بازار)
                            هستید که به محض تایید حسابتان برای شما فعال می شود و هر معامله ای در صرافی انجام شود، موجودی
                            شما به کیف پول همان بخشی که خرید یا فروش ثبت کرده باشید (کیف پول بازار- کیف پول اصلی) واریز
                            می شود.
                            توجه داشته باشید امکان واریز و برداشت مستقیم، فقط از کیف پول اصلی انجام می شود.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('6230577382b01a14d04eac94')">
                            <h4 class="header-color leading-12 text-primary">چه کوین هایی را میتوان در کیف پول داخلی
                                نگهداری کرد؟</h4>
                            <img id="toggle6230577382b01a14d04eac94" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="6230577382b01a14d04eac94"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            تمامی کوین هایی که در لیست خرید و فروش و کیف پول وجود دارد نظیر بیت کوین، اتریوم، ریپل و ...
                            را میتوان در کیف پول داخلی اوکی اکسچنج نگهداری کرد. همچنین می توانید از کیف پول خارجی واریز
                            کوین داشته باشید و کوین هایی که در لیست کیف پول اوکی اکسچنج موجود است را به کیف پول داخلی
                            خود منتقل و تا هر زمانی که خواستید نگهداری کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('6230577b82b01a14d04eac97')">
                            <h4 class="header-color leading-12 text-primary"> آیا نگهداری کوین در کیف پول اوکی اکسچنج
                                شامل هزینه است؟</h4>
                            <img id="toggle6230577b82b01a14d04eac97" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="6230577b82b01a14d04eac97"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            خیر نگهداری کوین خود در اوکی اکسچنج شامل هیچ هزینه ای نمی باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('66719642cf7461193de9d837')">
                            <h4 class="header-color leading-12 text-primary">چگونه میتوان به کیف پول داخلی کوین اضافه
                                کرد؟</h4>
                            <img id="toggle66719642cf7461193de9d837" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="66719642cf7461193de9d837"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            به کیف پول اصلی اوکی اکسچنچ مراجعه کنید و پس از جستجو کوین و انتخاب شبکه مورد نظر، گزینه
                            دریافت آدرس را کلیک کنید و وارد کیف پول خارجی خود شده و گزینه send و یا withdraw را انتخاب
                            کنید و آدرس اوکی اکسچنج را در کادر مربوطه وارد و مراحل برداشت خود را تکمیل کنید .لطفا در
                            انتخاب شبکه انتقال ارز یکسان بین کیف پول مبدا و مقصد و همچنین وارد کردن صحیح آدرس دقت نمائید
                            و توجه داشته باشید آدرس‌های واریز ارزی همه زمان دار هستند (از لحظه‌ای که آدرس به شما تعلق
                            می‌گیرد، بین 2 تا 8 ساعت زمان دارید تا واریز ارز خود را انجام دهید)؛ اگر به زمان بیشتری نیاز
                            دارید، می‌توانید با انجام مجدد مراحل واریز ارز قبل از پایان اعتبار آدرس، آن را تمدید کنیددر
                            غیر این صورت آدرس از شما گرفته می شود.

                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('6230579f82b01a14d04eac9d')">
                            <h4 class="header-color leading-12 text-primary">مدت زمان دریافت کوین پس از ثبت درخواست
                                برداشت از کیف پول داخلی چقدر است؟</h4>
                            <img id="toggle6230579f82b01a14d04eac9d" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="6230579f82b01a14d04eac9d"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            با توجه به این که ما جهت امنیت کاربران از کیف پول سرد استفاده می کنیم برداشت از کیف پول
                            داخلی به کیف پول خارجی از پلتفرم اوکی اکسچنج به صورت اتومات می باشد.در بعضی مواقع ممکن است
                            با توجه به عواملی همچون شلوغی شبکه ارزهای دیجیتال، کارمزد تراکنش و یا اختلال در شبکه مورد
                            نظر مدت زمان انتقال ارز ها به کیف پول خارجی طولانی شود.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623057ae82b01a14d04eaca0')">
                            <h4 class="header-color leading-12 text-primary">مدت زمان برداشت ریال به حساب ما چقدر است؟
                            </h4>
                            <img id="toggle623057ae82b01a14d04eaca0" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623057ae82b01a14d04eaca0"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            مدت زمان واریز ریال به حساب شما بین ۲۴ الی ۴۸ ساعت در روزهای کاری بانک خواهدبود. همچنین
                            تاریخ و ساعت واریز به حساب شما از بخش تاریخچه برداشت قابل پیگیری و مشاهده می باشد.
                            توجه داشته باشید تسویه ریالی در روزهای تعطیل به دلیل تعطیلی بانک ها و عدم فعالیت سیستم پایا
                            انجام نمی شود.

                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623057b982b01a14d04eaca3')">
                            <h4 class="header-color leading-12 text-primary">درخواست برداشت ریالی به چه حساب هایی میسر
                                می باشد؟</h4>
                            <img id="toggle623057b982b01a14d04eaca3" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623057b982b01a14d04eaca3"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            امکان ارسال حواله به همه بانک های کشور و حساب های شخص تایید شده در سایت امکان پذیر می باشد ،
                            جهت تسویه حساب ریالی باید نام صاحب حساب کاربری با صاحب شماره شبا یکی باشد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623057c082b01a14d04eaca6')">
                            <h4 class="header-color leading-12 text-primary">شماره شبا چیست و چگونه آن را بدست آوریم؟
                            </h4>
                            <img id="toggle623057c082b01a14d04eaca6" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623057c082b01a14d04eaca6"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            شماره شبا کد ۲۴ رقمی از اعداد است که تمامی حساب های بانکی کشور آن را دارا می باشند و جهت
                            تراکنش های بین بانکی استفاده می گردد. شما با جستجو در گوگل می توانید شماره شبا کارت خود را
                            بدست آورید. برای مثال، حساب شما برای بانک ملت است میتوانید با جستجو کلمه 'تولید شبای بانک
                            ملت' و پس از ورود به سایت، با وارد کردن شماره حساب، شماره شبا کارت خود را دریافت کنید.
                            همچنین می توانید با مراجعه به شعب بانکی خود، شبا کارت خود را دریافت کنید.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('62e0fa7658a134a144eb4288')">
                            <h4 class="header-color leading-12 text-primary">چگونه می توانید مقادیر کیف پول داخلی خود را
                                بین دو پلتفرم اوکی اکسچنج و اوکی اکسچنج تریدر انتقال دهید؟</h4>
                            <img id="toggle62e0fa7658a134a144eb4288" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="62e0fa7658a134a144eb4288"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            برای رمز ارزهای مشترک بین دو پلتفرم می توانید از بخش کیف پول قسمت انتقال اقدام کنید و به
                            صورت آنی مقادیر را جابه جا کنید.
                            گفتنی است که انتقال کوین و ریال بین پلتفرم ها به صورت رایگان است و شامل هیچگونه هزینه ای
                            نخواهد شد.
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center justify-between bg-new_basic-3 py-2 px-5 border-b border-gray-100 cursor-pointer"
                            onclick="toggleAnswerFunc('623080ba82b01a14d04ead45')">
                            <h4 class="header-color leading-12 text-primary">هزینه شبکه چیست؟</h4>
                            <img id="toggle623080ba82b01a14d04ead45" alt=""
                                src="https://cdn.ok-ex.io/asset/svg/arrowPrimary.svg" class="transition-all">
                        </div>
                        <div id="623080ba82b01a14d04ead45"
                            class="slide-y-fade-hidden leading-loose sm: sm:leading-loose px-4 accordion-content text-justify">
                            کارمزد انتقالات ارز دیجیتال زمانی کسر می گردد که کوین از یک کیف پول به کیف پول دیگر انتقال
                            یابد.
                            پردازش و تایید تراکنش ها ارز دیجیتال در بلاک‌چین هزینه‌ بر است و این هزینه‌ها برای پاداش به
                            ماینرها و اعتبارسنجی‌هایی که به روند تایید تراکنش‌ها و تامین امنیت شبکه کمک می‌کنند، استفاده
                            می‌شود کارمزد انتقالات ارز دیجیتال، می‌تواند بر اساس میزان شلوغی شبکه بلاک‌چین تغییر
                            کند.توجه داشته باشید کارمزد تراکنش در هر شبکه متفاوت است، که بر این اساس مدت زمان انجام
                            تراکنش نیز متغیر می شود.

                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>