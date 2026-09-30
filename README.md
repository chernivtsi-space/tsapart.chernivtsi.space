# T&S apart-hotel

Live site: https://tsapart.chernivtsi.space

## About
T&S apart-hotel — апарт-готель у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Стіна з керамічної плитки: великий курсивний «&» на кобальтовій плитці між «T» і «S» — кухонна плитка як знак апартаментів із кухнею. Поруч — плашка Booking 9.3.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Безкоштовна парковка
- Ресторан
- Сімейні номери
- Обслуговування номерів
- Трансфер з аеропорту
- Окрема ванна кімната
- Кухня в апартаментах

## Check-in / check-out
Заїзд 14:00–00:00; Виїзд 04:00–12:00

## Reviews
Booking.com 9.3/10 (1874), Google 4.7/5 (126). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 50 601 1001
- Email: info@tshotels.com.ua
- Official site: https://tshotels.com.ua/
- Booking.com: https://www.booking.com/hotel/ua/t-amp-s.uk.html
- Google Maps: https://maps.google.com/?cid=2779280570597390893
- Address: вул. Козачука, 16, Чернівці

## Not published
Кількість номерів (джерела дають 24, 25 і 26), зірковість, місткість апартаментів, обладнання кухні, Instagram. Основне посилання — офіційний сайт tshotels.com.ua.

## Forms
HotelOS (`ch-tsapart`): `stay-request` (проживання). Документ `hotels/ch-tsapart` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Арочні вікна старої будівлі: pexels.com/photo/38163648 (Natalia Sevruk)
- Резиденція буковинських митрополитів, нині Чернівецький університет: pexels.com/photo/39176014 (Tetiana Boriskova)
- Чернівецький дворик: pexels.com/photo/17265321 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
