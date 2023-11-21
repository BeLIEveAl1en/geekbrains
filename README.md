
#  Инструкция для работы с git и удалёнными репозиториями

## Что такое Git:

Git - это система управления версиями, позволяющая отслеживать изменения
в коде, сотрудничать над проектами, создавать ветки и эффективно управлять
историей разработки.

## Настройка пользователя:

Откройте терминал или командную строку и выполните следующие команды,
чтобы указать свои имя пользователя и адрес электронной почты:  
git config --global user.name "Ваше Имя"  
git config --global user.email "ваша@почта.com"

1. ### Создание нового репозитория:
    - Локально:  
      git init
    - На GitHub (или другом хостинге Git):  
      Создайте новый репозиторий через веб-интерфейс.

2. ### Работа с репозиторием:
    - Просмотр состояния изменений:  
      git status
    - Добавление изменений в индекс:  
      git add файл1 файл2
    - Фиксация изменений:  
      git commit -m "Ваш комментарий"
    - Просмотр истории коммитов:
      git log
    -

3. ### Работа с ветками:
    - Создание новой ветки:  
      git branch новая-ветка
    - Переключение на ветку:  
      git checkout новая-ветка
    - Слияние веток:
      git merge ветка-слияния
    -

4. ### Работа с удалёнными репозиториями:
    - Добавление удалённого репозитория:  
      git remote add имя-удаленного-репозитория URL-удаленного-репозитория
    - Отправка изменений на удалённый репозиторий:  
      git push имя-удаленного-репозитория ветка
    - Получение изменений с удалённого репозитория:  
      git pull имя-удаленного-репозитория ветка  
