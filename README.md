# Разработка системы внутренней аналитики для сервиса автоматической проверки домашних заданий

### Выпускная квалификационная работа
### Образовательная программа магистратуры «Машинное обучение и высоконагруженные системы» по направлению подготовки 01.04.02 Прикладная математика и информатика

### Выполнил: Диков Артем Владимирович

### Руководитель: Ахтямов Павел Ибрагимович, преподаватель ФКН НИУ ВШЭ

#### Целью данной работы является разработка системы внутренней аналитики, обеспечивающей поддержку принятия решений по следующим направлениям:
- развитие и улучшение сервиса проверки домашних заданий;
- эксплуатация и масштабирование сервиса;
- улучшение и доработка домашних заданий преподавателями курсов.

#### Описание данных
Для проверки домашних заданий студенты отправляют submissions (далее по тексту - посылки) в систему. Посылка содержит выполненное домашнее задание, а также служебную информацию, необходимую для запуска автоматической проверки домашнего задания системой. Все посылки логируются. Данные, извлекаемые из посылок, используются для внутренней аналитики. 

#### Задачи:
1. Проанализировать структуру и содержание посылок, используемых в системе автоматической проверки домашних заданий.
2. Разработать модель данных для удобного хранения и анализа информации, извлекаемой из посылок.
3. Подобрать и внедрить инструменты и библиотеки для интерактивного отображения аналитической информации.
4. Разработать дашборды для продуктовой аналитики.
5. Интегрировать разработанные дашборды в сервис и обеспечить к ним доступ пользователей, обладающих необходимыми для просмотра дашбордов правами доступа.
6. С использованием программной системы Grafana разработать дашборды для мониторинга технической информации и оценки нагрузки на систему.

#### План и ориентировочные даты выполнения:
1. Анализ структуры и содержания посылок, используемых в системе, и разработка модели данных (25.03)
2. Внедрение в разработку инструментов и библиотек для интерактивного отображения данных (08.04).
3. Разработка дашбордов для продуктовой аналитики и их интеграция в сервис (10.05).
4. Разработка дашбордов с помощью Grafana для мониторинга технической информации (01.06)

#### Итоговый продукт
Система, которая интегрирована в сервис проверки домашних заданий и осуществляет аналитику, предназначенную для поддержки принятия решений по следующим основным направлениям:
- развитие и улучшение сервиса проверки домашних заданий;
- масштабирование ресурсов;
- улучшение и доработка домашних заданий преподавателями курсов.

Стек технологий: Angular, Django REST Framework, PostgreSQL, Prometheus, Grafana, Kubernetes.


