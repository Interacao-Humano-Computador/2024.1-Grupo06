# Características da Plataforma para o projeto

## Introdução

Para dar prosseguimento ao projeto vê-se a necessidade de realizar uma análise detalhada do site como recomendado por Mayhew¹, um ponto importante é o ciclo de vida observado. Portanto, aqui trabalharemos em cima das características do site Detran/DF que serão suas funcionalidades, capacidades, suas interações e pontos fracos e fortes para que posteriormente possamos elaborar uma proposta de melhoria ao caso analisado.

## Características da Plataforma

O Portal de Serviços do Departamento de Trânsito do Distrito Federal (Detran/DF) é uma plataforma web que fornece diversos serviços relacionados ao trânsito para os cidadãos do Distrito Federal. Possui funcionalidades como consulta, alteração, emissão de documentos relacionados a multas, infrações, veículos, Carteira Nacional de Habilitação (CNH) entre outros. É possível acessá-lo por meio de qualquer dispositivo através de um navegador e conta com uma versão de aplicativo mobile. 


Alguns dos principais serviços da plataforma:

- Alteração de endereço da CNH;

- Alteração de endereço de veículo;

- Autoidentificação de condutor infrator;

- Autorização de estacionamento para idoso;

- Consulta da CNH;

- Consulta de processo de habilitação;

- Consulta de veículos;

- Conversão de autuação em advertência;

- Conversão de autuação em penalidade;

- Emissão de CRLV-e;

- Emissão de CRV (DUT);

- Mudança de placa modelo Mercosul;

- Recolocação de placa.

### Características Tecnlógicas

