# Instructions for Git

![windows](https://img.shields.io/powershellgallery/p/Read.md?label=Windows&logo=windows&style=social) ![git](https://img.shields.io/pypi/pyversions/gita?color=red&label=Git&logo=Git)

 - *Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.*
![Screenshot-4.jpg](https://i.postimg.cc/J7FHG66x/Screenshot-4.jpg)
##### *Instructions on how to use Git:*  
**Windows version**
1. Install [Git](https://git-scm.com) on your computer.

+ Run the downloaded Git installer file and follow the on-screen instructions, choosing options as you see fit. It is usually recommended to leave the default settings.
+ After installing Git, check that it has been successfully installed by opening a command prompt and typing **`"git --version"`**. 
__If Git has been installed correctly, you will see the version of Git installed on the command line.__

2. At the command prompt, enter the following command:
`git config --global user.name "Your Name"`
_Replace "Your Name" with your Git username._

3. Enter the command to set the Git email address:
`git config --global user.email "your-email"`
_Replace "your-email" with your Git email address._

4. If you want to use the default editor to enter the commit message, enter the following command:
`git config --global core.editor "nano"`
_You can specify your default editor instead of "nano", such as "notepad" or "vim"._

##### A dictionary of Git commands that you can use in the console after installation:

    git init - создание нового локального репозитория
    git status - отображение текущего состояния репозитория и списка измененных файлов
    git add <filename> - добавление файла в индекс для последующего коммита *git add .*
    git commit -m "commit message" - создание нового коммита с указанным сообщением
    git log - отображение коммитов
    git checkout <commit hash> переход опред. коммиту
    git checkout <branch name> - переключение на указанную ветку
    git checkout <branch hash> переход опред. ветку
    *. git checkout - b <branch name> Создание и сразу переход на ветку*
    git branch - Отображает список веток
    git branch -m <new branch name>
    git branch -d <new branch name> Удаление ветки, НО удалить текущею нельзя
    git merge <feature branch name> 
    *Слияние другой ветки (feature branch) в текущую ветку (receiving  branch)*
    git clone <url> Клонирование удаленного репозитория в локальный
    git branch -a = Отображает все ветки + те которые в удаленных репозиториях
    git pull - загрузка изменений из удаленного репозитория на локальный компьютер
    git push - отправка локальных изменений в удаленный репозиторий
    git remote add origin <url> = Подключения удаленного репозитория "origin - имя (можно любое)"
    git push -u origin <branch> Загрузка изменения из лок.ветки в удал. с созданием связи между ними
