|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|1.0| Pedro Igor | Criou o documento. |30/09/2019| Remoto|
|1.1| Pedro Igor | Adicionou mais detalhes aos cenários |30/09/2019| Remoto|
|1.2| Pedro Igor | Adicionou mais cenários para a tela "Meu Saldo." |08/10/2019| Remoto|
|1.3| Pedro Igor | Adicionou mais cenários de login/cadastro e menu lateral esquerdo. |01/11/2019| Remoto|
|1.4| Pedro Igor | Refatorou cenários de acordo com os resultados da inspeção realizada pelo Dâmaso. |01/11/2019| Remoto |
|1.5| Dâmaso Júnio | Formatou tabela de versão. |19/11/2019| Remoto |
|1.6| Pedro Igor | Adicionando rastreabilidade e formatando o artefato. | 23/11/2019 | Remoto |

# Cenários

## Rastreabilidade
Como o intuito dos cenários é criar cenas da utilização da aplicação, por consequência, grande parte (se não todos) dos requisitos elicitados participam da rastreabilidade deste artefato.
### Pré-rastreabilidade:
[Rich Picture](../pre_rastreabilidade/rich_picture.md)
### Elicitação:
[5W2H](../elicitacao/requisitos/5w2h_v2.md)<br>
[Análise de Discuso](../elicitacao/requisitos/analise_discurso.md)<br>
[Bainstrorming](../elicitacao/requisitos/brainstorm_v1.md)<br>
[Entrevista](../elicitacao/requisitos/entrevista.md)<br>
[Introspecção](../elicitacao/requisitos/introspeccao.md)<br>
[Observação](../elicitacao/requisitos/observacao.md)<br>
[Questionário](../elicitacao/requisitos/questionario.md)<br>
[Story Telling](../elicitacao/requisitos/storytelling_v1.md)<br>
[Requisitos Elicitados](../elicitacao/requisitos/requisitos_elicitados/requisitos_elicitados_v3.md)

<br>



## 1. Sumário
1. Sumário
2. Introdução
3. Metodologia
4. Questionário
5. Resultados
6. Conclusão
7. Referências

## 2. Introdução
<p align="justify">Cenários são utilizados para o desenvolvimento de possibilidades de utilização de determinado produto. Sendo assim, são definidas características de cenários reais para a imaginação de algo atualmente imaginável porém de possível execução. É definido um objetivo que comumente é a realização de uma tarefa disponível, logo em seguida são descritos características como contexto, atores participantes, recursos necessários, cenas deste cenário, restrições aos participantes das cenas assim como exceções que possam interromper o cumprimento do objetivo inicial. Cenários podem ser úteis para descrição em geral de requisitos visto que são mais fáceis de serem visualizados pelas pessoas.</p>

## 3. Metodologia
A metologia se baseou no livro Engenharia de Software - Ian Sommerville 9ª Edição que define o que são cenários e como utilizá-los. A técnica é útil por ser de simples interpretação por praticamente qualquer pessoa. Foram definidos então cenários baseados em possíveis utilizações de cada funcionalidade da aplicação.

## 4. Questionário
De acordo com o livro, cenários devem conter as seguinte características:

1. Uma descrição do que o sistema e os usuários esperam quando o cenário se iniciar.
2. Uma descrição do fluxo normal de eventos no cenário.
3. Uma descrição do que pode dar errado e como isso é tratado.
4. Informações sobre outras atividades que podem acontecer ao mesmo tempo.
5. Uma descrição do estado do sistema quando o cenário acaba.
A elicitação baseada em cenários envolve o trabalho com os stakeholders para identificar cenários e capturar
detalhes que serão incluídos nesses cenários. Os cenários podem ser escritos como texto, suplementados por diagramas, telas etc. Outra possibilidade é uma abordagem mais estruturada, em que cenários de eventos ou casos
de uso podem ser usados.

## 5. Resultados

### Saldo
***
**Histórico de transações**

