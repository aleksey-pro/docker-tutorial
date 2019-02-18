# На чем оcнован образ
FROM ubuntu 

MAINTAINER ANXIETER <anxieter@yandex.ru>

# Обновляем индексы, устанавливаем в него приложение, создаем ссылку, чтобы вызвать напрямую cowsay
RUN apt-get update && apt-get install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay


# Точка входа в директории с контейнером
ENTRYPOINT ["cowsay"]