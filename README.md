# youtrack-github-integration-example
<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/youtrack-logo.png?raw=true" width="30">
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/github-logo.png?raw=true" width="30">
<br/>

> Пример настройки Youtrack и интеграции с Github
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
В этом проекте мы попробовали симулировать процесс разработки проекта. Для управления разработкой использовали YouTrack.


### Настройка
1. Для работы мы выбрали облачную версию YouTrack и первое что потребовалось сделать - это зарегистрировать пользователей<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/user-registration.png?raw=true"><br/>
2. Создаём проекты, добавляем пользователей и даём им необходимые права<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/projects.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/add-users.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/user-access.png?raw=true"><br/>
3. Настраиваем интеграцию с Github<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/connect-github.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/check-vcs-usernames.png?raw=true"><br/>
> Обратите внимание на то, что почта и ник пользователя должны обязательно совпадать с тем, что указаны в конфигурации VCS на вашем устройстве.
> Проверить конфигурацию гита можно с помощью команды `git config --list`.
3. Создаём задачу и пробуем её выполнить с помощью git<br/>
    <img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/task.png?raw=true"><br/>
    Алгоритм использования прост: <br/>
    *  добавляем в  индекс `git add .`
    *  делаем коммит с сообщением `git commit -m “<message> #<taskId> <statusName>”`
    *  делаем пуш и наблюдаем результат `git push`
    <br/>
    
    Сообщения-команды:<br/>
    *  Для выполнения одной задачи - `message #DD-3 Done`
    *  Для выполнения множества задач - `message (#DD-1, #DD-2) In Progress`

4. Настраиваем доски для проектов<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/boards.png?raw=true"><br/>
5. Создаём задачи и симулируем процесс разработки<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/issues.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/simulation.png?raw=true"><br/>
6. Создаём отчеты<br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/gant.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/users-report.png?raw=true"><br/>
<img src="https://github.com/Mark1708/youtrack-github-integration-example/blob/main/assets/time-report.png?raw=true"><br/>

## Technologies
* YouTrack
* Github

## Status
Проект _закончен_

## Inspiration
Проект сделан в образовательных целях

## Contact
Created by [Gurianov Mark](https://mark1708.github.io/) - feel free to contact me!
#### +7(962)024-50-04 | mark1708.work@gmail.com | [github](http://github.com/Mark1708)

![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mark1708&repo=youtrack-github-integration-example&theme=chartreuse-dark&show_icons=true)