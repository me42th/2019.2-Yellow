|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|2.0| Letícia Karla e Dâmaso Júnio | Criou o documento. |25/10/2019| Remoto, via Draw.io|
|2.1| Letícia Karla e Dâmaso Júnio | Adicionou descrição sobre cada cada de uso |21/11/2019| Remoto|


# Casos de Uso

## Sumário
1. Sumário
2. Introdução
3. Metodologia
4. Casos de Uso
5. Resultados
6. Conclusão
7. Referências

## Introdução
<p align="justify">O diagrama documenta o que o aplicativo faz do ponto de vista do usuário. Em outras palavras, ele descreve as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários da Yellow.<br>
Em sua segunda versão, o diagrama foi dividido. E atualizado, de acordo com os feedbacks do professor e dos monitores em relação a como as tarefas deveriam ser mais detalhadas e especificadas possível. </p>

## Metodologia

Um Caso de Uso define uma sequencia de ações executadas pelo sistema retornando valores que podem ser observados pelos Atores. Um Ator é um papel que um usuário desempenha em relação ao sistema. Cada Caso de Uso descreve ações que o sistema deve executar para retornar algum valor para o Ator,   demostra as funcionalidades do sistema utilizadas pelos Atores. O Caso de Uso representa um fluxo completo de eventos, diálogo entre os Atores e o sistema.

## Casos de Uso
![UC1_RequisitosYellow](/img/modelagem/UC/UC_cadastro.png)
<br>
![UC2_RequisitosYellow](/img/modelagem/UC/UC_creditos.png)

## Resultados

### UC01 - Baixar o aplicativo

|Descrição|Fazer o download do aplicativo pela loja do sistema|
|---------|-|
|**Atores**|Usuário|
|**Pré-Condições**|Ter um smartphone Android e/ou iOS|
|**Linha de eventos**|Evento 01: Entrar na loja -> Baixar o aplicativo </br> Evento 02: Entrar na loja -> Procurar pelo aplicativo|
|**Fluxo principal**|**FP01 - Fazer o download do aplicativo:**</br> Esse fluxo tem como finalidade fazer o download do aplicativo Yellow </br> 1. O Ator entra na loja de aplicativos. </br> 2. O Ator procura pelo aplicativo na loja. </br> 3. O Ator realiza o download.|
|**Fluxos Alternativos**| -- |
|**Fluxos de exceções**|--|
|**Pós-condições**|O ator terá o aplicativo baixado em seu smartphone|

### UC02 - Fazer login

|Descrição|Efetuar o login no aplicativo|
|---------|-|
|**Atores**|Usuário|
|**Pré-Condições**|Ter o aplicativo instalado no smartphone Android e/ou iOS|
|**Linha de eventos**|Evento 01: Entrar no aplicativo -> Efetuar o login com Facebook </br> Evento 02: Entrar no aplicativo -> Efetuar o login com o Google|
|**Fluxo principal**|**FP01 - Fazer o login no aplicativo com o Facebook:**</br> 1. O Ator entra no aplicativo. </br> 2. O Ator clica em "Login com Facebook". </br> 3. O Ator acessa sua conta.|
|**Fluxos Alternativos**|**FA01 - Fazer o login no aplicativo com o Google:**</br>1. O Ator entra no aplicativo. </br> 2. O Ator clica em "Login com o Google". </br> 3. O Ator acessa sua conta.|
|**Fluxos de exceções**|**FE01 - O usuário não tem cadastro com o Facebook:**</br>1. O Ator não tem conta no Facebook</br>2. O Ator clica em "Login com Facebook".</br>3. O Ator não acessa sua conta</br> **FE02 - O usuário não tem cadastro com o Google**</br>1. O Ator não tem conta no Google.</br>2. O Ator clica em "Login com Google".</br>3. O Ator não acessa sua conta.|
|**Pós-condições**|O usuário deve ter acesso às funcionalidades do aplicativo.|

### UC03 - Pedir Suporte

