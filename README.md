# MKR2 — Django Recipes App

Це веб-додаток на Django для збереження кулінарних рецептів з категоріями, інгредієнтами, інструкціями та інтерфейсом на HTML-шаблонах.

## Технології
- Python 3.x
- Django 4.2
- HTML / Templates
- SQLite
- (опційно) Heroku

## Як запустити локально

```bash
git clone https://github.com/byblic/MKR2.git
cd MKR2
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
