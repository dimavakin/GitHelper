# Шпаргалка по **Git**  
## Первоначальная настройка  
Настройка информации о пользователе для всех локальных репозиториев  

```  
$ git config --global user.name "[имя]"  
```  

Устанавливает имя, которое будет отображаться в поле автора у выполняемых вами коммитов  

```  
$ git config --global user.email "[адрес электронной почты]"  
```  

Устанавливает адрес электронной почты, который будет отображаться в информации о выполняемых вами коммитах  


## Создание нового репозитория или получение его по существующему URL-адресу  

```  
$ git init [название проекта]  
```  

Создаёт новый локальный репозиторий с заданным именем  

```  
$ git clone [url-адрес]  
```  

Скачивает репозиторий вместе со всей его историей изменений  
 
## Внесение изменений  

Просмотр изменений и создание коммитов (фиксация изменений)  

```   
$ git status  
```  
```  
$ git add [файл]  
```  
Индексирует указанный файл для последующего коммита  
```  
$ git commit -m "[сообщение с описанием]"  
```  

Фиксирует проиндексированные изменения и сохраняет их в историю версий  
```  
$ git push [удалённый репозиторий] [ветка]  
```  

Загружает все изменения локальной ветки в удалённый репозиторий  