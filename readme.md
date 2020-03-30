<p align="center"><img src="https://laravel.com/assets/img/components/logo-homestead.svg"></p>



## Introduction

Laravel Homestead is an official, pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

Homestead runs on any Windows, Mac, or Linux system, and includes the Nginx web server, PHP 7.2, MySQL, Postgres, Redis, Memcached, Node, and all of the other goodies you need to develop amazing Laravel applications.

Official documentation [is located here](https://laravel.com/docs/homestead).

## 说明

基于官方包`tag-v7.8.0`修改：

1. scripts/homestead.rb:15 box_version 由 '>= 6.0.0' 改为 '> 0'
2. .gitignore 增加 .idea
3. 使用流程参考：[Laravel 5.7 Homestead](https://learnku.com/docs/laravel/5.7/homestead/2245)
4. 目前兼容的PHP版本为`php5.6`,`php7.0`,`php7.1`,`php7.2`

## homestead.box 国内下载

百度云下载 homestead-5.1.0.box (1.25G)

![微信扫一扫](./qrcode.jpeg)
