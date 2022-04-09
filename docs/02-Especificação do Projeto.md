# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

| Lucas Silva        |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/AutoCalc/blob/main/docs/img/Lucas.png) |**Idade:** 24 anos <br><br> **Ocupação:** Motorista de aplicativo | Aplicativos: LinkedIn, Whatsapp, Jornais. |
|**Motivações:** Lucas trabalha bastante e sempre bate metas estabelecidas pela Uber, porém, não vê para onde o dinheiro está indo. Ele tem em mente que a cada 3 dias precisa abastecer novamente, portanto, ele necessita de um meio para analisar os seus gastos semanais e comparar com os lucros.  |  **Frustrações:**  Por ficar cansado com o trabalho, Lucas acaba deixando as contas e o planejamento de lado, por ser pouco prático anotar e somar tudo sempre sem um espaço específico para isso. |**História:** Lucas era um estudante e viu a renda da família cair com a pandemia. Com isso procurou emprego por algum tempo, durante esta procura conheceu a profissão de motorista de aplicativo e está nela há 8 meses.| 

| Jaqueline Carvalho |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/AutoCalc/blob/main/docs/img/Jaqueline.png) |**Idade:** 36 anos <br><br> **Ocupação:** Representante comercial |Aplicativos: Whatsapp, Facebook, Instagram.|
|**Motivações:** Jaqueline sempre bate suas metas na empresa. De uns meses para cá viu seu auxílio combustível se manter o mesmo valor, mas sem conseguir chegar até o final do mês devido aos constantes aumentos dos combustíveis. Jaqueline sempre busca o posto mais barato, porém a empresa só permite abastecer em uma rede onde as opções de postos são limitados, por isso gostaria de um meio que comprovasse sua necessidade de um auxílio maior.  |**Frustrações:**  Apesar de já anotar e pesquisar, Jaqueline precisa de um meio rápido de consulta e de relatórios que não podem se perder, visto que não consegue trabalhar sem eles.|

| José Samarago      |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/AutoCalc/blob/main/docs/img/Jose.png)|**Idade:** 48 anos <br><br> **Ocupação:** Courier, empresa de transportes. |Aplicativos: Whatsapp, Telegram.|
|**Motivações:** José trabalhou com empresas de entregas durante 10 anos e sempre fez suas contas em uma caderneta. Ele gostaria de um modo em que ele pudesse levar ao seu gestor seus gastos, para que a empresa criasse um auxílio combustível ou parceria com alguma bandeira para melhorar seus rendimentos.  |**Frustrações:** José precisa de um relatório completo com datas e locais para mandar ao seu chefe, mas não pode ser feito manualmente por não ser aceito pela empresa.|

| André Firmino    |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/AutoCalc/blob/main/docs/img/Andre.png)|**Idade:** 56 anos <br><br> **Ocupação:** Sócio de uma empresa   |Aplicativos: Facebook, Whatsapp, LinkedIn.|
|**Motivações:** André é sócio administrador de uma empresa. Todos os dias gerencia vários representantes comerciais, mas de um tempo para cá tem visto um consumo maior de combustível de cada representante. André precisa limitar os litros para não perder o orçamento mensal, e precisa controlar seus colaboradores visitando clientes. Ele gostaria que cada um trouxesse seus gastos ao financeiro de uma forma padrão para conseguir avaliar a melhor forma de resolver o problema.  |**Frustrações:** André precisa que todos da sua empresa consigam usar o site da melhor forma, tanto para saber com qual combustível irá abastecer, quanto para deixar registrados os gastos. Ele precisa que seja de fácil aprendizado para todos.

| Antônio Carlos     |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/AutoCalc/blob/main/docs/img/Antonio.png)|**Idade:** 64 anos <br><br> **Ocupação:** Aposentado |Aplicativos: Whatsapp, Jornais.|
|**Motivações:** Antônio possui um carro modelo 2010 e sempre anotou em uma caderneta todos os abastecimentos desde que comprou o veículo. O problema é que hoje ele partilha o carro com seu filho e gostaria de ter controle dos abastecimentos para saber se vale a pena seu filho ir trabalhar de carro ou pegar o ônibus.|**Frustrações:** Antônio precisa de ver o preço do combustível diariamente com seu filho, assim como os dois necessitam ter acesso aos dados do carro com uma mesma conta. Antônio precisa passar por um tratamento médico, portanto, precisa economizar.|

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
|RF-001| O sistema deve gerenciar usuários | ALTA | 
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
|RNF-001| O sistema deve ser responsivo para que funcione bem em qualquer dispositivo | ALTA | 
|RNF-002| O sistema deve ser publicada em um ambiente acessível publicamente na internet | ALTA | 
|RNF-003| A aplicação deve ser compatível com os navegadores Google Chrome, Firefox, Microsoft Edge| ALTA |
|RNF-004| O sistema deve permitir o acesso de mais de um usuário a mesma conta | BAIXA |
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


![usecase2](https://user-images.githubusercontent.com/91639148/162327240-a4b38404-b669-4066-baa3-25d1eebfb8d1.png)