|Descrição|Solicitar suporte do aplicativo para resolver um problema|
|---------|-|
|**Atores**|Usuário|
|**Pré-Condições**|Ter o aplicativo instalado no smartphone Android e/ou iOS</br> Ter efetuado o login no aplicativo|
|**Linha de eventos**|Evento 01: Bicicleta não destrava -> Pedir suporte</br>Evento 02: Patinete não destrava -> Pedir suporte</br>Evento 03: Bicicleta não trava após o uso -> Pedir suporte </br>Evento 04: Patinete não trava após o uso -> Pedir suporte</br>Evento 05: Não é possível adicionar crédito na conta -> Pedir suporte</br>Evento 06: Pedir reembolso -> Pedir suporte</br>Evento 07: Veículo está danificado -> Pedir suporte</br>Evento 08: Algum problema surge -> Pedir suporte|
|**Fluxo principal**|**FP01 - O usuário solicita o suporte do aplicativo:**</br> 1. O Ator está utilizando o aplicativo. </br> 2. Surge um problema no uso do aplicativo e/ou dos veículos </br> 3. O Ator acessa a área de suporte ao usuário.|
|**Fluxos Alternativos**|--|
|**Fluxos de exceções**|**FE01 - O suporte não está disponível:**</br>1. O Ator está utilizando o aplicativo. </br> 2. Surge um problema no uso do aplicativo e/ou dos veículos.</br>3. O suporte não está disponível.|
|**Pós-condições**|O usuário recebe o suporte corretamente, para solucionar o seu problema.|

### UC04 - Acessar o perfil do usuário

|Descrição|Acessar o perfil do usuário|
|---------|-|
|**Atores**|Usuário|
|**Pré-Condições**|Ter uma conta no aplicativo|
|**Linha de eventos**|Evento 01: Abrir o aplicativo -> Clicar no ícone do perfil|
|**Fluxo principal**|**FP01 - O usuário acessa o próprio perfil**</br>1. O Ator entra no aplicativo.<br> 2. O Ator clica no ícone do perfil do usuário <br> 3. O Ator acessa o próprio perfil.|
|**Fluxos Alternativos**|--|
|**Fluxos de exceções**|**FE01 - O usuário não tem cadastro no aplicativo**<br> 1. O Ator entra no aplicativo <br> 2. O Ator não tem cadastro no aplicativo.|
|**Pós-condições**|O usuário consegue ter acesso às opções variadas na sua página de perfil.|

### UC05 - Pagar um boleto

|Descrição|Realizar o pagamento de um boleto bancário|
|---------|-|
|**Atores**|Usuário, Sistema|
|**Pré-Condições**|Ter o aplicativo instalado no smartphone Android e/ou iOS<br>Ter um cartão de crédito<br> Ter créditos no aplicativo|
|**Linha de eventos**|Evento 01: Abrir o aplicativo -> Clicar em "Carteira" -> Pagar um boleto.<br>Evento 02: Abrir o aplicativo -> Clicar em "Perfil" -> Clicar em "Carteira" -> Pagar um boleto.|
|**Fluxo principal**|**FP01 - Clicar em "Carteira"**<br>1. O Ator entra no aplicativo<br>2. O Ator clica no ícone da "Carteira" ao canto da tela<br>3. O Ator clica em "Pagar um boleto".|
|**Fluxos Alternativos**|**FA01 - Clicar em "Perfil"**<br>1. O Ator abre o aplicativo.<br>2. O Ator clica no ícone de "Perfil".<br>3. O Ator clica na opção "Carteira".<br>4. O Ator clica em "Pagar boleto".|
|**Fluxos de exceções**|**FE01 - O usuário não tem cartão de crédito**<br>1. O Ator clica em "Pagar boleto".<br>2. O Sistema pede para que seja feito o cadastro de um cartão de crédito.<br>**FE02 - O usuário não tem créditos no aplicativo**<br>1. O Ator clica em "Pagar boleto".<br>2. O Sistema informa que o usuário não tem créditos disponível.|
|**Pós-condições**|O usuário realiza o pagamento de um boleto bancário com sucesso.|

