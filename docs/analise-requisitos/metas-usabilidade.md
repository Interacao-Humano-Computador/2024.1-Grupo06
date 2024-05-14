# Metas de Usabilidade

## Introdução

Este documento estabelece critérios essenciais de usabilidade, essenciais para orientar o desenvolvimento e design de produtos. Define o processo de avaliação de usabilidade que será implementado ao longo do desenvolvimento do projeto, especificando os padrões aceitáveis e os não aceitáveis. A usabilidade é medida pela capacidade dos usuários específicos de alcançar objetivos definidos em contextos específicos com eficácia, eficiência e satisfação.

Para atingir esses padrões, definimos Metas de Usabilidade fundamentais, baseadas nas diretrizes de Jakob Nielsen: Aprendizado, Eficiência, Eficácia, Memorização, Segurança e Utilidade. Essas metas são pilares para a criação de interfaces intuitivas e acessíveis, buscando desenvolver soluções que atendam às necessidades operacionais do sistema e melhorem a experiência do usuário.

## Metodologia

Inicialmente, realizaremos uma avaliação detalhada para identificar quais das metas de usabilidade estão sendo atendidas e quais apresentam deficiências na plataforma atual. Esta avaliação envolverá testes de usabilidade que simulam o comportamento esperado dos usuários, considerando os atributos definidos no Perfil do Usuário. Com base nesses dados, ajustaremos o design e desenvolvimento para melhor alinhar a plataforma às expectativas dos usuários.

## Descrição das Metas de Usabilidade

- **Eficácia**: Capacidade do sistema de cumprir as funções esperadas, atingindo o propósito para o qual foi projetado.
- **Eficiência**: Como o sistema ajuda o usuário a realizar suas atividades desejadas economicamente, minimizando o número de etapas necessárias.
- **Segurança**: Proteção contra situações perigosas e prevenção de erros graves, com mecanismos para recuperação de ações.
- **Utilidade**: Funcionalidades oferecidas para realizar tarefas de maneira eficaz e satisfatória.
- **Aprendizado**: Facilidade com que o usuário pode aprender a operar o sistema de modo eficiente.
- **Memorização**: Capacidade de o usuário relembrar o uso do sistema após o aprendizado inicial, essencial para sistemas usados esporadicamente.

## Avaliação das Metas de Usabilidade

### Eficácia
- **Pergunta Chave**: O sistema serve ao propósito principal?
- **Avaliação**: Para responder a essa pergunta, é importante primeiro definir quais são esses propósitos principais. Partindo dos objetivos principais dentro do website, facilitar o acesso dos cidadãos a serviços relacionados a veículos, habilitação, infrações, e outros aspectos regulatórios e administrativos de trânsito. Vamos considerar alguns dos principais serviços oferecidos pelo portal do Detran DF para avaliar sua eficácia:

1. **Renovação de CNH (Carteira Nacional de Habilitação)**: O sistema deve permitir que os usuários renovem suas CNHs de maneira eficiente, sem a necessidade de visitas presenciais, a menos que seja absolutamente necessário.
- O sistema resolve em parte o processo de renovação da CNH, permitindo que o usuário inicie o processo online e continue o processo de renovação indo a uma clínica credenciada para realizar os exames necessários. Após isso, o usuário deve comparecer a um posto de atendimento do Detran para finalizar o processo. A eficácia do sistema pode ser avaliada pela facilidade de uso e clareza das instruções fornecidas aos usuários, porém uma certa limitação na indicação de clínicas credenciadas pode ser um ponto de melhoria.

2. **Consulta de Multas e Infrações**: Os usuários devem ser capazes de verificar facilmente quaisquer multas ou infrações registradas contra seus veículos ou CNHs, bem como acessar detalhes sobre cada infração.
- O sistema permite que os usuários consultem multas e infrações registradas contra seus veículos ou CNHs, fornecendo informações detalhadas sobre cada infração. O processo de consulta é relativamente simples e direto, mas a apresentação das informações poderia ser mais clara e intuitiva, facilitando a compreensão dos usuários. Outro ponto que vale ressaltar, é a falta de integração com outros órgãos de trânsito, o que pode limitar a abrangência das informações disponíveis, dificultando a obtenção de dados completos sobre infrações, o que pode ser um ponto de melhoria.

3. **Pagamento de Multas**: Deve ser possível pagar multas diretamente pelo portal, utilizando métodos de pagamento seguros e confiáveis.
- Atualmente o sistema permite que os usuários paguem multas diretamente pelo portal, oferecendo diferentes métodos de pagamento. No entanto, a experiência de pagamento pode ser aprimorada para torná-la mais intuitiva e eficiente, garantindo que os usuários possam concluir o processo sem dificuldades. Além disso, a segurança do sistema de pagamento deve ser uma prioridade, garantindo que as informações dos usuários sejam protegidas contra fraudes e vazamentos de dados, algo que não há como avaliar sem uma análise mais aprofundada, e com acesso ao código fonte do sistema.

4. **Acesso a Informações e Educação**: O portal deve oferecer acesso fácil a informações educacionais sobre segurança no trânsito, legislação vigente, e novidades ou alterações nas regulamentações de trânsito.
- O sistema fornece informações educacionais sobre segurança no trânsito, legislação vigente e outras informações relevantes para os usuários. No entanto, a organização e a apresentação dessas informações podem ser melhoradas para torná-las mais acessíveis e fáceis de encontrar. Além disso, a atualização constante dessas informações é essencial para manter os usuários informados sobre as últimas novidades e alterações nas regulamentações de trânsito, o que pode ser um ponto de melhoria.

