## Установка

1. Устанавливаем docker
2. $ docker pull direvius/yandex-tank
3. Получаем token на https://overload.yandex.net/. Cохраняем его в token.txt рядом с load.yaml
4. Переходим в директорию с load.yaml, выполняем $ docker run -v $(pwd):/var/loadtest -v $HOME/.ssh:/root/.ssh --net host -it direvius/yandex-tank
5. Нахоим строку вида Web link: https://overload.yandex.net/ХХХХХ, переходим по ссылке.
