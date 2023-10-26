## Описание репозитория
Вы находитесь в репозитории учебной дисциплины "Введение в распределенные технологии" реализующейся преподавателями [факультета инфокоммуникационных технологий](https://fict.itmo.ru) Университета ИТМО. При разработке учебной программы мы постарались учесть международный опыт в области распределенных технологий а также применить свой опыт при изучении данных технологий.

> Преподаватели тоже учатся, хорошие преподаватели учатся всю свою жизнь.

По этому постарайтесь отнестись к этой учебной дисциплине ответственно, мы в свою очередь постараемся дать все самые новые и интересные технологии которые помогут вам в вашей будущей карьере. Не бойтесь спрашивать и искать интересные решения в рабочих заданиях, а мы постараемся вам помочь и ответить на все вопросы в рамках тем учебной дисциплины. 
Дерзайте! 

## Обнаружение багов и предложения по улучшению

Если вы нашли баг в этой документации или хотели бы предложить улучшения, откройте [Issue или сделайте PR](https://docs.github.com/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request).

### Правила создания Issue

Не забывайте об общих правилах, когда создаете Issue:

1. Обратите внимание, в том ли репозитории вы публикуете обращение.

2. Если вы сообщаете о баге, убедитесь, что подобного Issue ещё нет.

3. Заполняйте заголовок и описание как можно точнее.

4. Желательно включать в заголовок Issue следующие флаги: [BUG], [PROPOSAL], [QUESTION].


## Создание PR

Данная документация может быть изменена посредством [PR (Pull Request)](https://docs.github.com/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) любым участником сообщества. Пожалуйста, не забудьте о простых правилах контрибуции.

### Правила констрибуции в репозиториях

1. Если вы хотели бы предложить небольшие изменения, например такие, как правки опечаток, форматирования, то предпочительнее PR.

2. Понятно опишите проблему и её решение, которое вы предлагаете. При необходимости, можете указать номер Issue.

3. Прежде чем править форматирование, убедитесь, что это действительно нужно.

4. Пожалуйста, постарайтесь придерживаться преобладающего стиля оформления кода и разметки Markdown.

## Локальное развертывание проекта
### Развертывание проекта в Docker контейнере

```
git clone https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies
cd introduction-to-distributed-technologies
docker pull squidfunk/mkdocs-material
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```


------


## Repository Description
You are in the repository of the educational discipline "Introduction to Distributed Technologies" implemented by the instructors of the [Faculty of Information and Communication Technologies](https://fict.itmo.ru) at ITMO University. When developing the educational program, we aimed to take into account international experience in the field of distributed technologies and apply our own expertise in studying these technologies.

> Teachers also learn, good teachers learn throughout their lives.

Therefore, please approach this educational discipline responsibly, and we, in turn, will strive to provide you with the latest and most interesting technologies that will help you in your future career. Don't hesitate to ask questions and seek interesting solutions in your assignments, and we will do our best to assist you and answer all your questions within the scope of the educational discipline.

Go for it!

## Bug Discovery and Improvement Suggestions

If you have found a bug in this documentation or would like to propose improvements, please open an [Issue or make a PR](https://docs.github.com/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request).

### Rules for Creating Issues

When creating an Issue, please remember the following general rules:

1. Make sure you are posting your inquiry in the correct repository.

2. If you are reporting a bug, ensure that a similar Issue does not already exist.

3. Provide a title and description as accurately as possible.

4. It is preferable to include the following flags in the Issue title: [BUG], [PROPOSAL], [QUESTION].

## Creating a PR

This documentation can be modified through a [PR (Pull Request)](https://docs.github.com/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) by any community member. Please do not forget about the simple contribution rules.

### Contribution Rules in Repositories

1. If you would like to suggest minor changes, such as fixing typos or formatting, a PR is preferred.

2. Clearly describe the issue and the solution you propose. If necessary, you can reference the Issue number.

3. Before making formatting changes, ensure that it is indeed necessary.

4. Please try to adhere to the prevailing code style and Markdown formatting.

## Local Project Deployment
### Project Deployment in a Docker Container

```
git clone https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies
cd introduction-to-distributed-technologies
docker pull squidfunk/mkdocs-material
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```
