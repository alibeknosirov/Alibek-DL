# ProJect-IT — IT Loyiha Boshqaruv Platformasi

## 📋 Platforma Haqida

**ProJect-IT** - bu zamonaviy web-asosida IT loyihalarni boshqaruv uchun tizimi. Platforma PMBOK 7 + Agile metodologiyasini qo'llab-quvvatlaydi va haqiqiy vaqtda loyihalar boʻyicha KPI larni kuzatish imkonini beradi.

### ✨ Asosiy Xususiyatlari

- **PMO Dashboard** - KPI kartalar va real-vaqt ko'rsatkichlari
- **Loyihalar Portfeli** - barcha loyihalar bo'yicha jadvali
- **Gantt Jadvali** - vizual vaqt chizig'i
- **EVM Monitor** - Earned Value Management analitikasi
- **Risk Register** - risk matritsasi va boshqaruv choralari
- **Analitika** - investitsiya samaradorligi (NPV, ROI, IRR)
- **Yangi Loyiha** - avtomatik ML bashoratlari bilan loyiha yaratish

---

## 🚀 Ishga Tushirish

### Talablar
- Zamonaviy brauzer (Chrome, Firefox, Safari, Edge)
- Internetga ulanish (Chart.js CDN uchun)

### Boshlash
1. **index.html** faylni brauzerda oching:
   ```
   Eng oson usul: index.html faylida 2 marta click qiling
   ```

2. Yoki lokal server orqali:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server)
   npx http-server
   ```

   Keyin brauzerde `http://localhost:8000` ni oching

---

## 📁 Fayl Tuzilishi

```
ProJect-IT/
├── index.html           # Asosiy HTML sahifasi
├── styles.css           # CSS styling va responsive dizayn
├── script.js            # JavaScript funksiyonallik
└── docx_content/        # Asl Word dokumenti
```

---

## 🎨 Dizayn va Ranglar

| Holat | Rang | Ma'nosi |
|--------|------|---------|
| **Yashil** 🟢 | #27ae60 | Vaqtida / Bajarilgan |
| **Orange** 🟠 | #f39c12 | Ogohlantirish / Kechikish |
| **Qizil** 🔴 | #e74c3c | Xavf / Muammo |
| **Ko'k** 🔵 | #3498db | Ma'lumot / Rejalashtirilgan |

---

## 📊 Sahifalar va Funksiyalari

### 1. **PMO Bosh Panel** (Dashboard)
- 4 ta KPI kartalari: Jami loyihalar, Vaqtida, Xavf ostida, Muammo
- RAG Status donut grafigi
- Muvaffaqiyat Ko'rsatkichlari (2019-2024)
- Faol loyihalar jadvali
- Qaror tezligi va KPI metrikalar

### 2. **Loyihalar Portfeli**
- Barcha 7 ta loyiha bo'yicha to'liq jadval
- Ustunlar: nomi, metodologiya, muddat, byudjet, SPI, CPI, progress, holat
- Blockchain To'lov muammoli loyihasi qizil ajratilgan

### 3. **Gantt Jadvali**
- 2025-yil bo'yicha loyihalar vaqt chizig'i
- Rangli statuslar: Yashil (vaqtida), Orange (kechikish), Qizil (muammo)
- Progress foizlari ko'rsatilgan

### 4. **EVM Monitor**
- Earned Value Management ko'rsatkichlari
- BAC, PV, EV, AC, SV, CV, SPI, CPI, EAC, ETC
- 8 oylik EVM dinamikasi grafigi

