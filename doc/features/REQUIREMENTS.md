# DESCRIÇÃO DO PROJETO

O candidato deve desenvolver uma aplicação simples de To-Do List usando Angular. A aplicação deve permitir que os usuários realizem as seguintes operações:

1. Adicionar Tarefa: Campo de entrada para adicionar novas tarefas.
2. ﻿﻿﻿Listar Tarefas: Exibir todas as tarefas em gima lista com as seguintes opções: Editar nome da tarefa. Excluir tarefa. Marcar como feito (com registro da data e hora da conclusão).
3. Listar Tarefas Concluídas: Uma lista separada que mostra as tarefas concluídas com a data e hora da conclusão.


## REQUISITOS

### Estrutura do Projeto 
- Utilize Angular CLI para criar a aplicação. 
- Organize o código em componentes, serviços e módulos.

#### ﻿﻿﻿Componentes 

1. AppComponent: Componente principal que gerencia o estado da aplicação.
2. TaskListComponent: Componente para listar as tarefas.
3. TaskitemComponent: Componente para cada tarefa individual, com opções de editar, excluir e marcar como feito. Completed TasksComponent: Componente para listar as tarefas concluidas.
4. Serviço TaskService: Serviço que gerencia a lógica de tarefas (adicionar, editar, excluir, marcar como feito).
5. Modelagem Crie um modelo de tarefa (Task) com as seguintes propriedades: id: número (identificador único). name: string (nome da tarefa). isCompleted: boolean (indica se a tarefa foi concluída). completionDate: Date (data e hora da conclusão).


#### TaskService
Serviço que gerencia a lógica de tarefas (adicionar, editar, excluir, marcar como feito).

#### ﻿﻿﻿Modelagem 
Crie um modelo de tarefa (Task) com as seguintes propriedades: 
- id: número (identificador único).
- name: string (nome da tarefa).
- isCompleted: boolean (indica se a tarefa foi concluida). completionDate: Date (data e hora da conclusão).


## FUNCIONALIDADES
### Adicionar Tarefa
Um campo de entrada e um botão para adicionar tarefas.

### Listar Tarefas
Mostrar todas as tarefas adicionadas.

### Cada tarefa deve ter:
- [ ] Um botão de editar que permite modificar o nome da tarefa.
- [ ] Um botão de excluir que remove a tarefa da lista.
- [ ] Um botão de "Marcar como Feito" que: Marca a tarefa como concluída.
- [ ] Registra a data e hora da conclusão.
- [ ] Listar Tarefas Concluídas
- [ ] Mostrar uma lista separada com as tarefas que foram marcadas como concluidas, exibindo a data e hora da conclusão.

## CRITÉRIOS DE AVALIAÇÃO
Funcionalidade: A aplicação atende aos requisitos especificados.

Qualidade do Código: O código é limpo, bem organizado e segue as melhores práticas do Angular.

Testes: Implemente testes unitários para o serviço e componentes principais.

Experiência do Usuário: A interface é amigável e intuitiva.
