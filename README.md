# Default nginx.conf


В данном репозитории находится дефолтный конфигурационный файл nginx


## Описание


nginx.conf - это  дефолтный конфигурационный файл nginx, поставляемый с пакетом nginx в Debian/Ubuntu.


### Системные требования


Для работы необходим веб-сервер nginx


```
sudo apt install nginx
```


### Установка


Если вы выполнили инструкции из предыдущего пункта, то у вас уже есть nginx.conf


 Проверить это можно так:


```
nginx -t
```

результат должен быть таким:

>nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
>nginx: configuration file /etc/nginx/nginx.conf test is successful

Если вы получили что-то другое или необходим именно этот конфиг, то необходимо выполнить следующие действия:

**Шаг 1.** Клонируем репозиторий
`git clone ...`

**Шаг 2.** Копируем
`cp  ...`

И проверяем: 
```
nginx -t
```

## Создано с помощью


* [vim](https://www.vim.org/) - the ubiquitous text editor


## Внесение правок


Прочтите [CONTRIBUTING.md](CONTRIBUTING.md) чтобы получить подробную информацию о правилах и процессе подачи запросов на включение кода.


## Управление версиями


Для управления версиями мы используем [SemVer](http://semver.org/). Информацию о доступных версиях см. в [тегах в этом репозитории](https://gitlab.rebrainme.com/egor/rebrain-devops-task-checkout/tags).



## Лицензия

Этот проект лицензируется в соответствии с лицензией MIT — подробности см. в файле [LICENSE.md](LICENSE.md).


## Благодарности


* Всем

