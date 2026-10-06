# Requisitos Funcionais 

### RF01 Cadastro de Usuário
* **Descrição:** O sistema deve permitir que um novo usuário realize seu cadastro informando e-mail, nome e senha.
* **Prioridade:** Alta
* **Requisitos Relacionados:** Não aplicável

### RF02 Login de Usuário
* **Descrição:** O sistema deve permitir que o usuário realize login para acessar suas informações e funcionalidades pessoais.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF01

### RF03 Gerenciamento dos dados pessoais do usuário
* **Descrição:** O sistema deve permitir que o usuário acesse e gerencie suas próprias informações cadastradas no aplicativo.
* **Prioridade:** Média
* **Requisitos Relacionados:** RF01, RF02

### RF04 Gerenciamento de tarefas
* **Descrição:** O sistema deve permitir que o usuário crie, visualize, edite e exclua tarefas em uma lista, podendo marcar cada tarefa como concluída após sua realização.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF05 Gerenciamento de anotações
* **Descrição:** O sistema deve permitir que o usuário crie, visualize, edite e exclua anotações para registrar conteúdos de aulas, lembretes, ideias e outras informações relevantes.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF06 Gerenciamento de eventos
* **Descrição:** O sistema deve permitir que o usuário crie, visualize, edite e exclua eventos no calendário, informando nome, data, horário e descrição.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF07 Configuração de lembretes de eventos
* **Descrição:** O sistema deve permitir que o usuário configure lembretes para eventos cadastrados, selecionando o momento em que deseja ser notificado antes do evento.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF06

### RF08 Notificação de eventos
* **Descrição:** O sistema deve enviar uma notificação ao usuário no momento configurado para o lembrete de um evento. A notificação deve apresentar informações, como nome e horário, que permitam ao usuário identificar o evento relacionado.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF07

### RF09 Cadastro de hábitos
* **Descrição:** O sistema deve permitir que o usuário cadastre hábitos informando seu nome e, opcionalmente, uma descrição, para registrar atividades que deseja realizar de forma recorrente.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF10 Configuração de recorrência de hábitos
* **Descrição:** O sistema deve permitir que o usuário configure a recorrência de seus hábitos, podendo definir uma frequência diária ou semanal, o horário de realização e, no caso de frequência semanal, o dia da semana.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF09

### RF11 Visualização de hábitos
* **Descrição:** O sistema deve permitir que o usuário visualize os hábitos cadastrados e suas respectivas frequências.
* **Prioridade:** Média
* **Requisitos Relacionados:** RF09, RF10

### RF12 Notificação de hábitos
* **Descrição:** O sistema deve permitir que o usuário configure e receba notificações para lembrá-lo da realização de seus hábitos.
* **Prioridade:** Média
* **Requisitos Relacionados:** RF09, RF10

### RF13 Sugestões de hábitos
* **Descrição:** O sistema deve disponibilizar sugestões de hábitos que o usuário possa adicionar à sua rotina.
* **Prioridade:** Baixa
* **Requisitos Relacionados:** RF09

### RF14 Criação de metas
* **Descrição:** O sistema deve permitir que o usuário crie metas de médio ou longo prazo relacionadas aos estudos ou a objetivos pessoais, sendo necessário definir etapas para cada meta criada.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF15 Criação de etapas de metas
* **Descrição:** O sistema deve permitir que o usuário crie etapas para suas metas, informando obrigatoriamente o nome da etapa e, opcionalmente, sua descrição e prazo.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF14

### RF16 Acompanhamento de progresso das metas
* **Descrição:** O sistema deve permitir que o usuário acompanhe o progresso de suas metas por meio da quantidade de etapas concluídas. Cada etapa deve poder ser marcada como concluída ou não concluída, e a meta deve ser considerada concluída quando todas as suas etapas forem marcadas como concluídas.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF14, RF15

### RF17 Temporizador de estudos
* **Descrição:** O sistema deve permitir que o usuário utilize um temporizador para organizar suas sessões de estudo, apresentando uma configuração padrão de 25 minutos de estudo e 5 minutos de descanso e permitindo que o usuário altere esses períodos conforme sua necessidade.
* **Prioridade:** Alta
* **Requisitos Relacionados:** RF02

### RF18 Registro de sessões de estudo
* **Descrição:** O sistema deve registrar o tempo utilizado pelo usuário em suas sessões de estudo realizadas por meio do temporizador.
* **Prioridade:** Média
* **Requisitos Relacionados:** RF17

### RF19 Consulta do histórico de estudos
* **Descrição:** O sistema deve permitir que o usuário consulte as informações registradas sobre suas sessões de estudo.
* **Prioridade:** Média
* **Requisitos Relacionados:** RF18


















