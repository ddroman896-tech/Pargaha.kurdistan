# پەرگەها کوردستان — POS & Inventory System

نظام نقاط البيع والمخزون مع قارئ الباركود بالكاميرا.
POS & Inventory system with camera barcode scanner (Tailwind CSS, Html5-Qrcode, Web Audio API).

## البنية / Structure

```
.
├── index.html
├── css/style.css
├── js/
│   ├── tailwind-config.js
│   └── app.js
└── README.md
```

## التشغيل / Run

افتح `index.html` في المتصفح، أو استخدم خادماً محلياً (مطلوب للكاميرا على بعض المتصفحات):

```bash
python3 -m http.server 8000
```

## النشر على GitHub Pages

1. ارفع الملفات إلى مستودع جديد.
2. Settings → Pages → Branch: `main` / root → Save.
3. سيكون الموقع على `https://USERNAME.github.io/REPO/` (HTTPS يسمح بالكاميرا).
