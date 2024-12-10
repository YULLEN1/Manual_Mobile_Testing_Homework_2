# Домашнее задание к занятию «Тестирование iOS-приложений»

### Цель задания

1. Развитие навыка сбора информации.
2. Самостоятельный анализ документации и требований Apple для приложений под iOS.
3. Умение применять полученную информацию к тестовому случаю. 

В результате выполнения задания вы:
- научитесь работать с требованиями гайдлайнов, нововведений от Apple;
- изучите, как проводить сравнительный анализ изменений версий ОС;
- познакомитесь с особенностями настройки мобильного устройства для подключения к тестированию.

### Инструкция к заданию

1. Скопируйте шаблон таблицы по [ссылке](https://u.netology.ru/backend/uploads/lms/content_assets/file/1033/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_1_2__MQA_1.2_.xlsx).
2. В названии файла введите корректное название лекции, ваши фамилию и имя.
3. Зайдите в «Настройки доступа» и выберите доступ «Просматривать могут все в интернете, у кого есть ссылка». [Ссылка на инструкцию](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop), как предоставить доступ к файлам и папкам на Google Drive.
4. В таблице прикрепите ссылки на выполненную работу по каждому заданию. Пожалуйста, прикладывайте прямые ссылки на скриншоты.
5. В личном кабинете прикрепите ссылку на свою таблицу с решениями и ждите, когда преподаватель её проверит.
6. Дополнительные задачи, отмеченные звёздочкой (*), выполняются по желанию. При помощи них можно получить дополнительную практику.
7. Выполненные задания можно прислать как по отдельности, так и все вместе. Во время проверки по частям у вашей домашней работы будет статус «На доработке».

------

## Задание 1
Вы работаете в игровой студии по разработке мобильных игр, которых за годы работы было выпущено очень много. Какие-то из них успешно стартовали и продолжают приносить стабильный доход, другие компания забросила и давно не обновляла в App Store.

На днях от App Store пришло письмо с предупреждением, что если в ближайшее время не будет обновления приложения, то одну вашу игру, которая когда-то была очень популярна, удалят из магазина.

Ваша компания решила возродить приложение, особо не меняя дизайн и делая ставку на то, что пользователям понравится ретростиль. 
В ближайшее время планируется доработать только систему регистрации и авторизации через соцсети, возможность сбора аналитики и активной push-коммуникации с помощью интеграции сервиса Firebase для ускорения роста конверсии. Регистрация по email для сохранения прогресса пользователей уже была реализована раньше.

Последний раз приложение обновляли с выпуском iOS 13.

**Что нужно сделать:**

1. Проанализировать выпуски следующих версий после iOS 13 и новых требований к приложениям от Apple.  
2. Определить, какие особенности этих версий iOS и требования от Apple важно учесть при доработке приложения.

Результат выполнения — ссылка на Google Docs в свободной форме с примерами анализируемых источников информации и списком важных моментов, которые необходимо учесть при решении поставленной задачи.

## Задание 2
Команда вашего друга несколько лет трудилась над фитнес-приложением. Процесс сильно затянулся, но в итоге приложение создали и наполнили контентом для тренировок.
После долгой разработки и тестирования приложение наконец-то отправлено на ревью для релиза в App Store. Но Apple отказал в его размещении с формулировкой:
«Не соответствует [установленным гайдлайнам](https://developer.apple.com/app-store/review/guidelines/) публикации в App Store». Версия на русском есть [по ссылке](https://habr.com/ru/post/574850/).
Другой дополнительной информации предоставлено не было.
Ваш друг запросил детали, и, чтобы не терять времени, попросил вас помочь проанализировать по предоставленным данным, что не так с приложением.

**Данные приложения:**

1. Название: Ad Workout X.
2. Возрастная категория: 4+.
3. Категория: здоровье и фитнес.
4. Язык: английский.
5. [Cкриншоты для App Store.](https://drive.google.com/drive/folders/1BJdfyQA8RDdcTpHRlBrtUBbfP8ykeaX4)
6. [Видео разделов приложения.](https://u.netology.ru/backend/uploads/lms/content_assets/file/1034/ABS_Workout_X_video.MP4)

**Что нужно сделать:** 

1. Проведите  анализ соответствия приложения гайдлайнам iOS. 
2. Обратите внимание на важные  моменты: иконка, скриншоты, авторизация, вид элементов экрана, селекторов, отображение кнопок, навигации, работа приложения с использованием нативных жестов.
4. Определите минимум три пункта несоответствия требованиям.

Результат выполнения — ссылка на на Google Docs с ответом в свободной форме. 

## Задание 3
Вы только устроились в компанию тестировщиком мобильных приложений. В первый же день вас попросили присоединиться к тестированию срочной сборки и через тимлида iOS-разработки добавить ваше новое тестовое устройство в TestFlight. Вы отправляете ему необходимые данные.

**Что нужно сделать:** 

- определите, какие данные вы передадите, чтобы вас смогли оперативно добавить в TestFlight. 

Результат выполнения — список требуемых данных в [предложенном шаблоне](https://u.netology.ru/backend/uploads/lms/content_assets/file/1033/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_1_2__MQA_1.2_.xlsx).

## Задание 4* 
Установка сборки с TestFlight. Выполняется при наличии тестового устройства iOS. 

1. Зайдите на [сервис](https://departures.to/).
2. Попробуйте присоединиться к бета-тестированию любого понравившегося вам приложения.
3. Установите последнюю сборку.

Результат выполнения — ссылка на скриншот установленного приложения с TestFlight.

-------

### Критерии оценки

1. Зачёт — выполнены все задания, ответы даны в развёрнутой форме, в решениях нет противоречий и нарушения логики. Задачи повышенной сложности, отмеченные звёздочкой, выполняются по желанию. 
2. На доработку — задания выполнены частично или не выполнены совсем, в логике решения заданий есть противоречия и существенные недостатки.

Любые вопросы по решению задач задавайте в чате учебной группы.

# [Решение](https://docs.google.com/spreadsheets/d/1h9n2UK923i8tGZhRNFTLrjBiTgd3j3m6/edit?gid=2043918268#gid=2043918268)
