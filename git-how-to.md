## 1. Создание SSH-ключа
"ssh-keygen -t ed25519 -C "ваш_email@example.com"

## 2. Добавление SSH-ключа в GitHub
1. Скопировать публичный ключ: "cat ~/.ssh/id_ed25519.pub"
2. Добавить ключ в GitHub: Перейти в Настройки GitHub. Нажмите New SSH Key. В поле Title указать название. Вставить скопированный ключ и нажать Add SSH Key.

## 3. Клонирование репозитория через SSH
1. Скопировать SSH-ссылку репозитория: скопировать ссылку (git@github.com:user/repo.git).

2. Клонировать репозиторий: git clone git@github.com:user/repo.git Проверка подключения: "ssh -T git@github.com". Если видим: Hi username! You've successfully authenticated... — ключ работает.



