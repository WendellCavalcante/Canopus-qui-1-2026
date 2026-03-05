🧠 **BRIEFING**

**1. Informações gerais** 

1.1 Nome do sistema: Cash Alert <br>
1.2 Nome da equipe: Canopus
 <br> <br><br>
**2. Problema e/ou necessidade**

2.1 Qual é o problema e/ou necessidade que o software deve resolver:  <br>
O sistema tem o propósito de garantir controle e planejamento financeiro para visualizar movimentações e evitar atrasos por meio de alertas e lembretes baseados em datas, prazos e valores de entrada e saída.

2.2 Quais são as dores dos usuários:  <br>
Boletos e contas atrasando ou vencendo; <br>
Geração de multas e juros; <br>
Ansiedade financeira e problemas psicológicos. <br>

2.3 O que acontece hoje sem o sistema:  <br>
Acúmulo de contas atrasadas; <br>
Falta de organização desejada com o saldo; <br>
Esquecimento de prazos de despesas; <br>
Falta de planejamento para lidar com valores de despesas; <br>
Organização financeira em planilhas simples ou anotações informais; <br>
Não há um sistema para lembrar o usuário de seus planejamentos e despesas. <br>
 <br> <br>
**3. Escopo funcional do sistema**

3.1 Principal objetivo do sistema: <br>
Registrar receitas e despesas a fim de promover controle financeiro pessoal eficiente, prevenindo atrasos por meio de alertas automatizados de vencimentos e desorganização nos demais gastos.

3.2 Funcionalidades específicas (secundárias) do sistema: <br>
Cadastrar perfil do usuário; <br>
Registrar saldo inicial; <br>
Cadastrar receitas; <br>
Cadastrar despesas; <br>
Cadastrar reservas financeiras; <br>
Cadastrar categorias de receitas; <br>
Cadastrar categorias de despesas; <br>
Cadastrar categorias de reservas financeiras; <br>
Classificar despesas como fixas ou variáveis; <br>
Configurar alertas para vencimento de despesas; <br>
Configurar alertas personalizados; <br>
Visualizar registros em formato de calendário; <br>
Gerar relatório financeiro mensal; <br>
Realizar buscas por filtros: saldo, categoria e intervalo de tempo; <br>
Criar históricos dos relatórios mensais; <br>
 <br> <br>
**4. Escopo não funcional** <br>
Arquitetura baseada no padrão MVC (Model-View-Controller); <br>
Segurança: política de privacidade LGPD, com autenticação por senha ou token via email/telefone (OpenID); <br>
Desempenho: tempo de resposta < 2s para registrar e <3s para consultar; caching de memórias acessadas com frequência; <br>
Disponibilidade e confiabilidade: backups automáticos para cada movimentação registrada no sistema; sistema disponível 24x7x365; Em caso de indisponibilidade temporária do servidor, o sistema deverá permitir funcionamento limitado offline, com sincronização posterior; <br>
Qualidade: todas as funcionalidades serão testadas, com 100% de cobertura para os fluxos críticos, cerca de 70–80% para funcionalidades secundárias e 60–70% para requisitos de suporte e não funcionais; <br>
Usabilidade e acessibilidade: acessibilidade adequada e usabilidade onboarding (simplificada e intuitiva); <br>
Conformidade e governança de dados: classificar dados (pessoal/sensível), política de retenção. <br>
 <br> <br>
**5. Usuários** <br>
Usuário final: pessoa física interessada em organizar e controlar suas finanças pessoais por meio do registro de receitas e despesas.
 <br> <br>
**6. Entregáveis** <br>
Documento de Visão do Sistema; <br>
Diagrama de Caso de Uso; <br>
Especificação de Caso de Uso; <br>
Diagrama de Classe; <br>
Documento de Arquitetura do Sistema; <br>
Protótipo do Sistema. <br>
