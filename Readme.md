# Instructions for Git
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
    git clone <url> - клонирование удаленного репозитория на локальный компьютер
    git add <filename> - добавление файла в индекс для последующего коммита
    git commit -m "commit message" - создание нового коммита с указанным сообщением
    git status - отображение текущего состояния репозитория и списка измененных файлов
    git push - отправка локальных изменений в удаленный репозиторий
    git pull - загрузка изменений из удаленного репозитория на локальный компьютер
    git branch - отображение списка веток в локальном репозитории
    git checkout <branch name> - переключение на указанную ветку
    git merge <branch name> - объединение текущей ветки с указанной веткой