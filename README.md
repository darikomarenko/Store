# Локальный запуск

0. установить зависимости `pip install -r requirements.txt`
1. запустить postgres
2. запустить redis-server
3. запустить celery `python3 -m celery -A store worker --events -B -S django -l debug`
4. запустить store `manage.py runserver`