# Modelo inicial do banco de dados
## Usuário
id_usuario; nome; e-mail; senha.
## Disciplina
id_disciplina; nome; semestre/período.
## Tarefa
id_tarefa; titulo; descricao; prazo; prioridade; status.
## Pasta
id_pasta; nome.
## Arquivo
id_arquivo; nome; tipo.
## Relacionamentos
Um usuário pode ter várias disciplinas e várias tarefas.

Uma disciplina pode ter várias tarefas e várias pastas.

Uma pasta poderá ter vários arquivos.
