# Fuck UTM

Расширение для Chrome/Edge, которое **удаляет трекинг-параметры из URL до перехода на сайт** (например: `ysclid`, `gclid`, `fbclid`, `utm_*`, `utm_bitrix_id`, `etext` и т.д.).

---

## Установка

1. Переходим в страницу расширений:

* Для Chrome: `chrome://extensions/`
* Для Edge: `edge://extensions/`

2. Включаем **Режим разработчика** (Developer mode)

3. Нажимаем **«Загрузить распакованное»** (Load unpacked)

4. Указываем папку, где лежат `rules.json` и `manifest.json`

5. Включаем расширение и проверяем.

---

## Пример

Ссылка из:

```text
https://rt.pornhub.org/?ysclid=mm104gojst328258463
```

Превращается в:

```text
https://rt.pornhub.org/
```

---

## Что чистится

Расширение удаляет популярные метки вроде:

* `ysclid`, `yclid`
* `gclid`, `fbclid`, `msclkid`, `dclid`
* `utm_source`, `utm_medium`, `utm_campaign`, `utm_term`, `utm_content`, `utm_id`, `utm_name`, `utm_referrer`, `utm_bitrix_id`
* `etext`
* и другие (список в `rules.json`)

