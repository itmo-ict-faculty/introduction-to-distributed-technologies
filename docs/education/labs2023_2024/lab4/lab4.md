## Лабораторная работа №4 "Сети связи в Minikube, CNI и CoreDNS"
### Описание

Это последняя лабораторная работа в которой вы познакомитесь с сетями связи в Minikube. Особенность Kubernetes заключается в том, что у него одновременно работают `underlay` и `overlay`  сети, а управление может быть организованно различными CNI.

### Цель работы

Познакомиться с CNI Calico и функцией `IPAM Plugin`, изучить особенности работы CNI и CoreDNS.

### Правила по оформлению

Правила по оформлению отчета по лабораторной работе вы можете изучить по [ссылке](../reportdesign.md)

### Ход работы

- При запуске minikube установите плагин `CNI=calico` и режим работы `Multi-Node Clusters` одновеременно, в рамках данной лабораторной работы вам нужно развернуть 2 ноды.

> Оригинальная инструкция для установки Calico в Minikube [ссылка](https://projectcalico.docs.tigera.io/getting-started/kubernetes/minikube)
> Оригинальная инструкция для включение 2-ух нод в Minikube [ссылка](https://minikube.sigs.k8s.io/docs/tutorials/multi_node/)

- Проверьте работу CNI плагина Calico и количество нод, результаты проверки приложите в отчет.

- Для проверки работы Calico мы попробуем одну из функций под названием `IPAM Plugin`.

- Для проверки режима `IPAM` необходимо для запущеных ранее нод указать `label` по признаку стойки или географического расположения (на ваш выбор).
  
> Оригинальная инструкция для назначения IP адресов в Calico [ссылка](https://projectcalico.docs.tigera.io/networking/assign-ip-addresses-topology)

- После этого вам необходимо разработать манифест для Calico который бы на основе ранее указанных меток назначал бы IP адреса "подам" исходя из пулов IP адресов которые вы указали в манифесте.

- Вам необходимо создать `deployment` с 2 репликами контейнера [ifilyaninitmo/itdt-contained-frontend:master](https://hub.docker.com/repository/docker/ifilyaninitmo/itdt-contained-frontend) и передать переменные в эти реплики: `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME`.

- Создать сервис через который у вас будет доступ на эти "поды". Выбор типа сервиса остается на ваше усмотрение. 

- Запустить в `minikube` режим проброса портов и подключитесь к вашим контейнерам через веб браузер.

- Проверьте на странице в веб браузере переменные `Container name` и `Container IP`. Изменяются ли они? Если да то почему?

- Используя `kubectl exec` зайдите в любой "под" и попробуйте попинговать "поды" используя `FQDN` имя соседенего "пода", результаты пингов необходимо приложить к отчету.  

### Результаты лабораторной работы

- Файлы с разработанными вами манифестами с расширением `.yaml`.

- Схема организации контейеров и сервисов нарисованная вами в [draw.io](https://app.diagrams.net) или Visio.

- Скриншоты c результатами работы.


------


## Laboratory Work No. 4 "Communication Networks in Minikube, CNI, and CoreDNS"
### Description

This is the last laboratory work in which you will become familiar with communication networks in Minikube. Kubernetes has the peculiarity of simultaneously using `underlay` and `overlay` networks, and management can be organized by various CNIs.

### Objectives

To get acquainted with CNI Calico and the `IPAM Plugin` feature, as well as to study the features of CNI and CoreDNS.

### Report Formatting Rules

You can learn the rules for formatting the report for the laboratory work by following this [link.](../reportdesign.md)

### Procedure 

- When starting Minikube, set the `CNI=calico` plugin and the `Multi-Node Clusters` mode simultaneously. For this laboratory work, you need to deploy 2 nodes.

> Original instructions for installing Calico in Minikube [link](https://projectcalico.docs.tigera.io/getting-started/kubernetes/minikube)
> Original instructions for enabling 2 nodes in Minikube [link](https://minikube.sigs.k8s.io/docs/tutorials/multi_node/)

- Check the operation of the Calico CNI plugin and the number of nodes. Include the results of the check in the report.

- To check the operation of Calico, we will try one of its functions called `IPAM Plugin`.

- To check the `IPAM` mode, you need to specify a `label` for the previously started nodes based on the criteria of a rack or geographic location (your choice).
  
> Original instructions for assigning IP addresses in Calico [link](https://projectcalico.docs.tigera.io/networking/assign-ip-addresses-topology)

- After that, you need to develop a Calico manifest that would assign IP addresses to the "pods" based on the IP address pools you specified in the manifest.

- You need to create a deployment with 2 replicas of the container [ifilyaninitmo/itdt-contained-frontend:master](https://hub.docker.com/repository/docker/ifilyaninitmo/itdt-contained-frontend) and pass the variables `REACT_APP_USERNAME`, `REACT_APP_COMPANY_NAME` to these replicas.

- Create a service through which you will access these "pods". The choice of service type is up to you.

- Start the port forwarding mode in `minikube` and connect to your containers through a web browser.

- Check the `Container name` and `Container IP` variables on the web browser page. Do they change? If yes, why?

- Using `kubectl exec`, enter any "pod" and try to ping other "pods" using the `FQDN` name of a neighboring "pod". Attach the ping results to the report.

### Laboratory Work Results

- Files with manifests developed by you with the `.yaml` extension.

- A diagram of the organization of containers and services drawn by you in [draw.io](https://app.diagrams.net) or Visio.

- Screenshots with the results of the work.