<b>Objetivo:</b> Visualizar o histórico de transações.

<b>Contexto:</b><br><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até as últimas opções.<br>
- O usuário seleciona "Histórico de transações".<br>
- O usuário visualiza transações caso haja.<br>

<b>Restrições:</b> O usuário está restrito a visualizar suas transações se houver.<br>

<b>Excessões:</b> Erro na conexão com a internet.<br>


****
**Solicitação de reembolso**

<b>Objetivo:</b> Solicitar um reembolso.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário, Suporte da Yellow.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até as últimas opções.<br>
- O usuário seleciona "Solicitar reembolso".<br>
- O usuário seleciona o motivo pelo qual está solicitando um reembolso.<br>
- O usuário clica em "Retornar a minha carteira".<br>
- O suporte da Yellow pode analisar o motivo da solicitação.<br>
- O suporte da Yellow disponibiliza o reembolso.<br>


<b>Restrições:</b> Usuário está restrito a solicitar reembolso de saldo disponível.<br>

<b>Excessões:</b> Erro na conexão com a internet. Atendimento Yellow pode não liberar o reembolso.<br>


****
**Centro de Ajuda**

<b>Objetivo:</b> Encontrar ajuda na utilização.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até as últimas opções.<br>
- O usuário seleciona "Acessar o centro de ajuda".<br>
- O usuário seleciona no que deseja ser ajudado.<br>


<b>Restrições:</b> O usuário está restrito a visualizar conteúdo sobre ajuda.<br>

<b>Excessões:</b> Erro na conexão com a internet. Bug no app que não mostra o conteúdo a ser mostrado.<br>

****
**Pagar conta e serviços**

<b>Objetivo:</b> Pagar uma conta ou serviço por meio do app.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até a opção "Serviços e contas".<br>
- O usuário seleciona a conta a qual deseja pagar.<br>
- O usuário preenche informações sobre a conta a ser paga. (No momento é mostrado apenas um formulário em branco.)<br>


<b>Restrições:</b> Usuário está restrito a pagar algum tipo de conta ou serviço.<br>

<b>Excessões:</b> Erro na conexão com a internet. Bug no app que não mostra o conteúdo a ser mostrado.<br>


****
**Pagar conta e serviços**

<b>Objetivo:</b> Pagar uma conta ou serviço por meio do app.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo"<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até a opção "Serviços e contas".<br>
- O usuário seleciona a conta a qual deseja pagar.<br>
- O usuário preenche informações sobre a conta a ser paga. (No momento é mostrado apenas um formulário em branco.)<br>


<b>Restrições:</b> Usuário está restrito a pagar algum tipo de conta ou serviço.<br>

<b>Excessões:</b> Erro na conexão com a internet. Bug no app que não mostra o conteúdo a ser mostrado.<br>


****
**Recarga de celular**

<b>Objetivo:</b> Recarregar número de celular.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado. Ter crédito suficiente para uma recarga de celular.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário navega até "Recargas de celular e planos" e seleciona uma operadora.<br>
- O usuário informa um número de celular para que seja realizado o serviço.<br>
- O usuário seleciona o valor da recarga e clica em "Próximo".<br>
- O usuário confirma o pagamento com o saldo na Yellow.<br>

<b>Restrições:</b> Usuário está restrito a fazer recargas nas operadoras disponíveis, restrito ao valor máximo de crédito disponível na conta.<br>

<b>Excessões:</b> Erro na conexão com a internet.<br>


****
**Transferir crédito**

<b>Objetivo:</b> Transferir créditos entre contas.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Ambos os usuários estarem logados. Ter crédito em uma das contas.<br>

<b>Atores:</b> Dois usuários.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário 1 e 2 abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- O usuário 1 e 2 navega até "Transferir dinheiro" e clica em "Enviar ou receber com QR".<br>
- O usuário 2 informa o valor a ser enviado.<br>
- O usuário 2 gera um QR Code para enviar o crédito, o usuário 1 recebe o crédito por meio do QR Code do usuário 1.<br>

