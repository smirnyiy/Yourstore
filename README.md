<h3>Этап 1. Создание и настройка проекта.</h3>

<p>Необходимые инструменты:</p>
<p>Система контроля версий Git;</p>
<p>Аккаунт на Github;</p>
<p>Установленный локально (на вашем компьютере) Python >= 3.5.</p>

<h3>Этап 2.Порядок выполнения</h3>
<p>Создайте копию данного проекта, нажав кнопку Fork в правом верхнем углу этой страницы</p>
<p>Клонируйте репозиторий командой в вашем терминале git clone адрес_вашего_репозитория</p>
<p>Создайте виртуальное окружение для своего проекта virtualenv python -m venv venv</p>  
<p>Активируйте виртуальное окружение командой venv\Scripts\activate</p>
<p>Установите все необходимые пакеты проекта командой pip install -r ./requirements.txt</p>
<p>для создания всех миграций вы должны находиться в папке StoreOnline</p>

<h3>Этап 3.Установите миграции командой</h3>
python manage.py makemigrations
python manage.py migrate

<h3>Этап 4. Запуск проекта
Запустите сервер командой
python manage.py runserver
После запуска сервера можно открыть браузер и перейти по адресу http://localhost:8000/ или http://127.0.0.1:8000/
