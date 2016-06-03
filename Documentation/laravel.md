# Laravel

Laravel по-русски
https://laravel.ru

Хелпер-файл для Laravel
https://gist.github.com/barryvdh/5227822

( http://arhamzul.com/laravel-5-netbeans/ )


Установка Laravel

С помощью установщика Laravel
Загрузим установщик Laravel с помощью Composer
composer global require "laravel/installer=~1.1"

Поместим каталог ~/.composer/vendor/bin в переменную PATH, чтобы исполняемый файл laravel мог быть найден системой ( http://sergeyivanov.ru/it/linux/dobavlenie-peremennyh-okruzheniya-path-centos.html )


После установки простая команда laravel new произведёт установку свежего Laravel в указанный каталог. Например, laravel new blog создаст каталог с именем blog, содержащий свежий Laravel со всеми установленными зависимостями. Этот способ установки намного быстрее, чем установка с помощью Composer:

laravel new blog


Ресурсы:
https://habrahabr.ru/post/197454/ Установка, настройка, создание и деплой приложения
https://ru.wikipedia.org/wiki/Laravel
http://angrydeer.ru/laravel 
http://angrydeer.ru/laravel/laravel-5-2-sajt-s-nulya-i-do-zapuska-ch-1-vstuplenie#more-9