<b>Restrições:</b> Usuário 2 está restrito a enviar o crédito disponível na conta.<br>

<b>Excessões:</b> Erro na conexão com a internet.<br>


****
**Adicionar crédito**

<b>Objetivo:</b> Adicionar crédito a conta.

<b>Contexto:</b><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone, dinheiro para ser inserido na conta.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo e clica em "Meu saldo" ou clica em "Adicionar crédito" na tela inicial.<br>
- O usuário seleciona "Adicionar crédito".<br>
- O usuário seleciona o valor ser inserido e a forma de pagamento.<br>
- O usuário confirma a compra de crédito.<br>

<b>Restrições:</b> O usuário está restrito inserir as quantidades disponíveis.<br>

<b>Excessões:</b> Erro na conexão com a internet. Boleto vencer.<br>



### Cadastro e Login

****
**No Android e IOS**

<b>Objetivo:</b> Criar uma conta ou entrar em uma conta existente.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Não estar logado.<br>

<b>Atores:</b> Novo usuário ou usuário que reinstalou a aplicação.<br>

<b>Recursos:</b> Smartphone

<b>Episódios:</b> <br>
- O usuário quer utilizar o aplicativo.<br>
- O usuário baixa a aplicação e abre.<br>
- O usuário dá as permissões para acesso a conta do google ou facebook.<br>
- O usuário pode utilizar o aplicativo se o login for feito com sucesso.<br>

<b>Restrições:</b> O usuário está restrito a logar por meio de uma conta do Google.<br>

<b>Excessões:</b> Falha na conexão na internet, erro ao digitar senha caso necessário.<br>



### Utilização
****
**Centro de Ajuda (Tela principal)**

<b>Objetivo:</b> Encontrar ajuda com carteira, bicicleta ou patinete.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário precisa de ajuda.<br>
- O usuário clica no "?" na tela inicial.<br>
- O usuário visualiza as opções de temas de ajuda disponíveis.<br>
- O usuário seleciona um tema.<br>
- O usuário especifica a ajuda que precisa selecionando as opções posteriormente disponibilizadas..<br>

<b>Restrições:</b> O usuário está restrito a encontrar ajuda com carteira, patinete e bicicleta.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>


****
**Reportar problema**

<b>Objetivo:</b> Reportar problema encontrado na utilização da aplicação.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
-O usuário quer informar problema.<br>
-O usuário clica no "?" na tela inicial.<br>
-O usuário seleciona "Report Issue".<br>
-O usuário especifica o tipo de problema a ser reportado.<br>
-O usuário segue o passo a passo solicitado pelo app.<br>

<b>Restrições:</b>O usuário está restrito a reportar problema mecânicos, de veículos não encontrados, veículos atrapalhando a circulação e fazer uma queixa.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>

****
**Contatar suporte**

<b>Objetivo:</b> Entrar em contato com o suporte.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário quer entrar em contato com a equipe de suporte.<br>
- O usuário clica no "?" na tela inicial.<br>
- O usuário seleciona "Contact Us".<br>
- O usuário especifica o tipo de contato assim como o tema.<br>
- O usuário escreve uma mensagem entre 15 e 200 caracteres e clica em "Send".<br>

<b>Restrições:</b> O usuário está restrito a contatar suporte sobre os motivos listados na aplicação.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>

****
**Encontrar patinete**

<b>Objetivo:</b> Encontrar um patinete disponível para utilização.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário quer encontrar um patinete.<br>
- O usuário clica em "patinete" na tela inicial.<br>
- O usuário visualiza num mapa patinetes disponíveis e sua localização.<br>
- O usuário se dirige ao local do patinete.<br>

<b>Restrições:</b> O usuário está restrito a encontrar um patinete no mapa.<br>

