# cft-java-test-task-2025

Работа над тестовым заданием проводилась на ОС Linux Ubuntu 24.04 LTS

Инструкция по запуску:

В папке startup:
1.1. java -jar application.jar < опции коммандой строки, например: -p result- > < список входных файлов >

В корневой папке проекта:
2.1. Для компиляции: mvn clean compile assembly:single

2.2. Для запуска: java -jar target/cft-task-1.0-SNAPSHOT-jar-with-dependencies.jar < опции коммандой строки > < список входных файлов >

Доп. данные:

Java: 17

Система сборки: Apache Maven 3.6.3

Доп. библиотеки: Jcommander 1.78 (https://mvnrepository.com/artifact/com.beust/jcommander/1.78)
