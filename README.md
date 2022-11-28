# Что я забываю, по github
## Копирую локальный репозиторий на github
1. В каталоге с нужными файлами создаю репозиторий.
        `# git init`
2.  Для всех файлов делаю коммит<br>
         # git add .<br>
         # commit -m "my first commit"
3. Создаю пустой репозиторий на **github**, README.md лицензию и прочее не создаю! Стараюсь, что бы репозиторий был совсем пустым!
4. Связываю локальный и репозиторий на **github** <br>
        `git remote add <repository_name> link`<br>
        `<repository_name>` - имя репозитория, чаще всего *origin*<br>
        `link` - ссылка на репозиторий на github<br>
К примеру:<br>
    #git remote add origin https://github.com/Olegfromr/for_github.git<br>
    #git branch -M main     //переименовываю ветку в ветку *main* весь затык именно в этом!!!<br>
    #git push -u origin main    //делаю push на *github* после этого смогу делать просто git push<br>
// Когда надо ввести имя и пароль ввожу своё имя: **Olegfromr** и НЕ пароль от github! А **ТОКЕН**!!!

### пара-ра-ра-рам! Всё!!!

## Копирую чужой репозиторий на локальный
git clone `link`<br> `link` -> ссылка на репозиторий<br>
    #git clone https://github.com/codedokode/pasta.git <br>

