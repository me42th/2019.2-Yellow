# Requisitos Elicitados

### Histórico de edições
| Nome|O que fez|Quando|
|-----|---------|------|
| Pedro, Dâmaso, Letícia | Criaram o documento. | 29/08/2019 |
| Gabriela, Dâmaso, Lucas | Alteraram e adicionaram alguns requisitos funcionais e não-funcionais baseados no novo brainstorming. | 23/09/2019 |
| Pedro | Adicionou mais alguns requisitos funcionais e não-funcionais baseado no brainstorming criado por parte do grupo. | 26/09/2019 |
| Lucas | Adicionou dois requisitos não-funcionais elicitados com a técnica de prototipação. | 29/09/2019 |
| Lucas | Adicionou dois requisitos funcionais e não-funcionais baseado na técnica de análise de discurso. | 29/09/2019 |

A partir do brainstorm elaborado foi possível elicitar alguns requisitos sendo eles funcionais e não funcionais.

## Requisitos Funcionais


| Nome | Descrição | Prioridade|Pré-Condições|
| -------- | -------- | -------- | ------|
| <b>RF001</b> | O sistema deve permitir o cadastro de novos usuários. |   Alta   | <b>N/A.</b> |
| <b>RF002</b> | O sistema deve permitir login na conta. |   Alta   | <b>RF001.</b> |
| <b>RF003</b> | O sistema tem que ser capaz de recarregar créditos para a utilização dos veículos. | Alta | <b>RF001.</b> |
| <b>RF004</b> | O sistema tem que mostrar a localização dos veículos disponíveis.  | Alta | <b>RF001, RF002.</b> |
| <b>RF005</b> | O usuário tem que ser capaz de desbloquear um veículo (público).  | Alta | <b>RF001, RF002, RF003, RF004.</b> |
| <b>RF006</b> | O aplicativo deveria permitir bloquear a bicicleta novamente. | Alta | <b>RF005.</b> |
| <b>RF007</b> | O sistema poderia permitir compartilhamento de crédito. | Baixo| <b>RF001.</b>|
| <b>RF008</b> | O sistema tem que informar ao usuário sobre o seu uso, e os seus gastos.  | Alta | <b>RF003.</b>|
| <b>RF009</b> | A aplicação deveria ter integração com bancos digitais de forma que facilite a inserção de crédito. | Alta| <b>RF003.</b>|
| <b>RF010</b> | O sistema poderia disponibilizar códigos e cupons promocionais. | Média | <b>RF003.</b>|
| <b>RNF011</b> | A aplicação deve disponibilizar um local para os usuários relatarem defeitos nos veículos. | Média | <b>RF001, RF002.</b>|


## Requisitos Não Funcionais

| Código | Descrição | Prioridade|
| -------- | -------- | -------- |
| <b>RNF001</b> | A aplicação deve ser prática e simples de utilizar.  |  Média    |
| <b>RNF002</b> | A aplicação deve aceitar diversos meios de pagamento.|Alta |
| <b>RNF003</b> | A aplicação deve ser econômica na utilização de dados do smartphone.| Média |
| <b>RNF004</b> | A aplicação deve ser leve evitando travamentos causados pelo desempenho do smartphone.|Média |
| <b>RNF005</b> | O custo para aluguel de um meio de transporte deve ser baixo. |Alta |
| <b>RNF006</b> | A aplicação deve abranger a maior área urbana possível. |Alta |
| <b>RNF007</b> | A aplicação deve promover descontos e promoções a públicos determinados. (estudantes, servidores públicos, usuários de determinada empresa, etc..) | Média |
| <b>RNF008</b> | Os avisos sobre os gastos devem ser feitos de forma prévia, de forma que o usuário possa parar de utilizar antes de ser cobrado uma quantia indevida. | Alta |
| <b>RNF009</b> | Os códigos promocionais devem funcionar tanto com formatos de descontos, como também em créditos para utilização imediata. | Média |
| <b>RNF010</b> | A aplicação deve ter permissão para usar a câmera do dispositivo móvel. | Alta |
| <b>RNF011</b> | O mapa deve possuir um tamanho que facilite a visualização da localização dos veículos. | Alta |
| <b>RNF012</b> | A aplicação deve se certificar que o usuário é mais de 18 anos. | Média |