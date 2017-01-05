# Русский перевод игры Salt 1.9.2

Перевод состоит из двух типов файлов.
* Файлы текста. Директория "russian/text"
* Файлы скриптов. Директория "russian/scripts"

Установка происходит одинаково, Вы можете сразу заменять оба типа файлов.
**Обратите внимание, перевод текста можно использовать с разными версиями игры.**
Перевод скриптов для каждой версии свой! **Установка скриптов не на ту версию приведет к невозможности запуска игры!**

### Установка перевода.
Для замены файлов игры используйте [UnityEX](http://www.zoneofgames.ru/forum/index.php?showtopic=36240).

1. Папки из директории "russian/text" (или\и russian/scripts) скопируйте в "Salt/Salt_Data/Unity_Assets_Files/"
2. Запустите UnityEX и нажмите "Открыть архив Unity"
3. Выбираете файл "Salt/Salt_Data/sharedassets1.assets"
4. Нажмите "Запаковать все файлы" и дождитесь завершения.
5. Повторите пункты 3 и 4 для остальных файлов.
6. Наслаждайтесь игрой.

### Правка перевода.
## Правка тестовых файлов
Берёте не переведенный оригинальный файл из original, переводите его и помещяете в russian.

1. Файл перевода должен иметь кодировку UTF-8 без BOM.
2. Две пустые строки в тексте означают переход на следующую страницу книги.
3. При переводе скриптов учтите, размер переведенного файла должен совпадать с размером оригинала. (txt файлы это не затрагивает)

* **sharedassets1** текст всех книг и диалогов.
* **sharedassets2** текст помощи и некоторых квестов.
* **level2** текст GUI и квестового журнала.

### Внесение изменений в репозиторий перевода.
1. Вы сами вносите изменения в git. (Требуется аккаунт на github).
2. Вы можете прислать мне архив с вашим переводом на snake.sel@gmail.com и я сам залью перевод в git.

