##### Teste de Login
- **Teste de Login Correto**
  - Pré-condição: Usuário válido e senha correta.
  - Passos:
    1. Acessar a página de login.
    2. Inserir credenciais válidas.
    3. Ir para a home.
  - Pós-condição: O usuário é redirecionado para a home.

- **Teste de Login Incorreto**
  - Pré-condição: E-mail e senha incorreta.
  - Passos:
    1. Acessar a página de login.
    2. Inserir credenciais inválidas.
    3. Enviar sem conseguir acessar o aplicativo.
  - Pós-condição: Uma mensagem de erro é exibida “credenciais inválidas”.

#### Teste de Listagem de Pedidos
- **Teste de Listagem de Pedidos Correto**
  - Pré-condição: O usuário está autenticado no sistema.
  - Passos:
    1. Estar logado no aplicativo.
    2. Navegar até a página de listagem de compras.
    3. Verificar a exibição correta da quantidade de itens adquiridos.
    4. Clicar para acessar os detalhes de uma compra.
  - Pós-condição: O usuário pode visualizar todos os itens comprados.

- **Teste de Listagem com Falha na Exibição**
  - Pré-condição: Acesso à página de listagem de compras sem exibição dos itens.
  - Passos:
    1. Acessar a página de listagem de compras.
    2. Verificar a presença de uma mensagem de erro ou ausência de itens.
    3. Tentar recarregar a página ou realizar ações de atualização.
  - Pós-condição: Uma mensagem de erro é exibida, indicando o problema de exibição dos itens “400”.

#### Teste de Listagem de Fornecedores
- **Teste de Fornecedores Correto**
  - Pré-condição: O usuário consegue visualizar todos os fornecedores.
  - Passos:
    1. Acessar a página de listagem de fornecedores.
    2. Verificar se todos os fornecedores estão listados corretamente.
  - Pós-condição: O usuário visualiza todos os fornecedores com suas informações detalhadas e precisas.

- **Teste de Fornecedores Incorreto**
  - Pré-condição: Erro ao tentar visualizar os fornecedores.
  - Passos:
    1. Acessar a página de listagem de fornecedores.
    2. Tentar visualizar os fornecedores e suas informações.
  - Pós-condição: Uma mensagem de erro é exibida “400”.

### Integração do Front-end e Back-end

#### Vídeo de Demonstração (Até 5 minutos)
- Mostrar a interação do usuário com o front-end e os registros no back-end.
  
#### Imagens no Markdown
- Capturar a dinâmica dos testes através de imagens no Markdown do GitHub.

### Integração do Back-end e API Externa (SOA)

#### Teste de Predição de Melhor Fornecedora para uma Diretoria
- **Teste Correto**
  - Pré-condição: O modelo predito indica a melhor fornecedora para uma diretoria.
  - Passos:
    1. Análise detalhada dos critérios de seleção e requisitos específicos da diretoria.
    2. Utilização do modelo preditivo para classificar e recomendar a fornecedora mais adequada.
  - Pós-condição: A diretoria recebe uma recomendação precisa da melhor fornecedora com base nos critérios estabelecidos.

### Documentação e Evidências

- Plano de Testes
- Relatórios de execução e logs da aplicação
- Planilha de testes de integração e regressão
- Telas dinâmicas (resultados que envolvem requisições no banco de dados)
- Verificação de testes positivos e negativos

Estas revisões estão alinhadas com o que foi pedido no barema, facilitando a execução e documentação dos testes de integração entre o front-end, back-end e outras integrações.
