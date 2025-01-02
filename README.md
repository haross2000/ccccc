# نظام تحليل العملات الرقمية بالذكاء الاصطناعي

نظام متكامل لتحليل العملات الرقمية وتقديم توصيات البيع والشراء باستخدام الذكاء الاصطناعي.

## المميزات
- تحليل البيانات التاريخية للعملات الرقمية
- التنبؤ بالأسعار باستخدام نماذج التعلم العميق
- تحليل المؤشرات الفنية
- نظام توصيات ذكي للبيع والشراء
- واجهة مستخدم تفاعلية لعرض التحليلات والتوصيات

## المتطلبات
- Python 3.8+
- قم بتثبيت المكتبات المطلوبة:
```bash
pip install -r requirements.txt
```

## كيفية الاستخدام
1. قم بإنشاء ملف `.env` وأضف مفاتيح API الخاصة بك:
```
BINANCE_API_KEY=your_api_key
BINANCE_API_SECRET=your_api_secret
```

2. قم بتشغيل التطبيق:
```bash
python main.py
```

3. افتح المتصفح على العنوان: `http://localhost:8000`

## هيكل المشروع
- `data/`: مجلد لتخزين البيانات
- `models/`: نماذج الذكاء الاصطناعي
- `utils/`: أدوات مساعدة
- `api/`: خدمات API
- `dashboard/`: واجهة المستخدم
