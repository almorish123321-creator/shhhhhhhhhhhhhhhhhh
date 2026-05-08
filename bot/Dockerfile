FROM python:3.11-slim

WORKDIR /app

# نسخ جميع ملفات البوت (السياق هو مجلد bot/)
COPY . /app

# تثبيت المتطلبات
RUN pip install --no-cache-dir -r requirements.txt

# إنشاء مجلد المخرجات
RUN mkdir -p /app/output

# استخدام متغيرات البيئة من Railway (لا تكتب التوكن هنا!)
# ENV TELEGRAM_BOT_TOKEN و ENV ADMIN_USER_ID تُعرّف من Railway

CMD ["python", "bot_updated.py"]
