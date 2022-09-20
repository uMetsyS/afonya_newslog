# Афоня
Тестовое задание: модуль логирования новостей

Установка:
1. разверните модуль в папку /local/modules/
2. Установите модуль через Административную панель Bitrix (Настройки - Модули - ! Логирование действий с новостями -> Установить) * Восклицательный знак добавлен, чтобы легче было найти модуль среди других тестовых заданий и модулей
3. В настройках модуля задайте email и период отправки

При желании в настойках можно:
* email администратора, если он отличается от текущего 
* период отправки, если требуется отправлять отчет чаще / реже
* ID Почтового шаблона, если требуется заменить на свой собтвенный
* тип инфоблока, если потребуется логировать не только новости
* дату последнего обновления, чтобы в отчет попали события только более поздней даты
* статус агента, если требуется отслеживать, но не нужно отправлять отчет

Для удобства тестирования во вкладку Контент админки выведен текущий Лог новостей и подпукнт Формирование отчета, чтобы не ждать, пока произойдет событие на CRON
