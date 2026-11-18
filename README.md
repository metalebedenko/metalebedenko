# Привет, я Серго

[English](README.en.md)

Проектирую прикладные ИИ-системы. Мой основной язык — Python. Сначала разбираюсь, какой результат нужен человеку и на каких примерах его проверить. Затем выбираю большую или малую модель с учётом качества, задержки и стоимости. Подключаю модели через API и запускаю открытые модели локально.

В боте для дайджестов модель готовит содержание, а Python проверяет структуру данных и собирает PDF. Выпуск попадает в историю отправленных только после успешного ответа Telegram.

[Обсудить проект в Telegram · @lebedovichh](https://t.me/lebedovichh)

## Проекты

**Investment Digest Bot — дайджест в PDF**  
Бот находит материалы об инвестиционных идеях и собирает из них выпуск. Его можно прочитать перед отправкой в Telegram. [Полистать демовыпуск на вымышленных данных, 7 страниц](https://github.com/metalebedenko/investment-digest-bot/blob/main/docs/demo-digest.pdf) · [Почему PDF и отправка разделены](https://github.com/metalebedenko/investment-digest-bot/blob/main/README.ru.md#почему-подготовка-pdf-отделена-от-отправки)

**3D Landings — сайты для заказа деталей**  
Заменить сломанную деталь, заказать пробную партию или изготовить прототип — для каждого случая я сделал свою страницу. В одном из демо можно загрузить 3D-модель и получить предварительный расчёт. [Посмотреть главный экран](https://github.com/metalebedenko/3d-landings-showcase/blob/main/docs/preview.png) · [Как запустить демо локально](https://github.com/metalebedenko/3d-landings-showcase)

**EarPods AI Keys — диктовка с кнопки наушников**  
С пульта USB-C EarPods можно включить диктовку на Mac, стереть символ и нажать Enter. Этот сценарий проверен на двух физических Mac. Действия кнопок настраиваются. [Настройки кнопок](https://github.com/metalebedenko/earpods-ai-keys/blob/main/docs/media/button-settings.png) · [Проверка на двух Mac](https://github.com/metalebedenko/earpods-ai-keys/blob/main/README.ru.md#диктовка-без-клавиатуры) · [Скачать предварительную версию для Apple silicon](https://github.com/metalebedenko/earpods-ai-keys/releases/tag/v0.1.0-preview.3)

**Кафе и рестораны Москвы — цены по округам**  
Разобрал выборку из 8 402 записей о московских заведениях за лето 2022 года. В центре цены оказались выше, чем на окраинах, а примерно 38% заведений в выборке относились к сетям. [Выводы](https://github.com/metalebedenko/eda-horeca-moscow#ключевые-результаты) · [Графики и расчёты](https://github.com/metalebedenko/eda-horeca-moscow/blob/main/EDA_HoReCa_Moscow.ipynb)

**mri-review — помощник для расшифровки МРТ**  
Исследовательский навык для ИИ-агента. Если есть заключение, агент объясняет формулировки врача простыми словами. Если есть снимки, он помогает разобрать, что видно на конкретном кадре и что стоит уточнить у рентгенолога. [Как устроен навык](https://github.com/metalebedenko/mri-review)

**micromanager — доступ ИИ-агента к компьютеру**  
Владелец выбирает, к каким файлам дать доступ. Когда агент хочет изменить файл или выполнить команду, владелец может одобрить или отклонить запрос. [Как это работает](https://github.com/metalebedenko/micromanager) · [Скачать v0.0.4](https://github.com/metalebedenko/micromanager/releases/tag/v0.0.4)
