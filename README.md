# Blog Sayt

Bu loyiha **Django framework** yordamida yaratilgan oddiy blog saytidir. Sayt foydalanuvchilarga blog postlar yaratish, tahrirlash va o'chirish imkoniyatini beradi.

---

## 🚀 Loyihaning funksiyalari

- Foydalanuvchi kirishi va ro'yxatdan o'tishi
- Blog postlarni yaratish
- Blog postlarni ko'rish
- Blog postlarni tahrirlash va o'chirish
- Responsiv (mobilga mos) dizayn

---

## 📂 Loyihaning tarkibi

Loyiha quyidagi papka va fayllardan iborat:

```plaintext
blog_sayt/
├── blog/               # Blog ilovasi
│   ├── migrations/     # Django ma'lumotlar bazasi migratsiyalari
│   ├── admin.py        # Admin panel sozlamalari
│   ├── apps.py         # Ilova konfiguratsiyasi
│   ├── models.py       # Ma'lumotlar bazasi modellari
│   ├── views.py        # Foydalanuvchi interfeysi uchun funksiyalar
│   ├── urls.py         # URL marshrutlari
├── blog_sayt/          # Loyihaning asosiy papkasi
│   ├── settings.py     # Loyiha sozlamalari
│   ├── urls.py         # Loyihaning URL marshrutlari
│   ├── wsgi.py         # WSGI server sozlamalari
│   ├── asgi.py         # ASGI server sozlamalari
└── manage.py           # Django boshqaruv fayli