<b>Excessões:</b> Falha na aplicação ao mostrar localização, patinete foi alugado enquanto o usuário chegava ao local.<br>


****
**Encontrar bicicleta**

<b>Objetivo:</b> Encontrar uma bicicleta disponível para utilização.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário procurando por uma bicicleta.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário quer encontrar uma bicicleta.<br>
- O usuário clica em "bike" na tela inicial.<br>
- O usuário visualiza num mapa bicicletas disponíveis e sua localização.<br>
- O usuário se dirige ao local da bicicleta.<br>

<b>Restrições:</b> O usuário está restrito a encontrar uma bicicleta no mapa.<br>

<b>Excessões:</b> Falha na aplicação ao mostrar localização, bicicleta foi alugada enquanto o usuário chegava ao local.<br>


****
**Liberar veículo**

<b>Objetivo:</b> Liberar um veículo para utilização.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone e veículo (bicicleta, patinete)

<b>Episódios:</b> <br>
- O usuário encontra um veículo.<br>
- O usuário clica em "Scan" na tela inicial.<br>
- O usuário liga o flash casso necessário e tenta capturar o QR Code no veículo.<br>
- O usuário pode digitar o código caso o episódio anterior falhe ou o usuário prefira.<br>
- O usuário pode utilizar o veículo caso haja créditos suficientes para um aluguel.<br>

<b>Restrições:</b> O usuário está restrito a desbloquear um veículo e alugar.<br>

<b>Excessões:</b> Rasura no QR Code do veículo.<br>

****
**Utilização da Yellow - Lazer**

<b>Objetivo:</b> Utilizar uma bicicleta para lazer.

<b>Contexto:</b><br>
- <b>Local Físico:</b> Parque.<br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado e ter créditos na conta.<br>

<b>Atores:</b> Usuário em momento de lazer.<br>

<b>Recursos:</b> Smartphone

<b>Episódios:</b> <br>
- O usuário precisa de uma bicicleta para lazer.<br>
- O usuário utiliza o smartphone para procurar uma bicicleta.<br>
- O usuário desbloqueia e aluga ao encontrar uma bicicleta.<br>
- O usuário utiliza a bicicleta para se divertir.<br>
- O usuário bloqueia novamente a bicicleta.<br>

<b>Restrições:</b> O usuário está restrito a escolher uma bicicleta dentre as disponibilizadas.<br>

<b>Excessões:</b> Não encontrar bicicleta disponível, bicicleta disponível com defeito.<br>

****
**Utilização da Yellow - Trabalho**

<b>Objetivo:</b> Utilizar uma bicicleta para o transporte para o trabalho.

<b>Contexto:</b><br>
- <b>Local Físico:</b> Residência do usuário, parada de ônibus, estação de metrô.<br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado e ter créditos na conta.<br>

<b>Atores:</b> Usuário indo trabalhar.

<b>Recursos:</b> Smartphone

<b>Episódios:</b> <br>
- O usuário precisa de uma bicicleta para ir da parada de ônibus para o local de trabalho.<br>
- O usuário utiliza o smartphone para procurar uma bicicleta.<br>
- O usuário desbloqueia e aluga uma bicicleta após econtrá-la.<br>
- O usuário utiliza a bicicleta para se locomover até o local de trabalho.<br>
- O usuário bloqueia novamente a bicicleta.<br>

****
**Utilização da Yellow - Transporte até Faculdade**

<b>Objetivo:</b> Utilizar uma bicicleta para o transporte até a faculdade.

<b>Contexto:</b><br>
- <b>Local Físico:</b> Residência do usuário, parada de ônibus, estação de metrô.<br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado e ter créditos na conta.<br>

<b>Atores:</b> Usuário indo para a faculdade.

<b>Recursos:</b> Smartphone

