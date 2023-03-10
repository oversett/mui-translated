

# Дорожная карта <meta data-oversett="" data-original-text="Roadmap">

<p class="description">Дорожная карта - это живой документ, и вполне вероятно, что приоритеты будут меняться, но приведенный ниже список должен дать некоторое представление о наших планах на следующий основной выпуск и на будущее.</p>

## Методология <meta data-oversett="" data-original-text="Methodology">

MUI ориентируется на сообщество - вопросы, которые вызывают наибольший резонанс у сообщества, получают наибольшее внимание. Пожалуйста, **проголосуйте** (👍) на GitHub за вопросы, которые вам наиболее интересны. Благодарим вас за участие [в опросе разработчиков](/blog/2021-developer-survey-results/).

## Приоритеты <meta data-oversett="" data-original-text="Priorities">

Вот основные приоритеты:

-   **Больше компонентов**. 🧰 Мы должны строго расставлять приоритеты, так как разработка полноценного компонента занимает значительное количество времени. Мы применяем следующую стратегию:
    -   Определить часто требуемые компоненты. Для этого мы используем множество ресурсов: ответы на вопросы опроса разработчиков, количество голосов за вопросы на GitHub, объем поиска Algolia, объем поиска Google, использование документации, загрузки npm и т.д.
    -   Приоритет отдавайте созданию часто востребованных компонентов.
    -   Поощряйте использование сторонних компонентов, если они уже существуют и хорошо поддерживаются.
-   **Дизайн.** 🎀 Мы относительно современны, но руководство по Material Design [развивается](https://material.io/blog/). И мы тоже должны развиваться. Мы также планируем внедрить [второй дизайн](https://github.com/mui/material-ui/issues/22485).
-   **Лучшая кастомизация.** 💅 Мы хотим сделать настройку компонентов интуитивно понятной, независимо от того, используете ли вы глобальный CSS или стилизованные компоненты:
-   **Лучшая документация.** 📚 Ни одно решение не будет полным без отличной документации.
-   **Производительность.** 🚀 Абстракция React имеет свою цену. Чем больше компонентов вы отображаете, тем медленнее будет работать ваша страница. Вы заметите разительную разницу при рендеринге большой таблицы или списка.
-   **Размер пакета.** 📦 Вы можете следить за нашим прогрессом [с помощью отчета bundlephobia.com](https://bundlephobia.com/package/@mui/material). Обратите особое внимание на стоимость отдельных модулей в разделе "Анализ экспорта".
-   **TypeScript.** 📏 Мы постоянно совершенствуем определения. Кодовая база в основном написана на JavaScript с написанными вручную определениями `.d.ts`. Хотя мы не планируем миграцию как самостоятельную работу, новые модули пишутся на TypeScript.
-   **Доступность.** ♿️ У нас относительно [немного проблем с доступностью](https://darekkay.com/blog/accessible-ui-frameworks/), но мы стремимся решить их все. Мы будем признательны за помощь экспертов по доступности.

## Ежеквартальная дорожная карта <meta data-oversett="" data-original-text="Quarterly roadmap">

Дорожная карта нашего проекта на GitHub - это место, где вы можете узнать о том, над какими функциями мы работаем, на какой стадии они находятся и когда мы ожидаем их появления:

-   [MUI Core](https://github.com/mui/material-ui/projects/25). Этот репозиторий сосредоточен на создании великолепных систем дизайна с помощью React, а также на предоставлении двух готовых к использованию тем (пока что Material Design, еще одна появится в ближайшем будущем).
-   [MUI X](https://github.com/mui/mui-x/projects/1). Этот репозиторий фокусируется на предоставлении продвинутых компонентов React. Некоторые из них имеют лицензию MIT, другие доступны по коммерческой лицензии.
-   [MUI Design kits](https://github.com/mui/mui-design-kits/projects/1)Этот репозиторий фокусируется на предоставлении компонентов для дизайнеров на Figma и других инструментах проектирования. Это отличное место, чтобы оставлять отзывы, запросы на функции и задавать вопросы.

## Новые компоненты <meta data-oversett="" data-original-text="New components">

Вот компоненты, над поддержкой которых мы будем работать в экосистеме MUI:

-   🧪 Близок к тому, чтобы стать стабильным, уже выпущен как нестабильный
-   🛠 В процессе разработки, будет или уже выпущен как нестабильный
-   ⏳ Планируется к созданию

| Название | Продукт | Статус |
| --- | --- | --- |
| Расширенный макет | MUI X | ⏳   |
| Карусель | MUI X | ⏳   |
| Графики | MUI X | ⏳   |
| Сетка данных | MUI X | 🧪  |
| Выборка даты | MUI X | 🧪  |
| Выбор диапазона дат | MUI X | 🧪  |
| Выпадающий | MUI Core | ⏳   |
| Дропзона | MUI X | ⏳   |
| Загрузка файлов | MUI X | ⏳   |
| Диаграмма Ганта | MUI X | ⏳   |
| Манометр | MUI X | ⏳   |
| Изображение | MUI Core | ⏳   |
| Каменная кладка | MUI Core | 🧪  |
| Навбар | MUI Core | ⏳   |
| Вложенное меню | MUI X | ⏳   |
| NProgress | MUI Core | ⏳   |
| Числовой ввод | MUI Core | ⏳   |
| Редактор насыщенного текста | MUI X | ⏳   |
| Планировщик | MUI X | ⏳   |
| Scrollspy | MUI Core | ⏳   |
| Sparkline | MUI X | ⏳   |
| Временная шкала | MUI Core | 🧪  |
| Выбор дерева | MUI X | ⏳   |
| Просмотр дерева | MUI X | 🧪  |
| Древовидный вид - флажок | MUI X | ⏳   |
| Древовидный вид - перетаскивание | MUI X | ⏳   |
| Древовидный вид - мультивыбор | MUI X | 🧪  |
| Древовидный вид - Виртуализация | MUI X | ⏳   |
| Разделитель окон | MUI X | ⏳   |

:::warning
**Отказ от ответственности**: Мы работаем в динамичной среде, и все может измениться. Предоставленная информация предназначена только для ознакомления с общим направлением. Мы можем решить добавить или удалить новые элементы в любое время, в зависимости от наших возможностей по обеспечению соответствия стандартам качества. Разработка, выпуск и сроки реализации любых функций и возможностей остается на усмотрение MUI. Дорожная карта не является обязательством, обязанностью или обещанием выполнить в любое время.
:::
