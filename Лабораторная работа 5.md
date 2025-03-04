# Лабораторная работа №5
В данной лабораторной работе требуется подготовить разработанное вами web-приложение к выпуску в production.
1. Создайте pom.xml файл в вашем клиентском приложении.
2. Добавьте плагин для работы с [node.js и npm](https://github.com/eirslett/frontend-maven-plugin?tab=readme-ov-file#installation) через maven.
3. Добавьте шаги выполнения плагина: установка node/npm, установка зависимостей, сборка frontend проекта.
4. Добавьте в pom.xml вашего backend приложения плагин [maven-resources-plugin](https://maven.apache.org/plugins/maven-resources-plugin/plugin-info.html). Переместите при помощи плагина собранное клиентское приложение в папку /static/ вашего собранного backend проекта.
5. Создайте pom.xml файл в родительской папке, содержащей frontend и backend часть.
6. Подключите в родительском pom.xml в качестве модулей frontend и backend часть.
7. Запустите сборку jar.
8. Запустите полученный jar. Убедитесь, что ваше приложение работоспособно.
