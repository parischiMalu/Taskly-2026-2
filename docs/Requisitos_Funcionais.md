# Requisitos Funcionais 

<table>
  <thead>
    <tr style="background-color: purple; color: white">
      <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
      <th style="border-style:solid;border-width:1px;text-align:center">Requisito Funcional</th>
      <th style="border-style:solid;border-width:1px;text-align:center">Descrição</th>
      <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
      <th style="border-style:solid;border-width:1px;text-align:center">RF relacionado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <span id="rf-01"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF01</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Cadastro de Usuário</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que um novo usuário realize seu cadastro informando e-mail, nome e senha.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Não aplicável</td>
    </tr>
    <tr>
      <span id="rf-02"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF02</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Login de Usuário</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário realize login para acessar suas informações e funcionalidades pessoais.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
    </tr>
    <tr>
      <span id="rf-03"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF03</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Gerenciamento dos dados pessoais do usuário</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário acesse e gerencie suas próprias informações cadastradas no aplicativo.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF02</td>
    </tr>
    <tr>
      <span id="rf-04"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF04</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Gerenciamento de tarefas</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário crie, visualize, edite e exclua tarefas em uma lista, podendo marcar cada tarefa como concluída após sua realização.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-05"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF05</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Gerenciamento de anotações</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário crie, visualize, edite e exclua anotações para registrar conteúdos de aulas, lembretes, ideias e outras informações relevantes.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-06"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF06</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Gerenciamento de eventos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário crie, visualize, edite e exclua eventos no calendário, informando nome, data, horário e descrição.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-07"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF07</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Configuração de lembretes de eventos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário configure lembretes para eventos cadastrados, selecionando o momento em que deseja ser notificado antes do evento.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
    </tr>
    <tr>
      <span id="rf-08"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF08</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Notificação de eventos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve enviar uma notificação ao usuário no momento configurado para o lembrete de um evento. A notificação deve apresentar informações, como nome e horário, que permitam ao usuário identificar o evento relacionado.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
    </tr>
    <tr>
      <span id="rf-09"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF09</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Cadastro de hábitos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário cadastre hábitos informando seu nome e, opcionalmente, uma descrição, para registrar atividades que deseja realizar de forma recorrente.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-10"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF10</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Configuração de recorrência de hábitos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário configure a recorrência de seus hábitos, podendo definir uma frequência diária ou semanal, o horário de realização e, no caso de frequência semanal, o dia da semana.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09</td>
    </tr>
    <tr>
      <span id="rf-11"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF11</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Visualização de hábitos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário visualize os hábitos cadastrados e suas respectivas frequências.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09, RF10</td>
    </tr>
    <tr>
      <span id="rf-12"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF12</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Notificação de hábitos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário configure e receba notificações para lembrá-lo da realização de seus hábitos, utilizando o horário definido na configuração de recorrência do hábito.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09, RF10</td>
    </tr>
    <tr>
      <span id="rf-13"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF13</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Sugestões de hábitos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve disponibilizar sugestões de hábitos que o usuário possa adicionar à sua rotina.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09</td>
    </tr>
    <tr>
      <span id="rf-14"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF14</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Criação de metas</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário crie metas de médio ou longo prazo relacionadas aos estudos ou a objetivos pessoais, sendo necessário informar um nome para a meta.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-15"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF15</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Criação de etapas de metas</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário crie etapas para suas metas, informando obrigatoriamente o nome da etapa e, opcionalmente, sua descrição e prazo.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF14</td>
    </tr>
    <tr>
      <span id="rf-16"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF16</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Acompanhamento de progresso das metas</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário acompanhe o progresso de suas metas por meio da quantidade de etapas concluídas. Cada etapa deve poder ser marcada como concluída ou não concluída, e a meta deve ser considerada concluída quando todas as suas etapas forem marcadas como concluídas.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF14, RF15</td>
    </tr>
    <tr>
      <span id="rf-17"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF17</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Temporizador de estudos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário utilize um temporizador para organizar suas sessões de estudo, apresentando uma configuração padrão de 25 minutos de estudo e 5 minutos de descanso e permitindo que o usuário altere esses períodos conforme sua necessidade. O temporizador deve permitir pausar, retomar e cancelar uma sessão.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
    </tr>
    <tr>
      <span id="rf-18"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF18</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Registro de sessões de estudo</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve registrar o tempo utilizado pelo usuário em suas sessões de estudo realizadas por meio do temporizador.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF17</td>
    </tr>
    <tr>
      <span id="rf-19"></span>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF19</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Consulta do histórico de estudos</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve permitir que o usuário consulte as informações registradas sobre suas sessões de estudo.</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
      <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF18</td>
    </tr>
  </tbody>
</table>
