
# Sistema de Gestão de Estoque (SGE)

Bem-vindo ao Sistema de Gestão de Estoque (SGE), um projeto desenvolvido em Django e Bootstrap 5 para facilitar o gerenciamento de estoque. Este README fornece informações essenciais sobre como configurar e executar o projeto em seu ambiente local.

## Requisitos:

Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

- Python (versão recomendada: 3.7 ou superior)
- Django (instalado automaticamente ao seguir as instruções abaixo)
- Outras dependências listadas no arquivo `requirements.txt`

## Criação do Ambiente Virtual:

Certifique-se de que você está no diretório do projeto e crie o ambiente virtual com o comando:
```bash
python3 -m venv venv
```

## Instalação das Dependências:

Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:
```bash
pip install -r requirements.txt
```

## Rodando o Projeto:

Após instalar as dependências, aplique as migrations no banco de dados com o comando:
```bash
python manage.py migrate
```

Criar um super usuário com o comando:
```bash
python manage.py createsuperuser
```

Agora, o projeto já pode ser inicializado com o comando:
```bash
python manage.py runserver
```

OBS: Esse comando subirá um servidor local de desenvolvimento.

Após isso, o sistema poderá ser acessado em:
[http://localhost:8000/admin](http://localhost:8000/admin)

Você será direcionado para a tela de login do Admin do Django. Para acessar, bastar informar as credenciais criadas através do comando `python manage.py createsuperuser`
