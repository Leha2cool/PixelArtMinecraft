# PixelArtMinecraft

English
Image → Minecraft Pixel Art Converter
PixelArt → Minecraft Datapack
A client-side, single-page web app that lets you:

Upload any image (up to 512×512px)

Pixelate it by a Minecraft block palette

Apply brightness, contrast and black-&-white filters

Choose orientation (XZ floor, XY wall, relative to player)

Generate /setblock or /summon falling_block commands

Download as a standalone .mcfunction or a complete datapack for Minecraft 1.16.5

Features
Live Preview: zoomed grid view with filter controls.

Command Generation: copy to clipboard or download file.

Datapack Export: auto-package with pack.mcmeta and data/<name>/functions/.

Fully Client-Side: no server required.

Installation & Usage
Clone the repository:


Upload an image, adjust settings, click “Generate Commands”.

Use buttons to:

“Download .mcfunction” – for manual or datapack import.

“Download Datapack” – ZIP including pack.mcmeta and data/....




Русский
Конвертер изображений в Minecraft-пиксель-арт
PixelArt → Minecraft Datapack
Клиентское одностраничное веб-приложение, которое позволяет:

Загрузить любое изображение (макс. 512×512px)

Пикселизировать его по палитре блоков Minecraft

Применить фильтры яркости, контраста и чёрно-белый режим

Выбрать ориентацию (плоскость XZ, стена XY, относительно игрока)

Сгенерировать команды /setblock или /summon falling_block

Сохранить результат в виде .mcfunction или готового datapack’а для Minecraft 1.16.5

Возможности
Превью: увеличение, сетка, фильтры (яркость/контраст/ЧБ).

Генерация команд: удобно копировать или скачивать файл.

Datapack: автоматическая упаковка с pack.mcmeta и функцией в data/<имя>/functions/.

Полностью на клиенте: без сервера, не требует бэкенда.


Загрузите изображение, настройте параметры, нажмите «Генерировать команды».

По кнопкам:

«Скачать .mcfunction» – файл для datapack’а или импорта вручную.

«Скачать Datapack» – ZIP с pack.mcmeta и папкой data/....

Структура репозитория


├── index.html       # Основная страница
├── README.md        # Этот файл
└── LICENSE          # Лицензия
