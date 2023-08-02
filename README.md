# Projeto_API_Rest_Django 

## API REST com Django

Este é um projeto de exemplo que demonstra como criar uma API RESTful com Django usando o Django REST framework.

## Pré-requisitos

Certifique-se de ter o Python e o Django instalados no seu sistema.

termninal:
python --version
# Python 3.6.0

django-admin --version
# 3.2.7

Clone este repositório para o seu ambiente local:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

Execute as migrações do banco de dados:
python manage.py migrate

Crie um superusuário para acessar o painel de administração:
python manage.py createsuperuser

nicie o servidor de desenvolvimento:
python manage.py runserver

obs: utilize python3 para qualquer ação no terminal 

A API estará disponível em http://localhost:8000/.

Endpoints

Aqui estão alguns endpoints disponíveis nesta API:

1.GET /api/tasks/: Retorna a lista de tarefas.

2.POST /api/tasks/: Cria uma nova tarefa.

3.GET /api/tasks/{id}/: Retorna os detalhes de uma tarefa específica.

4.PUT /api/tasks/{id}/: Atualiza uma tarefa existente.

5.DELETE /api/tasks/{id}/: Exclui uma tarefa.





