GitBash - оболочка эмулирующая взаимодействие с программой git как это реализовано на Linux.

Команды для работы в оболочке:

pwd — выводит текущий каталог (Print Working Directory).
ls — отображает список файлов и папок в текущей директории.
ls -a — показывает скрытые файлы.
ls -l — отображает детальный список файлов.
cd <путь> — смена текущей директории (Change Directory).
cd .. — переход на уровень выше.
cd ~ — переход в домашнюю директорию.
mkdir <имя> — создание новой директории.
touch <имя_файла> — создание нового пустого файла.
rm <имя_файла> — удаление файла.
rm -r <имя_папки> — рекурсивное удаление папки и всех её содержимых.

git init — инициализация нового локального репозитория.
git clone <url> — клонирование удалённого репозитория на локальный компьютер.
git status — отображает состояние репозитория (изменённые, добавленные, удалённые файлы).
git add <имя_файла> — добавляет изменения файла в индекс (стейджинг).
git add . — добавляет все изменённые файлы в индекс.
git commit -m "сообщение" — создаёт коммит с описанием изменений.
git push origin <ветка> — отправляет изменения на удалённый репозиторий (GitHub, GitLab).
git pull origin <ветка> — получает изменения с удалённого репозитория и сливает их с локальными.

ssh-keygen -t rsa -b 4096 -C "your_email@example.com" — создание SSH-ключа.
ssh-add ~/.ssh/id_rsa — добавление SSH-ключа в агент для автоматической аутентификации.
ssh -T git@github.com — проверка подключения к GitHub по SSH.
