# Авторы и лицензии ресурсов

## Санта (спрайты `sprites/santa-idle.png`, `sprites/santa-jump.png`)

- Набор: **Santa Claus — Free Sprites**
- Автор: **pzUH**
- Лицензия: **CC0 1.0 (общественное достояние)**. Можно использовать в любых проектах, в том числе коммерческих, менять и распространять. Указывать автора не обязательно, мы указываем из уважения.
- Источник: https://opengameart.org/content/santa-claus-free-sprites (поле «License(s): CC0»)
- Копия у автора: https://pzuh.itch.io/santa-claus-free-sprites. На вопрос в комментариях о лицензии автор ответил «Yes CC0».
- Текст лицензии: https://creativecommons.org/publicdomain/zero/1.0/

Проверка подлинности (1 ноября 2026):
- исходный архив `SantaSprites.zip`, 11 237 894 байт;
- SHA-256: `5c2370c9a107b4e86b290159a23ea16154fe5179d072fe8adf65a1ed08d07265`;
- хэш локальной копии совпал с файлом, скачанным с OpenGameArt в тот же день;
- в архиве только PNG (98 шт.), проект DragonBones и README. Исполняемых файлов нет, все PNG имеют корректную сигнатуру.

Что изменено: из анимаций Idle и Jump взят каждый второй кадр. Пустые поля обрезаны по общей рамке кадров, высота уменьшена до 200 px, кадры склеены в горизонтальную полосу.

| Файл | Кадров | Кадр, px | SHA-256 |
|---|---|---|---|
| `sprites/santa-idle.png` | 8 | 127×200 | `5b147d5d49816043d0e550795cdd06a24a184002157010dfb4908cde209d952d` |
| `sprites/santa-jump.png` | 8 | 170×200 | `8694d8a5f31b8d2ccb4b6c37f764bb46d73fe49fe47efebef8b9c38e0dde5f1b` |

## Шрифт Caveat

- Автор: Impallari Type. Лицензия: SIL Open Font License 1.1. Вшит в `index.html`.

## Шрифты Comfortaa и Rubik Mono One

- **Comfortaa** — автор Johan Aakerlund. Основной текст приложения.
- **Rubik Mono One** — авторы Hubert & Fischer. Подписи разделов и кнопки.
- Лицензия обоих: **SIL Open Font License 1.1**. Можно бесплатно использовать в любых проектах, в том числе коммерческих, и встраивать в страницу. Продавать сами шрифты отдельно нельзя.
- Источник: Google Fonts (https://fonts.google.com/specimen/Comfortaa, https://fonts.google.com/specimen/Rubik+Mono+One). Скачаны 6 ноября 2026.
- Взяты только наборы символов «кириллица» и «латиница» в формате WOFF2. Файлы не менялись, они вшиты в `index.html` в base64.

| Набор | Байт | SHA-256 |
|---|---|---|
| Comfortaa, кириллица (переменная насыщенность 300–700) | 18 448 | `a0fee7d935b77461c002a314cfa398f1d32bf5aedb98063884239400e4663eaf` |
| Comfortaa, латиница | 30 872 | `408f20ae9895ceefa460a383d76497a91abc469e3d00b49f080efc7f4b12c60e` |
| Rubik Mono One, кириллица | 6 156 | `84d22c91c134519324b93a76e646905df09bcee123163f06fe79ccd07bf44b23` |
| Rubik Mono One, латиница | 12 752 | `4c1f9c2e5e3f867641f60becebfc11cd0e6ab02aa96bac88d750e37de8fce3c4` |

## Остальная графика

Подарки, большой подарок с крышкой, открытка, мешок, ёлка, гирлянда, снег и конфетти нарисованы кодом прямо в `index.html` для этого проекта.