#### Conclusão sobre a Eficácia

O sistema do Detran DF atende parcialmente aos propósitos principais para os quais foi projetado, oferecendo funcionalidades essenciais para os usuários, como renovação de CNH, consulta de multas e infrações, pagamento de multas e acesso a informações educacionais. No entanto, existem áreas que requerem melhorias para garantir a eficácia do sistema, como a clareza das instruções fornecidas aos usuários, a apresentação das informações disponíveis, a integração com outros órgãos de trânsito e a segurança do sistema de pagamento. Essas melhorias podem contribuir significativamente para aprimorar a experiência dos usuários e aumentar a eficácia do sistema como um todo.

### Eficiência
- **Pergunta Chave**: Quantos recursos são utilizados para realizar a tarefa específica?
- **Avaliação**: Utilizando o serviço mais utilizado do website do Detran DF, a consulta de multas e infrações, podemos avaliar a eficiência do sistema em termos de tempo e esforço necessários para realizar a tarefa. A eficiência pode ser medida pela rapidez com que os usuários conseguem acessar as informações desejadas, bem como pela facilidade de navegação e interação com o sistema. A utilização desse serviço pdoe revelar alguns problemas de eficiência, como a falta de filtro de busca, a apresentação de informações desnecessárias, e principalmente a falta de integração com outros órgãos de trânsito, o que pode dificultar a obtenção de dados completos sobre infrações, tornando o processo mais demorado e complexo do que o necessário, dando ao usuário uma experiência menos eficiente, tendo que recorrer a outros meios para obter as informações desejadas.

### Segurança
- **Pergunta Chave**: O sistema previne erros? Recupera ações anteriores?
- **Avaliação**: O sistema do Detran DF é seguro em termos de proteção de dados, principalmente por utilizar o meio do gov.br para autenticação dos usuários, garantindo a segurança das informações pessoais dos usuários. No entanto, a segurança do sistema de pagamento deve ser uma prioridade, garantindo que as informações dos usuários sejam protegidas contra fraudes e vazamentos de dados, algo que não há como avaliar sem uma análise mais aprofundada, e com acesso ao código fonte do sistema. Um outro ponto importante a se destacar, é a demora da resposta para o sistema dar "baixa" em uma multa paga, o que pode gerar confusão e desconfiança por parte dos usuários, que podem achar que o pagamento não foi efetuado corretamente, ou que o sistema está com problemas, podendo até mesmo efetuar o pagamento novamente, gerando transtornos desnecessários, que poderiam ser evitados com uma resposta mais rápida do sistema, ou com o "travamento" do pagamento após a primeira tentativa, evitando pagamentos duplicados.

### Utilidade
- **Pergunta Chave**: O sistema oferece a funcionalidade certa no contexto certo?
- **Avaliação no sistema**: Em uma primeira vista, observa-se que o sistema oferece diversos serviços que antigamente só seriam possíveis em uma unidade física do Detran, de forma online. Porém, quando vamos para a prática, muitos serviços não funcionam de forma correta, com muitos deles estando desatualizados, como o serviço de conferir quais clínicas estão credenciadas, CFC's, entre outros. Também há o caso, por exemplo, de que o sistema só registra multas tomadas no âmbito estadual, no caso, do DF, caso o condutor receba uma multa em outro estado, ou seja aplicado por outro órgão, não irá constar no sistema.

### Aprendizagem
- **Pergunta Chave**: É fácil aprender a usar o sistema?
- **Avaliação**: Uma vez feito o login do usuário, o sistema é bem simples de usar, seguindo vários padrões que são de fácil aprendizado. O problema se encontra na página de login, onde não é muito claro como é o processo para criar uma conta, e a integração com uma conta GOV.com não é feita de forma eficaz.

### Memorização
- **Pergunta Chave**: O usuário retém o conhecimento sobre como usar o sistema?
- **Avaliação**: Conforme explicitado anteriormente, o sistema tem uma interface bem simples e que seguem vários padrões, tornando a memorização um aspecto bem fácil de ser aplicado. No geral, dá pra dizer que a utilização do sistema é bastante intuitiva, até mesmo com usuários bom algumas limitações.

## Conclusão

Resumo das principais descobertas da avaliação, destacando as áreas de sucesso e as que requerem melhorias.

## Referência Bibliográfica

NIELSEN, Jacob. Designing Web Usability: The Practice of Simplicity Peachpit Press, la edição 1999

Diana Fournier. As 6 metas de Usabilidade. MEDIUM, 2016. Disponível em: https://irlabr.wordpress.com/apostila-de-ihc/6-usabilidade-e-suas-metas/. Acesso em: 13 mai. 2024.

## Histórico de versão

| Versão | Data       | Descrição                                 | Autor(es)                                                                                         | Revisor(es)                                    |
| ------ | ---------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 11/05/2024 | Criação da página. | [Vinicius Vieira](https://github.com/viniciusvieira00)| [Filipe Carvalho](https://github.com/filipe-002) |
| `1.1`  | 11/05/2024 | Adicionando tópicos. | [Filipe Carvalho](https://github.com/filipe-002)| [Daniel Coimbra](https://github.com/DanielCoimbra) | 
