#### [НАЗАТ](readme.md)
## Новая ветка

Создадим новый проект 

![Git](./assets/13.png)

добавляем файл index.html

![Git](./assets/14.png)

Делаем первый комит


![Git](./assets/15.png)

Cоздаем новую ветку develop. Она создаётся  из ветки  master 

         git checkout -b develop master  

Проверяем сколько у нас веток  

         git branch -a

![Git](./assets/16.png)

Мы видим что у на две ветки Develop и master. Активная ветка Develop.

давайте создадим в этой ветки еще две паки js и css

         mkdir js css

и проверим с помощью команды 
      
        ll

![Git](./assets/17.png)



Делаем комит и переходим в ветку master. Для того что перейти в ветку master используем команду  



         git switch master



![Git](./assets/18.png)

проверяем какие файлы у нас содержит ветка  master

         ll

 ![Git](./assets/19.png)

 Давайте сольем ветку  develop в  ветку  master 

         git merge develop


 ![Git](./assets/20.png)


 Проверяем файлы в ветки master


          ll

 ![Git](./assets/21.png)








    




    







