### Подготовка файлов

---

1. Создайте папку, в которой будет храниться проект.
2. Добавьте первые необходимые файлы.

### Создание репозитория и первый коммит

---

1. Зайдите в терминал **Git Bush** и перейдите в папку проекта
2. Первое, что нужно сделать - инициализировать репозиторий. Вводим команду **git init***

Чтобы проверить статус репозитория используется команда **git status**.

3. Добавим необходимые файлы в репозиторий, чтобы не потерять их версии - 
**git add (название файла)**. Можно использовать **git add --all** - добавляем все 
файлы папки в репозиторий. 

4. Для сохранения изменений необходимо сделать коммит - положить старые файлы на
полочку в шкафу репозитория. Введем команду **git commit -m 'Комментарий'**. 
Комментарий лучше делать более информативным, чтобы вы и ваши коллеги понимали, 
какие изменения были внесены в проект.

Чтобы проверить журнал изменений можно использовать команду **git log**.

### Связываем репозитории

---

1. Чтобы связать два репозитория используется команда **git remote add origin
(ssh ссылка, скопированная с github)**

Для проверки, что репозитории связались испольхуется команда **git remote -v**

2. Добавляем наши изменения в удаленный репозитории, используя команду **git push -u origin 
master (либо main)**. Далее можем просто писать **git push**, потому что основаня
ветка уже создана.