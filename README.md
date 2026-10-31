# wtautodraw

**[русский](#русский) · [english](#english)**

---

## русский

**wtautodraw** - веб-приложение, которое превращает любое изображение в пользовательский прицел для war thunder (`.blk`) в пару кликов. выберите фото из галереи, и приложение само найдет контуры и нарисует их линиями.

> проект еще сырой: возможны ошибки и недоработки.

### возможности

- **автоматическая обводка.** фото превращается в плавные линии: выделение контуров, склейка разрывов, сглаживание и упрощение.
- **ластик.** стирайте лишние линии прямо на превью, с отменой действий и полным сбросом.
- **автолимит линий.** приложение само снижает точность, чтобы уложиться в заданное максимальное число линий.
- **настройки прицела.** размер, сдвиг по осям, толщина линий, цвет, центральный крест и отзеркаливание.
- **показ оригинала.** исходное фото можно включить под линиями для сравнения.
- **два языка.** интерфейс переключается между русским и английским.
- **готовый `.blk`.** файл создается в формате пользовательских прицелов war thunder.

### как пользоваться

1. откройте сайт и нажмите «выбрать фото из галереи» (или перетащите картинку в окно).
2. при необходимости подстройте ползунки: чувствительность, детализацию, плавность, максимум линий.
3. уберите лишнее ластиком, подберите размер и положение.
4. нажмите «скачать .blk».
5. положите файл в папку `UserSights` в папке с игрой war thunder и выберите его в настройках игры.

### совет

- если линий слишком много (обычно если свыше 2500) то рисунок в игре скорее всего будет обрезанным, поэтому выходить за этот лимит не советую.

### запуск

это один файл `index.html`, без сборки и зависимостей. откройте его двойным кликом или разместите на любом статическом хостинге, например на github pages.

### примечание

проект неофициальный и никак не связан с gaijin entertainment. war thunder - товарный знак его владельца.

*made by murales*

---

## english

**wtautodraw** is a web app that turns any image into a custom war thunder sight (`.blk`) in just a few clicks. pick a photo from your gallery and the app finds the outlines and draws them as lines for you.

> the project is still raw: bugs and rough edges are possible.

### features

- **automatic tracing.** a photo becomes smooth lines: edge detection, gap bridging, smoothing and simplification.
- **eraser.** wipe unwanted lines right on the preview, with undo and a full reset.
- **automatic line limit.** the app lowers precision on its own to stay within the maximum number of lines you set.
- **sight settings.** size, offsets, line thickness, color, center cross and mirroring.
- **original overlay.** show the source photo under the lines to compare.
- **two languages.** the interface switches between russian and english.
- **ready-to-use `.blk`.** the file follows the war thunder user sight format.

### how to use

1. open the site and click “choose a photo” (or drag an image into the window).
2. adjust the sliders if needed: sensitivity, detail, smoothness, max lines.
3. remove anything unwanted with the eraser and set the size and position.
4. click “download .blk”.
5. put the file into the `UserSights` folder inside your war thunder game folder and select it in the game settings.

### tips

- If there are too many lines (usually over 2,500), the drawing in the game will most likely be cut off, so I don't recommend exceeding this limit.

### running

it is a single `index.html` file with no build step and no dependencies. open it with a double click or host it on any static hosting, for example github pages.

### disclaimer

this is an unofficial project and is not affiliated with gaijin entertainment. war thunder is a trademark of its owner.

*made by murales*
