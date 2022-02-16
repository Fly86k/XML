XML
 21. Создать внешний репозиторий c названием XML.  
 >**github.com->repositories->press "New"->giving name to repository-> click on "Create repository"**
 22. Клонировать репозиторий XML на локальный компьютер.  
 >**GitHub->копируем адрес созданного репозитория XML->в GitBash пишем $ git clone https://github.com/Fly86k/XML.git**
 23. Внутри локального XML создать файл “new.xml”.  
 >**$ touch new.xml**
 24. Добавить файл под гит.  
 >**$ git add new.xml**
 25. Закоммитить файл.  
 >**$ git commit -m "create new file"**
 26. Отправить файл на внешний GitHub репозиторий.  
 >**$ git push**
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
 >**$ vim new.xml**  
 >>**<About_Me>**
    >>**<Name>Igor</Name>**  
	>>**<Last_name>Fil</Last_name>**  
	>>**<Age>35</Age>**  
	>>**<Pets>**  
	>>>**<Type_of_pet>Dog</Type_of_pet>**  
	>>>**<Breed_of_dog>English cocker spaniel</Breed_of_dog>**  
	>>>**<Gender>Male</Gender>**  
	>>>**<Age>0.8</Age>**  
	>>>**<Name>Chester</Name>**  
	>>**</Pets>**  
	>>**<Future_salary>120000</Future_salary>**  
>>**</About_Me>**
 28. Отправить изменения на внешний репозиторий.  
 >**$ git add .**  
 >**$ git commit -m "Edit new.xml"**  
 >**$ git push**
 29. Создать файл preferences.xml  
 >**$ touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
 >**$ vim preferences.xml  
 >>**<Preferences>** 
 >>**<Favorite_movie>Терминатор</Favorite_movie>** 
 >>**<Favorite_TV_series>МосГаз</Favorite_TV_series>** 
 >>**<Favorite_food>Утка по Пекински</Favorite_food>** 
 >>**<Favorite_season>Лето</Favorite_season>** 
 >>**<Favorite_country>Уругвай</Favorite_country>**  
 >>**</Preferences>**
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
 >**$ touch skills.xml**  
 >**$ vim skills.xml** 
 >>**<Skills>** 
 >>**<Base_theory> 1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</Base_theory>**  
 >>**<Client-Server>2. Что такое клиент-серверная архитектура.</Client-Server>**  
 >>**<HTTP_methods>3. HTTP Методы запросов на сервер.</HTTP_methods>**
 >>**<Codes>4. Коды ответов HTTP сервера.</Codes>**  
 >>**<Structures>5. Структуры HTTP запросов и ответов.</Structures>**  
 >>**<JSON>6. Что такое JSON, XML. Их структура.</JSON>**  
 >>**<Other_skills>и другие навыки</Other_skills>**  
 >>**</Skills>**
 32. Сделать коммит в одну строку.  
 >**$ git add .**  
 >**$ git commit -m "Changes in file skills.xml and preferences.xml"**  
 33. Отправить сразу 2 файла на внешний репозиторий.  
 >**$ git push**
 34. На веб интерфейсе создать файл bug_report.xml.  
 >**в созданном репозитории клик "Add file" -> "Create new file" -> присваиваем файлу ИМЯ bug_report.xml**
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 >**click на "Commit new file"**
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
 >**в выбранном файле bug_report.чьд клик на "Edit this file"**
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 >**click на "Commit new file"**
 38. Синхронизировать внешний и локальный репозиторий XML  
 >**$ git pull**