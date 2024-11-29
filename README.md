# Iris
откройте Powershell в каталоге, а затем скопируйте и вставьте все эти команды в терминал (при последней команде потребуется нажать Enter, чтобы запустить приложение)

Первоначальная установка:

    python -m venv .venv

    .venv\Scripts\Activate.Ps1

    python -m pip install --upgrade pip

    pip install -r requirements.txt

    uvicorn use:app

Дальнейший запуск:

    .venv\Scripts\Activate.Ps1
    uvicorn use:app