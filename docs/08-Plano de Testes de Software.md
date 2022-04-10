# Plano de Testes de Software

Os requisitos para realização dos testes de software são:
- Site publicado na Internet
- Navegador da Internet - Google Chrome, Firefox, Microsoft Edge
- Qualquer dispositivo <br> <br> Os testes funcionais a serem realizados são descritos a seguir.

## Roteiro

|Caso de teste     | CT 01 - Gerenciar usuário (Criar cadastro) |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | 	 RF-001 - O sistema deve gerenciar o usuário
|**Objetivo do Teste** | Verificar se a função de cadastro do usuário está operando corretamente. |
|**Passos**  |	1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Cadastre-se” 3) Preencher os campos com as informações pessoais, como o nome, telefone, email e senha 4) Clicar no botão “Cadastrar” |
|**Critérios de Êxito** | “Cadastro realizado”. |

|Caso de teste     | CT 02 - Gerenciar usuário (Excluir cadastro) |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | 	 RF-001 - O sistema deve gerenciar o usuário
|**Objetivo do Teste** | Verificar se a função de excluir o cadastro do usuário está operando corretamente. |
|**Passos**  |	1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar "excluir cadastro" |
|**Critérios de Êxito** | “Cadastro excluído com sucesso”. |

|Caso de teste     | CT 03 - Gerenciar usuário (Alterar dados pessoais) |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | 	 RF-001 - O sistema deve gerenciar o usuário
|**Objetivo do Teste** | Verificar se a função de alteração de dados do usuário está operando corretamente. |
|**Passos**  |	1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar "alterar dados" 4) Alterar o e-mail, senha e telefone 5) Clicar no botão "Alterar" |
|**Critérios de Êxito** | “Realizado a alteração”. |

|Caso de Teste |CT-04 – Efetuar login |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-002 - O sistema deve efetuar login do usuário |
|**Objetivo do Teste** | Verificar se a função de login do usuário está operando corretamente. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Login” 3) Preencher os campos com as informações pessoais, como o email e senha  4) Clicar no botão “Fazer login” |
|**Critérios de Êxito** | O sistema será direcionado para a homepage com as informações do próprio usuário. |

|Caso de Teste |CT-05 – Recuperar senha |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-003 - O sistema deve recuperar a senha do usuário. |
|**Objetivo do Teste** | Verificar se a recuperação de senha está na funcionalidade. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Clicar no botão “Esqueci a senha” 3) Informar o e-mail de acesso 4) Informar o código recebido pelo e-mail  5) Digitar a nova senha 5) Clicar na opção “alterar a senha”  |
|**Critérios de Êxito** | “Sua senha foi alterada com sucesso”. |

|Caso de Teste |CT-06 – Gerenciar veículos (Cadastrar veículos) |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-004 - O sistema deve gerenciar veículos. |
|**Objetivo do Teste** | Verificar se a função de cadastro de veículos está operando corretamente. |
|**Passos** | 1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Clicar no botão "Cadastre o seu veículo" 4) Inserir as informações do veículo, como o modelo, ano e km/l.  5) Clicar no botão "Cadastrar" |
|**Critérios de Êxito** | "Veículo cadastrado". |

|Caso de teste |CT 07 - Gerenciar usuário (Excluir cadastro de veículos) |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | 	 RF-004 - O sistema deve gerenciar veículos. |
|**Objetivo do Teste** | Verificar se a função de excluir o cadastro de veículos está operando corretamente. |
|**Passos**  |	1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar o veículo de escolha 4) Selecionar a opção "excluir cadastro" |
|**Critérios de Êxito** | “Veículo excluído com sucesso”. |

|Caso de Teste |CT-08 – Registrar abastecimentos |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-005 - O sistema deve registrar abastecimentos <br><br> RF-006 - Para cada registro de abastecimento, o sistema deve permitir que o usuário registre comentários |
|**Objetivo do Teste** | Verificar a funcionalidade do registro de abastecimentos. |
|**Passos** |  1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar a opção "Meus veículos" 4) Selecionar o veículo necessário 5) Clicar em "registrar o abastecimento", informar a quantidade de litros abastecido, tipo de combustível, valor total gasto, local de abastecimento 6) Adicionar um comentário na opção "comentários" caso necessite informar mais algum detalhe sobre o abastecimento 7) Clicar no botão "Registrar" | 
|**Critérios de Êxito** | "Registro realizado". |

|Caso de Teste |CT-09 – Visualizar registro de abastecimentos |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-007 - O sistema deve emitir relatório sobre o abastecimento de um ou mais veículos |
|**Objetivo do Teste** | Verificar a funcionalidade de emitir relatório está operando corretamente. |
|**Passos** |  1) Acessar o site “x” com o browser escolhido 2) Fazer o login 3) Selecionar a opção "emitir relatórios" 4) Selecionar a data desejada  5) Clicar em "emitir relatório"  | 
|**Critérios de Êxito** | Será visualizado uma tela com o relatório conforme solicitado. |




