|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|1.0| Pedro Igor | Criou o documento. |30/09/2019| Remoto, via Google Drive|
|1.1| Pedro Igor | Adicionou mais detalhes aos cenários |30/09/2019| Remoto, via Google Drive|
|1.2| Pedro Igor | Adicionou mais cenários para a tela "Meu Saldo." |08/10/2019| Remoto, via Google Drive|
|1.3| Pedro Igor | Adicionou mais cenários de login/cadastro e menu lateral esquerdo. |01/11/2019| Remoto, via Google Drive|
|1.4| Dâmaso Júnio | Formatou o documento. |19/11/2019| Remoto |

# Cenários

<p align="justify">Cenários são utilizados para o desenvolvimento de possibilidades de utilização de determinado produto. Sendo assim, são definidas características de cenários reais para a imaginação de algo atualmente imaginável porém de possível execução. É definido um objetivo que comumente é a realização de uma tarefa disponível, logo em seguida são descritos características como contexto, atores participantes, recursos necessários, cenas deste cenário, restrições aos participantes das cenas assim como exceções que possam interromper o cumprimento do objetivo inicial.</p>


## Saldo
****
**Histórico de transações**

<b>Objetivo:</b> Visualizar o histórico de transações.

<b>Contexto:</b><br><br>
- <b>Local:</b> Tela "Meu Saldo".<br>
- <b>Tempo:</b> Qualquer momento.<br>
- <b>Pré-condição:</b> Estar logado.<br>

<b>Atores:</b> Usuário.

<b>Recursos:</b> Smartphone.

<b>Episódios:</b> <br>
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até as últimas opções.<br>
- Usuário seleciona "Histórico de transações".<br>
- Usuário visualiza transações caso haja.<br>

<b>Restrições:</b> Usuário está restrito a visualizar suas transações se houver.<br>

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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até as últimas opções.<br>
- Usuário seleciona "Solicitar reembolso".<br>
- Usuário seleciona o motivo pelo qual está solicitando um reembolso.<br>
- Usuário clica em "Retornar a minha carteira".<br>
- Suporte da Yellow pode analisar o motivo da solicitação.<br>
- O reembolso fica disponível.<br>


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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até as últimas opções.<br>
- Usuário seleciona "Acessar o centro de ajuda".<br>
- Usuário seleciona no que deseja ser ajudado.<br>


<b>Restrições:</b> Usuário está restrito a visualizar conteúdo sobre ajuda.<br>

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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até a opção "Serviços e contas".<br>
- Usuário seleciona a conta a qual deseja pagar.<br>
- Usuário preenche informações sobre a conta a ser paga. (No momento é mostrado apenas um formulário em branco.)<br>


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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até a opção "Serviços e contas".<br>
- Usuário seleciona a conta a qual deseja pagar.<br>
- Usuário preenche informações sobre a conta a ser paga. (No momento é mostrado apenas um formulário em branco.)<br>


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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até "Recargas de celular e planos" e seleciona uma operadora.<br>
- Usuário informa um número de celular para que seja realizado o serviço.<br>
- Usuário seleciona o valor da recarga e clica em "Próximo".<br>
- Usuário confirma o pagamento com o saldo na Yellow.<br>

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
- Usuário abre o aplicativo e clica em "Meu saldo" ou em "Minha carteira" no menu lateral esquerdo.<br>
- Usuário navega até "Transferir dinheiro" e clica em "Enviar ou receber com QR".<br>
- Usuário informa o valor a ser recebido ou enviado.<br>
- Usuário prossegue e é gerado um QR Code para que seja feito o envio/recepção do crédito.<br>

<b>Restrições:</b> Usuário está restrito a enviar o crédito disponível na conta.<br>

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
- Usuário abre o aplicativo e clica em "Meu saldo" ou clica em "Adicionar crédito" na tela inicial.<br>
- Usuário seleciona "Adicionar crédito".<br>
- Usuário seleciona o valor ser inserido e a forma de pagamento.<br>
- Usuário confirma a compra de crédito.<br>

<b>Restrições:</b> Usuário está restrito inserir as quantidades disponíveis.<br>

<b>Excessões:</b> Erro na conexão com a internet. Boleto vencer.<br>



## Cadastro e Login

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
- Usuário quer utilizar o aplicativo.<br>
- Usuário baixa a aplicação e abre.<br>
- Usuário dá as permissões para acesso a conta do google ou facebook.<br>
- Caso tudo esteja correto as funções do aplicativo se tornam utilizáveis.<br>

<b>Restrições:</b> Usuário está restrito a logar por meio de uma conta do Google.<br>

<b>Excessões:</b> Falha na conexão na internet, erro ao digitar senha caso necessário.<br>



## Utilização
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
- Usuário precisa de ajuda.<br>
- Usuário clica no "?" na tela inicial.<br>
- É mostrada as opções de temas de ajuda disponíveis.<br>
- Usuário seleciona um tema.<br>
- Usuário especifica a ajuda que precisa selecionando as opções posteriormente disponibilizadas..<br>

<b>Restrições:</b> Usuário está restrito a encontrar ajuda com carteira, patinete e bicicleta.<br>

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
- Usuário quer informar problema.<br>
- Usuário clica no "?" na tela inicial.<br>
- Usuário seleciona "Report Issue".<br>
- Usuário especifica o tipo de problema a ser reportado.<br>
- Usuário segue o passo a passo solicitado pelo app.<br>

