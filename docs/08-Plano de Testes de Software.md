# Plano de Testes de Software

|Caso de teste     | CT 01 - Gerenciar usuário |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | 	 RF-001 - O sistema deve gerenciar o usuário
|**Objetivo do Teste** | Verificar se a função de cadastro do usuário está operando corretamente. |
|**Passos**  |	1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Cadastre-se” 3) Preencher os campos com as informações pessoais, como o nome, telefone, email e senha 4) Clicar no botão “Cadastrar” |
|**Critérios de Êxito** | “Cadastro realizado”. |

|Caso de Teste |CT-02 – Efetuar login |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-002 - O sistema deve efetuar login do usuário |
|**Objetivo do Teste** | Verificar se a função de login do usuário está operando corretamente. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Login” 3) Preencher os campos com as informações pessoais, como o email e senha  4) Clicar no botão “Fazer login” |
|**Critérios de Êxito** | O sistema será direcionado para a homepage com as informações pessoais do próprio usuário. |

|Caso de Teste |CT-03 – Recuperar senha |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-003 - O sistema deve recuperar a senha do usuário. |
|**Objetivo do Teste** | Verificar se a recuperação de senha está na funcionalidade. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Esqueci a senha” 3) Informar o e-mail de acesso 4) Informar o código recebido pelo e-mail  5) Digitar a nova senha 5) Clicar na opção “alterar a senha”  |
|**Critérios de Êxito** | “Sua senha foi alterada com sucesso”. |

|Caso de Teste |CT-04 – Gerenciar veículos |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-004 - O sistema deve gerenciar veículos. |
|**Objetivo do Teste** | Verificar se a função de cadastro de veículos está operando corretamente. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Clicar no botão "Cadastre o seu veículo" 4) Inserir as informações do veículo, como o modelo, ano e km/l.  5) Clicar no botão "Cadastrar" |
|**Critérios de Êxito** | "Veículo cadastrado". |

|Caso de Teste |CT-05 – Registrar abastecimentos |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-005 - O sistema deve registrar abastecimentos <br><br> RF-006 - Para cada registro de abastecimento, o sistema deve permitir que o usuário registre comentários |
|**Objetivo do Teste** | Verificar a funcionalidade do registro de abastecimentos. |
|**Passos** |  1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar a opção "Meus veículos" 4) Selecionar o veículo necessário 5) Clicar em "registrar o abastecimento", informar a quantidade de litros abastecido, tipo de combustível, valor total gasto, local de abastecimento 6) Adicionar um comentário na opção "comentários" caso necessite informar mais algum detalhe sobre o abastecimento 7) Clicar no botão "Registrar" | 
|**Critérios de Êxito** | "Registro realizado". |



<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.
 
## Ferramentas de Testes (Opcional)

Comente sobre as ferramentas de testes utilizadas.
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
