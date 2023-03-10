

# Поддерживаемые платформы <meta data-oversett="" data-original-text="Supported platforms">

<p class="description">Узнайте о платформах, от современных до старых, которые поддерживаются MUI.</p>

## Браузер <meta data-oversett="" data-original-text="Browser">

MUI поддерживает последние, стабильные версии всех основных браузеров и платформ. Вам не нужно предоставлять полифилл JavaScript, поскольку он управляет неподдерживаемыми функциями браузера внутренне и изолированно.

| Edge | Firefox | Chrome | Safari (macOS) | Safari (iOS) | IE  |
| --- | --- | --- | --- | --- | --- |
| \>= 91 | \>= 78 | \>= 90 | \>= 14 | \>= 12.5 | 11 (частичная поддержка) |

Полный список можно найти в нашем [.browserlistrc](https://github.com/mui/material-ui/blob/master/.browserslistrc#L12-L27) (проверьте запись `stable` ).

Поскольку Googlebot использует службу веб-рендеринга (WRS) для индексации содержимого страницы, очень важно, чтобы MUI поддерживал ее.[WRS регулярно обновляет используемый им движок рендеринга](https://webmasters.googleblog.com/2019/05/the-new-evergreen-googlebot.html). Вы можете ожидать, что компоненты MUI будут рендериться без серьезных проблем.

### IE 11 <meta data-oversett="" data-original-text="IE 11">

MUI обеспечивает **частичную** поддержку IE 11. Имейте в виду следующее:

-   Некоторые компоненты не имеют поддержки. Например, новые компоненты, сетка данных, выборка даты.
-   Некоторые компоненты имеют ухудшенную поддержку. Например, отсутствует радиус границы контурного ввода, combobox не удаляет диакритические знаки, анимация кругового прогресса шатается.
-   Может произойти сбой самой документации.
-   Вам необходимо установить [пакет наследия](/material-ui/guides/minimizing-bundle-size/#legacy-bundle).
-   Возможно, вам потребуется установить полифиллы. Например, для [переходной зависимости popper.js](https://popper.js.org/docs/v2/browser-support/#ie11).

В целом, библиотека не ставит в приоритет поддержку IE 11, если это вредит наиболее распространенным вариантам использования. Например, мы будем закрывать новые проблемы, связанные с IE 11, и можем не объединять запросы на исправление, которые улучшают поддержку IE 11.

В v6 будет полностью удалена поддержка IE 11.

## Сервер <meta data-oversett="" data-original-text="Server">

MUI поддерживает [Node.js](https://github.com/nodejs/node) начиная с версии 12.0 для рендеринга на стороне сервера. Цель - поддерживать Node.js вплоть до [последней версии в режиме обслуживания](https://github.com/nodejs/Release#release-schedule).

### Префиксация CSS <meta data-oversett="" data-original-text="CSS prefixing">

Имейте в виду, что некоторые функции CSS [требуют](https://github.com/cssinjs/jss/issues/279) дополнительного шага постпроцессинга, который добавляет префиксы, специфичные для конкретного производителя. Эти префиксы автоматически добавляются в клиент благодаря функции [`jss-plugin-vendor-prefixer`](https://www.npmjs.com/package/jss-plugin-vendor-prefixer).

CSS, используемый в этой документации, обрабатывается с помощью [`autoprefixer`](https://www.npmjs.com/package/autoprefixer)Вы можете использовать [реализацию документации](https://github.com/mui/material-ui/blob/47aa5aeaec1d4ac2c08fd0e84277d6b91e497557/pages/_document.js#L123) в качестве вдохновения. Имейте в виду, что это влияет на производительность страницы. Это обязательное действие для статических страниц, но оно должно быть сбалансировано с тем, чтобы ничего не делать при рендеринге динамических страниц.

## React <meta data-oversett="" data-original-text="React">

MUI поддерживает самые последние версии React, начиная с ^17.0.0 (та, что с делегированием событий в корне React). Просмотрите более старые [версии](https://mui.com/versions/) для обратной совместимости.

## TypeScript <meta data-oversett="" data-original-text="TypeScript">

MUI требует минимальную версию TypeScript 3.5. Это направлено на то, чтобы соответствовать политике [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped), с поддержкой версий TypeScript, которым менее двух лет.
