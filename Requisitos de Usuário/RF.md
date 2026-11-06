# 1. Requisitos Funcionais

<p align="justify">A <i>Tabela 1</i> a seguir contém os Requisitos Funcionais (RF) elicitados.</p>

| ID | Requisito | Descrição | Prioridade | Requisitos Relacionados |
| :--: | :--: | :-- | :--: | :--: |
| <span id="rf-01"></span> RF01 | Cadastro de Usuário | O sistema deve permitir que um novo usuário realize seu cadastro informando e-mail, nome e senha. | Alta | Não aplicável |
| <span id="rf-02"></span> RF02 | Login de Usuário | O sistema deve permitir que o usuário realize login para acessar suas informações e funcionalidades pessoais. | Alta | RF01 |
| <span id="rf-03"></span> RF03 | Gerenciamento dos dados pessoais do usuário | O sistema deve permitir que o usuário acesse e gerencie suas próprias informações cadastradas no aplicativo. | Média | RF01, RF02 |
| <span id="rf-04"></span> RF04 | Gerenciamento de tarefas | O sistema deve permitir que o usuário crie, visualize, edite e exclua tarefas em uma lista, podendo marcar cada tarefa como concluída após sua realização. | Alta | RF02 |
| <span id="rf-05"></span> RF05 | Gerenciamento de anotações | O sistema deve permitir que o usuário crie, visualize, edite e exclua anotações para registrar conteúdos de aulas, lembretes, ideias e outras informações relevantes. | Alta | RF02 |
| <span id="rf-06"></span> RF06 | Gerenciamento de eventos | O sistema deve permitir que o usuário crie, visualize, edite e exclua eventos no calendário, informando nome, data, horário e descrição. | Alta | RF02 |
| <span id="rf-07"></span> RF07 | Configuração de lembretes de eventos | O sistema deve permitir que o usuário configure lembretes para eventos cadastrados, selecionando o momento em que deseja ser notificado antes do evento. | Alta | RF06 |
| <span id="rf-08"></span> RF08 | Notificação de eventos | O sistema deve enviar uma notificação ao usuário no momento configurado para o lembrete de um evento. A notificação deve apresentar informações, como nome e horário, que permitam ao usuário identificar o evento relacionado. | Alta | RF07 |
| <span id="rf-09"></span> RF09 | Cadastro de hábitos | O sistema deve permitir que o usuário cadastre hábitos informando seu nome e, opcionalmente, uma descrição, para registrar atividades que deseja realizar de forma recorrente. | Alta | RF02 |
| <span id="rf-10"></span> RF10 | Configuração de recorrência de hábitos | O sistema deve permitir que o usuário configure a recorrência de seus hábitos, podendo definir uma frequência diária ou semanal, o horário de realização e, no caso de frequência semanal, o dia da semana. | Alta | RF09 |
| <span id="rf-11"></span> RF11 | Visualização de hábitos | O sistema deve permitir que o usuário visualize os hábitos cadastrados e suas respectivas frequências. | Média | RF09, RF10 |
| <span id="rf-12"></span> RF12 | Notificação de hábitos | O sistema deve permitir que o usuário configure e receba notificações para lembrá-lo da realização de seus hábitos, utilizando o horário definido na configuração de recorrência do hábito. | Média | RF09, RF10 |
| <span id="rf-13"></span> RF13 | Sugestões de hábitos | O sistema deve disponibilizar sugestões de hábitos que o usuário possa adicionar à sua rotina. | Baixa | RF09 |
| <span id="rf-14"></span> RF14 | Criação de metas | O sistema deve permitir que o usuário crie metas de médio ou longo prazo relacionadas aos estudos ou a objetivos pessoais, sendo necessário informar um nome para a meta. | Alta | RF02 |
| <span id="rf-15"></span> RF15 | Criação de etapas de metas | O sistema deve permitir que o usuário crie etapas para suas metas, informando obrigatoriamente o nome da etapa e, opcionalmente, sua descrição e prazo. | Alta | RF14 |
| <span id="rf-16"></span> RF16 | Acompanhamento de progresso das metas | O sistema deve permitir que o usuário acompanhe o progresso de suas metas por meio da quantidade de etapas concluídas. Cada etapa deve poder ser marcada como concluída ou não concluída, e a meta deve ser considerada concluída quando todas as suas etapas forem marcadas como concluídas. | Alta | RF14, RF15 |
| <span id="rf-17"></span> RF17 | Temporizador de estudos | O sistema deve permitir que o usuário utilize um temporizador para organizar suas sessões de estudo, apresentando uma configuração padrão de 25 minutos de estudo e 5 minutos de descanso e permitindo que o usuário altere esses períodos conforme sua necessidade. O temporizador deve permitir pausar, retomar e cancelar uma sessão. | Alta | RF02 |
| <span id="rf-18"></span> RF18 | Registro de sessões de estudo | O sistema deve registrar o tempo utilizado pelo usuário em suas sessões de estudo realizadas por meio do temporizador. | Média | RF17 |
| <span id="rf-19"></span> RF19 | Consulta do histórico de estudos | O sistema deve permitir que o usuário consulte as informações registradas sobre suas sessões de estudo. | Média | RF18 |

<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>
