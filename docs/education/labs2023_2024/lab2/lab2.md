## Лабораторная работа №2 "Развертывание веб сервиса в Minikube, доступ к веб интерфейсу сервиса. Мониторинг сервиса."
### Описание

В данной лабораторной работе вы познакомитесь с развертыванием полноценного веб сервиса с несколькими репликами. 

### Цель работы

Ознакомиться с типами "контроллеров" развертывания контейнеров, ознакомится с сетевыми сервисами и развернуть свое веб приложение. 

### Правила по оформлению

Правила по оформлению отчета по лабораторной работе вы можете изучить по [ссылке](../reportdesign.md)


### Ход работы

- Вам необходимо создать `deployment` с 2 репликами контейнера [ifilyaninitmo/itdt-contained-frontend:master](https://hub.docker.com/repository/docker/ifilyaninitmo/itdt-contained-frontend) и передать переменные в эти реплики: `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`.

- Создать сервис через который у вас будет доступ на эти "поды". Выбор типа сервиса остается на ваше усмотрение. 

- Запустить в `minikube` режим проброса портов и подключитесь к вашим контейнерам через веб браузер.

- Проверьте на странице в веб браузере переменные `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME` и `Container name`. Изменяются ли они? Если да то почему?

- Проверьте логи контейнеров, приложите логи в отчёт.

### Результаты лабораторной работы

- Файлы с разработанными вами манифестами с расширением `.yaml`.

- Схема организации контейеров и сервисов нарисованная вами в [draw.io](https://app.diagrams.net) или Visio.

- Скриншоты c результатами работы.


------


## Laboratory Work No. 2 "Deploying a Web Service in Minikube, Accessing the Web Interface of the Service, Monitoring the Service"
### Description

In this laboratory work, you will become familiar with deploying a full-fledged web service with multiple replicas.

### Objectives

To learn about the types of container deployment "controllers," become acquainted with network services, and deploy your own web application.

### Report Formatting Rules

You can learn the rules for formatting the report for the laboratory work by following this [link.](../reportdesign.md)


### Procedure

- You need to create a `deployment` with 2 replicas of the container ifilyaninitmo/itdt-contained-frontend:master and pass variables to these replicas: `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`.

- Create a service through which you will have access to these "pods." The choice of service type is up to you.

- Start the port forwarding mode in `minikube` and connect to your containers via a web browser.
  
- Check if the variables `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`, and `Container name` change on the web page. If yes, why?

- Check the logs of the containers and include the logs in the report.

### Laboratory Work Results
- Files with manifests developed by you with the `.yaml` extension.

- A diagram of the organization of containers and services drawn by you in [draw.io](https://app.diagrams.net) or Visio.

- Screenshots with the results of the work.
