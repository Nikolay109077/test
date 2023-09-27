# Business-solutions
Динамическая распознавание текста на изображении


Приведенный код создает веб-страницу, на которой можно загружать изображение. После загрузки, он использует функцию recognize_text() для распознавания текста на изображении. Распознанный текст сохраняется в текстовый файл, который затем отправляется пользователю для скачивания.

Добавьте HTML-шаблон index.html в папку templates в вашем проекте Flask


Примечание:
Убедитесь, что у вас установлена последняя версия Tesseract-OCR и вы правильно настроили путь к tessdata. Можете проверить переменную среды TESSDATA_PREFIX и убедиться, что она указывает на правильную директорию tessdata.

Если у вас нет файла rus.traineddata, вам может потребоваться его скачать. Вы можете найти этот файл на официальном сайте Tesseract-OCR и разместить его в директории tessdata.

Файл rus.traineddata, должен находится в папке Tesseract-OCR\tessdata
