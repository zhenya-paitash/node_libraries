Node.js libraries
===
![node](https://media.giphy.com/media/kdFc8fubgS31b8DsVu/giphy.gif)

Tree
---
    ├─ database/
    │  ├─ bcrypt/
    │  ├─ faker/
    │  ├─ jsonwebtoken/
    │  ├─ lowdb/
    │  └─ uuid/
    ├─ filesystem/
    │  ├─ archiver/
    │  ├─ child_process/
    │  ├─ decompress/
    │  ├─ download/
    │  ├─ formidable/
    │  ├─ fs/
    │  ├─ multer/
    │  ├─ os/
    │  └─ zlib/
    ├─ http/
    │  ├─ axios/
    │  ├─ http/
    │  └─ request/
    ├─ image/
    │  ├─ imagemin/
    │  ├─ jimp/
    │  ├─ lqip/
    │  ├─ sharp/
    │  └─ spritesmith/
    ├─ web/
    │  ├─ moment/
    │  ├─ morgan/
    │  ├─ nodemailer/
    │  ├─ querystring/
    │  ├─ rss-parser/
    │  └─ tinycolor2/
    └─ web_scraping/
       ├─ cheerio/
       └─ puppeteer/

Libraries
---
package           |description| source
:-----------------|:----------|:---
**DATABASE**      |
[bcrypt](tree/master/database)            | `Библиотека хэширования паролей.`
faker             | `Модуль для генерирации поддельных данных в node.js/браузере.`
jsonwebtoken      | `Модуль для работы с JSON Web Token, или просто JWT. Представляет собой строку, полученную на основе формата JSON, и используется в качестве более безопасной и простой альтернативы сессиям и файлам cookie для авторизации.`
lowdb             | `Маленькая база данных JSON для Node, Electron и браузера. Работает на Lodash.`
uuid              | `Модуль для генерации UUID (универсального уникального идентификатора), также известного как GUID (глобальный уникальный идентификатор).`
**FILESYSTEM**    |
archiver          | `Потоковый интерфейс для создания архивов.`
child_process     | `Предоставляет возможность создавать дочерние процессы.`
decompress        | `Модуль обеспечивает только распаковку архивов.`
download          | `Модуль для скачивания и извлечения файлов.`
formidable        | `Модуль Node.js для анализа данных формы, особенно загрузки файлов.`
fs                | `Модуль для работы с файлами.`
multer            | `Multer — это middleware для фреймворка express для обработки multipart/form-data, нужная в первую очередь при загрузке файлов. Написана как обертка над busboy для ее максимально эффективного использования. ВАЖНО: Multer не обрабатывает никакой другой тип форм, кроме multipart/form-data.`
os                | `Модуль предоставляет набор операционных системных методов.`
zlib              | `Модуль обеспечивает функциональные возможности сжатия, реализованные с использованием Gzip, Deflate / Inflate и Brotli.`
**HTTP**          | 
axios             | `http-клиент на основе promise для браузера и node.js.`
http              | `Встроенный node.js модуль для использования сервера и клиента http.`
request           | `Модуль для простого способа совершать http-вызовы. Он поддерживает HTTPS и по умолчанию следует перенаправлениям.`
**IMAGE**         |
imagemin          | `Модуль для уменьшения изображений.`
jimp              | `Библиотека обработки изображений для Node, полностью написанная на JavaScript, без собственных зависимостей.`
lqip              | `LQIP: заполнитель изображений низкого качества.`
sharp             | `Преобразование больших изображений в распространенных форматах в более мелкие, удобные для Интернета изображения JPEG, PNG и WebP различных размеров.`
spritesmith       | `Модуль преобразования изображений в таблицы спрайтов и координатные карты.`
**WEB**           |
moment            | `Библиотека дат JavaScript для анализа, проверки, управления и форматирования дат.`
morgan            | `Промежуточное ПО регистратора запросов(логов) http для node.js.`
nodemailer        | `Модуль для работы с почтой в Node.js.`
querystring       | `Модуль querystring предоставляет утилиты для парсинга и форматирования строк запросов URL. `
rss-parser        | `Небольшая библиотека для превращения RSS-XML-каналов в объекты JavaScript.`
tinycolor2        | `TinyColor - это небольшая быстрая библиотека для управления цветом и преобразования в JavaScript. Он позволяет вводить множество форм, обеспечивая преобразование цветов и другие вспомогательные функции цвета. Не имеет зависимостей.`
**WEB SCRAPING**  |
cheerio           | `Парсинг модуль. Быстрая, гибкая и экономичная реализация jQuery для сервера. Cheerio анализирует разметку и предоставляет API для просмотра/управления полученной структурой данных. Он не интерпретирует результат, как это делает веб-браузер. В частности, он не производит визуальную визуализацию, не применяет CSS, не загружает внешние ресурсы и не выполняет JavaScript.`
puppeteer         | `Puppeteer - это библиотека Node, которая предоставляет высокоуровневый API для управления Chrome или Chromium по протоколу DevTools. Puppeteer по умолчанию работает без header, но его можно настроить для запуска полного Chrome или Chromium.`

