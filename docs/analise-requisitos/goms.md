#GOMS#

## Introdução GOMS ##

O Método GOMS (Goals, Operators, Methods, and Selection rules) é uma abordagem de análise de tarefas que descreve as etapas de uma tarefa em termos de objetivos a serem alcançados, operadores disponíveis, métodos para realização e regras de seleção para escolher entre diferentes métodos. Ela funciona separando as tarefas em elementos específicos e atômicos, facilitando a identificação de possíveis problemas de usabilidade e a otimização do design da interface.

Explicando os quatro tipos de elementos utilizados no método GOMS:

• Objetivos (Goals): representam o que o usuário quer fazer no sistema

• Operadores (Operators): primitivas internas (cognitivas) ou externas (as ações concretas que o sistema permite que os usuários façam, tal como um comando e seus parâmetros digitados no teclado; a seleção de menus; o clique de um botão)
• métodos (methods): sequência bem conhecidas de subobjetivos e operadores que permitem atingir um objetivo maior

• regras de seleção (selection rules): permitem decidir qual método utilizar numa determinada situação



### Alterar Endereço do Veículo

#### Descrição Detalhada

**GOAL 0: Alterar endereço do veículo**
- O usuário deseja alterar o endereço de cadastro do seu veículo.

**GOAL 1: Escolher veículo**
- **OP 1.1:** O usuário seleciona o veículo que deseja alterar o endereço no sistema.

**GOAL 2: Alterar os desejados campos do endereço**
- **OP 2.1:** O usuário altera os campos desejados do endereço (CEP, logradouro, número, complemento, município, UF, bairro).
- **OP 2.2:** O usuário confirma as alterações realizadas.

### Regras de Seleção

- **Se** o usuário tiver mais de um veículo cadastrado, **então** ele deve escolher o veículo correto no GOAL 1.
- **Se** algum campo obrigatório não for preenchido, **então** o sistema deve alertar o usuário para completá-lo antes de confirmar.

### Solicitar Permissão Internacional para Dirigir (PID)

#### Descrição Detalhada

**GOAL 0: Emitir permissão para dirigir em outro País**
- O usuário deseja obter uma Permissão Internacional para Dirigir (PID) para dirigir em outro país.

**GOAL 1: Se informar dos requisitos e instruções**
- **OP 1.1:** O usuário lê os requisitos e instruções fornecidos no site para a solicitação da PID.
- **OP 1.2:** O usuário clica no botão "prosseguir" após ler as instruções.

**GOAL 2: Escolher a forma de recebimento da PID**
- **OP 2.1:** O usuário seleciona o local onde deseja receber a PID (no Detran ou por encomenda).
- **OP 2.2:** O usuário confirma a escolha do local de recebimento.

**GOAL 3: Pagamento**
- **OP 3.1:** O usuário consente com os termos de pagamento.
- **OP 3.2:** O usuário realiza o pagamento da taxa para emissão da PID.

#### Regras de Seleção

- **Se** o usuário não entender algum requisito ou instrução, **então** ele deve buscar ajuda ou esclarecimento antes de prosseguir com GOAL 1.
- **Se** o usuário escolher receber a PID por encomenda, **então** ele deve fornecer um endereço válido e completo no GOAL 2.
- **Se** o pagamento não for confirmado, **então** o usuário deve verificar os dados de pagamento e tentar novamente.

### Emissão de Nada Consta da CNH

#### Descrição Detalhada

**GOAL 0: Emitir Nada Consta da CNH**
- O usuário deseja obter um documento que comprove a ausência de infrações na sua CNH.

**GOAL 1: Acesso ao website**
- **OP 1.1:** O usuário abre o navegador e digita o URL do DETRAN-DF.
- **OP 1.2:** O usuário navega pelo site até encontrar a página de login.

**GOAL 2: Realizar Login**
- **OP 2.1:** O usuário insere seu nome de usuário e senha nos campos apropriados.
- **OP 2.2:** O usuário clica no botão de login para acessar sua conta.

**GOAL 3: Selecionar a Funcionalidade de Consultar CNH**
- **OP 3.1:** O usuário passa o mouse sobre a opção "CNH" no menu de navegação.
- **OP 3.2:** O usuário clica na opção "Consultar CNH" que aparece no menu.

**GOAL 4: Visualizar Informações da CNH**
- **OP 4.1:** O usuário vê uma página com um resumo das informações da sua CNH, incluindo pontos, dados pessoais e detalhes da CNH.

**GOAL 5: Completar verificação de segurança**
- **OP 5.1:** O usuário completa a verificação de segurança "Não sou um robô" para confirmar que é um usuário legítimo.

**GOAL 6: Emitir Documento "Nada Consta"**
- **OP 6.1:** O usuário clica no botão que diz "Emitir nada consta".
- **OP 6.2:** O usuário vê um ícone de carregamento que indica que o sistema está processando a emissão do documento.

**GOAL 7: Visualizar e Agir sobre o Documento**
- **OP 7.1:** A página se atualiza e o documento "Nada Consta" é exibido.
- **OP 7.2:** O usuário escolhe entre imprimir o documento ou enviá-lo para seu e-mail.

#### Regras de Seleção

- **Se** o usuário já tiver um login, **então** ele deve prosseguir com o GOAL 2.
- **Se** o usuário não encontrar a opção "Consultar CNH" no menu, **então** ele deve procurar na seção de serviços disponíveis no site.
- **Se** a verificação de segurança falhar, **então** ele deve tentar novamente até ser bem-sucedido.
- **Se** o documento "Nada Consta" não for exibido após o carregamento, **então** o usuário deve verificar sua conexão e tentar emitir novamente.


## 📑 Histórico de versão

|   Versão   | Data  | Descrição            | Autor                                                  | Revisor |
| :--------: | :---: | :------------------- | ------------------------------------------------------ | ------- |
| 06/05/2024 |  1.0  | GOMS 1 e 2| [Pedro Sena](https://github.com/pedroyen21) | [Filipe Carvalho](https://github.com/Filipe-002)     |
| 20/05/2024 |  1.1  | GOMS 3| [Vinicius Vieira](https://github.com/viniciusvieira00) | -- |
