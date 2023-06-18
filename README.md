<div align="center" id="top"> 
  <img src="./.github/app.png" alt="Redis Logo" />
</div>

<h1 align="center">Redis Compose Project</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/laspegasuscommunity/redis?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/laspegasuscommunity/redis?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/laspegasuscommunity/redis?color=56BEB8">
  <img alt="License" src="https://img.shields.io/github/license/laspegasuscommunity/redis?color=56BEB8">
  <img alt="Github issues" src="https://img.shields.io/github/issues/laspegasuscommunity/redis?color=56BEB8" />
  <img alt="Github forks" src="https://img.shields.io/github/forks/laspegasuscommunity/redis?color=56BEB8" />
  <img alt="Github stars" src="https://img.shields.io/github/stars/laspegasuscommunity/redis?color=56BEB8" />
</p>

<hr>

<p align="center">
  <a href="#dart-о-проекте">О проекте</a> &#xa0; | &#xa0;
  <a href="#sparkles-особенности">Особенности</a> &#xa0; | &#xa0;
  <a href="#rocket-технологии">Технологии</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-требования">Требования</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-начало">Начало</a> &#xa0; | &#xa0;
  <a href="#memo-лицензия">Лицензия</a> &#xa0; | &#xa0;
  <a href="https://github.com/orgs/laspegasuscommunity/people" target="_blank">Авторы</a>
</p>

<br>

## :dart: О проекте ##

Redis - это хранилище данных с открытым исходным кодом, сетевое, в памяти, хранилище ключевых значений с опциональной долговечностью. Он написан на языке ANSI C. Сегодня разработка Redis спонсируется компанией Redis Labs; до этого она спонсировалась компаниями Pivotal и VMware. Согласно ежемесячному рейтингу DB-Engines.com, Redis является самым популярным хранилищем ключевых значений. Название Redis означает REmote DIctionary Server.

## :sparkles: Особенности ##

:heavy_check_mark: Важнейшая особенность контейнеров — их сравнительно короткий жизненный цикл. Любой контейнер можно остановить, перезапустить или уничтожить, если это необходимо. Данные, которые содержатся в контейнере, при этом тоже пропадут. Так выработалось правило проектирования приложений: не хранить важные данные в контейнере. Такой подход называют Stateless;\
:heavy_check_mark: Объем контейнеров измеряется в мегабайтах, поскольку в них упаковывают лишь те процессы и зависимости ОС, которые необходимы для выполнения кода. Легковесные контейнеры быстро запускаются и экономят место на диске;\
:heavy_check_mark: Один контейнер соответствует одному запущенному процессу. Отключение отдельного контейнера для отладки или обновления никак не помешает нормальной работе всего приложения;\
:heavy_check_mark: Контейнеризация обеспечивает надежную изоляцию процессов и повышает уровень безопасности систем. Приложения, которые работают внутри контейнера, не имеют доступа к основной ОС и не могут на неё влиять;\
:heavy_check_mark: Благодаря контейнерам можно автоматизировать развертывание приложений на разных хостах;\
:heavy_check_mark: Использование контейнеров позволяет перейти с монолита на микросервисную архитектуру. За счет этого ускоряется разработка новой функциональности, поскольку нет опасений, что изменения в одной компоненте затронут всю остальную систему;\
:heavy_check_mark: С точки зрения эффективности контейнеры котируются выше виртуальных машин. На одинаковом оборудовании можно запустить большое количество контейнеров, тогда как ВМ будет в разы меньше. Это важно при использовании облачной инфраструктуры — потребуется меньше ресурсов;

## :rocket: Технологии ##

В данном проекте были использованы следующие инструменты:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## :white_check_mark: Требования ##

Перед началом :checkered_flag:, вам нужно иметь [Git](https://git-scm.com) и [Docker](https://www.docker.com/) установленными.

## :checkered_flag: Начало ##

```bash
# Клонируйте этот проект
$ git clone https://github.com/laspegasuscommunity/redis.git

# Доступ
$ cd postgres

# Запустите проект
$ docker-compose up -d

# Сервер инициализируется в <http://redis>
```

## :memo: Лицензия ##

Этот проект находится под лицензией MIT. Для получения более подробной информации см. [LICENSE](LICENSE) файл.

<h4 align="right"> 
	Сделано с :heart: <a href="https://github.com/orgs/laspegasuscommunity/people/ponfertato" target="_blank">ponfertato</a>
</h4> 

&#xa0;

<h4 align="center"> 
	<a href="#top">Вернуться к началу 🔝</a>
</h4> 