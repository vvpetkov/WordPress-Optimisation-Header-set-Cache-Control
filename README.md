# Kодa от видеото за урока: оптимизиране на кеша в WordPress!
WordPress Оптимизация - 12/15 - Оптимизация на кеширането - как да го направим? 
[Видеото в YouTube] (https://youtu.be/JNcBMFWnQHM?list=PLJFGnkVSSuK9jXq4AZU-9J-EMcqNYMx8c)

Преди да сложа кода, страницата ми се кешираше 60 от 100 (D)*

* файл : "Code" съдържа: кода показан във видеото и вече страницата ми се кешира 80 от 100 (B)

* файл : "Code 2"  съдържа кода показан от статия намерена с гугъл, но с него страницата ми се кешираше 77 от 100  (C)

* файл : "Code 3"  съдържа кода показан във видеотo, НО с добавен формат за .svg и вече страницата ми се кешира 86 от 100 (B)

* файл : "Code 4"  съдържа кода "Code 3", НО с добавка от "Code 2" за ETag , не е тестван!

* файл : "Code 5" съдържа кода "Code 4", НО с добавка за favicon.ico, която не даде резултат! 

## Страницата нямаше [favicon.ico](https://codex.wordpress.org/Creating_a_Favicon), заложих favicon.ico и теста се оправи 

# Ползвайте ["Code 3"](https://raw.githubusercontent.com/vvpetkov/WordPress-Optimisation-Header-set-Cache-Control/master/Code%203) 90/100 (A)

*Данните за 60 от 100 са дадени за www.mebelisofia.com от www.webpagetest.org

![Image](http://mebelisofia.com/webpagetest.jpg)

