# Выполнено ДЗ №1

 - [ ] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Создана ветка kubernetes-prepare и добавлены соответствующие файлы
 - Установлен kubectl
 - Установлен minikube
 - Установлен kubernates dashboard
 - Установлен k9s
 - Подготовлен образ и манифест для запуска web приложения
 - Дополнен манифест frontend-pod-healthy.yaml переменными окружения - под запущен

## Как запустить проект:
 - Применить манифест в кластере
 ```kubectl create -f kubernetes-intro/web/web-pod.yaml``` 

## Как проверить работоспособность:
 - Выполнить port-forward до пода my-web-app
 - Перейти по ссылке http://localhost:8000/index.html и http://localhost:8000/homework.html

## PR checklist:
 - [ ] Выставлен label с темой домашнего задания
