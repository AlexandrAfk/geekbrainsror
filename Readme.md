Логин - любой, пароль - secret
app is now deployed to https://dry-hollows-82648.herokuapp.com/
---
Что нужно сделать.

A) Выполнить домашку до рабочего состояния.

1. Сделать таки домашку - сделать rack приложение с парочкой своих идей. Например сделайте себе сайт-визитку с информацией о себе и добавьте переход по ссылке и отправку каких-либо данных в форме.
2. Завести учетную запись на heroku.com
3. Выложить свое приложение на heroku чтобы работало с вашими придумками.


Б) Сделать pull-request мне на приемку для комментирования.

> https://github.com/urfu-2015/guides/blob/master/how-to-pull-request.md


1. Делаете fork репозитория https://github.com/apavlyut/geekbrainsror
2. В нем создаете ветку которую называете на английском по своему имени и фамилии, в моем случае это могло бы быть так: git checkout -b 'alexander-pavlyut'
3. В эту ветку складываете весь ваш rack проект и комитите.
4. Сообщаете мне название вашей ветки -> я создаю ее в репозитории у себя.
5. Вы пушите в свой форк на github, ваше rack
6. Перед пулл реквестом обязательно обновляетесь из исходного репозитория из созданной ветки для вас.
7. На гитхабе делаете pull-request в котором указываете в моем репозитории вашу ветку которую я для вас создаю по вашему запросу.
8. Ждете либо комментариев либо приемку вашего кода.

Ответы на возможные вопросы:

* Что мы делаем? - мы учимся и взаимодействуем как настоящие разработчики в команде.
* Как нам это поможет в обучении? - Все домашние задания я буду принимать теперь через пулл реквесты для того чтобы иметь возможность оставлять комментарии по существу и в итоге принимать результаты аргументировано и прозрачно для вас.
* Почему один репозиторий на всех? - потому что вся история всего обучения должна быть запротоколирована и быть доступна всем. Гит это позволяет. Фактически вы хозяин своей ветки.
* Как пушить в хероку если я нахожусь в своей ветке а не в мастере? - Хероку позволяет запушить следующией командой любую ветку:

> допустим я нахожусь в своей ветке alexander-pavlyut и я могу сделать следующую команду для выкладки в хероку:

```bash
git push heroku alexander-pavlyut:master
```

Все вопросы принимаются в следующем порядке:

1. Указываете пункт задания на котором у вас проблема
2. Отмечаете чем закончился предыдущий пункт перед проблемой.
3. Получаете ответ что делать дальше.

Пример проведенной коммуникации с вымышленным аккаунтом в котором я все это провернул находится тут https://github.com/apavlyut/geekbrainsror/pull/1
