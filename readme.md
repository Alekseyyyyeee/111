# Основные команды Git.

- "git -v" или "git --version" - просмотр текущей версии Git
- "git -h" или "git --help" - просмотр основных команд

- "git log" - показывает журнал изменений

## Команды для работы с репозиторием (хранилищем файлов)
 - "git init" -создаёт репозиторий
 
    - "git add название файла" - добавляет файл в репозиторй

    - "git commit -m название_коммита" - записывает изменения в репозиторий

 ## Команды для рабочего дерева
- "git status" - показыват статус рабочего дерева

    - "git switch" - переключает ветки

    - "git merge название ветки" - вливает выбранную ветку в ту, на который мы находмся на данный момент
    
    - "git checkout номер коммита"; "git checkout название ветки" - открывает одну из сохранённых веток

    - "git checkout master" - переключает на основную рабочую ветку

