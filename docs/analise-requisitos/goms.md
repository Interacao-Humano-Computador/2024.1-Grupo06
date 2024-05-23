#GOMS#

##Introdução GOMS ##

O Método GOMS (Goals, Operators, Methods, and Selection rules) é uma abordagem de análise de tarefas que descreve as etapas de uma tarefa em termos de objetivos a serem alcançados, operadores disponíveis, métodos para realização e regras de seleção para escolher entre diferentes métodos. Ela funciona separando as tarefas em elementos específicos e atômicos, facilitando a identificação de possíveis problemas de usabilidade e a otimização do design da interface.

Explicando os quatro tipos de elementos utilizados no método GOMS:

• Objetivos (Goals): representam o que o usuário quer fazer no sistema

• Operadores (Operators): primitivas internas (cognitivas) ou externas (as ações concretas que o sistema permite que os usuários façam, tal como um comando e seus parâmetros digitados no teclado; a seleção de menus; o clique de um botão)
• métodos (methods): sequência bem conhecidas de subobjetivos e operadores que permitem atingir um objetivo maior

• regras de seleção (selection rules): permitem decidir qual método utilizar numa determinada situação


### Alterar endereço do veículo ###

Tarefa em que o usuário precisa realizar a alteração do endereço em que seu veículo está cadastrado.

GOAL 0: Alterar endereço do veículo
	GOAL 1: Escolher veículo
		OP 1.1: Escolher veículo
	GOAL 2: Alterar os desejados campos do endereço
		OP 2.1: Alterar campos
		OP 2.2: Confirmar alterações


### Solicitar Permissão Internacional para Dirigir (PID) ### 

Tarefa em que o usuário solicita uma Permissão Internacional para Dirigir

GOAL 0: Emitir permissão para dirigir em outro País
	GOAL 1: Se informar dos requisitos e instruções
		OP 1.1: Ler requisitos e instruções para a solicitação
		OP 1.2: Clicar no botão prosseguir
	GOAL 2: Escolher a forma de recebimento da PID
		OP 2.1: Selecionar local de recebimento
		OP 2.2: Confirmar
	GOAL 3: Pagamento
		OP 3.1: Consentir o pagamento
		OP 3.2: Pagar


### Emissão CRLV ###

### Análise GOMS: Solicitação de CRLV-e

#### Operações

| Operação                       | Feedback/Plano                                          | Operadores                                                |
|--------------------------------|---------------------------------------------------------|-----------------------------------------------------------|
| Acessar barra de serviços      | **Feedback:** Apresentar todos os serviços existentes. <br> **Plano:** Solicitar CRLV. | - Apontar para a barra de serviços. <br> - Clicar na barra de serviços. |
| Selecionar opção "Emitir CRLV-e" |                                                         | - Procurar a opção "Emitir CRLV-e". <br> - Clicar em "Emitir CRLV-e". |
| Acessar conta ou fazer login   |                                                         | - Identificar a seção de login. <br> - Clicar no botão/link de login. |
| Fazer login com CPF e senha    | **Input:** Inserir CPF cadastrado e senha. <br> **Plano:** Se os dados estiverem corretos, informar ao servidor que está tudo ok. | - Localizar o campo de CPF. <br> - Digitar o CPF. <br> - Localizar o campo de senha. <br> - Digitar a senha. <br> - Clicar no botão de login. |
| Fazer login com GOV.br         | **Input:** Inserir CPF cadastrado e senha no GOV.br. <br> **Plano:** Se os dados estiverem corretos, informar ao servidor que está tudo ok. | - Localizar a opção de login GOV.br. <br> - Clicar na opção de login GOV.br. <br> - Localizar o campo de CPF no GOV.br. <br> - Digitar o CPF. <br> - Localizar o campo de senha no GOV.br. <br> - Digitar a senha. <br> - Clicar no botão de login no GOV.br. |
| Selecionar veículo             |                                                         | - Identificar a seção de seleção de veículo. <br> - Procurar o veículo relevante na lista. <br> - Clicar para selecionar o veículo. |
| Fazer o download do documento  |                                                         | - Localizar o botão/link de download do documento. <br> - Clicar no botão/link de download. |

#### Problemas e Recomendações

| Problema                                 | Recomendação                                                                                                 |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Apresentar todos os serviços existentes  | Garantir que a barra de serviços liste claramente todos os serviços disponíveis, com ícones ou rótulos intuitivos para facilitar a identificação e seleção rápida. |
| Fazer login com CPF e senha              | Assegurar que o processo de login seja fluido, com mensagens de erro claras se o CPF ou a senha estiverem incorretos. Considerar a implementação de uma função "Esqueci a Senha" para conveniência do usuário. |
| Fazer login com GOV.br                   | Garantir que a integração com o GOV.br seja tranquila. Fornecer instruções claras para os usuários sobre como proceder caso encontrem problemas com o login no GOV.br. |
| Selecionar veículo                       | Se os usuários tiverem múltiplos veículos, garantir que a lista seja apresentada claramente com informações suficientes (por exemplo, modelo, número da placa) para identificar facilmente o veículo correto. |
| Fazer o download do documento            | Assegurar que o link/botão de download esteja destacado e funcione corretamente em diferentes dispositivos e navegadores. Fornecer uma mensagem de confirmação ou notificação após a conclusão do download. |



## 📑 Histórico de versão

|   Data  | Versão | Descrição  | Autor                                                  | Revisor |
| :--------: | :---: | :------------------- | ------------------------------------------------------ | ------- |
| 06/05/2024 |  1.0  | GOMS 1 e 2| [Pedro Sena](https://github.com/pedroyen21) | [Filipe Carvalho](https://github.com/Filipe-002)     |
| 06/05/2024 |  1.0  | GOMS CRLV| [Filipe Carvalho](https://github.com/Filipe-002)   |  -- |