```
# Criar o ambiente virtual
python -m venv venv

# Ativar o ambiente virtual (Windows)
.\venv\Scripts\activate

# Instalar o Django
pip install django

# Criar o projeto
django-admin startproject project .

# Criar o app (exemplo contact)
python manage.py startapp contact
```

# Migrando a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

# Criando e modificando a senha de um super usuário

```
python manage.py createsuperuser
python manage.py changepassword USERNAME
```