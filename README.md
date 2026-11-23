# WOOF Observatory

## О проекте / токене

WOOF — токен сети TON, связанный с экосистемой Lost Dogs. В официальном канале проекта WOOF упоминается как токен для кастомизации Lost Dogs NFT в Bazaar и как награда в игре Lost Dogs: Signals. Это описание применения токена по заявлениям проекта.

Контракт: `EQBKyWOOFXlJpzYO8e44JG6uf6L3v4bYbbBBnKj9OHwBXjzm`, точность: 9.

Источники, проверены 23.11.2026:

- https://tonapi.io/v2/jettons/EQBKyWOOFXlJpzYO8e44JG6uf6L3v4bYbbBBnKj9OHwBXjzm
- https://t.me/s/lostdogscoeng

Каналы: [RU](https://t.me/lostdogscoru) · [EN](https://t.me/lostdogscoeng).

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
The bundled snapshot contains verified WOOF data; section freshness and incomplete-source states are shown in the interface.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Статус запуска

Исходники созданы из чистой основы 1.3.0. Workflow обновления запускается при изменении исходников и вручную через GitHub Actions. Подключение к действующему Cloudflare-планировщику раз в 30 минут не подтверждено. Публикация в TON Storage / Resistance Tools не выполнялась.

Проверены 17 Python-тестов и 15 JavaScript-тестов, идентичность токена и сборка автономного HTML. Визуальная проверка мобильной и настольной вёрстки остаётся незавершённой: локальный Chromium не запустился, а доступный браузер заблокировал открытие локального файла.
