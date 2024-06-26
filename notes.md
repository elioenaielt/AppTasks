# LISTA DE TAREFAS

Uma aplicação frontend com HTML, CSS e JS para gerir tarefas.
No Backend vamos ter uma API NodeJS + Express + MySQL para servit o frontend

# BASE DE DADOS

    user
        id 
        username
        password
        created_at
        updated_at

    tasks
        id
            id_user
            task_text
            task_status(new | in progres | canceled | done)
            created_at
            updated_at

# TAREFAS A DESENVOLVER NO PROJETO

    > criar a estrutura inicial
        -base do frontend(html css jss| bootstrap)
        -base do backend (node + express + mysql) com uma resposta padrão
    
    > no frontend
    - páginas necessárias para a navegação do app.
    - pequenos testes de comunicalão entre front e backend - utilizaçao de Ajax(XMLhttprequest | fetch API)



    estrutura base de cada página
        bootstrap(slate) bootswatvh
        fontawesome

    - ver tarefas
        titulo
        filtro para escolher que tarefas queremos ver(select)
        botao para adicionar tarefas
        (mensagem sobre facto de nao existirem tarefas)
        caixa para tarefas
            - possibilidade de alterar o status, editar tarefa e eliminar tarefa
            paragrafo com o total de tarefas disponiveis(de acordo com o filtro)
        
    -adicionar tarefa
        input:text com o texto da tarefa
        botão para cancelar
        botão paara submeter tarefa
            
    - edtar tarefa
        input:text para editar o texto da tarefa
        botão para cancelar
        botão para submeter alteração

    (eliminar será feito com uma modal)