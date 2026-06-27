# dzen-feed

RSS-лента для канала Дзена [`dzen.ru/yaniktoim`](https://dzen.ru/yaniktoim): статьи корпуса
**yaniktoim**, преобразованные из ZML3 в Dzen-HTML.

- Публичный URL ленты: `https://imyavel.github.io/dzen-feed/feed.xml`
- Лента **генерируется** конвейером `dzenru` (`build_feed.mjs`), вручную `feed.xml` не правится.
- Контент тела статьи лежит в `<content:encoded>`; правка статьи руками в Студии Дзена навсегда
  отцепляет её от ленты, а обновления из ленты применяются лишь ≤7 дней после первой загрузки.

Подробности и правила преобразования — в проекте `dzenru` (`project.md`, §3).
