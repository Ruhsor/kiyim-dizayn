# Kiyim Dizayn

Bu loyiha mobil qurilmalar uchun tayyor bo'lgan `PWA` (progressive web app) bo'lib, kiyim tasvirlarini chizish, rang berish va bezash imkonini beradi.

## Xususiyatlar
- Qalam, bo'yash va o'chirish asboblari
- Kiyim shablonlari: futbolka, ko'ylak, shim
- Ranglar va naqshlar tanlash
- O'yin/stiker kabi oddiy chizish imkoniyatlari
- PWA ishlashi uchun manifest va service worker

## Ishga tushirish

1. Repositoriyani klonlang.
2. `index.html` faylini brauzerda oching.
3. Yoki lokal server bilan ishlating:

```bash
python -m http.server 8000
```

Keyin brauzerda `http://localhost:8000` ni oching.

## Fayllar
- `index.html` — asosiy UI va chizish logikasi
- `manifest.json` — PWA konfiguratsiyasi
- `sw.js` — service worker
- `icon.svg` — app ikonkasi
