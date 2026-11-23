# Словник полів моделі фільму

| Поле (name) | Тип даних | HTML-елемент | Обмеження |
|---|---|---|---|
| code | String | input text | required, pattern="MOV-[0-9]{3}" |
| title | String | input text | required, minlength="2", maxlength="100" |
| imageUrl | String | input url | required |
| category | String | select | required |
| duration | Number | input number | min="1", max="500", step="1" |
| releaseYear | Number | input number | min="1900", max="2026", step="1" |
| addedAt | Date | input date | min, max |
| description | String | textarea | maxlength="1000" |
| inStock | Boolean | input checkbox | true/false |
