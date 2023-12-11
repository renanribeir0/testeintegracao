##### Teste de Login

<img width="178" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/8c003abd-2d1e-4a41-98bf-4d5d18d25e2a">

- **Teste de Login Correto**
<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/679ca041-2eb7-409b-ae0f-12225efb8614">

  - Pré-condição: Usuário válido e senha correta.
  - Passos:
    1. Acessar a página de login.
    2. Inserir credenciais válidas.
    3. Ir para a home.
  - Pós-condição: O usuário é redirecionado para a home.

- **Teste de Login Incorreto**
- 
<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/03a9ac89-ec1a-4ceb-955f-6970e078bcce">

  - Pré-condição: E-mail e senha incorreta.
  - Passos:
    1. Acessar a página de login.
    2. Inserir credenciais inválidas.
    3. Enviar sem conseguir acessar o aplicativo.
  - Pós-condição: Uma mensagem de erro é exibida “credenciais inválidas”.

#### Teste de Listagem de Pedidos

<img width="179" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/98cce332-46bd-44fb-a018-c645bdbebcab">

- **Teste de Listagem de Pedidos Correto**

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/43042115-67bb-46fc-8b63-6209df7d486e">


  - Pré-condição: O usuário está autenticado no sistema.
  - Passos:
    1. Estar logado no aplicativo.
    2. Navegar até a página de listagem de compras.
    3. Verificar a exibição correta da quantidade de itens adquiridos.
    4. Clicar para acessar os detalhes de uma compra.
  - Pós-condição: O usuário pode visualizar todos os itens comprados.

- **Teste de Listagem com Falha na Exibição**

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/f17e8b55-4a08-4e40-8583-6a37eb029677">

  - Pré-condição: Acesso à página de listagem de compras sem exibição dos itens.
  - Passos:
    1. Acessar a página de listagem de compras.
    2. Verificar a presença de uma mensagem de erro ou ausência de itens.
    3. Tentar recarregar a página ou realizar ações de atualização.
  - Pós-condição: Uma mensagem de erro é exibida, indicando o problema de exibição dos itens “400”.

#### Teste de Listagem de Fornecedores

<img width="179" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/ad065b8d-9f2a-450e-9ec6-1333239696a7">

- **Teste de Fornecedores Correto**
  
<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/1808aca1-eb54-4b8e-a71b-23bb615fd887">

  - Pré-condição: O usuário consegue visualizar todos os fornecedores.
  - Passos:
    1. Acessar a página de listagem de fornecedores.
    2. Verificar se todos os fornecedores estão listados corretamente.
  - Pós-condição: O usuário visualiza todos os fornecedores com suas informações detalhadas e precisas.

- **Teste de Fornecedores Incorreto**
  
<img width="497" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/2255295f-2e91-450c-b7c9-2a5f4445b8da">

  - Pré-condição: Erro ao tentar visualizar os fornecedores.
  - Passos:
    1. Acessar a página de listagem de fornecedores.
    2. Tentar visualizar os fornecedores e suas informações.
  - Pós-condição: Uma mensagem de erro é exibida “400”.

    

#### Teste de Listagem de Escolas com Diretorias

<img width="179" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/179d3e13-b187-49a4-a598-5c329907c44d">


##### Teste Correto

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/766fdd8f-a0e7-46dd-ad06-19ddf03aa532">

- **Pré-condição:** O usuário consegue visualizar todas as diretorias e acessar informações sobre as escolas.
- **Passos:**
  1. Acessar a página inicial (home).
  2. Verificar a presença e acesso a todas as diretorias.
- **Pós-condição:** O usuário consegue visualizar todas as diretorias.

##### Teste Incorreto

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/b44f72c4-4f99-465a-8a88-c87d8634b1ab">

- **Pré-condição:** Erro ao tentar visualizar as diretorias.
- **Passos:**
  1. Acessar a página inicial (home).
  2. Tentar visualizar as diretorias.
- **Pós-condição:** Uma mensagem de erro é exibida “400”.

#### Teste de Predição da Melhor Fornecedora para uma Diretoria
- **Teste Correto:**

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/0e0f62ec-9fd0-43b7-a598-be83a0b33fc5">

  - **Pré-condição:** O modelo preditivo indica a melhor fornecedora para uma diretoria.
  - **Passos:**
    1. Analisar critérios e requisitos da diretoria.
    2. Utilizar o modelo preditivo para recomendar a fornecedora adequada.
  - **Pós-condição:** A diretoria recebe uma recomendação precisa da melhor fornecedora, facilitando a tomada de decisão.

### Integração do Front-end e Back-end

#### Teste de Criação e Atualização de Entregas

<img width="179" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/f204cb26-23ea-4459-b6e5-d862f381dcd7">


##### Teste Correto (Criação de Entrega)

<img width="497" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/bdba7564-5180-4bf3-a09a-9d8578486f7e">

- **Pré-condição:** O usuário consegue criar uma entrega.
- **Passos:**
  1. Acessar a página de criação de entrega.
  2. Inserir informações necessárias.
  3. Criar a entrega.
- **Pós-condição:** O usuário cria a entrega e confirma com sucesso.

##### Teste Incorreto (Criação de Entrega)

<img width="494" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/a1804621-bbf8-4201-a14f-2b284a21c1e6">

- **Pré-condição:** Erro ao tentar criar uma entrega.
- **Passos:**
  1. Acessar a página de criação de entrega.
  2. Não consegue visualizar as informações.
- **Pós-condição:** Uma mensagem de erro é exibida “400”.

##### Teste de Atualização de Entrega

<img width="179" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/21d70d11-d895-4730-b693-1b0355f06372">

- **Teste Correto:**

<img width="496" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/8b454404-0bb4-4fc2-84d7-e420faeb73ab">

  - **Pré-condição:** Usuário quer atualizar uma entrega.
  - **Passos:**
    1. Acessar a página de edição de entrega.
    2. Atualizar informações existentes.
    3. As informações são alteradas.
  - **Pós-condição:** A entrega é atualizada com sucesso.

##### Teste Incorreto (Atualização de Entrega)

<img width="497" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/e65c16d4-61eb-4214-9df2-cb6d257d0fcf">

- **Pré-condição:** Erro ao tentar acessar a página de edição de entrega.
- **Passos:**
  1. Acessar a página de edição de entrega.
  2. Erro na hora de atualizar.
- **Pós-condição:** Uma mensagem de erro é exibida “403”.

#### Teste de Criação de Pedido

##### Teste Correto

<img width="497" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/ef1aac78-9a3f-41e0-81ad-34e139760a5a">

- **Pré-condição:** Usuário tenta criar um pedido.
- **Passos:**
  1. Acessar a página de criação de pedido.
  2. Inserir informações necessárias.
  3. Criar o pedido.
- **Pós-condição:** O usuário consegue criar um pedido.

##### Teste Incorreto

<img width="495" alt="image" src="https://github.com/renanribeir0/testeintegracao/assets/110369271/8b8a5463-25e9-4f22-a99b-3f29ee11dfa9">

- **Pré-condição:** Usuário tenta criar um pedido, mas não consegue acessar a página ou visualizar as informações.
- **Passos:**
  1. Não consegue acessar a página de criação de pedido.
  2. Não consegue visualizar as informações.
- **Pós-condição:** Uma mensagem de erro é exibida “403”.


