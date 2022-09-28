Игра змейка.
Написана на Python 3.10.7 с использованием встроенных библиотек Tkinter и виджетов ttk.
Необходима установка библиотеки для работы с изображениями Pillow.

# Развертывание на локальной машине:
Mac OS, Linux OS
1. Создаем виртуальное окружение: python -m venv venv (или python3, если в системе стоит несколько интерпретаторов)
2. Активируем venv: source venv/bin/activate
3. Устанавливаем зависимости: pip install -r requirements.txt (pip3 если стоит несколько интерпретаторов)

Windows OS
1. Создаем виртуальное окружение: python -m venv venv (или python3, если в системе стоит несколько интерпретаторов)
2. Активируем venv: venv\scripts\activate
3. Устанавливаем зависимости: pip install -r requirements.txt (необязательный шаг, т.к. зависимостей нет).

    Если вы используете PowerShell и при активации виртуального окружения вы получаете ошибку с указанием на невозможность запуска скрипта,
то необходимо изменить политики запуска скриптов. Для этого запустите PowerShell от имени администратора и
наберите команду: Set-ExecutionPolicy -ExecutionPolicy AllSigned -Scope LocalMachine. Эта команда установит
политику запуска только подписанных скриптов для всех локальных пользователей. При дальнейшей активации
виртуального окружения нужно будет указать запускать скрипт всегда, набрав А.
4. Деактивация виртуального окружения - venv\scripts\deactivate. Если вы используете PowerShell просто закройте сеанс.
