[githowto.com/ru](https://githowto.com/ru)

1. Заходим через командную строку в нужную папку: cd path
2. Просим git чтобы он следил за этой папкой: git init
3. Прописываем две конфигурационные команды: git config --local user.name "Neoluxer"
4. git config --local user.email neoluxe@yandex.ru
5. Мы можем конфигурировать файлы как локально так и глобально (на все проекты на этом компьютере, которые будем создавать)/
6. Можно сохранять файлы в индекс и можно создавать контрольные точки.
7. Посмотреть статус репозитория: git status
8. Добавить все (ALL) файлы: git add -A
9. Можно добавить конкретный файл или файлы с конкретным расширением: git add *.md
10. -a значит все файлы
11. -m означает massage
12. Создаем контрольную точку: git commit -a -m"first commit"
13. Узнать какие комиты были: git log
14. Копируем
 git remote add origin https://github.com/Neoluxer/Neoluxer_bot.git из
GITHUB
15. Вставляем в терминал (добавляем удаленный репозиторий. Теперь локальный репозиторий связан с удаленным)
16. git push -u origin master  (Запушиваем репозиторий)
17. Изменение репозитория для пуша: git remote set-url origin https://github.com/Neolux
er/Testing.git
18. git remote -v    - Проверка удаленного репозитория
