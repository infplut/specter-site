# Specter Site

Статический сайт-витрина. Никакого backend: ключи и HWID остаются на Cloudflare Worker.

## Перед публикацией

Ссылка на покупку уже стоит:

```text
https://funpay.com/users/7776085/
```

Она используется в шапке, в первом экране и в блоке «Купить ключ». Если профиль FunPay изменится — замени ссылку в `index.html`.

## GitHub Pages

1. Создай публичный репозиторий, например `specter-site`.
2. Загрузи в него все файлы из этой папки:
   - `index.html`
   - картинки `logo.png`, `esp.png`, `aimbot.png`, `silent-aim.png`, `player.png`, `world.png`, `players.png`, `configs.png`
   - `favicon.ico`
3. Открой **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`.
6. Нажми **Save**.
7. Через 1–2 минуты сайт будет тут:

```text
https://ТВОЙ-НИК.github.io/specter-site/
```

Если назвать репозиторий `ТВОЙ-НИК.github.io`, адрес будет:

```text
https://ТВОЙ-НИК.github.io/
```

## Важно

GitHub Pages может заблокировать сайт за тематику игровых читов. Если это критично, этот же набор файлов можно залить на Cloudflare Pages без изменений.

## Что менять

- `logo.png` — логотип.
- `*.png` — скриншоты.
- `index.html` — тексты, цены, ссылка на FunPay.
