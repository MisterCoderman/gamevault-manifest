🟦 GameVault — Open Manifest

Fixing issues with games that store save files inside the game’s own directory

Many older or poorly adapted games store their save data directly in the installation folder.
This breaks the proper operation of the GameVault client: cloud saves fail to load, backups behave inconsistently, and synchronization may stop working entirely.

The GameVault Manifest was created to solve this problem.
It adds custom rules for such games, redirecting their save files to the correct directories so the client can track them properly.

If your game stores its saves “in the wrong place,” send me the path to its save folder.
I’ll add support to the manifest and improve compatibility.

✉️ How to Help

Please provide the following information:

Game title

Path to the save folder (as it appears in the file system)

A screenshot of the game page in GameVault

📌 Requirements

The game folder must be located on any local drive.

Supported directories include anything like:

D:\Games\GameVault

E:\GameVault

F:\Games

C:\Games\GameVault

The main requirement: games must be stored inside a Games or GameVault folder located on any local partition.
<hr>
🟦 GameVault — Открытый Манифест

Исправление проблем с играми, которые хранят сохранения внутри папки с самой игрой

Многие старые и плохо адаптированные игры сохраняют прогресс прямо в каталоге, где установлены.
Это ломает корректную работу GameVault-клиента: облачные сохранения не подгружаются, резервирование работает нестабильно, а синхронизация может полностью пропадать.

GameVault Manifest создан для решения этой проблемы.
Он добавляет индивидуальные правила для таких игр, перенаправляя сохранения в правильные каталоги, чтобы клиент мог корректно их отслеживать.

Если ваша игра сохраняет прогресс "не туда" — присылайте путь до её сохранений.
Я добавлю поддержку в манифест и улучшу совместимость.

✉️ Как помочь

Отправляйте следующую информацию:

название игры

путь к папке сохранений (как в файловой системе)

Скриншот страницы игры в GameVault

📌 Требования

Папка с играми должна находиться на любом локальном диске

Поддерживаются каталоги, расположенные на любом диске, например:

D:\Games\GameVault

E:\GameVault

F:\Games

C:\Games\GameVault

Главное требование — игры должны находиться в папке Games или GameVault, расположенной на любом локальном разделе.
