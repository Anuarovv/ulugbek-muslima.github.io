# Файлы для замены / Files to replace

## 📸 couple.png
Замените этот файл на фото молодожёнов (детское фото).
Рекомендуемый размер: 600×600 px, формат PNG (с прозрачным фоном) или JPG.

## 🏛 venue.png
Замените на реальное фото тойханы/места проведения свадьбы.
Рекомендуемый размер: 600×400 px.

## 🎵 music.mp3
Добавьте файл music.mp3 в эту папку — он будет воспроизводиться кнопкой-нотой.

---

## Настройка сайта (в index.html, блок CONFIG)

```js
const CONFIG = {
  groomName: 'Улугбек',
  brideName: 'Муслима',
  weddingDate: new Date('2026-08-07T18:00:00'),  // ← Дата свадьбы
  weddingMonth: 8,    // 0=Январь, 3=Апрель
  weddingDay: 7,
  weddingYear: 2026,
  venueName: 'Банкетный зал Томирис, ул. Кыргауылды, 1а',
  venueMapLink: 'https://go.2gis.com/Ltr75',  // ← Ссылка на карту
  googleFormLink: 'https://docs.google.com/forms/d/e/1FAIpQLSf6I6AtENVMBbxVsQemuJ4XCDkMoED7eJYWtPfhd4bVyDYI0g/viewform?usp=header',          // ← Ссылка на Google Form
};
```

## Казахский перевод (в index.html, блок TRANSLATIONS.kk)
Раздел уже есть — просто замените тексты на правильные переводы.