### UC06 - Compartilhar crédito com os amigos

|Descrição|Realizar o compartilhamento de crédito entre os usuários|
|---------|-|
|**Atores**|Usuário e Sistema|
|**Pré-Condições**|Duas pessoas diferentes, tenham o cadastro no aplicativo.<br>Uma das pessoas deve ter créditos no aplicativo.|
|**Linha de eventos**|Evento 01: Abrir o aplicativo -> Clicar em "Perfil" -> Clicar em "Carteira" -> Compartilhar créditos.<br>Evento 02: Abrir o aplicativo -> Clicar em "Carteira" -> Compartilhar créditos.|
|**Fluxo principal**|**FP01 - Clicar em "Carteira"**<br>1. O Ator abre o aplicativo.<br>2. O Ator clica em "Carteira".<br>3. O Ator clica em "Compartilhar crédito com amigos".<br> 4. É feito o compartilhamento.|
|**Fluxos Alternativos**|**FA01 - Clicar em "Perfil"**<br>1. O Ator abre o aplicativo.<br>2. O Ator clica em "Perfil".<br>3. O Ator clica em "Carteira".<br>4. O Ator clica em "Compartilhar crédito com amigos".<br>5. É feito o compartilhamento.|
|**Fluxos de exceções**|**FE01 - Usuário não tem crédito**<br>1. O Ator clica em "Compartilhar crédito com amigos".<br>2. O Sistema informa que o usuário não tem créditos disponíveis.<br>3. O compartilhamento não é feito|
|**Pós-condições**|O segundo usuário recebe os créditos compartilhados para que ele possa utilizar no aplicativo.|

### UC07 - Adicionar promoções

|Descrição| Adicionar promoções para o usuário utilizar|
|---------|-|
|**Atores**| Sistema e usuário.|
|**Pré-Condições**|A empresa desenvolver promoções para os usuários do aplicativo. <br> As promoções devem estar visíveis para o usuário.|
|**Linha de eventos**|Evento 01: Os desenvolvedores deixam a promoção disponível na tela inicial. -> O usuário clica na promoção. -> O usuário utiliza a promoção. <br> Evento 02: A empresa disponibiliza códigos promocionais -> O usuário escreve o código quando for pagar os créditos. |
|**Fluxo principal**|**FP01 - Clicar na Promoção** <br> 1.  O Ator abre o aplicativo. <br> 2. O ator clica na "Promoção". <br> 3. O ator utiliza a promoção. <br> **FP02 - Utilizar código promocional** <br> 1. O sistema gera o "Código Promocional". <br> 2. O ator clica em "Carteira". <br> 3. O usuário adiciona o crédito. <br> 4. O usuário insere o código promocional.  |
|**Fluxos Alternativos**|N/A.|
|**Fluxos de exceções**|**FE01 - O usuário não tem direito a código Promocional** <br> 1. O usuário adiciona o crédito <br> 2. O usuário tenta colocar o código promocional. <br> 3. O sistema informa ao usuário que ele não tem direito à código promocional.|
|**Pós-condições**|O usuário paga mais barato pelos créditos, ou recebe promoções que facilitem o uso do produto oferecido pelo aplicativo.|

### UC08 - Recarregar créditos do celular

