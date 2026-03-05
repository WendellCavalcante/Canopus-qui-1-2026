DOCUMENTO VISÃO



Grupo: Canopus



1 - Introdução: 

&nbsp;	O sistema Cash Alert é uma plataforma web que tem o propósito de garantir o controle e planejamento do financeiro para observar a movimentação. Evitando atrasos de contas por meio de alertas e lembretes inteligentes via e-mail. Estes são baseados em datas e em prazos de valores de entrada e saída, seguindo todos os dados de receitas e despesas inseridos pelo usuário. O sistema apresenta os dados de forma analítica, transformando registros brutos em informações úteis para o planejamento de curto e longo prazo. A aplicação é estruturada no padrão Model-View Controller (MVC), garantindo escalabilidade e separação de responsabilidades. Para assegurar a integridade e a confiança do usuário, o sistema adota políticas de governança de dados em conformidade com a LGPD e mecanismos de segurança via OpenID. Com alta disponibilidade e suporte a operações offline, o Cash Alert atua não apenas como um relatório de dados, mas como uma ferramenta de apoio à saúde financeira, reduzindo a ansiedade causada pelos esquecimentos de prazos e pela falta de organização.



2 - Objetivos do sistema:

	

&nbsp; Pessoas sofrem com a falta de controle de suas finanças por não terem uma visão concreta e completa de suas movimentações, gerando uma série de problemas, como: atrasos em pagamentos, débitos de multas com altos juros, acúmulo de contas ignoradas, gastos excessivos e invisíveis e falta de planejamento adequado, que podem levar o indivíduo à deficiência de retenção de dinheiro, prejuízos com dívidas e estresse/ansiedade frequente com suas finanças. Para resolver essas questões, Cash Alert atua na disponibilidade de inserção de gastos fixos e variáveis, que irão proporcionar uma visão completa das movimentações realizadas pelo usuário. Além disso, possui um sistema de alertas via e-mail que irá notificar o usuário do vencimento de suas contas e lembrá-lo de especificações financeiras a partir de alertas personalizados. O sistema também possibilita o cadastro de receitas e reservas mensais, que integram o dashboard completo para visão das movimentações e a manutenção dos históricos mensais, gerando, assim, um controle completo das finanças do usuário, para que encontre a sensação de prosperidade financeira a partir do seu gerenciamento adequado.



3 - Stakeholders usuários e clientes: 

Usuário: utilizador do sistema, é o único impactado com este sistema, capaz de realizar todas as funcionalidades.



4 - Escopo:

Cadastrar perfil do usuário (registrar por CPF, nome, contato e senha);

Registrar saldo inicial (preencher/editar o salto total no momento do acesso);

Cadastrar receitas (preencher saldos do mês com categoria, data e valor);

Cadastrar despesas (preencher despesas do mês com categoria, data e valor);

Cadastrar reservas financeiras (preencher com valor em poupança, caixinha ou investimento com informações de categoria e valor);

Classificar despesas como fixas ou variáveis (definir o cronograma de repetição das despesas, como isolada, diária, mensal, semanal, em dias úteis, anual);

Configurar alertas para vencimento de despesas (definir canal \[email ou telefone], configurar a mensagem exibida, quantidade de alertas por data e horário);

Configurar alertas personalizados (Configurar alertas baseados em uma data e hora especificada pelo usuário);

Visualizar registros em formato de calendário (Visualizar registros criados pelo usuário baseadas em mês e dia por calendário do sistema);

Vincular registros em calendário externo (Vincular registros no calendário do teams e/ou google calendar);

Gerar relatório financeiro mensal (Gerar relatório ao final de todo mês especificando as ações financeiras dos usuários);

Realizar buscas por filtros (Realizar buscas nos registros com base em suas características: valor, tipo, categoria e intervalo de tempo);

Criar históricos dos relatórios mensais (Gerar relatórios com base nos registros e intervalo de tempo definido pelo usuário).



5 - Restrições:

Funcionalidade apenas web, precisa de conexão.

O sistema não consegue descobrir saldos e despesas além do que for registrado pelo usuário.



6 - Critérios de sucesso: 

Teste de software para validação da performance requisitada e esperada do sistema;

Sistemas de controle de satisfação do usuário com o sistema;

Tempo de utilização da plataforma;

Indicadores de taxa de abandono.



