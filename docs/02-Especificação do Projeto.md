# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

<img align="center" alt="Lucas Silva" width="100%" src="https://media.discordapp.net/attachments/844003333982257164/952747818936827954/Screenshot_1.png?width=791&height=401">
<img align="center" alt="Jaqueline Carvalho" width="100%" src="https://media.discordapp.net/attachments/844003333982257164/952747819339513876/Screenshot_2.png">
<img align="center" alt="Antônio Carlos" width="100%" src="https://media.discordapp.net/attachments/844003333982257164/952747820358729749/Screenshot_5.png">
<img align="center" alt="José Samarago" width="100%" src="https://media.discordapp.net/attachments/844003333982257164/952747819746332732/Screenshot_3.png">
<img align="center" alt="André Firmino" width="100%" src="https://media.discordapp.net/attachments/844003333982257164/952747820052529182/Screenshot_4.png">

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO...| QUERO/PRECISO ... |PARA ...                |
|--------------------|------------------------------------|----------------------------------------|
|Lucas | Uma lista de todos os meus abastecimentos       | Saber o meu lucro no fim do mês |
|Jaqueline, André | Gerenciar o auxílio concedido pela empresa            | Conseguir alterar o valor do auxílio |
|André | Gerenciar os veículos utilizados pela empresa          | Analisar o que cada funcionário gasta em combustível|
|André | Calcular os gastos dos abastecimentos diários         | Para avaliar se compensa abastecer em um posto mais distante e barato|
|José | Passar meu controle do papel para o online        | Facilitar o controle|
|José | Identificar os abastecimentos por data     | Comprovar gastos|
|Antônio | Controle dos abastecimento     | Analisar qual tipo de transporte será ideal para o meu filho em cada dia|
|Antônio | Economizar nos abastecimentos    | Conseguir pagar o meu tratamento médico|
|Antônio | Ter acesso ao meu próprio gasto e do meu filho    | Dividir Contas|


Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve cadastrar o usuário | ALTA | 
|RF-002| O sistema deve efetuar login do usuário   | ALTA |
|RF-003| O sistema deve recuperar a senha do usuário | ALTA |
|RF-004| O sistema deve gerenciar veículos | ALTA |
|RF-005| O sistema deve registrar abastecimentos | ALTA |
|RF-006| Para cada registro de abastecimento, o sistema deve permitir que o usuário registre comentários | MÉDIA |
|RF-007| O sistema deve emitir relatório sobre o abastecimento de um ou mais veículos | ALTA |
|RF-008| O sistema deve ter a opçao de extrair relatório em forma de gráfico sobre o gasto dos abastecimentos | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | ALTA | 
|RNF-002| O sistema deve ser publicada em um ambiente acessível publicamente na internet | ALTA | 
|RNF-003| A aplicação deve ser compatível com os navegadores Google Chrome, Firefox, Microsoft Edge| ALTA |
|RNF-004| O sistema deve permitir o acesso de mais de um usuário a mesma conta | MÉDIA |
|RNF-005| A aplicação deve possuir interface limpa, com visualização voltada apenas para as necessidades do usuário no momento | MÉDIA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre letivo, que acontece no dia 26/06/2022 |
|02| O projeto deve ter no mínimo 06 casos de uso      |



## Diagrama de Casos de Uso

| ATOR   | DESCRIÇÃO                         |
|--------|-----------------------------------|
| Usuário | Pessoa interessada em ter controle sobre os gastos dos seus abastecimentos. |

| CASO DE USO | DESCRIÇÃO | RF |
|-------------|-----------|----|


![use case](https://user-images.githubusercontent.com/91639148/158084473-ffaf37ab-1fbc-4a40-b266-b50d2a2eba0c.png)
