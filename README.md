# Pastebin
Projeto de uma API simples de pastebin

# Dependências
- python - Versão 3.5+
- asgiref==3.3.4
- Django==3.2.4
- djangorestframework==3.12.4
- Pygments==2.9.0
- python-decouple==3.4
- pytz==2021.1
- sqlparse==0.4.1

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
7. Teste a instalação carregando o servidor de desenvolvimento (http://localhost:8000 no navegador):
```
(venv) python manage.py runserver
```