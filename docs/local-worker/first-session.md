# Первая сессия на воркере HPLVE-PC

Проверка, что сессия видит репозиторий и каталоги Windows. Секреты не открывать и не цитировать: в ответе только «есть» или «нет».

1. Клон лежит внутри Linux-диска WSL, в `~/projects/local-agent`, а не в `/mnt/c/...`.
2. `git remote -v` указывает на `https://github.com/hplve777-mat-x/local-agent.git`.
3. `git status` выполняется в этом клоне. Результат команды записать в ответ.
4. Проверить наличие путей воркера, не читая содержимое:
   - `~/projects/local-agent`
   - `/mnt/c/DISK - D`
   - `C:\DISK - D\AI SYSTEM\cursor-agent\` (`/mnt/c/DISK - D/AI SYSTEM/cursor-agent`)
   - `/mnt/c/Users/HPLVE/.claude`
   - `/mnt/c/Users/HPLVE/.codex` и файл `/mnt/c/Users/HPLVE/.codex/auth.json`
   - `/mnt/c/Users/HPLVE/.agents`
   - `/mnt/c/Users/HPLVE/AppData/Local/Claude`
   - `/mnt/c/Users/HPLVE/AppData/Local/Claude-3p`
5. Ничего не создавать, не удалять и не переименовывать за пределами клона и `C:\DISK - D\AI SYSTEM\cursor-agent\`.
