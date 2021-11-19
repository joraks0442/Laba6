# LR6
Лабораторная работа №6
#### Ход работы
Для начала я создал аккаунт на Github. После этого сделал копию исходного репозитория к себе. После скачал и установил Git.
Первым делом настроил Git введя параметры `email git config --global user.name <username>` и `git config --global user.email <email>`.
Затем с помощью `git clone <url>` загрузил репозиторий.

![image](Screenshots/config.jpg)

После этого добавил в репозиторий файл "new file.txt." и с помощью `git pull`

![image](Screenshots/pull.jpg)

Далее с помощью команда `git log` запрашиваем историю изменений ветки, а с помощью `git checkout <name>` переключаемся между ветками

![image](Screenshots/log1.jpg)

![image](Screenshots/log2.jpg)

Далее пытаемся объеденить ветки masters и branch1 командой `git merge branch1` 