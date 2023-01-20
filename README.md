# pre-commit-config

Этот репозиторий включает в себя конфигурационный файл для pre-commit и настройки для различных линтеров и проверок.

## Установка

Установить pre-commit можно, следуя [официальной инструкции](https://pre-commit.com/#installation):

```shell
pip install pre-commit
```

## Использование как подмодуля

Подключить этот репозиторий в качестве подмодуля можно следующим образом:

```shell
# Из корня основного проекта
git submodule add -b master https://github.com/mziai/pre-commit-config.git
git submodule init
git submodule update
```

Затем нужно создать символическую ссылку в корень основного проекта:

```shell
ln -s pre-commit-config/.pre-commit-config.yaml .pre-commit-config.yaml
ln -s pre-commit-config/.clang-format .clang-format
```