### 5. **Risk Register**
- Bubble chart: Risk Matritsasi (Ehtimollik vs Ta'sir)
- 5 ta asosiy risk batafsil jadvali
- Risk ball, nomi, ehtimollik, ta'sir va boshqaruv choralari

### 6. **Analitika**
- Ko'rsatkichlar Taqqoslamasi (Oldin/Keyin)
- NPV Dinamikasi (477.7 mln so'm investitsiya)
- Investitsiya metrikalar: ROI, IRR, Payback Period

### 7. **Yangi Loyiha**
- Forma: nomi, metodologiya, rahbari, sanalar, byudjet, prioritet, sprint
- ML Model Bashorati (GradientBoost):
  - Muvaffaqiyat ehtimoli: 74%
  - Muddat xavfi: O'rta (35%)
  - Byudjet xavfi: Past (22%)
- Tavsiya etilgan Sprint strukturasi

---

## 📱 Responsive Dizayn

Platform barcha cihozlarda ishlaydi:
- **Desktop** (1200px+) - to'liq ko'rinish
- **Tablet** (768px-1199px) - 2-ustun layout
- **Mobil** (<768px) - 1-ustun, horizontal scroll sidebar

---

## 🔧 Texnologiyalar

- **HTML5** - semantik markup
- **CSS3** - modern styling, Grid va Flexbox
- **JavaScript (Vanilla)** - page navigation, interaktivlik
- **Chart.js 4.4.0** - grafiklar va diagrammalar
  - Doughnut charts (RAG status)
  - Line charts (Success metrics, EVM)
  - Bar charts (Analytics, Gantt)
  - Bubble charts (Risk matrix)

---

## 📊 Platforma Metrikalar

### Portfel Statistikasi
- **Jami Loyihalar**: 15 ta
- **Portfel Qiymati**: 1.24 mlrd so'm
- **Vaqtida**: 11 ta (73.3%)
- **Xavf Ostida**: 3 ta
- **Muammo**: 1 ta (Blockchain To'lov)

### Samaradorlik Ko'rsatkichlari
| Ko'rsatkich | Oldin | Keyin | O'zgarish |
|-------------|-------|-------|-----------|
| Vaqtida Yakunlash | 38% | 82% | +44 pp ✓ |
| Byudjet Normasida | 44% | 85% | +41 pp ✓ |
| Muvaffaqiyat | 41% | 88% | +47 pp ✓ |
| Stakeholder NPS | 59 | 91 | +32 ✓ |
| Qaror Vaqti | 72 h | 8 h | -89% ✓ |

### Investitsiya Samaradorligi
- **BAC**: 477.7 mln so'm
- **Qaytarim Muddati**: 2.6 yil
- **ROI**: 219.5%
- **IRR**: ~42%

---

## 🎯 Ishlash Tamoyillari

1. **Sidebar navigatsiya** - sahifalar orasida o'tish
2. **Dinamik chartlar** - real-vaqt ma'lumotlari
3. **Rang-kodirilgan statuslar** - tez aniqlash
4. **Responsive layout** - istalgan cihozda
5. **ML bashoratlari** - yangi loyihalar uchun

---

## 💡 Foydalanish Jumlalari

### Manager uchun
- Dashboard-dan KPI larni tez ko'rish
- Risk Reestrdagi muammolarga e'tibor berish
- NPV diagrammasi orqali investitsiya samaradorligini kuzatish

### PMO uchun
- Gantt jadvalida vaqt kuzatuvi
- EVM metrikalar orqali aniq rivojlanish tahlili
- Loyihalar portfelida prioritetlar belgilash

### Investor uchun
- Analitika sahifasida 5-yillik prognozlar
- ROI va IRR ko'rsatkichlari
- Muvaffaqiyat statistikasi

---

## 🔐 Ma'lumot Maxfiylik

- Barcha ma'lumot brauzer-da saqlangan (localStorage yo'q)
- Server-ga ulanish yo'q
- HTML5 based statik application

---

## 🆘 Tez Ko'chma Masalalar

### Grafiklar ko'rinmayotgan?
- Internetga ulanish tekshiring (Chart.js CDN uchun)
- Brauzer cache ni tozalash: Ctrl+Shift+Delete

### Navigatsiya ishlamilyapti?
- JavaScript yoniq ekanini tekshiring
- Brauzerni qaytadan yuklang (Ctrl+R)

### Responsive dizayn to'g'ri kelmaydi?
- Brauzer window o'lchamini o'zgartiring
- F12 → Device Toolbar orqali mobil ko'rinishni sinab ko'ring

---

## 📞 Muallif Ma'lumotlari

**Yaratuvchi**: Nosirov Alibek  
**Davraga**: 2025  
**Maqsadi**: Bitirish Malakaviy Ishi - Interaktiv Platform  
**Universitet**: Toshkent Davlat Iqtisodiyot Universiteti

---

## 📜 Litsenziya

Open source educational project. Erkintaur foydalanish mumkin.

---

## 🙏 Rahmat!

ProJect-IT platformasidan foydalanganiniz uchun rahmat! 
Agar savollaringiz yoki takliflariingiz bo'lsa, muallif bilan bog'laning.

**Happy Project Management! 🚀**
# Alibek-DL
# Alibek-DL