Não foram encontradas informações oficiais a respeito das tecnologias usadas para desenvolver a plataforma. Entretanto, foi usada uma extensão do navegador [Chrome](https://www.google.com/intl/pt-BR/chrome/) chamada [Snov.io](https://chromewebstore.google.com/detail/website-technology-checke/phealodnoblgkcfbhpdebpihdbfmggpi) que faz uma análise do código fonte da página para encontrar padrões pertencentes a determinadas tecnologias. Ela aponta que para desenvolver o site foi utilizado o Framework [Angular](https://angular.io/) e a linguagem [Typescript](https://www.typescriptlang.org/).

Vale lembrar que as informações providas pela extensão não são 100% confiáveis, mas podem oferecer informações úteis na ausência de fontes oficiais.

## Requisitos do Sistema

Para assegurar que o Portal de Serviços do Departamento de Trânsito do Distrito Federal (Detran/DF) atenda de forma eficaz às necessidades dos usuários, é crucial estabelecer requisitos do sistema claros e detalhados. Esses requisitos são fundamentais para orientar o desenvolvimento e a manutenção do portal, garantindo que ele ofereça funcionalidades úteis e uma operação confiável. A seguir, são detalhados os requisitos funcionais e não funcionais do sistema, baseados nas funcionalidades observáveis e em suposições razoáveis, uma vez que informações detalhadas sobre o sistema interno não estão disponíveis publicamente.

### Requisitos Funcionais

1. **Autenticação de Usuários**: O portal deve permitir o registro e autenticação de usuários, essencial para o acesso a serviços personalizados e seguros.

2. **Consulta de Informações**: Os usuários devem poder consultar informações detalhadas sobre CNH, veículos, multas, infrações e processos de habilitação.

3. **Atualização de Dados**: O sistema deve permitir aos usuários atualizar seus dados pessoais e de veículos.

4. **Emissão de Documentos**: Capacidade de emitir digitalmente documentos como CRLV-e e CRV.

5. **Pagamento de Multas e Taxas**: Integração com sistemas de pagamento para facilitar o pagamento de multas e taxas.

6. **Notificações**: Envio de notificações automáticas sobre atualizações importantes.

### Requisitos Não Funcionais

1. **Usabilidade**: O portal deve ser intuitivo e acessível a todos os usuários, incluindo aqueles com limitações.

2. **Desempenho**: Capacidade de suportar um alto volume de acessos simultâneos sem perda significativa de desempenho.

3. **Segurança**: Medidas robustas de segurança para proteger dados sensíveis contra acessos não autorizados e ataques.

4. **Compatibilidade**: Suporte a uma variedade de dispositivos e navegadores.

5. **Disponibilidade**: Disponibilidade contínua do serviço, com manutenções programadas para horários de menor tráfego.

6. **Escalabilidade**: Flexibilidade para escalar recursos conforme o aumento da demanda.

É importante destacar que, devido à natureza fechada de algumas informações do sistema, esta análise se baseia em funcionalidades observáveis e em suposições comuns para plataformas similares.

## Limites da Plataforma

O Portal de Serviços do Departamento de Trânsito do Distrito Federal (Detran/DF) oferece uma gama de funcionalidades essenciais para a gestão de questões relacionadas ao trânsito. No entanto, existem algumas limitações que podem impactar a experiência do usuário e a eficácia da plataforma:

- **Necessidade de Autenticação**: Usuários não registrados têm acesso limitado a determinadas funcionalidades, exigindo autenticação para acessar serviços personalizados, como consulta de multas e alterações de endereço.

- **Usabilidade e Acessibilidade**: Apesar de ser acessível por dispositivos variados, o portal pode não oferecer a melhor experiência de usabilidade para todos os usuários, especialmente aqueles com necessidades especiais, como deficiências visuais, devido à falta de ferramentas adequadas de acessibilidade.

- **Limitações de Interatividade e Personalização**: A interatividade com o usuário pode ser limitada, sem opções avançadas de personalização ou recomendações automáticas baseadas no histórico do usuário.

- **Falta de Integração Completa**: Embora ofereça diversos serviços, a plataforma não se apresenta totalmente integrada com outros sistemas estaduais ou federais, o que pode dificultar a obtenção de informações completas e atualizadas, especialmente em casos de transferência de veículos entre estados, ou consulta de multas em outros estados, e outros órgãos de trânsito.

## Metodologia

Para a análise do Portal de Serviços do Departamento de Trânsito do Distrito Federal (Detran/DF), adotou-se o método de avaliação conhecido como *avaliação heurística*. Este método envolve os usuários pertencentes ao grupo de trabalho, que examinam a interface e interações do portal para identificar problemas de usabilidade com base em princípios pré-estabelecidos, conhecidos como heurísticas.

### Processo de Avaliação Heurística

1. **Seleção de Avaliadores**: Todos os membros do grupo de trabalho são designados como avaliadores, com base em suas habilidades e experiências em interação humano-computador e design de interfaces.

2. **Definição de Heurísticas**: Utilização das dez heurísticas de Nielsen, que incluem critérios como compatibilidade do sistema com o mundo real, consistência e padrões, prevenção de erros, e reconhecimento em vez de lembrança.

3. **Sessões de Avaliação**: Cada avaliador explora independentemente o portal, simulando interações de usuários reais e identificando desvios das heurísticas estabelecidas.

4. **Compilação de Resultados**: Todos os avaliadores compilam suas descobertas em relatórios individuais.

5. **Reunião de Consolidação**: Os avaliadores se reúnem para discutir seus achados, consolidando um relatório final que aponta os principais problemas de usabilidade e recomendações para melhoria.

6. **Priorização de Problemas**: Identificação e priorização dos problemas de usabilidade mais críticos que necessitam de intervenção imediata.

7. **Elaboração de Recomendações**: Formulação de recomendações específicas para cada problema identificado, visando melhorar a experiência do usuário e a eficácia geral do portal.

Este método permite uma avaliação detalhada e sistemática da interface do Portal Detran/DF, focando em melhorias que podem ser implementadas para resolver problemas de usabilidade antes que afetem negativamente a experiência do usuário. Ao não envolver diretamente os usuários durante a fase inicial de avaliação, economiza-se recursos e tempo, permitindo uma identificação rápida de áreas que necessitam de ajustes ou melhorias.

## Referências Bibliográficas

1. BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## 📑 Histórico de versão

|   Versão   | Data  | Descrição            | Autor                                                  | Revisor |
| :--------: | :---: | :------------------- | ------------------------------------------------------ | ------- |
| 1.0 |  11/05/2024  | Adição das características da Plataforma| [Pedro Sena](https://github.com/pedroyen21) | [Pedro Miguel](https://github.com/pedromadbr)     |
| 1.1 |  12/05/2024  | Adição da introdução ao documento| [Pedro Miguel](https://github.com/pedromadbr) | [Vinicius Vieira](https://github.com/viniciusvieira00)     |
| 1.2 |  13/05/2024  | Adição de tópicos| [Vinicius Vieira](https://github.com/viniciusvieira00) | [Pedro Miguel](https://github.com/pedromadbr)     |
