# Что я забываю, по github
## Копирую локальный репозиторий на github
1. В каталоге с нужными файлами создаю репозиторий.
        `# git init`
2.  Для всех файлов делаю коммит<br>
         # git add .<br>
         # commit -m "my first commit"
3. Создаю пустой репозиторий на **github**, REAFME.md лицензию и прочее не создаю! Стараюсь, что бы репозиторий был совсем пустым!
4. Связываю локальный и репозиторий на **github**
        `git remote add <repository_name> link`
        `<repository_name>` - имя репозитория, чаще всего *origin*
        `link` - ссылка на репозиторий на github<br>
К примеру:<br>
    #git remote add origin https://github.com/Olegfromr/for_github.git
    #git branch -M main     //переименовываю ветку в ветку *main* весь затык именно в этом!!!
    #git push -u origin main    //делаю push на *github* после этого смогу делать просто git push
// Когда надо ввести имя и пароль ввожу своё имя: **Olegfromr** и НЕ пароль от github! А ТОКЕН!!!

### пара-ра-ра-рам! Всё!!!

