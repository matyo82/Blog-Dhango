# Blog-Django

یک پروژه وبلاگ با استفاده از Django، PostgreSQL و Docker.

## ویژگی‌ها

- مدیریت پست‌ها
- استفاده از PostgreSQL به‌عنوان پایگاه داده
- پیکربندی Docker برای توسعه و تولید

## پیش‌نیازها

- Python 3.x
- Docker و Docker Compose
- PostgreSQL
- Django 5.x

## نصب و راه‌اندازی

```bash
git clone https://github.com/matyo82/Blog-Dhango.git
cd Blog-Dhango
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```


## ساختار پروژه

- `blog/`: اپلیکیشن اصلی وبلاگ
- `mysite/`: پروژه Django
- `requirements.txt`: وابستگی‌ها
- `docker-compose.yml`: پیکربندی Docker

## مشارکت

1. فورک کنید.
2. یک شاخه جدید ایجاد کنید.
3. Pull Request ارسال کنید.
