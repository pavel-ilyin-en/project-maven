# Игра "гонки"

Задание: Нужно сделать исполняемый JAR-файл с игрой на JavaFX через графический движок от JavaRush
Link: https://javarush.com/quests/lectures/jru.module3.lecture00

- Билд **mvn clean install** , результат - jar со всеми зависимостями внутри в папке lib/
- Запуск игры через **mvn javafx:run** - игра запускается
- Запуск **<путь к java 18> -jar <имя результирующего jar файла>** - игра запускается

- закомментирована часть xml для копирования зависимости из папки проекта в локальный репозиторий, плагин maven-install; копирование сделано в командной строке maven **mvn install:install-file -Dfile:C:\Users\pavel\IdeaProjects\project-maven\lib\desktop-game-engine.jar -DgroupId="com.javarush" -DArtifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar**
