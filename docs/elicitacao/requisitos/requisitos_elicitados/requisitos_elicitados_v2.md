# Requisitos Elicitados

### Histórico de edições
| Nome|O que fez|Quando|
|-----|---------|------|
| Pedro Igor e Gabriela | Criaram esta versão com mais requisitos elicitados. | 16/10/2019 |

<br>

| Nome | Descrição | Prioridade|Pré-Condições|
| -------- | -------- | -------- | ------|
| RF001 | O sistema deve permitir o cadastro de novos usuários. | Alta | N/A. |
| RF002 | O sistema deve permitir login na conta. | Alta | RF001. | 
| RF003 | O sistema tem que ser capaz de recarregar créditos para a utilização dos veículos em uma quantidade flexível.| Alta | RF001. |
| RF004 | O sistema tem que mostrar a localização dos veículos disponíveis. | Alta | RF001, RF002. |
| RF005 | O usuário tem que ser capaz de desbloquear um veículo (público). | Alta | RF001, RF002, RF003, RF004. |
| RF006 | O aplicativo deveria permitir bloquear a bicicleta novamente. | Alta | RF005. |
| RF007 | O sistema poderia permitir compartilhamento de crédito. | Baixo | RF001. |
| RF008 | O sistema tem que informar ao usuário sobre o seu uso, gastos e crédito disponível. | Alta | RF003. |
| RF009 | A aplicação deveria ter integração com bancos digitais de forma que facilite a inserção de crédito. | Alta | RF003. |
| RF010 | O sistema poderia disponibilizar códigos e cupons promocionais na própria aplicação e recompensas para algumas tarefas. | Média | RF003. |
| RF011 | A aplicação deve disponibilizar um local para os usuários relatarem defeitos nos veículos e mal posicionamento na cidade. | Média | RF001, RF002. |
| ----- | ----------- | ------ | ----- |
| RF012 | A aplicação deve realizar a verificação de login em duas etapas de forma flexível. | | |
| RF013 | O sistema deve diferenciar no mapa bicicletas e patinetes. | | |
| RF014 | O sistema deve emitir um aviso de possíveis penalidades e sugestões para não estacionar os veículos em área fora de atuação. | | |
| RF015 | O sistema deve fornecer um histórico de corridas, com as informações deste. | | |
| RF016 | O sistema deve fornecer suporte acessível e flexível. | | |
| RF017 | O sistema deve permitir compartilhar a viagem. | | |
| RF018 | O sistema deve permitir o usuário sair da atual conta. | | |
| RF019 | O sistema deve informar o estado da bateria do veículo. | | |
| RF020 | O sistema deve mostrar os locais adequados para estacionar um veículo. | | |
| RF021 | O sistema deve permitir escolher um dentre vários idiomas. | | |


## Requisitos não funcionais

| Código | Descrição | Prioridade|
| -------- | -------- | -------- |
| RNF001 | A aplicação deve ser prática e simples de utilizar, além de direcionar o usuário em como utilizar. | | 
| RNF002 | A aplicação deve aceitar diversos meios de pagamento. | |
| RNF003 | A aplicação deve ser econômica na utilização de dados do smartphone. | |
| RNF004 | A aplicação deve ser leve evitando travamentos causados pelo desempenho do smartphone. | |
| RNF005 | O custo para aluguel de um meio de transporte deve ser baixo. | |
| RNF006 | A aplicação deve abranger a maior área urbana possível. | |
| RNF007 | A aplicação deve promover descontos e promoções a públicos determinados. (estudantes, servidores públicos, usuários de determinada empresa, etc..) | |
| RNF008 | Os avisos sobre os gastos devem ser feitos de forma prévia, de forma que o usuário possa parar de utilizar antes de ser cobrado uma quantia indevida. | |
| RNF009 | Os códigos promocionais devem funcionar tanto com formatos de descontos, como também em créditos para utilização imediata. | |
| RNF010 | A aplicação deve ter permissão para usar a câmera do dispositivo móvel.| |
| RNF011 | O mapa deve possuir um tamanho que facilite a visualização da localização dos veículos.| |
| RNF012 | A aplicação deve apresentar as restrições e termos de uso para o usuário (por ex., de idade) antes mesmo de seu uso. | |
| ----- | ------------- | ------------- |
| RNF013 | A aplicação deve ser flexível quanto às formas de fazer login. (ex: google, facebook). | |
| RNF014 | A aplicação deve ser segura quanto aos dados e saldo do cliente. | |
| RNF015 | A aplicação deve permitir que o usuário solicite um reembolso. | |