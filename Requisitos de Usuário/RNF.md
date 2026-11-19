# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utilizando a técnica de Brainstorm.</p>

| ID   |                                 Requisito NF                              | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: |:-------------: | :--------: | :-----------------: |
| RNF01 | A partir da tela inicial o usuário deve ser capaz de consultar sua rotina do dia em até 3 cliques. | Produto/Usabilidade | Média | - |
| RNF02 | O pacote de instalação do sistema não deve ser superior a 1 Gigabyte. | Produto/Eficiência | Alta | - |
| RNF03 | As operações de cadastro, consulta, edição e exclusão devem ser concluídas em até 3 segundos, em condições normais de conexão. | Produto/Eficiência | Alta | - |
| RNF04 | A partir da tela inicial o usuário deve ser capaz de consultar sua rotina de outros dias do mês em até 7 cliques. | Produto/Usabilidade | Média | - |
| RNF05 | O sistema não deve exibir os dados de um usuário a outros usuários. | Externos/Éticos | Alta | RF02, RNF06 |
| RNF06 | O sistema deve armazenar e gerenciar os dados do usuário conforme a Lei Geral de Proteção de Dados. | Externos/Legais  | Alta | RF01, RF02, RF03 |
| RNF07 | O sistema deve enviar as notificações de lembrete até 1 minuto após o horário definido. | Produto/Eficiência | Alta | RF07, RF08 |
| RNF08 | O sistema deve permitir o uso e a consulta de tarefas, notas e hábitos já salvos mesmo quando o dispositivo estiver sem conexão com a internet (Modo Offline). | Produto/Disponibilidade | Média | - |
| RNF09 | O código-fonte do sistema deve ser versionado utilizando o Git e mantido em um repositório centralizado no GitHub. | Organizacional/Implementação | Alta | - |
| RNF10 | O sistema deve exibir mensagens de erro sempre que ocorrer uma falha de validação ou conexão. As mensagens de erro devem informar o que ocorreu e como o usuário pode corrigir.| Produto/Usabilidade | Média | - |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>
