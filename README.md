# Домашнее задание к занятию 5. «Оркестрация кластером Docker контейнеров на примере Docker Swarm»


## Задача 1

Дайте письменые ответы на вопросы:

- В чём отличие режимов работы сервисов в Docker Swarm-кластере: replication и global?
- Какой алгоритм выбора лидера используется в Docker Swarm-кластере?
- Что такое Overlay Network?

### Ответ



## Задача 2

Создайте ваш первый Docker Swarm-кластер в Яндекс Облаке.

Чтобы получить зачёт, предоставьте скриншот из терминала (консоли) с выводом команды:
```
docker node ls
```

### Ответ

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled.png "1")

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled2.png "1")

## Задача 3

Создайте ваш первый, готовый к боевой эксплуатации кластер мониторинга, состоящий из стека микросервисов.

Чтобы получить зачёт, предоставьте скриншот из терминала (консоли), с выводом команды:
```
docker service ls
```

### Ответ

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled3.png "1")

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled5.png "1")

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled6.png "1")

## Задача 4 (*)

Выполните на лидере Docker Swarm-кластера команду, указанную ниже, и дайте письменное описание её функционала — что она делает и зачем нужна:
```
# см.документацию: https://docs.docker.com/engine/swarm/swarm_manager_locking/
docker swarm update --autolock=true
```

### Ответ

![Скрин](https://github.com/Jlljully/Virt_5/blob/main/Untitled4.png "1")
