# Установка и настройка Velocity

Пункты которые должны быть выполнены до прочтения остальных категорий: \
1 - У вас должно быть 2 сервера \
2 - Основной сервер должен быть на ядре [Paper](https://papermc.io/downloads/paper) / [Purpur](https://purpurmc.org/downloads)

## Категория 1 - Скачивание и установка ядра Velocity
Шаг 1: Заходим на официальный сайт [Velocity](https://papermc.io/downloads/velocity) и нажимаем на синюю кнопку. ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/d38e07f4-03fe-4db8-a568-22bf1f4598a4) \
Шаг 2: Зайдите на наш [сайт](https://mgr.veroid.net/), выберите сервер где у вас будет Velocity и перейдите на него. ![Screenshot_1](https://github.com/Dosto4ka/VWIKI/assets/57598008/efc57463-0c9d-4136-b2a7-01ff24f7d6b7) \
Шаг 2.1: Перейдите во вкладку <mark>`Файлы`</mark> ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f)
Шаг 2.2: Пролистните чуть ниже и найдите файл server.jar![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/2a01dff9-201b-433c-b9e3-fe3602f50390)
Шаг 3: Нажмите ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) и удалите данный файл.

Подробнее: 
1. Находим ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) справа от файла ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/7ca41560-d5a2-4750-a177-37b062e54b34)
2. Выбираем в открывшемся окне <mark>`Удалить`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/b89c9910-c009-4231-8a1f-2939698177dd)

Шаг 4: Заходим в загрузки браузера и переносим файл с ядром который недавно скачали в область где находятся другие файлы. \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/089a87f1-34f9-47df-bcfa-00bbe1a80b32)

Шаг 5: Нажмите ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) и переименуйте данный файл.

Подробнее:
1. Находим ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) справа от файла ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/5d35f620-446d-471a-8ed2-c4e703fc271c)
2. Выбираем в открывшемся окне <mark>`Переименовать`</mark> и меняем название на <mark>`server.jar`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/0d7a074a-567e-495f-a0fb-96167d0c9a31)

Шаг 6: Перейдите во вкладку <mark>`Параметры запуска`</mark>![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/3857f6df-5660-4bba-a7b8-6743866e613e)
Шаг 6.1: Нажмите на версию вашей Java.
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/20251b27-8159-4bd1-8f93-22f14fc76668)
Шаг 6.2: Выберите значение <mark>`Java 16`</mark> или <mark>`Java 17`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/8ef6475f-eb66-4fe7-ae23-6a8ad06a83c2)

Шаг 7: Запустите сервер Velocity используя вкладку <mark>`Консоль`</mark> ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/24d55d10-ee7d-43d6-9955-b4ab22cc7006)

## Категория 2 - Настройка Velocity
Шаг 1: Перейдите во вкладку <mark>`Файлы`</mark> ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f)
Шаг 2: Найдите файл с названием <mark>`Velocity.toml`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/93545e21-f4a3-4290-8099-021444e04204)

Шаг 3: Просмотрите файл и найдите 16 строку \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/081ca7d2-1887-40a0-9980-1aba43d67701) \
Шаг 3.1: Измените значение online-mode с <mark>`true`</mark> на <mark>`false`</mark>.

Шаг 4: Найдите 37 строку \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/58f0d09d-ccc6-426f-8bc1-f52cd13a6c30) \
Шаг 4.1: Измените значение player-info-forwarding-mode с <mark>`NONE`</mark> на <mark>`modern`</mark>.

Шаг 5: Найдите 75 строку \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/a6e0dc28-d6a5-48a4-93f9-d4a6ed74a203) \
Шаг 5.1: Измените значение <mark>`127.0.0.1:30066`</mark> на <mark>`172.18.0.1:port`</mark> в изменённом варианте нужно сменить port на порт вашего основого сервера и у вас есть возможность изменить название <mark>`lobby`</mark> на то которое вам нужно.

Шаг 6: Найдите 81 строку \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/ae1ffc17-40b0-4802-abf6-e85c6ea8d5c6) \
Шаг 6.1: Измените значение <mark>`lobby`</mark> на то имя которое вы поставили в шаге 5.1

Шаг 7: Найдите файл с названием <mark>`forwarding.secret`</mark> и скопируйте то что в нём находится, оно вам понадобится в категории 3.

Шаг 8: Перезапустите сервер Velocity используя вкладку <mark>`Консоль`</mark> ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/24d55d10-ee7d-43d6-9955-b4ab22cc7006)

## Категория 3 - Настройка Paper / Purpur
Шаг 1: Находим с левой стороны <mark>`Мои сервера`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/06b65aa6-f472-4c80-8317-2528ef9c22b5) \
Шаг 1.1: Выберите ваш основной сервер и перейдите на него.
![Screenshot_1](https://github.com/Dosto4ka/VWIKI/assets/57598008/efc57463-0c9d-4136-b2a7-01ff24f7d6b7) \

Шаг 2: Перейдите во вкладку <mark>`Файлы`</mark> ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f)

Шаг 3: Пролистните чуть ниже и найдите файл <mark>`paper.yml`</mark>

Шаг 4: Найдите в данном файле категорию <mark>`velocity-support`</mark> \
![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/d59f3936-2a98-448f-ac41-aca597de5c2c) \
Шаг 4.1: Измените значение enabled с <mark>`false`</mark> на <mark>`true`</mark>. \
Шаг 4.2: Измените значение secret на то что вы скопировали. (2 категория, шаг 7)

Шаг 5: Перезапустите оба сервера.

## Небольшая заметка:
Подключаться нужно через Velocity. **Напрямую подключиться к указанному в конфигурации серверу не получиться!**
В случае если остались вопросы или данная статья вам не помогла, обратитесь в тикеты.
