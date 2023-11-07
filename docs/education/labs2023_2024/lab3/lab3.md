## Лабораторная работа №3 "Сертификаты и "секреты" в Minikube, безопасное хранение данных."
### Описание
В данной лабораторной работе вы познакомитесь с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube. 

### Цель работы
Познакомиться с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube. 

### Правила по оформлению

Правила по оформлению отчета по лабораторной работе вы можете изучить по [ссылке](../reportdesign.md)


### Ход работы

- Вам необходимо создать `configMap` с переменными: `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`.

- Вам необходимо создать `replicaSet` с 2 репликами контейнера [ifilyaninitmo/itdt-contained-frontend:master](https://hub.docker.com/repository/docker/ifilyaninitmo/itdt-contained-frontend) и используя ранее созданный `configMap` передать переменные `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME` .

- Включить `minikube addons enable ingress` и сгенерировать TLS сертификат, импортировать сертификат в minikube. 

- Создать ingress в minikube, где указан ранее импортированный сертификат, FQDN по которому вы будете заходить и имя сервиса который вы создали ранее.

> Если вы делаете эту работу на Windows/macOS для доступа к ingress вам необходимо использовать команду `minikube tunnel` к созданному ingress. 
> Если вы делаете эту работу на Windows/macOS для доступа к ingress вам необходимо в hosts добавить ip address localhost и ваш FQDN. Если установлен Linux, то нужно указывать minikube ip.

- В `hosts` пропишите FQDN и IP адрес вашего ingress и попробуйте перейти в браузере по FQDN имени. 

- Войдите в веб приложение по вашему FQDN используя HTTPS и проверьте наличие сертификата.

> Обычно в браузере это маленький замочек рядом с FQDN сайта, нажмите на него и сделайте скриншот с информацией.

### Результаты лабораторной работы

- Файлы с разработанными вами манифестами с расширением `.yaml`.

- Схема организации контейеров и сервисов нарисованная вами в [draw.io](https://app.diagrams.net) или Visio.

- Скриншоты c результатами работы.

------


## Laboratory Work No. 3 "Certificates and Secrets in Minikube, Secure Data Storage"
### Description
In this laboratory work, you will become familiar with certificates and secrets in Minikube, as well as the rules for secure data storage in Minikube.

### Objectives
To get acquainted with certificates and secrets in Minikube and learn the rules for secure data storage in Minikube.. 

### Report Formatting Rules
You can learn the rules for formatting the report for the laboratory work by following this [link.](../reportdesign.md)


### Procedure

- You need to create a `configMap` with the variables: `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`.

- You need to create a `replicaSet` with 2 replicas of the container [ifilyaninitmo/itdt-contained-frontend:master](https://hub.docker.com/repository/docker/ifilyaninitmo/itdt-contained-frontend) and pass the variables `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME` using the previously created `configMap`.

- Enable `minikube addons enable ingress` and generate a TLS certificate, then import the certificate into Minikube.

- Create an ingress in Minikube, specifying the previously imported certificate, the FQDN you will use to access it, and the name of the service you created earlier.
  
>If you are doing this work on Windows/macOS, to access the ingress, you need to use the `minikube tunnel` command for the created ingress.
> If you are doing this work on Windows/macOS, you need to add the IP address and your FQDN to the hosts file.

- In the `hosts` file, add the FQDN and IP address of your ingress, and try to access it in your browser using the FQDN. 

- Access the web application using your FQDN over HTTPS and check for the presence of the certificate.
  
> Typically, in the browser, you will see a small padlock icon next to the site's FQDN. Click on it and take a screenshot of the information.

### Laboratory Work Results

- Files with manifests developed by you with the .yaml extension.

- A diagram of the organization of containers and services drawn by you in [draw.io](https://app.diagrams.net) or Visio.

- Screenshots with the results of the work.