|Descrição|Inserir créditos no celular utilizando crédito da Yellow|
|---------|-|
|**Atores**|Usuário e Sistema.|
|**Pré-Condições**|O usuário ter créditos no aplicativo e chip de celular, que possua sistema de recarga de crédito.|
|**Linha de eventos**|Evento 01: O sistema estabelece conexão com as operadoras de telefonia -> O sistema disponibiliza as operadoras para o usuário. <br> Evento 02: O usuário escolhe a quantidade de crédito que irá recarregar o celular -> o sistema disponibiliza campos para adicionar o número telefônico.|
|**Fluxo principal**|**FP01 - Inserir crédito** <br> 1. O ator abre o aplicativo. <br> 2. O ator clica em "Carteira". <br> 3. O usuário clica em "Recarga de Celular". <br> 4. O ator clica na "Operadora de Telefonia". <br> 5. O usuário insere o número telefônico. <br> 6. O usuário confirma a operação.|
|**Fluxos Alternativos**|**FA01 - Clicar em "Perfil"**<br>1. O Ator abre o aplicativo.<br>2. O Ator clica em "Perfil".<br>3. O Ator clica em "Carteira".<br> 4. O usuário clica em "Recarga de Celular". <br> 5. O ator clica na "Operadora de Telefonia". <br> 6. O usuário insere o número telefônico. <br> 7. O usuário confirma a operação.|
|**Fluxos de exceções**|**FE01 - Usuário não tem crédito**<br>1. O Ator clica em "Recarregar Celular".<br>2. O Sistema informa que o usuário não tem créditos disponíveis.<br>3. A recarga não é realizada.|
|**Pós-condições**|O usuário tem créditos no celular para utilizar da forma que prefirir.|

### UC09 - Pedir reembolso

|Descrição|Realizar reembolso ao usuário|
|---------|-|
|**Atores**|Usuário e Sistema.|
|**Pré-Condições**|O sistema deve ter realizado uma cobrança indevida ao usuário.|
|**Linha de eventos**|Evento 01: O usuário verifica que houve uma cobrança indevida -> O usuário contata o aplicativo. <br> Evento 02: O aplcativo analisa o pedido de reembolso do usuário -> O aplicativo informa ao usuário a ação decidida.|
|**Fluxo principal**|**FP01 - Pedir reembolso** <br> 1. O ator abre o aplicativo.<br> 2. O ator clica em "Carteira".<br> 3. O ator clica em "Pedir reembolso".|
|**Fluxos Alternativos**|**FA01 - Clicar em "Perfil"**<br>1. O Ator abre o aplicativo.<br>2. O Ator clica em "Perfil".<br>3. O Ator clica em "Carteira".<br>4. O ator clica em "Pedir reembolso".|
|**Fluxos de exceções**|**FE01 - O usuário não realizou compra de crédito**<br>1. O usuário clica em "Estornar Crédito"<br>2. O sistema informa ao usuário que ele não utilizou crédito|
|**Pós-condições**|O usuário soluciona seus problemas de cobranças indevidas.|

### UC10 - Digitar o código de barras

|Descrição|Permitir a digitação do código de barras |
|---------|-|
|**Atores**|Usuário e Sistema|
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC11 - Escanear o código de barras

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC12 - Recarregar créditos

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC13 - Cadastrar meios de pagamentos

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC14 - Criar uma conta com o Google

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC15 - Acessar o aplicativo

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC16 - Cadastrar o usuário

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC17 - Adicionar telefone

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC18 - Criar conta com o Facebook

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC19 - Confirmar cadastro por SMS

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC20 - Confirmar cadastro via WhatsApp

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC21 - Requisitar contas em redes sociais

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC22 - Ler informações sobre o usuário

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC23 - Requisitar número do telefone

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC24 - Reportar problema

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC25 - Pedir ajuda

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC26 - Resolver problema

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||

### UC27 - Prestar auxílio

|Descrição||
|---------|-|
|**Atores**||
|**Pré-Condições**||
|**Linha de eventos**||
|**Fluxo principal**||
|**Fluxos Alternativos**||
|**Fluxos de exceções**||
|**Pós-condições**||


## Conclusão
<p align="justify">O diagrama de casos de uso, serve para dar uma visão mais clara sobre como é organizada as tarefas e assim, ficando mais simples o desenvolvimento de tela a tela.</p>

## Referências

1. COCKBURN, Alistair. Writing Effective Use Cases. [S. l.: s. n.], 2011. 275 p.
2. BEZERRA, Eduardo. Princípios de Análise e Projeto de Sistemas com UML. 2ª. ed. Rio de Janeiro: Campus/Elsevier, 2006. 392 p. ISBN 8535216960.
