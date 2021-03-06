---
layout: post
title: Простая и удобная аналитика для веб-разработчика
categories : [webdev, analytics]
---

Простая и удобная аналитика для веб-разработчика
============================================================

Я пробовал популярные сервисы аналитики (Google Analytics и Яндекс.Метрику), но ни один из них не смог помочь мне разобраться с тем, что происходит с моими сайтами. Так как я профессионально не занимаюсь аналитикой, но стараюсь наблюдать за статистикой сайтов — это побочная потребность веб-разработки.

Мне необходимо немного: количество человек и просмотров, популярные страницы, с каких сайтов на меня переходят люди.


## Популярные сервисы ##

### Google Analytics ###

Если с установкой не было никаких проблем, то с интерфейсом был просто ужас и кошмар. Главная страница, встречающая тебя, просто ужасна и более того — на ней ничего нельзя понять. Невозможно разобраться с тем, сколько же было человек на сайте. Для того, чтобы добраться до нужных тебе данных необходимо пройтись через несколько медленных ajax-страниц, затем проявить смекалку, чтобы найти нужный пункт. Когда я пользовался этой аналитикой, у меня было ощущение, что Гугл намерено прячет то, зачем я пришёл к нему на этот сервис. Спустя пару месяцев уже не было никакого желания пользоваться этим кошмаром. Отдельную книгу можно написать про то, как посмотреть статистику для другого вашего сайта.

### Яндекс.Метрика ###

Не уходя с первого я попробовал метрику и оказалось, что она сделана намного осознанее. Нет дикого интерфейса — легче понимаешь, что и где находится. Забавной игрушкой, на которую я потратил десяток часов своей жизни является вебвизор — возможность посмотреть на действия пользователь на сайте. Если бы не Gauges, то я бы остался на метрике.

## Мысли спустя год после первого счётчика: ##

— Кажется, я делаю что-то не так, если мне не нужны 90% фич аналитических сервисов.

## Gauges ##

Около года назад, я заметил, что GitHub пользуется сторонней аналитикой (как оказалось позже, своей собственной). Это была [Gauges][2].

Я понял, что пользоваться Google-аналитикой больше не могу — физическая усталость преследовала меня после каждого сеанса, поэтому я сразу же попробовал Gauges. Я ни секунды не жалею оплаченной подписки и вот уже несколько месяцев пользуюсь аналитикой от гитхаба. Спустя какое-то время я осознал почему этот сервис подошёл мне больше других. Всё потому, что авторы придерживались определённой [философии][1] при создании сервиса для себя. На суть философии, как мне кажется, повлияло также то, что создатели сервиса сами по себе разработчики. Смысл сводится к трём постулатам:

* всё в одном месте;
* мониторинг трафика в реальном времени;
* адекватные ответы на первостепенные вопросы.

## Интерфейс Gaug.es ##

Я считаю, что лучше один раз увидеть, да и сам я был бы очень рад скриншотам интерфейса до начала пользования (таковых я не нашёл), поэтому далее я приложу изображения основных разделов на примере моих сайтов.

В данный момент интерфейс аналитики у меня выглядит так:

![](http://content.screencast.com/users/yaajing/folders/Jing/media/207c7e72-85be-4cba-b7b0-436b15367e7c/00000346.png)

Слева список счётчиков, а справа самая важная информация по первому счётчику.
Порядок счётчиков можно менять перетаскиванием. Страницу обновлять не нужно, все данные отображаются на странице по мере их появления.

### Вкладка Live Data ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/423bae2a-d5f2-461e-8803-b89c3a044a22/00000347.png)

### Вкладка Views and People ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/7462d6ba-3741-47a7-88da-944b9f24b196/00000348.png)

### Вкладка Referring Sites ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/a6823ed5-d67d-4981-8a21-6e766179784a/00000349.png)

### Вкладка Top Content ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/cce4124d-4d33-4a2e-95d9-80237ed51dba/00000350.png)

### Вкладка Search Terms ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/f8a5c5a2-bd96-4afc-80f9-6ab57ce960f2/00000353.png)

### Вкладка GeoLocation ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/1f84f369-6fb1-4243-b354-9126a7b1424d/00000354.png)

### Вкладка Technology ###

#### Browsers ###

Статистика по браузерам.

![](http://content.screencast.com/users/yaajing/folders/Jing/media/cd05879b-efa2-41c4-b190-a2ddb3a93efa/00000355.png)

#### Browser Support ###

Статистика по доступным фичам ваших пользователей.

![](http://content.screencast.com/users/yaajing/folders/Jing/media/fc48f1f6-1092-44c2-a4f6-d3d6f996384a/00000356.png)

#### Platforms ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/335f0ecc-a6ed-4963-9535-ced1b7097b1c/00000358.png)

### Вкладка Gauges Settings ###

![](http://content.screencast.com/users/yaajing/folders/Jing/media/530f633f-da4e-488a-9773-c6c57b3e0596/00000359.png)

## Заключение ##

В gauges я нашёл то, что тщетно искал в других сервисах — простота, удобство и вдобавок к этому получил современный интерфейс.  





[1]: http://get.gaug.es/philosophy
[2]: http://get.gaug.es/