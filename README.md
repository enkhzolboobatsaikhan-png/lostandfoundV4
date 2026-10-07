# МУИС Lost & Found

Файлууд:

- `index.html` - HTML бүтэц
- `style.css` - дизайн, responsive UI
- `script.js` - Firebase + application logic
- `firestore.rules` - Firestore Security Rules (Firebase Console > Firestore > Rules хэсэгт буулгаж Publish хийнэ)

## Ажиллуулах

VS Code дээр энэ folder-ийг нээгээд `index.html`-ийг Live Server-ээр ажиллуул.
GitHub Pages дээр байршуулахдаа 3 файлыг (index.html, style.css, script.js) repo-ийн root-д оруулна.

## Шинэ боломжууд

- Эможи ашиглаагүй: бүх дүрс нь SVG эсвэл текст.
- Мэдэгдэл: зар батлагдах / татгалзагдах үед, мөн алдсан болон олсон зар таарах үед (ангилал, нэр, байршил, огноо) хоёр талд мэдэгдэл очно.
- Устгах хүсэлт: хэрэглэгч "Миний зар" хэсгээс шалтгаан бичиж хүсэлт илгээнэ, админ "Устгах хүсэлт" таб дээр зөвшөөрч устгана эсвэл татгалзана.

## Анхаарах зүйл

Firebase Web config нь client-side config. Үндсэн хамгаалалт нь Firebase Authentication болон Firestore Security Rules дээр байх ёстой.
Шинэ боломжууд ажиллахын тулд `firestore.rules`-ийг заавал дахин Publish хийх ёстой (notifications, delreqs цуглуулга нэмэгдсэн).
