## 1. Получение ветки с сервера
1. Загрузить все изменения с удалённого репозитория, но не сливать их с текущей веткой: git fetch. Переключиться на нужную ветку: git checkout <имя_ветки>.
## 2. Слияние веток 
1. Перейти в целевую ветку: git checkout <целевая_ветка>;
2. Выполнить слияние: git merge <исходная_ветка>.
## 3. Действия после слияния
1. Проверить работоспособность: запустить тесты или проверить код вручную;
2. Отправить обновлённую ветку на сервер: git push.