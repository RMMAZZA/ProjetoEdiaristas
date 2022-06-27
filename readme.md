# Projeto e-diaristas 

### Instalando o projeto

#### Clonar o projeto
`git clone https://github.com/RMMAZZA/ProjetoEdiaristas.git`

#### Instalar dependências
`pip install -r requirements.txt`

#### Alterar configurações do BD no arquivo 'settings.py'
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nome_do_bd',
        'HOST': 'host_do_bd',
        'PORT': porta_bd,
        'USER': 'usuário_bd',
        'PASSWORD': 'senha_bd'

```

#### Migrar o banco de dados
`python manage.py migrate`

#### Iniciar o servidor
`python manage.py runserver`
