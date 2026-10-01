# Воркер на Windows

Имя машины в Cursor: `HPLVE-PC`.

На Windows `agent worker start` для CLI `2026.09.28-64d2043` не стартует: модуль `better-sqlite3` собран под Node ABI 127, встроенный Node этой сборки сообщает ABI 137. Пока это так, рабочий запуск описан в `wsl-workaround.md`.

Каталог версий CLI на этой машине: `%LOCALAPPDATA%\cursor-agent\versions\2026.09.28-64d2043`.
