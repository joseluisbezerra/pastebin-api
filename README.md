# Pastebin
Projeto de uma simples API REST de pastebin feito com o Django REST Framework

# Dependências
- python - Versão 3.5+
- asgiref==3.3.4
- certifi==2021.5.30
- chardet==4.0.0
- colorama==0.4.4
- Django==3.2.4
- djangorestframework==3.12.4
- djangorestframework-simplejwt==4.7.1
- httpie==2.4.0
- idna==2.10
- Pygments==2.9.0
- PyJWT==2.1.0
- PySocks==1.7.1
- python-decouple==3.4
- pytz==2021.1
- requests==2.25.1
- requests-toolbelt==0.9.1
- sqlparse==0.4.1
- urllib3==1.26.5

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