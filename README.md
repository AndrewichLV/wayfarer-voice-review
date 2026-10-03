# Wayfarer — ревью озвучки

Сайт для тестировщиков русской озвучки [Wayfarer](https://www.curseforge.com/wow/addons/wayfarer-russian-voiceover)
(WoW Forever): https://andrewichlv.github.io/wayfarer-voice-review/

Тестировщик вводит ник и код приглашения (он в Discord Wayfarer), слушает реплики по одной и отмечает:
всё верно, есть ошибка (ударение, голос, обрезка, подача, текст) или пропустить. Каждую реплику проверяет
один человек: пока её кто-то слушает, другим она не выдаётся.

Звук — Opus 24 кбит/с (сжатая копия озвучки аддона), список реплик — `lines.json`, отметки хранятся в Supabase.
Тексты квестов — официальная русская локализация игры (© Blizzard Entertainment).
