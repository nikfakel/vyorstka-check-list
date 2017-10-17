# vyorstka-check-list
Чек лист по  верстке
1. Всегда делай так, будто с твоими исходниками будет работать огромный злой уголовник, ненавидящий долго разбираться в чужом коде и знающий твой домашний адрес
2. Проверяй то что ты делаешь
 - кроссбраузерно - в хроме/фаерфоксе/сафари/ие (требования к ИЕ будут в тз) и в мобильных браузерах
 - адаптивно - все разрешения от 320 до бесконечности, портрет/лэндскейп, учитывай, что поворот экрана может сломать верстку и, особенно, скрипты (вешай события на resize())
 - оптимально - Google Page Speed в помощь
3. Используй современные технологии
 - GIT - для всего, кроме совсем маленьких проектов
 - gulp\webpack - либо можешь использовать наш готовый шаблон галп, либо свой, но без хардкорных плагинов (либо описывай зачем они там нужны), с хорошей структурой.
 - выбирай scss, а не sass, 
 - flex'ы, а не флоаты (нет, гриды не надо)
 - mobile first, а не desktop first,
 - BEM, а не block-12-left (если умеешь что то другое, кроме БЕМа - используй, но только грамотно и чтобы другой разработчик мог это понять. Если не умеешь, то https://ru.bem.info/methodology/quick-start/)
 - Но все в меру - проверяй можно ли использовать что-то на caniuse.com

4. Всегда оптимизируй картинки. Для графики - старый добрый jpg, (png для полупрозрачных картинок), для элементов оформления - svg (в крайнем случае png). Для ретины srcset или другие инструменты. Картинки для оформления всегда делай бэкграундом или шрифтом или еще как-нибудь, но не засоряй ими html.
5. Используй возможности сборщика для удобной работы с кэшем - либо версии css/js, либо хеши на все файлы (это есть в нашем сборщике)
6. Учитывай, что дизайнер часто пишет рыбу - а значит текст и блоки, в которых он содержится, могут измениться по ширине, количество элементов в списке может увеличиться, а некоторые могут вовсе исчезнуть. Проведи тест на одиннадцатиклассницу (https://habrahabr.ru/company/2gis/blog/246831/)
7. Делай семантично! 2к17 как никак. 
8. Позаботься о шрифтах - подключай сначала с гугла, если нет, то используй фонтгенератор (fontsquirrel например). Идеально, если знаешь больше одного способа подключить шрифты. Если разных шрифтов больше трех-четырех - сообщи об этом всем, чаще всего так быть не должно. 
9. Добавь в закладки - https://nicothin.github.io/criteria-of-quality-frontend/index-0.0.3.html и https://epixx.github.io/code-guide/#html - тут детальный список всего, что нужно проверить
10. Нормально делай - нормально будет. В сложных ситуациях спрашивай дизайнера, прожект-менеджера (пусть хоть чем то полезным займется ;), других фронтендеров. Обсуждение проблемы поможет сэкономить много времени.



Чеклист для запуска сайта - https://www.cubeline.ru/blog/posts/chek-list-45-punktov-dlya-proverki-sajta-pered-zapuskom.html
