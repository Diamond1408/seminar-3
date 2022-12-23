# Инструкция по работе с Git


## Что такое гит
***Git*** - самая популярная рализация распределенной системы контроля версий (версионность поддерживается и на сервере и у каждого клиентак). Самой распространенной реализацией ***Git*** является (GitHub)[https://github.com]


## Подготовка репозитория
Для создания репозитория используется команда *Git init*. Для этого необходимо открыть в терминале папку с будущим репозиторием и написать *git init*

## Cоздание коммитов


### Добавленеи файлов к комиту
Для добавление файла к новому коммиту используется команда *git add*. Используется она следующим образом: в терминале с папкой репозиторием пишем *git add <название файла>*.

## Cоздание коммита
для создания новой фиксации (коммита) используется команда *git commit*. для этого в терминале с папкой-репозиторием пишем *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***

## Журнал изменений
для просмотра истории изменений используется команда *git log*. для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Перемещение между коммитами
для перемещени на другую фиксацию (коммит) используется команда *git checkout*. Для этого необходимо, как показано в прошлом пункте, в журнале изменений найти необходимый коммит и его хеш(номер), после чего в терминале с папкой-репозиторием надо написать *git checkout <хеш коммита>*. После выполнения этой команды мы попадаем в состояние **detached head**, в котором никаие следующие коммиты сохроняться не будут. Для выхода из этого состояния необходимо написать *git checkout master*. 


## Журнал изменений
для просмотра истории изменений используется команда *git log*. для этого в терминале с папкой-репозиторием необходимо написать *git log*.


## Ветки в гит
### создание веток в гит
Для созданий веток используем команду git branch

### Перемещение между ветками
Для перехода на другую ветку используется команда **

## Слияние веток и разрешение конфликтов

## Удаление веток

