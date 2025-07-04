# Установка Git на macOS

---

## 1. Проверка установлен ли Git

Откройте **Терминал** и выполните команду:

```bash
git --version
```

Если вы видите версию, например `git version 2.39.5`, значит `Git` уже установлен.

Если команда вызывает окно с предложением установить инструменты разработчика — соглашайтесь, и `Git` будет установлен автоматически.

---

## 2. Установка Git через Homebrew

Если `Git` не установлен, проще всего поставить его через Homebrew.

```bash
brew install git
```

Проверьте установку:

```bash
git --version
```

---

## 3. Настройка Git (имя и email)
После установки желательно настроить имя пользователя и email — они будут использоваться при коммитах:

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "ваш@email.com"
```

---

## Готово!
Теперь Git установлен и настроен. Можно клонировать репозитории, делать коммиты.
