# https://github.com/Pau1R/p51

## команды GIT
```bash
git --version
git init
git config user.name "Ваше Имя" 
git config user.email "ваша@почта.com"
git config --list
git status
git add новый_файл.txt
git commit -m "Описание изменений"
git log
git restore файл.txt  # Отменяет локальные правки (возвращает к последнему коммиту)
git restore --staged файл.txt  # Убирает из staged, но оставляет изменения в файле
git checkout хеш_коммита -- файл.txt # Откат к определенному коммиту
git remote add origin https://github.com/Pau1R/i_am_a_teapot.git
git config credential.helper "store --file=.git/credentials"
```

## команды linux
```bash
cd /путь/к/вашей/папке
echo "Привет, Git!" > hello.txt
touch мой_файл.txt
nano создаем_или_редактируем_файл.txt
```
