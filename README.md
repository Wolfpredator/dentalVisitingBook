# dentalVisitingBook
[Требования][1] 
[Установка Maven][2] 
[Сборка проекта][3]
[Использование собранного проекта][4]
[1] Требования H1
=================
- Java 9.0
- Maven

[2] Установка Maven H1
======================
Установка необходима только в случае осутсвия Maven на устройстве, на котором будем осуществлятся сборка проекта. Для проверки можно в командной строке написать `mvn -v`
1. Скачать архив - <http://mirror.linux-ia64.org/apache/maven/maven-3/3.6.0/binaries/apache-maven-3.6.0-bin.zip>
2. Распаковать в любую дерикторию
3. Прописать путь до ./maven/bin/ в перменную PATH операционной системы. 

[3] Сборка проекта H1
======================
1. Через консоль перейти в каталог с файлом pom.xml
2. Прописать `mvn clean compile assembly:single`

[4] Использование собранного проекта H1
=======================
