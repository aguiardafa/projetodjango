# Simplificar comando para rodar Servidor Localmente

Configuração de como simplificar o comando de rodar o servidor local do Django

### Para quem usa Windows:

1. Crie o arquivo: nome_do_projeto\.venv\Scripts\mng.bat contendo o conteúdo do arquivo: nome_do_projeto\contrib\mng-sample

Exemplo comando na raiz do projeto:
cp contrib/mng-sample .venv/Scripts/mng.bat

2. Execute o comando doskey no Windows (dentro do projeto):

doskey mng=@python "%VIRTUAL_ENV%\..\manage.py" $*

3. Executar comando simplificado para rodar o servidor local (dentro do projeto):

mng runserver

