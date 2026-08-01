# 🌤 Weather App

A simple Python application that fetches real-time weather data for any city using the **OpenWeatherMap API**.

[🇮🇷 نسخه فارسی](README.fa.md)

## ✨ Features

- Get current temperature in Celsius
- Feels-like temperature
- Humidity, pressure, and wind speed
- Weather condition description
- Handles API and connection errors gracefully

## 🛠 Requirements

- Python 3.8+
- `requests` package
- Free API key from [OpenWeatherMap](https://home.openweathermap.org/api_keys)

## 🖥 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/weather-app.git
cd weather-app
2. Install dependencies
bash
Copy
pip install -r requirements.txt
3. Configure your API key
Open config.py and replace the API key with your own.

4. Run the app
bash
Copy
python main.py
Then enter a city name in English, for example:

yaml
Copy
Enter city name : tehran
📊 Sample Output
yaml
Copy
========================================
🌤  Weather in Tehran, IR
========================================
🌡  Temperature: 32.5°C (feels like: 35.1°C)
💧  Humidity: 23%
🌀  Pressure: 1008 hPa
🌬  Wind Speed: 2.6 m/s
☁️  Status: clear sky
🧪 Quick Test
bash
Copy
python -c "from main import get_weather; print(get_weather('london'))"
📚 Project Structure
weather-app/
Copy
weather-app/
.gitignore
README.md
README.fa.md
config.py       # API key configuration
main.py         # Main application
requirements.txt
📜 License
MIT

Made with ❤️ and Python

yaml
Copy

---

## 📄 README.fa.md (فارسی)

```markdown
# 🌤 اپلیکیشن آب و هوا

یک برنامه ساده پایتونی که داده‌های لحظه‌ای آب و هوای هر شهر را با استفاده از **OpenWeatherMap API** دریافت می‌کند.

[🇬🇧 English Version](README.md)

## ✨ امکانات

- دریافت دمای فعلی (بر حسب سانتی‌گراد)
- نمایش دمای احساسی (Feels Like)
- رطوبت، فشار و سرعت باد
- توضیح وضعیت آب و هوا
- مدیریت خطاهای API و اتصال به‌صورت حرفه‌ای

## 🛠 پیش‌نیازها

- Python 3.8 یا بالاتر
- پکیج `requests`
- کلید API رایگان از [OpenWeatherMap](https://home.openweathermap.org/api_keys)

## 🖥 نصب و اجرا

### ۱. دریافت ریپازیتوری

```bash
git clone https://github.com/YOUR_USERNAME/weather-app.git
cd weather-app
۲. نصب وابستگی‌ها
bash
Copy
pip install -r requirements.txt
۳. تنظیم کلید API
فایل config.py را باز کنید و کلید خود را جایگزین کنید.

۴. اجرای برنامه
bash
Copy
python main.py
سپس نام شهر را به انگلیسی وارد کنید، مثلاً:

yaml
Copy
Enter city name : tehran
📊 نمونه خروجی
کپی
========================================

🌤 آب و هوای Tehran, IR

========================================

🌡 دما
32.5°C (احساس: 35.1°C)
💧 رطوبت
23%
🌀 فشار
1008 hPa
🌬 سرعت باد
2.6 m/s
☁️ وضعیت
clear sky
🧪 تست سریع
bash
Copy
python -c "from main import get_weather; print(get_weather('london'))"
