# 🏗️ Diagrama de Classes

## 1. Introdução
Explique a importância do diagrama de classes para a modelagem estática do sistema.  

## 2. Classes Identificadas
Liste as classes principais (Ex.: Usuário, Livro, Empréstimo).  

## 3. Relacionamentos
Explique rapidamente os relacionamentos (herança, associação, agregação, composição).  

Com base nos diagramas:

**`<<include>>`**
- `IncluirPerfil` inclui `RegistroDeSaldoInicial` — ao cadastrar um perfil, o saldo inicial é registrado obrigatoriamente.
- `ConsultarAlerta` inclui `CadastroDeAlertas` — consultar um alerta sempre aciona o cadastro.
- `ConsultarReceita` inclui `CadastroDeReceitas` — idem para receitas.
- `IncluirReservaFinanceira` inclui `CadastroDeReservasFinanceiras`.
- `GerarDashboardMensal` inclui `FechamentoDeHistoricoMensal`.
- `GerarRelatorioPersonalizado` inclui `RealizarBuscasPorFiltros`.

**`<<extend>>`**
- `EfetuarLogin` e `AlterarCredenciais` estendem `AutenticacaoDeUsuario`.
- `AlterarPerfil`, `ConsultarPerfil` e `ExcluirCredenciais` estendem `ManutencaoDeUsuario`.
- `ExcluirAlerta`, `AlterarAlerta` e `IncluirAlerta` estendem `CadastroDeAlertas`, assim como `VisualizacaoDeCalendario`.
- `ExcluirDespesa`, `AlterarDespesa` e `ConsultarDespesa` estendem `CadastroDeDespesas`, com `IncluirDespesa` estendendo via `IncluirAlerta`.
- `ExportarRelatorioParaPDF` estende `GerarRelatorioPersonalizado` e `ExportarDashboardParaPDF` estende `GerarDashboardMensal`.

**Generalização (herança)**
- `IncluirSaldoInicial` e `AlterarSaldoInicial` herdam de `RegistroDeSaldoInicial` — representado pela seta com triângulo fechado no diagrama 1.

## 4. Diagrama UML
Adicione aqui a imagem do diagrama:  
