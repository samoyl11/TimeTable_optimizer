# Timetable_optimizer
## Участники проекта:
- Александр Самойленко 
- Арсений Гавриленко
- Булат Усеинов
- Кирилл Киселёв
- Постников Григорий
## Для запуска сервера локально на устройстве необходимо:
1. Установить виртуальное окружение virtualenv на компьютер.
2. Активировать виртуальное окружение для проекта, чтобы соблюдать версии всех зависимостей в проекте:
``` $ source ./env/bin/activate ```
3. Установить зависимости в активированное виртуальное окружение:
``` $ pip install -r requirements.txt ```
4. Все готово для запуска сервера, для этого необходимо запустить скрипт:
``` $ python manage.py runserver ```
5. Далее переходим по url, который высветился в терминале (по умолчанию ``` localhost:8000/ ```).
## Комментрии по работе с сайтом проекта:
- При переходе по url вы попадаете на главную страничку сайта
- На главной страничке сайта есть Navbar с кнопкой ``` optimize ```, которая откроет страничку с формой для параметров оптимизации
- В данный момент оптимизатор работает только с расписанием предзагруженным на сервер (т.е. расписанием МФТИ)

