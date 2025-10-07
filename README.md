# SuaPrimeiraPaginaDeMarco

Projeto Django desenvolvido como introdução ao padrão **MVT**.

## Requisitos

- Python 3.x  
- Django (instalar com `pip install django`)

## Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/SuaPrimeiraPaginaDeMarco.git
   cd SuaPrimeiraPaginaDeMarco

# Execute as Migrações
python manage.py makemigrations
python manage.py migrate

# Rode o Servidor
python manage.py runserver

# Acesse o navegador
http://127.0.0.1:8000/

# Funcionalidades
Criar Autores, Categorias e Posts.

Exibir posts na página inicial.

Buscar posts por título.

# Ordem para testar
Crie um Autor.

Crie uma Categoria.

Crie um Post (vinculando autor e categoria).

Vá na página de Busca e pesquise pelo título do post.
