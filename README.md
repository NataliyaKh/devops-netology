# devops-netology
Будут проигнорированы следующие файлы, находящиеся в каталоге terraform:
* Всё наполнение каталога /.terraform
* Файлы состояния ( .tfstate) 
* Файлы с записями об ошибках экстренного завершения программы (crash log files)
* Файлы переменных (.tfvars)
* Файлы переопределения (override files)
* Файлы c информацией о блокировке (transient lock info files)
* Файлы конфигурации CLI

На файлы, находящиеся за пределами каталога terraform, правило игнорирования не распространяется. 

Новая строка