<b>Restrições:</b> Usuário está restrito a reportar problema mecânicos, de veículos não encontrados, veículos atrapalhando a circulação e fazer uma queixa.<br>

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
- Usuário quer entrar em contato com a equipe de suporte.<br>
- Usuário clica no "?" na tela inicial.<br>
- Usuário seleciona "Contact Us".<br>
- Usuário especifica o tipo de contato assim como o tema.<br>
- Usuário escreve uma mensagem entre 15 e 200 caracteres e clica em "Send".<br>

<b>Restrições:</b> Usuário está restrito a contatar suporte sobre os motivos listados na aplicação.<br>

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
- Usuário quer encontrar um patinete.<br>
- Usuário clica em "patinete" na tela inicial.<br>
- É mostrado num mapa patinetes disponíveis e sua localização.<br>
- O usuário se dirige ao local do patinete.<br>

<b>Restrições:</b> Usuário está restrito a encontrar um patinete no mapa.<br>

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
- Usuário quer encontrar uma bicicleta.<br>
- Usuário clica em "bike" na tela inicial.<br>
- É mostrado num mapa bicicletas disponíveis e sua localização.<br>
- O usuário se dirige ao local da bicicleta.<br>

<b>Restrições:</b> Usuário está restrito a encontrar uma bicicleta no mapa.<br>

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
- Usuário encontra um veículo.<br>
- Usuário clica em "Scan" na tela inicial.<br>
- Usuário liga o flash casso necessário e tenta capturar o QR Code no veículo.<br>
- Caso o episódio anterior falhe ou o usuário prefira é possível digitar o código.<br>
- O veículo é liberada caso haja créditos suficientes para um aluguel.<br>

<b>Restrições:</b> Usuário está restrito a desbloquear um veículo e alugar.<br>

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
- Usuário precisa de uma bicicleta para lazer.<br>
- Usuário utiliza o smartphone para procurar uma bicicleta.<br>
- Ao encontrar uma bicicleta desbloqueia e aluga.<br>
- Utiliza a bicicleta para se divertir.<br>
- Bloqueia novamente a bicicleta.<br>

<b>Restrições:</b> Usuário está restrito a escolher uma bicicleta dentre as disponibilizadas.<br>

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
- Usuário precisa de uma bicicleta para ir da parada de ônibus para o local de trabalho.<br>
- Usuário utiliza o smartphone para procurar uma bicicleta.<br>
- Ao encontrar uma bicicleta desbloqueia e aluga.<br>
- Utiliza a bicicleta para se locomover até o local de trabalho.<br>
- Bloqueia novamente a bicicleta.<br>

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
- Usuário precisa de uma bicicleta para ir da parada de ônibus até a faculdade.<br>
- Usuário utiliza o smartphone para procurar uma bicicleta.<br>
- Ao encontrar uma bicicleta desbloqueia e aluga.<br>
- Utiliza a bicicleta para se locomover até a faculdade.<br>
- Após utilização bloqueia novamente.<br>


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
- Usuário precisa de uma bicicleta para se locomover entre os prédios da universidade.<br>
- Usuário utiliza o smartphone para procurar uma bicicleta.<br>
- Ao encontrar uma bicicleta desbloqueia e aluga.<br>
- Se locomove para os locais necessários.<br>
- Bloqueia novamente a bicicleta.<br>

## Menu lateral esquerdo

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
- Usuário abre o aplicativo.<br>
- Usuário clica nos 3 tracinhos na horizontal.<br>
- Usuário seleciona "Get free rides".<br>
- Usuário compartilha seu código com amigos.<br>
- Usuário ganha corridas de acordo com a quantidade de amigos que entraram na aplicação utilizando seu código.<br>

<b>Restrições:</b> Usuário está restrito a ganhar corridas grátis compartilhando a aplicação com amigos.<br>

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
- Usuário abre o aplicativo.<br>
- Usuário clica nos 3 tracinhos na horizontal.<br>
- Usuário seleciona "Promotions".<br>
- Usuário clica em "Add promotion".<br>
- Usuário insere código de promoção.<br>
- Usuário usufrui de benefícios da promoção.<br>

<b>Restrições:</b> Usuário.<br>

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
- Usuário abre o aplicativo.<br>
- Usuário clica nos 3 tracinhos na horizontal.<br>
- Usuário seleciona "My trips".<br>
- Usuário visualiza as viagens<br>

<b>Restrições:</b> Usuário está restrito a visualizar as próprias viagens realizadas.<br>

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
- Usuário abre o aplicativo.<br>
- Usuário clica nos 3 tracinhos na horizontal.<br>
- Usuário seleciona "Terms & Conditions".<br>
- Usuário visualiza os termos e condições de utilização.<br>

<b>Restrições:</b> Usuário está restrito a visualizar os termos e condições de utilização.<br>

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
- Usuário abre o aplicativo.<br>
- Usuário clica nos 3 tracinhos na horizontal.<br>
- Usuário seleciona "Logout".<br>
- A conta é removida.<br>

<b>Restrições:</b> Usuário está restrito a sair de sua conta.<br>

<b>Excessões:</b> Erro de conexão com a internet, erro ao mostrar contéudo.<br>
