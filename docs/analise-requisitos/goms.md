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


## 📑 Histórico de versão

|   Versão   | Data  | Descrição            | Autor                                                  | Revisor |
| :--------: | :---: | :------------------- | ------------------------------------------------------ | ------- |
| 06/05/2024 |  1.0  | GOMS 1 e 2| [Pedro Sena](https://github.com/pedroyen21) | [Filipe Carvalho](https://github.com/Filipe-002)     |
