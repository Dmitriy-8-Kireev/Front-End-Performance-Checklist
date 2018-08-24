<h1 align="center">
<br>
  <img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170">
  <br>
    <br>
  Чек-лист производительности фронтенда
  <br>
</h1>

<h4 align="center">🎮 Единственный чек-лист производительности фронтенда, который справляется лучше других.</h4>
<p align="center">Одно простое правило: "Учитывайте производительность при дизайне и написании кода"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link">
    <img src="https://img.shields.io/badge/chat-on_gitter-008080.svg?style=flat-square" alt="Gitter">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#Как-использовать">Как использовать</a> • <a href="#Участие-в-проекте">Участие в проекте</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Другие чек-листы:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Чек-лист фронтенда</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Чек-лист дизайна фронтенда</a>
</p>

> Примечание переводчика: возможны ошибки и неточности перевода, спасибо всем, кто их найдёт и предложит исправления! Может это очевидно, но считаю необходимым указать, что названия ссылок хоть и частично переведены, их контент на английском языке, за исключением случаев, когда рядом со ссылкой на оригинал указан перевод (к сожалению, очень-очень редко).

## Содержание

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Шрифты](#Шрифты)**
4. **[Изображения](#Изображения)**
5. **[JavaScript](#javascript)**
6. **[Сервер](#Сервер) (в процессе)**
7. **[JS-фреймворки](#Производительность-js-фреймворков) (в процессе)**

## Введение

Производительность — огромная тема, но это не всегда забота «бэкенда» или «администратора»: это также ответственность фронтенда. Чек-лист производительности фронтенда — это исчерпывающий список пунктов, которые вы должны проверить или, по крайней мере, знать о них, как фронтенд-разработчик, и применять в своём проекте (личном и коммерческом).

### Как использовать?

Для каждого правила будет приведён параграф, поясняющий *почему* это правило важно и *как* вы можете его исправить. Для получения более подробной информации вам нужно перейти по ссылкам, которые будут указывать на 🛠 инструменты, 📖 статьи или 📹 средства, которые могут завершить чек-лист.

Все пункты в **Чек-листе производительности фронтенда** необходимы для достижения наивысшей оценки производительности, но вы найдёте индикатор, который поможет вам в конечном счёте определить приоритеты некоторых правил. Существует 3 уровня приоритета:

* ![Low][low] означает, у этого пункта *низкий* приоритет.
* ![Medium][medium] означает, у этого пункта **средний** приоритет. Вам не следует избегать выполнение этого пункта.
* ![High][high] означает, у этого пункта **высокий** приоритет. Настоятельно не рекомендуется избегать соблюдения этого правила, поэтому необходимо выполнить рекомендуемые исправления.

### Инструменты производительности

Список инструментов, которые вы можете использовать для тестирования или мониторинга вашего веб-сайта или приложения:

 * 🛠 [WebPagetest - Тест производительности и оптимизации сайта](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Проверка скорости и анализ сайта](https://www.dareboost.com/) (используйте купон WPCDD20 для получения скидки 20%)
 * 🛠 [Treo: Мониторинг скорости страницы](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Оптимизация производительности и скорости сайта](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Pingdom - Тест скорости сайта](https://tools.pingdom.com)
 * 📖 [Pagespeed - Инструмент и руководство по оптимизации](https://varvy.com/pagespeed/)
 * 📖 [Сделайте сайты быстрее | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Добро пожаловать в прекрасный мир веб-оптимизации](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/) - Мониторинг и анализ быстродействия веб-приложений
 * 🛠 [Dotcom-Tools - Тест скорости сайта и проверка веб-производительности](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Pingdom - Мониторинг доступности сервера и сайта](https://www.pingdom.com/product/uptime-monitoring/) ([Ссылка на бесплатную регистрацию](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Мониторинг производительности фронтенда](https://speedcurve.com)
 * 🛠 [PWMetrics - Инструмент командной строки и библиотека для сбора метрик производительности](https://github.com/paulirish/pwmetrics)
* 🛠 [Varvy - Оптимизация скорости страницы](https://varvy.com/pagespeed/)
* 🛠 [Lighthouse - Google](https://developers.google.com/web/tools/lighthouse/#devtools)

### Справочные руководства

 * 📹 [Цена JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([текстовая версия](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)) ([🇷🇺 перевод](https://habr.com/company/ruvds/blog/419369/))
 * 📖 [Начало работы с анализом производительности во время выполнения | Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [Состояние веба | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Размер страницы не имеет значения](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Varvy - Глоссарий веб-производительности](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Обновлённая коллекция ценных ресурсов веб-производительности](https://github.com/fabkrum/web-performance-resources)
---

## HTML

![html]

- [ ] **Минифицированный HTML:** ![medium] HTML-код минифицирован; комментарии, проблемы и новые строки удалены из файлов-ресурсов, используемых в продакшене.

    *Почему:*
    > Удаление всех ненужных пробелов, комментариев и переводов строк уменьшит размер вашего HTML и ускорит время загрузки страницы сайта и, очевидно, облегчит загрузку сайта вашим пользователям.

    *Как:*
    > У большинства фреймворков есть плагины для обеспечения миницификации веб-страниц. Вы можете использовать кучу NPM-модулей, которые могут делать данную работу автоматически.

    * 🛠 [HTML minifier | Минифицировать код](http://minifycode.com/html-minifier/)
    * 🛠 [Онлайн-сжатие HTML](http://refresh-sf.com)
    * 📖 [Экспериментирование с HTML-минификатором — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **Удалить ненужные комментарии:** ![low] Убедитесь, что комментарии удалены из ваших страниц.

    *Почему:*
    > Комментарии не очень полезны для пользователя, поэтому должны быть удалены из файлов в продакшене. Случай, когда вы можете сохранить комментарии — это сохранить источник (происхождение) библиотеки.

    *Как:*
    > В большинстве случаев комментарии могут быть удалены, используя плагин для минификации HTML.

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **Удалить ненужные атрибуты:** ![low] Атрибутов типов, такие как `type="text/javascript"` или `type="text/css"`, больше не нужны, и их следует удалить.

    ```html
    <!-- До HTML5 -->
    <script type="text/javascript">
        // JavaScript-код
    </script>

    <!-- В настоящее время -->
    <script>
        // JavaScript-код
    </script>
    ```

    *Почему:*
    > Атрибуты типов не нужны, поскольку HTML5 подразумевает `text/css` и `text/javascript` по умолчанию. Неиспользованный код следует удалить, если он не используется вашим сайтом или приложением, т.к. это он добавляет больше размера вашим страницам.

    *Как:*
    > ⁃ Убедитесь, что у тегов `<link>` и `<script>` нет атрибутов типа.

    * 📖 [Тег Script | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **Всегда размещайте теги подключения CSS до тегов, загружающих JavaScript:** ![high] Убедитесь, что ваш CSS всегда загружается перед JavaScript-кодом.

    ```html
    <!-- Не рекомендуется -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Рекомендуется -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *Почему:*
    > Наличие тегов подключения CSS до любого JavaScript позволяет повысить параллельную загрузку, которая ускоряет время отрисовки страницы браузером.

    *Как:*
    > ⁃ Убедитесь, что теги `<link>`  и `<style>` в вашем `<head>` всегда находятся перед вашим `<script>`.

    * 📖 [Порядок стилей и скриптов для pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Сократить количество элементов iframe:** ![high] Используйте элементы `iframe` только в том случае, если у вас нет другой технической возможности. Старайтесь избегать элементов iframe столько, сколько сможете.

**[⬆ вернуться в начало](#Содержание)**

## CSS

![css]

- [ ] **Минификация:** ![high] Все CSS-файлы минифицированы, комментарии, проблемы и новые строки удалены из файлов для продакшена.

    *Почему:*
    > Когда CSS-файлы, содержимое загружается быстрее и меньше данных отправляются клиенту. Важно всегда минифицировать CSS-файлы в продакшене. Это выгодно для любого пользователя, как и для каждого бизнеса, который хочет снизить расходы на пропускную способность и снизить использование ресурсов.

    *Как:*
    > Используйте инструменты для минификации ваших файлов автоматически automatically до или во время сборки или деплоя.

    * 🛠 [Модульный минификатор, основанный на экосистеме PostCSS - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Онлайн-сжатие CSS](http://refresh-sf.com)


- [ ] **Объединение:** ![medium] CSS-файлы объединены в один файл *(Не всегда действительно для HTTP/2)*.

    ```html
    <!-- Не рекомендуется -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Рекомендуется -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Почему:*
    > Если вы все ещё используете HTTP/1, вам по-прежнему нужно объединять ваши файлы, это меньше относится, если ваш сервер использует HTTP/2 (должны быть сделаны тесты).

    *Как:*
    > ⁃ Используйте онлайн-инструмент или любой другой плагин до или во время вашей сборки или деплоя для объединения файлов.
    ⁃ Разумеется, убедитесь, что объединение не нарушило работы вашего проекта.

    * 📖 [HTTP: оптимизация доставки приложений - Высокопроизводительная браузерная сеть (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Передовые практики производительности в эру HTTP/2](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Нет блокировки:** ![high] CSS-файлы следует быть неблокируемыми для предотвращения работы с DOM до полной загрузки.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Почему:*
    > CSS-файлы могут блокировать загрузку страницы и задерживать отрисовку вашей страницы. Использование `preload` может на самом деле загружать файлы CSS до того, как браузер начнёт показывать содержимое страницы.

    *Как:*
    > ⁃ Вам нужно добавить атрибут `rel` со значением `preload` и атрибут `as="style"` в элемент `<link>`.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Пример использования preload в CSS, используя loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Предварительная загрузка содержимого с помощью rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Предварительная загрузка: что в этом хорошего? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Длина CSS-классов:** ![low] Длина ваших классов может иметь (небольшое) воздействие на ваши HTML- и CSS-файлы (в конечном счёте).

    *Почему:*
    > Даже влияние производительности может быть спорным, принятие решения о стратегии именования, используемой в вашем проекте может оказать существенное влияние на удобство сопровождение ваших таблиц стилей. Если вы используете BEM, в некоторых случаях вы можете получить классы с большим количеством символов, чем это необходимо. Всегда важно мудро выбирать ваши имена и пространства имён.

    *Как:*
    > Установка ограничения в плане количества символов может быть интересно для некоторых людей, но добиться разделения сайта на компоненты может помочь уменьшить количество классов (и определений) и длину ваших классов.

    * 🛠 [Сравнение производительности: длинные и короткие классы · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **Неиспользуемый CSS:** ![medium] Удалить неиспользуемые CSS-селекторы.

    *Почему:*
    > Удаление неиспользуемых CSS-селекторов может уменьшить размер ваших файлов, а затем ускорить загрузку ваших ресурсов.

    *Как:*
    > ⚠️ Всегда проверяйте, не содержит ли код CSS-фреймворка, который вы хотите использовать, ещё не включённый код сброса/нормализации стилей. Иногда вам может понадобиться не все, что находится внутри файла стилей для сброса/нормализации.

    * 🛠 [UnCSS - Онлайн удаление неиспользуемого кода](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **Критичный CSS:** ![high] Критичный CSS (or "above the fold") собирает весь CSS-код, используемый для отрисовки видимой части страницы. Он встраивается перед подключением вашего основного CSS и между `<style></style>` в одну строку (минифицирован, если это возможно).

    *Почему:*
    > Встраивание критического CSS помогает ускорить отрисовку веб-страниц, уменьшая количество запросов на сервер.

    *Как:*
    > Сгенерировать критический CSS с помощью онлайн-инструментов или используя такой плагин, который разработал Эдди Османи (Addy Osmani).

    * 📖 [Понимание критического CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Инструмент для генерации критического CSS от Эдди Османи на GitHub](https://github.com/addyosmani/critical).
    * 📖 [Встраивание критического CSS для лучшей веб-производительности | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
    * 🛠 [Генератор критического CSS по URL-адресу :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
    * 📖 [Уменьшение размера содержимого в верхней части страницы](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **Встраиваемый или встроенный CSS:** ![high] Избегайте использования встраиваемого или встроенного CSS внутри вашего `<body>` (Недействительно для HTTP/2)

    *Почему:*
    > Одна из первых причин — это просто хорошая практика **отделять содержимое от дизайна**. Это также способствует более удобному коду и поддерживает доступность вашего сайта. Что касается производительности — это уменьшает размер файлов ваших HTML-страниц и время загрузки.

    *Как:*
    > Всегда используйте внешние таблицы стилей или встраивайте CSS в ваш `<head>` (и следуйте другим правилам производительности CSS)

    * 📖 [Соблюдение передовых практик CSS: избегайте встроенных стилей CSS](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Анализ сложности таблиц стилей:** ![high] Анализ таблиц стилей может помочь вам указать на проблемы, избыточный код и дублирования CSS-селекторов.

    *Почему:*
    > Иногда у вас может быть избыточный код или ошибки проверки в вашем CSS, анализ CSS-файлов и устранение этих трудностей может помочь вам ускорить CSS-файлы (потому что ваш браузер будет загружать их быстрее)

    *Как:*
    > Ваш CSS должен быть организован, использование препроцессора CSS может помочь в этом. Некоторые онлайн-инструменты, перечисленные ниже, также помогут вам проанализировать и исправить ваш код.

    * 🛠 [TestMyCSS | Оптимизация и проверка производительности CSS](http://www.testmycss.com/)
    * 📖 [Статистика CSS](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: Анализатор сложности CSS-селекторов и производительности](https://github.com/macbre/analyze-css)

**[⬆ вернуться в начало](#Содержание)**

## Шрифты

![fonts]

* 📖 [Книга от издательства «A Book Apart» — «Руководство по веб-шрифтам»](https://abookapart.com/products/webfont-handbook)

- [ ] **Форматы шрифтов:** ![medium] Вы используете формат WOFF2 в своём веб-проекте или приложении.

    *Почему:*
    > Согласно Google, формат сжатия веб-шрифта WFF 2.0 обеспечивает в среднем прирост на 30% по сравнению с WOFF 1.0. Поэтому лучше использовать WOFF 2.0, а WOFF 1.0 в качестве фолбэка и TTF.

    *Как:*
    > Проверьте перед покупкой нового шрифта, что он доступен в формате WOFF2. Если вы используете бесплатный шрифт, вы всегда можете использовать Font Squirrel для создания всех необходимых вам форматов шрифтов.

    * 📖 [WOFF 2.0 – Узнайте больше о новом поколении веб-шрифтов и сконвертируйте TTF в WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Font Squirrel - Создайте собственный набор шрифтов с помощью @font-face](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Генерация иконочного шрифта в формате SVG, PDF & PNG](https://icomoon.io/app/)
    * 📖 [Использование @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Используйте `preconnect` для быстрой загрузки ваших шрифтов:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Зачем:*
    > Когда вы пришли на сайт, ваше устройство должно узнать, где находится ваш сайт, и с каким сервером ему нужно подключиться. Ваш браузер должен связаться с DNS-сервером и дождаться завершения проверки перед получением ресурса (шрифты, файлы CSS...).

    *Почему:*
    > ⁃ Перед использованием предварительной загрузки (prefetch) ваших веб-шрифтов, воспользуйтесь webpagetest для оценки вашего веб-сайта. <br>
    ⁃ Ищите DNS-запросы с сине-зелёным цветом и обратите внимание на запрашиваемый хост. <br>
    ⁃ Предварительно загружаемые шрифты поместите в `<head>`.

    * 📖 [Быстрые Google-шрифты с помощью Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Сделайте ваш сайт быстрее с помощью подсказок Preconnect | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Окончательное руководство по подсказкам браузера: Preload, Prefetch и Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/) ([🇷🇺 перевод](https://webformyself.com/okonchatelnoe-rukovodstvo-po-podskazkam-v-brauzere-preload-prefetch-i-preconnect/))
    * 📖 [Всеобъемлющее руководство по стратегиям загрузки шрифтов — zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)

- [ ] **Размер веб-шрифта:** ![medium] Размеры веб-шрифта не должны превышать 300 Кб (со всеми вариантами)

 * 📖 [Байты шрифтов - Размер страницы](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Предотвратите использование Flash или невидимого текста:** ![medium] Избегайте использования прозрачного текста до загрузки веб-шрифта

 * 📖 [`font-display` для широких масс](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: Будущее отрисовки шрифтов в вебе](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ вернуться в начало](#Содержание)**

## Изображения

![images]

 * 📖 [Байты изображений в 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Оптимизация изображений:** ![high] Ваши изображения оптимизированы, сжаты без прямого воздействия на конечного пользователя.

    *Зачем:*
    > Оптимизированные изображения загружаются быстрее в вашем браузере и потребляют меньше данных.

    *Как:*
    > ⁃ Попробуйте использовать эффекты CSS3, когда это возможно (вместо небольшого изображения) <br>
    ⁃ Когда это возможно, используйте шрифты вместо текста, закодированного в ваших изображениях <br>
    ⁃ Используйте SVG <br>
    ⁃ Используйте инструмент и укажите уровень сжатия ниже 85.

    * 📖 [Оптимизация изображений | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 🛠 [TinyJPG – Сжатие JPEG-изображений разумно](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Онлайн-оптимизирование изображений](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - Оптимизация и сжатие JPEG-фотографий и PNG-изображений](https://compressor.io/compress)
    * 🛠 [Cloudinary - Инструмент анализа изображений](https://webspeedtest.cloudinary.com)
    * 🛠 [SVGOMG - Оптимизация векторных графических файлов SVG](https://jakearchibald.github.io/svgomg/)

* [ ] **Формат изображений:** ![high] Выберите формат изображения должным образом.

    *Зачем:*
    > Чтобы гарантировать, что ваши изображения не замедлят ваш сайт, выберите нужный формат

    *Почему:*
    > ⁃ Используйте [Lighthouse](https://developers.google.com/web/tools/lighthouse/) для определения того, какие изображения в конечном счёте могут использовать **форматы нового поколения** (такие как JPEG 2000m JPEG XR или WebP) <br>
    ⁃ Сравните различные форматы, иногда использование PNG8 лучше, чем PNG16, иногда это не так.

    * 📖 [Обслуживание изображений в форматах нового поколения | Tools for Web Developers | Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [Какой правильный формат изображения для сайта? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - Явный победитель — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-бит против 16-бит - Какую цветную глубину вы должны использовать и почему это имеет значение - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Используйте векторное изображение против растровых:** ![medium] Prefer using vector image rather than bitmap images (when possible).

    *Зачем:*
    > Векторные изображения (SVG), как правило, являются меньше, чем изображения, и SVG адаптивные и масштабируются. Эти изображения могут быть анимированы и изменены через CSS.

* [ ] **Размеры изображений:** ![medium] Установите атрибуты `width` и `height` на элемент `<img>`, если окончательное отрисованное изображение известно.

    *Зачем:*
    > Если заданы высота и ширина, пространство, необходимое для изображения, сохраняется при загрузке страницы. Однако без этих атрибутов браузер не знает размер изображения и не может зарезервировать для него подходящее пространство. Эффект будет заключаться в том, что раскладка страницы изменится во время загрузки (при загрузке изображений).

* [ ] **Избегайте использование изображений в формате Base64:** ![medium] Иногда вы можете преобразовать крошечные изображения в base64, но на самом деле это не лучшая практика.

    * 📖 [Кодирование и производительность Base64, первая и вторая часть от Гарри Робертс (Harry Roberts)](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [Более пристальный взгляд на производительность изображения Base64 – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [Когда base64 кодирует изображения (а когда их нет) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
    * 📖 [Base64 кодирует изображения для более быстрых страниц | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Ленивая загрузка:** ![medium] Изображения вне текущей области страницы загружены лениво (Фолбэк с noscript всегда предоставлен).

    *Зачем:*
    > Это улучшит время ответа текущей страницы, а затем предотвратит загрузку ненужных изображений, которые пользователю могут не понадобиться.

    *Как:*
    > ⁃ Используйте [Lighthouse](https://developers.google.com/web/tools/lighthouse/) для определения сколько **изображений находятся вне экрана**. <br>
    ⁃ Используйте плагин JavaScript из списка ниже для ленивой загрузки ваших изображений. Убедитесь, что вы настроили ленивую загрузку только изображений, находящихся вне экрана <br>
    ⁃ Также убедитесь, что лениво загружаемые изображения отображаются при наведении курсора или при других пользовательских действиях.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Ленивая загрузка изображений и видео | Основы Web | Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 блестящих способов ленивой загрузки изображений для быстрой загрузки страницы - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Адаптивные изображения:** ![medium] Обеспечьте отображение изображений, близких к размеру вашего дисплея.

    *Зачем:*
    > Маленьким устройствам не нужны изображения больше, чем их вьюпорт. Рекомендуется иметь несколько версий одного изображения разных размеров.

    *Как:*
    > ⁃ Создавайте разные размеры изображений для целевых устройств <br>
    ⁃ Используйте `srcset` и `picture` для доставки нескольких вариантов каждого изображения.

     * 📖 [Адаптивные изображения - Изучение веб-разработки | MDN](https://developer.mozilla.org/ru/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ вернуться в начало](#Содержание)**

## JavaScript

![javascript]

- [ ] **Минифицикация JS:** ![high] Все файлы JavaScript минифицированы, комментарии, пробелы и новые строки удалены из производственных файлов *(все ещё действительно при использовании HTTP/2)*.

    *Зачем:*
    > Удаление всех ненужных пробелов, комментариев и переводов строк уменьшит размер ваших файлов JavaScript и ускорит загрузку страниц вашего сайта и, очевидно, облегчит загрузку для вашего пользователя.

    *Как:*
    > ⁃ Используйте инструменты, перечисленные ниже, чтобы автоматически минифицировать ваши файлы до или во время сборки или деплоя.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Онлайн-сжатие JavaScript](http://refresh-sf.com)
    * 📖 [Короткое чтение: Чем отличается HTTP/2? Должны ли мы все ещё минифицировать и объединять?](https://scaleyourcode.com/blog/article/28)

* [ ] **Нет JavaScript внутри:** ![medium] *(Только для сайта)* Избегайте наличия нескольких блоков кода с JavaScript, встроенных в середину страницы. Перегруппируйте свой JavaScript-код внутри внешних файлов или в конечном итоге в `<head>` или в конце вашей страницы (до `</body>`).

    *Зачем:*
    > Размещение встраиваемого кода JavaScript непосредственно в ваш `<body>` может замедлить вашу страницу, потому что он загружается, когда DOM строится. Лучший вариант — использовать внешние файлы с `async` или `defer`, чтобы избежать блокировки DOM. Другой вариант — разместить некоторые скрипты внутри `<head>`. В большинстве случаев это код аналитики или небольшой скрипт, который необходимо загрузить до того, как DOM начнёт обрабатываться.

    *Как:*
    > Убедитесь, что все ваши файлы загружены с помощью `async` или `defer` и разумно определяют код, который вам нужно загрузить в `<head>`.

     * 📖 [11 советов по оптимизации JavaScript и повышению скорости загрузки сайта](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Неблокирующий JavaScript:** ![high] Файлы JavaScript загружаются асинхронно, используя `async` или отложено с использованием атрибута `defer`.

    ```html
    <!-- Атрибут defer  -->
    <script defer src="foo.js"></script>

    <!-- Атрибут async -->
    <script async src="foo.js"></script>
    ```

    *Зачем:*
    > JavaScript блокирует нормальный синтаксический анализ HTML-документа, поэтому, когда парсер доходит до тега `<script>` (особенно внутри `<head>`), он перестаёт извлекать и запускать его. Добавление `async` или `defer` настоятельно рекомендуется, если ваши скрипты размещены в верхней части страницы, менее полезно, если находятся перед тегом `</ body>`. Но хорошая практика всегда использовать эти атрибуты, чтобы избежать каких-либо проблем с производительностью.

    *Как:*
    > ⁃ Добавьте `async` (если скрипт не полагается на другие скрипты) или `defer` (если скрипт опирается на асинхронный скрипт или полагается на него) в качестве атрибута вашего тега скрипта. <br>
    ⁃ Если у вас небольшие скрипты, возможно, используйте встроенное подключение скрипта выше подключения асинхронных скриптов.

    * 📖 [Удалить блокирующий отрисовку JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Отложить загрузку JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **JS-библиотеки оптимизированы и обновлены:** ![medium] Все библиотеки JavaScript, используемые в вашем проекте, необходимы (желательно использовать обычный JavaScript для простого функционала), обновлены до последней версии и не перегружают ваш JavaScript ненужными методами.

    *Зачем:*
    > В большинстве случаев новые версии поставляются с исправлением оптимизации и безопасности. Вам следует использовать наиболее оптимизированный код для ускорения проекта и обеспечить, чтобы вы не замедляли ваш сайт или приложение без использования устаревшего плагина.

    *Как:*
    > Если ваш пакет использует NPM-пакеты, [npm-check](https://www.npmjs.com/package/npm-check) — довольно интересная утилита для обновления ваших библиотек.

    * 📖 [Вам может не понадобиться jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Обычный JavaScript для разработки мощных веб-приложений](https://plainjs.com/)

- [ ] **Проверьте ограничение размера зависимостей:** ![low] Обеспечьте использование разумных внешних библиотек, большую часть времени вы можете использовать более лёгкую библиотеку для одной и той же функциональности.

    *Зачем:*
    > У вас может возникнуть соблазн использовать один из 745 000 пакетов, которые вы можете найти на [npm](https://www.npmjs.com/), но вам нужно выбрать лучший пакет для ваших нужд. Например, MomentJS - это потрясающая библиотека, но с множеством методов, которые вы никогда, возможно, не будете использовать, поэтому был создан Day.js. Почувствуйте разницу: 2 Кб против 16,4 Кб для Moment.

    *Как:*
    > Всегда сравнивайте и выбирайте лучшую и более лёгкую библиотеку для своих нужд. Вы также можете использовать такие инструменты, как [npm trend](http://www.npmtrends.com/), чтобы сравнить количество загрузок пакетов NPM или [Bundlephobia](https://bundlephobia.com/), чтобы узнать размер ваших зависимостей.

    * 🛠 [ai/size-limit: Предотвращение раздувание JS-библиотек. Если вы случайно добавляете большую зависимость, Size Limit выдаст ошибку.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Ограничение размера: Сделайте веб легче — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **Профилирование JavaScript:** ![medium] Проверьте проблемы с производительностью в ваших JavaScript-файлах (и CSS тоже).

    *Зачем:*
    > Сложность JavaScript может замедлить производительность во время выполнения. Идентификация этих возможных проблем имеет важное значение для обеспечения максимально плавного пользователем вашего проекта.

    *Как:*
    > Используйте инструмент «Временная шкала» в инструменте разработчика Chrome для оценки событий сценариев и найдите тот, который может занять слишком много времени.

    * 📖 [Ускорить выполнение JavaScript | Tools for Web Developers | Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [Профилирование JavaScript с помощью инструментов разработчика Chrome — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [Как записывать снимки кучи | Tools for Web Developers | Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Глава 22 - Профилирование фронтенда - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)

**[⬆ вернуться в начало](#Содержание)**

## Сервер

![server-side]

- [ ] **Размер страницы < 1500 Кб (в идеале < 500 Кб):** ![high] Уменьшите размер страницы, а также ресурсов на столько, сколько сможете.

    *Почему:*
    > В идеале вы должны пытаться ориентироваться к < 500 Кб, но состояние веба показывает, что медиана килобайтов составляет около 1500 Кб (даже на мобильных устройствах). В зависимости от ваших целевых пользователей, подключений, устройств важно уменьшить максимально возможное количество окончательных килобайтов, чтобы иметь лучшее пользовательское взаимодействие, насколько это возможно.

    *Как:*
    > Все правила внутри чек-листа производительности фронтенда помогут вам максимально сократить размер ресурсов и кода.

    * 📖 [Размер страницы](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [Сколько стоит посещение моего сайта?](https://whatdoesmysitecost.com/)
    * 🛠 [Измерить полный размер страницы в инструментах разработчика Chrome - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Время загрузки страницы < 3 секунд:** ![high] Сократите максимально возможное время загрузки страницы для того, чтобы быстро доставить контент своим пользователям.

    *Почему:*
    > Чем быстрее сайт или приложение, тем меньше вероятность увеличения отказов, другими словами у вас меньше шансов потерять вашего пользователя или будущего клиента. Достаточно исследований по этому вопросу доказывают это.

    *Как:*
    > Использовать онлайн-инструмент, такой как [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) или [WebPageTest](https://www.webpagetest.org/) для анализа что может замедлить работу и использовать чек-лист производительности фронтенда, чтобы улучшить время загрузки.

    * 🛠 [Сравните скорость вашего мобильного сайта](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Проверьте скорость и производительность вашего мобильного сайта - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Среднее время загрузки для 2018 - Как вы сравниваете? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Время загрузки первого байта < 1.3 секунды:** ![high] Сократите на столько, сколько сможете время, когда ваш браузер ожидает, прежде чем получать данные.

    * 📖 [Что такое TTFB в инструментах разработчика и что с этим делать?](https://scaleyourcode.com/blog/article/27)
    * 📖 [Мониторинг ваших серверов с бесплатным инструментами — это легко](https://scaleyourcode.com/blog/article/7)
    * 📖 [Время загрузки первого байта (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Инструмент тестирования глобальной латентности](https://latency.apex.sh)

* [ ] **Размер кук:** ![medium] Если вы используете куки, то проверьте, что каждый файл кук не превышает 4096 байт, а ваше доменное имя содержит не более 20 файлов кук.

    *Почему:*
    > Куки передаются в HTTP-заголовках между серверами и браузерами. Важно максимально уменьшить размер файлов кук, чтобы минимизировать воздействие на время ответа пользователя.

    *Как:*
    > Исключить ненужные куки

    * 📖 [Спецификация Cookie: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Куки HTTP](https://developer.mozilla.org/ru/docs/Web/HTTP/Cookies)
    * 🛠 [Ограничения кук в браузере](http://browsercookielimits.squawky.net/)
    * 📖 [Производительность сайта: Куки не такие замечательные на вкус - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Передовые практики по веб-производительности от Google #3: Минимизировать накладные расходы запроса - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Минимизация HTTP-запросов:** ![high] Обязательно убедитесь, что каждый запрошенный файл имеет важное значение для вашего веб-сайта или приложения.
 * 📖 [Объединить внешние CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Объединить внешний JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Используйте CDN для доставки ваших ресурсов:** ![medium] Используйте CDN для быстрой доставки вашего содержимого по всему миру.

 * 📖 [10 советов по оптимизации производительности CDN - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [Кеширование HTTP | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Обслуживайте файлы из одинакового протокола:** ![high] Избегайте использования вашего сайта с помощью HTTPS и отдачи входящих файлов по протоколу HTTP.

- [ ] **Обрабатывать доступные файлы:** ![high] Избегайте запросов с недоступными файлами (404).
  * 📖 [Как избежать плохих запросов](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **HTTP-заголовки кеширования установлены корректно:** ![high] Установите HTTP-заголовки, чтобы избежать дорогостоящего числа круговых задержек (roundtrips) между браузером и сервером.
 * 📖 [Использование cache-control для кеширования в браузере](https://varvy.com/pagespeed/cache-control.html)

- [ ] **Сжатие GZIP / Brotli включено:** ![high]

 * 🛠 [Проверьте работу сжатия GZIP](https://checkgzipcompression.com/)
 * 🛠 [Проверьте работы сжатия Brotli](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ вернуться в начало](#Содержание)**

---
## Производительность JS-фреймворков

### React

 * 📖 [Оптимизация производительности - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [Манипуляция изображениями React | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Отладка производительности React с версии 16 и инструментов разработчика Chrome](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

### Vue

## Производительность и CMS

### WordPress

#### Статьи

  * 📖 [19 советов по ускорению производительности WordPress (обновлено)](https://www.wpbeginner.com/wordpress-performance-speed/)
  * 📖 [Ускорьте свой WordPress - как сохранять изображения, оптимизированные для интернета](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)
  
#### Рекомендуемые плагины

---

## Переводы

Чек-лист производительности фронтенда хочет быть доступным и на других языках! Не стесняйтесь принять участие в переводе!

* 🇵🇹 Португальский: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Китайский: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇫🇷 Французский: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
 * 🇰🇷 Корейский: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)

## Участие в проекте

**Откройте ишью или пулреквест для предлложения изменений или добавлений.**

## Поддержка

Если у вас есть какие-либо вопросы или предложения, не стесняйтесь использовать Gitter или Twitter:

* [Чат на Gitter](https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Автор

**Сделано с ❤️ [Дэвидом Диазом (David Dias)](https://github.com/thedaviddias) в [@influitive](https://influitive.com/) 🇨🇦**

## Контрибьюторы

Этот проект существует благодаря тем людям, которые вносят свой вклад. [[Принять участие]](.github/CONTRIBUTING.md).

## License

[MIT](LICENCE)

Все иконки предоставлены [Icons8](https://icons8.com/)

**[⬆ вернуться в начало](#Содержание)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
