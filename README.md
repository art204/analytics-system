# Разработка системы внутренней аналитики для сервиса автоматической проверки домашних заданий

### Выпускная квалификационная работа
### Образовательная программа магистратуры «Машинное обучение и высоконагруженные системы» по направлению подготовки 01.04.02 Прикладная математика и информатика

### Выполнил: Диков Артем Владимирович

### Руководитель: Ахтямов Павел Ибрагимович, преподаватель ФКН НИУ ВШЭ

#### Цель работы 
Разработка системы внутренней аналитики, обеспечивающей поддержку принятия решений, 
для веб-сервиса по проверке домашних заданий akhcheck.ru

#### Описание данных
Для проверки домашних заданий студенты отправляют submissions (далее по тексту - посылки) в систему. 
Посылка содержит выполненное домашнее задание, а также служебную информацию, необходимую для запуска автоматической 
проверки домашнего задания системой. Все посылки логируются. 
Данные, извлекаемые из посылок, используются для внутренней аналитики. 

#### Задачи:
1. Разработка API, который предоставляет аналитическую информацию по учебному курсу.
2. Визуализация данных и интеграция аналитических графиков в веб-сервис akhcheck.ru.
3. Разработка пользовательского интерфейса для удобного и быстрого построения графиков, а также фильтрации данных, по которым строится график.

#### План и ориентировочные даты выполнения:
1. Анализ структуры и содержания посылок, используемых в системе (25.03)
2. Внедрение в разработку инструментов и библиотек для интерактивного отображения данных (08.04)
3. Разработка API, предоставляющего аналитическую информацию по учебному курсу (01.05)
4. Разработка пользовательского интерфейса для просмотра учебной аналитики (01.06)

#### Итоговый продукт
API, который предоставляет аналитическую информацию по учебному курсу, а также графики и диаграммы для просмотра этой информации, 
интегрированные в веб-сервис akhcheck.ru.

Стек технологий: Angular, Django REST Framework, PostgreSQL, Kubernetes.

### demo
- 01 Количество посылок и пользователей в день [https://youtu.be/ImUmlwSDDIo]
- 02 Сдача задания по дням [https://youtu.be/JuTIaZziQwQ]
- 03 Количество студентов или посылок по заданиям [https://youtu.be/sDl1gtR4AqA]
- 04 Распределение оценок [https://youtu.be/eIbwT9fqJ74]
- 05 Распределение количества попыток [https://youtu.be/wWP1IAx2mjI]
- 06 Распределение студентов по преподавателям [https://youtu.be/H3t5XiLZGMA]
- 07 Распределение посылок и студентов по статусам [https://youtu.be/VuehPGSXOuE]


