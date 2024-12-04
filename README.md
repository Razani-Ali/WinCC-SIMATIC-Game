# WinCC & SIMATIC Industrial Automation Game

## English

### Overview

This is a simple yet engaging game developed using **WinCC** and **SIMATIC** industrial automation software. The game involves players firing flames to destroy ducks and droplets while avoiding collisions to protect their hearts. The game has three levels, each with increasing difficulty. Players can earn points by eliminating ducks or droplets. It’s implemented using **Ladder Logic**, and object movements and collision detection are controlled with timers.

### Features

- **3 Levels**: Increasing difficulty with higher droplet rates and faster duck movement.
- **Timer-based Object Movement**: Timers are used for controlling the movement of flames and droplets.
- **Collision Detection**: Function blocks compare positions to detect collisions between objects.
- **Hearts and Scoring**: Players start with 3 hearts and lose one upon a collision. Scoring increases by killing ducks or destroying droplets.
- **Pause, Continue, Restart**: Players can pause, continue, or restart the mission during gameplay.
- **Red Line Boundary**: Ducks cannot cross the red line on the screen.

### Installation and Setup

1. **WinCC and SIMATIC Setup**: Make sure you have **WinCC** and **SIMATIC** installed and configured for industrial automation.
2. **Import the Project**: Clone or download this repository and import the project files into your **WinCC** project.
3. **Simulate with PLCsim**: Use **PLCsim** to simulate the game environment. This allows you to test the project without needing the physical PLC hardware.
4. **Test the Game**: After uploading to **PLCsim**, run the game and interact with the system via the control panel.

### Usage

- **Start the Game**: Run the project and interact with the system using the control panel.
- **Game Controls**: The game controls are simple—fire flames, avoid collisions, and try to score as much as possible.
- **Levels**: As you progress, the difficulty increases with more aggressive ducks and faster-moving droplets.

---

## فارسی

### معرفی

این یک بازی ساده و جذاب است که با استفاده از نرم‌افزارهای **WinCC** و **SIMATIC** برای اتوماسیون صنعتی توسعه یافته است. در این بازی، بازیکنان باید شعله‌ها را برای از بین بردن اردک‌ها و قطرات شلیک کنند، در حالی که باید از برخوردها جلوگیری کرده و جان‌های خود را حفظ کنند. بازی شامل سه سطح است که هرکدام با افزایش سختی همراه است. بازیکنان می‌توانند با از بین بردن اردک‌ها یا قطرات امتیاز کسب کنند. این بازی با استفاده از **Ladder Logic** پیاده‌سازی شده است و حرکت اشیاء و شناسایی برخوردها با تایمرها کنترل می‌شود.

### ویژگی‌ها

- **3 سطح**: سختی بازی در هر سطح افزایش می‌یابد، نرخ قطرات بیشتر و حرکت اردک‌ها سریع‌تر می‌شود.
- **حرکت اشیاء با تایمر**: تایمرها برای کنترل حرکت شعله‌ها و قطرات استفاده می‌شوند.
- **شناسایی برخورد**: بلوک‌های توابع موقعیت‌ها را مقایسه کرده و برخوردهای بین اشیاء را شناسایی می‌کنند.
- **قلب‌ها و امتیازدهی**: بازیکنان با 3 قلب شروع می‌کنند و با برخورد به اشیاء یکی از قلب‌ها را از دست می‌دهند. امتیاز با از بین بردن اردک‌ها یا قطرات افزایش می‌یابد.
- **مینی‌مست، ادامه، یا شروع مجدد**: بازیکنان می‌توانند در حین بازی، بازی را متوقف، ادامه دهند یا دوباره شروع کنند.
- **خط قرمز**: اردک‌ها نمی‌توانند از خط قرمز عبور کنند.

### نصب و راه‌اندازی

1. **راه‌اندازی WinCC و SIMATIC**: اطمینان حاصل کنید که **WinCC** و **SIMATIC** نصب و برای اتوماسیون صنعتی پیکربندی شده‌اند.
2. **وارد کردن پروژه**: این مخزن را کلون یا دانلود کرده و فایل‌های پروژه را وارد پروژه **WinCC** کنید.
3. **شبیه‌سازی با PLCsim**: از **PLCsim** برای شبیه‌سازی محیط بازی استفاده کنید. این امکان را به شما می‌دهد که بدون نیاز به سخت‌افزار PLC، پروژه را آزمایش کنید.
4. **آزمایش بازی**: پس از بارگذاری پروژه در **PLCsim**، بازی را اجرا کرده و با سیستم از طریق پنل کنترل تعامل کنید.

### نحوه استفاده

- **شروع بازی**: پروژه را اجرا کرده و از پنل کنترل برای تعامل با سیستم استفاده کنید.
- **کنترل‌های بازی**: کنترل‌های بازی ساده است؛ شعله‌ها را شلیک کنید، از برخوردها اجتناب کنید و سعی کنید بیشترین امتیاز را کسب کنید.
- **سطوح**: با پیشرفت در بازی، سختی بازی افزایش می‌یابد و اردک‌ها سریع‌تر حرکت می‌کنند و قطرات بیشتری شلیک می‌شود.
