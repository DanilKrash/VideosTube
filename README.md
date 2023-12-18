<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">VideosTube Advanced Project Template</h1>
    <br>
</p>

Проект в виде мини ютуба.
-------------------

ФУНКЦИОНАЛ

```
backend

	Регистрация/Авторизация;
	Загружать небольшие видео;
	Редактировать видео;
	Редактировать комментарии
	Просмотр статистики канала
	Просмотр статистики последнего загруженного видео

frontend
	Регистрация/Авторизация;
	Возможность поставить/убрать лайк/дизлайк
	Оставлять комментарии под видео
	Отвечать на комментарии
	Просмотр видео
   	Просмотр похожих видео
   	Просмотр истории просмотренных видео
   	Глобальный поиск по видео
   	Подписка/Отписка на каналы
   	Просмотр видео определённого канала
```	

-------------------
 

[![Latest Stable Version](https://img.shields.io/packagist/v/yiisoft/yii2-app-advanced.svg)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![Total Downloads](https://img.shields.io/packagist/dt/yiisoft/yii2-app-advanced.svg)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![build](https://github.com/yiisoft/yii2-app-advanced/workflows/build/badge.svg)](https://github.com/yiisoft/yii2-app-advanced/actions?query=workflow%3Abuild)

СТРУКТУРА ДИРЕКТОРИИ
-------------------

```
common
    config/              contains shared configurations
    mail/                contains view files for e-mails
    models/              contains model classes used in both backend and frontend
    tests/               contains tests for common classes    
console
    config/              contains console configurations
    controllers/         contains console controllers (commands)
    migrations/          contains database migrations
    models/              contains console-specific model classes
    runtime/             contains files generated during runtime
backend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains backend configurations
    controllers/         contains Web controller classes
    models/              contains backend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for backend application    
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
frontend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains frontend configurations
    controllers/         contains Web controller classes
    models/              contains frontend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for frontend application
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
    widgets/             contains frontend widgets
vendor/                  contains dependent 3rd-party packages
environments/            contains environment-based overrides
```
