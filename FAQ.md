# Underbloom — FAQ

=============================== РУССКИЙ ===============================

**Сколько стоит? Можно в коммерции?**
Бесплатно. Используй в любых треках, включая коммерческие, без отчислений.
Нельзя только продавать сам плагин — см. `LICENSE.txt`.

**Установил, но не вижу плагин в DAW.**
Папка `Underbloom.vst3` должна лежать в `C:\Program Files\Common Files\VST3\`
(инсталлятор кладёт туда автоматически, или выбери путь вручную).
После установки пересканируй плагины и **полностью перезапусти** DAW.
`Rescan` без перезапуска не перезагрузит уже открытый экземпляр плагина.

**Как загрузить сэмпл?**
Перетащи файл прямо на плагин (drag-and-drop) или нажми кнопку загрузки.
Поддерживаются WAV, AIFF, FLAC, OGG, MP3, а также видео (MP4, M4A, MOV, AVI —
берётся только аудиодорожка).

**Что делают режимы?**
- **Стебель** — базовый сэмплер с плавным лупом.
- **Удержание** — гранулярный sustain: звук «зависает» облаком зёрен.
- **Отражение** — луп / реверс / ping-pong с изменяемым темпом.
- **Сияние** — банк звенящих резонаторов на гармониках ноты (колокол, стекло).
- **Погружение** — тайм-стретч дрейф: playhead медленно блуждает в выбранной зоне.

**Как работают пресеты?**
В шапке плагина — бар `◀ имя ▶`. Стрелки листают пресеты, клик по имени
открывает меню: выбрать, сохранить свой или удалить пользовательский.
Пользовательские пресеты хранятся в `Documents\Underbloom\Presets\<Режим>\`.

**Что хранит пресет?**
Громкость, ADSR и 5 параметров текущего режима. Точки Корень/Старт/Конец
пресет не трогает — они остаются твоими.

**Мой сэмпл не звучит / звучит тихо.**
Убедись, что плагин получает MIDI-ноты (или нажми ноту в Standalone).
В режиме Сияние — подними параметр «Сияние» (dry/wet). В режиме Погружение —
«Поток».

**Есть версии для Mac / Linux?**
Пока только Windows 10/11 (64-bit): VST3 и Standalone.

**Поддерживает ли плагин MPE или полифонию?**
Базовая полифония есть. MPE не поддерживается.

=============================== ENGLISH ===============================

**Is it free? Can I use it commercially?**
Yes, freeware. Use it in any tracks, including commercial, with no royalties.
You just may not sell the plugin itself — see `LICENSE.txt`.

**I installed it but my DAW doesn't show it.**
The `Underbloom.vst3` folder must be in `C:\Program Files\Common Files\VST3\`
(the installer places it there automatically, or choose a custom path).
After installation, rescan plugins and **fully restart** your DAW.
Rescanning without a restart won't reload an already-open plugin instance.

**How do I load a sample?**
Drag and drop a file onto the plugin, or click the load button.
Supported: WAV, AIFF, FLAC, OGG, MP3, and video files (MP4, M4A, MOV, AVI —
audio track only is extracted).

**What do the modes do?**
- **Stem** — basic sampler with smooth loop crossfade.
- **Retain** — granular sustain: sound held as a cloud of grains.
- **Reflect** — loop / reverse / ping-pong with variable rate.
- **Radiate** — ringing resonator bank tuned to note harmonics (bell, glass).
- **Delve** — timestretched drift: playhead slowly wanders within a set zone.

**How do presets work?**
The `◀ name ▶` bar in the header. Arrows cycle through presets; click the name
for a menu: select, save your own, or delete a user preset.
User presets are stored in `Documents\Underbloom\Presets\<Mode>\`.

**What does a preset store?**
Volume, ADSR, and the 5 mode-specific parameters. Root/Start/End positions are
not touched — they stay as you set them.

**My sample doesn't sound / sounds quiet.**
Make sure the plugin is receiving MIDI notes (or press a note in Standalone).
In Radiate mode, raise the Radiate (dry/wet) knob. In Delve mode, raise Flow.

**Mac / Linux versions?**
Windows 10/11 (64-bit) only for now: VST3 and Standalone.

**Does it support MPE or polyphony?**
Basic polyphony is supported. MPE is not.

---
Contact: psychedelic.rain@gmail.com · https://www.psyrain.ru