<b>Episódios:</b> <br>
- O usuário precisa de uma bicicleta para ir da parada de ônibus até a faculdade.<br>
- O usuário utiliza o smartphone para procurar uma bicicleta.<br>
- O usuário desbloqueia e aluga uma bicicleta após encontrá-la.<br>
- O usuário utiliza a bicicleta para se locomover até a faculdade.<br>
- O usuário bloqueia novamente a bicicleta.<br>


****
**Utilização da Yellow - Transporte entre prédios da faculdade**

<b>Objetivo:</b> Utilizar uma bicicleta para o transporte entre prédios da faculdade.

<b>Contexto:</b><br>
- <b>Local Físico:</b> Prédio da faculdade.<br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado e ter créditos na conta.<br>

<b>Atores:</b> Usuário se locomovendo pela faculdade.

<b>Recursos:</b> Smartphone

<b>Episódios:</b> <br>
- O usuário precisa de uma bicicleta para se locomover entre os prédios da universidade.<br>
- O usuário utiliza o smartphone para procurar uma bicicleta.<br>
- O usuário desbloqueia e aluga após encontrar uma bicicleta.<br>
- O usuário se locomove para os locais necessários.<br>
- O usuário bloqueia novamente a bicicleta.<br>

### Menu lateral esquerdo

****
**Ganhe corridas grátis**

<b>Objetivo:</b> Ganhar corridas grátis.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo.<br>
- O usuário clica nos 3 tracinhos na horizontal.<br>
- O usuário seleciona "Get free rides".<br>
- O usuário compartilha seu código com amigos.<br>
- O usuário ganha corridas de acordo com a quantidade de amigos que entraram na aplicação utilizando seu código.<br>

<b>Restrições:</b> O usuário está restrito a ganhar corridas grátis compartilhando a aplicação com amigos.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>

****
**Promoções**

<b>Objetivo:</b> Aplicar promoções.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário quer aplicar código de promoção.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo.<br>
- O usuário clica nos 3 tracinhos na horizontal.<br>
- O usuário seleciona "Promotions".<br>
- O usuário clica em "Add promotion".<br>
- O usuário insere código de promoção.<br>
- O usuário usufrui de benefícios da promoção.<br>

<b>Restrições:</b> Usuário está limitado a utilizar de promoções disponivéis.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo, código de promoção antigo ou inválido.<br>

****
**Minhas viagens**

<b>Objetivo:</b> Visualizar viagens realizadas.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
-O usuário abre o aplicativo.<br>
-O usuário clica nos 3 tracinhos na horizontal.<br>
-O usuário seleciona "My trips".<br>
-O usuário visualiza as viagens<br>

<b>Restrições:</b>O usuário está restrito a visualizar as próprias viagens realizadas.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo, demora ao processar viagem recém finalizada.<br>

****
**Termos e condições**

<b>Objetivo:</b> Visualizar termos e condições.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo.<br>
- O usuário clica nos 3 tracinhos na horizontal.<br>
- O usuário seleciona "Terms & Conditions".<br>
- O usuário visualiza os termos e condições de utilização.<br>

<b>Restrições:</b> O usuário está restrito a visualizar os termos e condições de utilização.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>

****
**Deslogar (sair) da conta**

<b>Objetivo:</b> Sair da conta.

<b>Contexto:</b><br>
- <b>Local:</b> Tela inicial.<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.<br>

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- O usuário abre o aplicativo.<br>
- O usuário clica nos 3 tracinhos na horizontal.<br>
- O usuário seleciona "Logout".<br>
- O usuário tem a conta removida.<br>

<b>Restrições:</b> Usuário está restrito a sair de sua conta.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>

## 6.Conclusão
Os cenários foram úteis para visualizar na prática a utilização da aplicação, o caminho feliz da utilização. O detalhamento dos cenários permitem até mesmo que sirvam como uma espécie de guia de utilização da aplicação assim como visualizar possíveis erros que o usuário possa encontrar.

## 7. Referências
Sommerville, I. Engenharia de Software. 9a Edição. Addison Wesley. 2007.