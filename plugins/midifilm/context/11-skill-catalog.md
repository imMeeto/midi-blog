# Навыки MIDI FILM

Версия 1.1.0: 45 навыков content-producer и отдельный навык контекста бренда. В чате с подключённым плагином можно выбрать навык либо назвать его в сообщении. В Codex доступен явный вызов `$имя-навыка`, когда новая версия установлена.

- Сведения о Дмитрии и бренде — [`$midifilm-context`](../skills/midifilm-context/SKILL.md).
- Составная задача или выбор маршрута — [`$content-producer`](../skills/content-producer/SKILL.md).
- Конкретный формат — профильный навык из таблицы.

| Вызов | Назначение |
| --- | --- |
| [`$content-producer`](../skills/content-producer/SKILL.md) | Диспетчер |
| [`$cp-analytics`](../skills/cp-analytics/SKILL.md) | Разбор статистики одной площадки |
| [`$cp-analytics-cross`](../skills/cp-analytics-cross/SKILL.md) | Сводный отчёт по всем площадкам |
| [`$cp-app`](../skills/cp-app/SKILL.md) | Мобильное приложение |
| [`$cp-audience`](../skills/cp-audience/SKILL.md) | Аватары и распаковка аудитории |
| [`$cp-audit`](../skills/cp-audit/SKILL.md) | Аудит аккаунта |
| [`$cp-automation`](../skills/cp-automation/SKILL.md) | Автоматизация процессов |
| [`$cp-bot`](../skills/cp-bot/SKILL.md) | Автоворонка в боте |
| [`$cp-brand-setup`](../skills/cp-brand-setup/SKILL.md) | Профиль бренда |
| [`$cp-calendar`](../skills/cp-calendar/SKILL.md) | Производственный календарь и ритм |
| [`$cp-caption`](../skills/cp-caption/SKILL.md) | Подписи к постам |
| [`$cp-carousel`](../skills/cp-carousel/SKILL.md) | Карусели и галереи |
| [`$cp-carousel-render`](../skills/cp-carousel-render/SKILL.md) | Рендер слайдов HTML → PNG |
| [`$cp-client`](../skills/cp-client/SKILL.md) | Работа с клиентским брендом |
| [`$cp-clip`](../skills/cp-clip/SKILL.md) | Нарезка длинного материала на короткие ролики |
| [`$cp-collab`](../skills/cp-collab/SKILL.md) | Интеграции, посевы, работа с блогерами |
| [`$cp-community`](../skills/cp-community/SKILL.md) | Сообщество, негатив, кризис и отзывы |
| [`$cp-compliance`](../skills/cp-compliance/SKILL.md) | Правовой чек перед публикацией |
| [`$cp-content-plan`](../skills/cp-content-plan/SKILL.md) | Контент-план |
| [`$cp-cover`](../skills/cp-cover/SKILL.md) | Обложки и превью |
| [`$cp-design-system`](../skills/cp-design-system/SKILL.md) | Тема бренда |
| [`$cp-dzen`](../skills/cp-dzen/SKILL.md) | Контент для Дзена |
| [`$cp-email`](../skills/cp-email/SKILL.md) | Рассылки и прогревы |
| [`$cp-funnel`](../skills/cp-funnel/SKILL.md) | Воронка и конверсии |
| [`$cp-geo`](../skills/cp-geo/SKILL.md) | Видимость в ответах нейросетей |
| [`$cp-hook`](../skills/cp-hook/SKILL.md) | Генератор хуков |
| [`$cp-humanizer`](../skills/cp-humanizer/SKILL.md) | Снятие машинных следов |
| [`$cp-image-prompt`](../skills/cp-image-prompt/SKILL.md) | Генеративные картинки |
| [`$cp-landing`](../skills/cp-landing/SKILL.md) | Лендинг и посадочные страницы |
| [`$cp-lead-magnet`](../skills/cp-lead-magnet/SKILL.md) | Лид-магниты |
| [`$cp-offer`](../skills/cp-offer/SKILL.md) | Оффер и продающий текст |
| [`$cp-personal-brand`](../skills/cp-personal-brand/SKILL.md) | Позиционирование человека |
| [`$cp-platform-fit`](../skills/cp-platform-fit/SKILL.md) | Адаптация единицы контента под площадки |
| [`$cp-production`](../skills/cp-production/SKILL.md) | Съёмка, свет, звук, монтаж и субтитры |
| [`$cp-repurpose`](../skills/cp-repurpose/SKILL.md) | Переупаковка |
| [`$cp-script-long`](../skills/cp-script-long/SKILL.md) | Сценарий длинного видео |
| [`$cp-script-short`](../skills/cp-script-short/SKILL.md) | Сценарий короткого вертикального видео |
| [`$cp-seo`](../skills/cp-seo/SKILL.md) | Поиск: Яндекс и Google |
| [`$cp-stories`](../skills/cp-stories/SKILL.md) | Истории и вертикальные серии |
| [`$cp-telegram`](../skills/cp-telegram/SKILL.md) | Контент для Telegram |
| [`$cp-trends`](../skills/cp-trends/SKILL.md) | Тренды и форматы |
| [`$cp-video-score`](../skills/cp-video-score/SKILL.md) | Скоринг сценария до съёмки |
| [`$cp-vk`](../skills/cp-vk/SKILL.md) | Контент для ВКонтакте |
| [`$cp-voice`](../skills/cp-voice/SKILL.md) | Голос автора |
| [`$cp-web`](../skills/cp-web/SKILL.md) | Сайт технически |

## Примеры

- «Используй cp-script-short: сценарий на 60 секунд от моего лица про бота, которого я собрал».
- «Используй cp-content-plan: контент-план MIDI FILM с учётом 8 часов в неделю».
- «Используй cp-voice, затем cp-humanizer: перепиши этот текст моим голосом».
- «Используй content-producer: помоги собрать запуск блога из нескольких задач».

Профиль MIDI FILM и справочники включены в пакет. Доступ к исходному репозиторию для их чтения не нужен. Интеграции с внешними сервисами и автоматические публикации отдельно не подключаются установкой этих инструкций.
