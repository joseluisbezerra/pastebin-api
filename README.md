# Pastebin
Projeto de uma simples API REST de pastebin feito com o Django REST Framework

# Instalação
1. Crie um ambiente virtual:
```
python3 -m venv venv
```
2. Ative o ambiente virtual;
3. Instale as dependências:
```
(venv) pip install -r requirements.txt
```
4. Em seguida você vai precisar criar um arquivo .env:
```
(venv) python contrib/env_gen.py
```
5. Sincronize a base de dados:
```
(venv) python manage.py migrate
```
6. Crie um super usuário (Administrador do sistema):
```
(venv) python manage.py createsuperuser
```
7. Teste a instalação carregando o servidor de desenvolvimento (http://localhost:8000):
```
(venv) python manage.py runserver
```