# Вступление

Данный репозиторий предназначен для выкладки и показа личных наработок по направлению DevOps

## Github Actions. Срабатывание workflow по ключевому слову в комментарии к PR и checkout в нужную ветку

Создан workflow, который по ключевому слову deploy в комментарии к PR (раздел Conversation) запускает дальнейшие jobs.
При этом также осуществляется сбор информации о вливаемой ветке (source branch или head ref), чтобы сделать корректный checkout в нее при клонировании репозитория. Это необходимо для сборки и деплоя нужной ветки на тот или иной стенд.
