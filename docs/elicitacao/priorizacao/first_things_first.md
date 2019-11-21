|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|1.0| Pedro Igor | Criou o documento. |27/09/2019| Remoto, via Google Drive|
|1.1| Pedro Igor | Alterou a ordem dos elementos da tabela. |27/09/2019| Remoto, via Google Drive|
|1.2| Gabriela Lemos | Editou a tabela e adicionou a tabela de justificativa para cada requisito avaliado. |28/09/2019| Remoto, via Google Drive|
|1.3| Dâmaso Júnio | Formatou o documento | 19/11/2019 | Remoto |

# First Things First


## Objetivo

<p align="justify">Ao utilizar a técnica de priorização de requisitos "First Things First", o objetivo a se alcançar é estabelecer uma certa ordem de prioridade em relação à implementação de certas funcionalidades, considerando fatores que impactam na disponibilização delas aos usuários da aplicação.</p>

## Avaliação do que deve entrar na análise
| Funcionalidade | Estado | Justificativa |
| -------------- | ------ | ------------- |
| Cadastro de usuários. | Permanece | Não possui dependências |
| Login em conta. | Permanece | Não possui dependências |
| Recarregar créditos | Permanece | Possui dependências porém é dependência de outras tarefas. |
| Mostrar localização de veículos | Permanece | Possui dependências porém é dependência de outras tarefas. |
| Desbloquear um veículo | Permanece | Possui dependências porém é dependência de outras tarefas. |
| Bloquear veículo novamente | Não permanece | Depende de "Desbloquear um veículo". |
| Permitir compartilhamento de crédito | Não entra | Depende de "Cadastro de usuários". |
| Informar gastos | Não entra | Depende de "Recarregar créditos". |
| Integração com bancos digitais | Não entra | Depende de "Recarregar créditos". |
| Disponibilizar códigos e cupons promocionais. | Não entra | Depende de "Recarregar créditos". |

<br>

## Priorização First Things First
| Funcionalidade | Benefício relativo | Penalidade | Valor Total | Valor % | Custo Relativo | Custo % | Risco relativo | Risco % | Prioridade |
| -------------- | ------------------ | ---------- | ----------- | ------- | -------------- | ------- | -------------- | ------- | ---------- |
| Mostrar localização de veículos |8|8|24|23,762376238|7|19,444444444|8|24,242424242|54,3924913|
| Recarregar créditos |6|9|21|20,792079208|7|19,444444444|7|21,212121212|51,1407663|
| Desbloquear um veículo |8|8|24|23,762376238|8|22,222222222|8|24,242424242|51,1407663|
| Cadastro de novos usuários |4|8|16|15,841584158|7|19,444444444|5|15,151515152|45,7902725|
| Login em uma conta |4|8|16|15,841584158|7|19,444444444|5|15,151515152|45,7902725|
| Total |30|41|101|100|36|100|33|100|-|

**Pesos adotados:** </br>
Benefício relativo: 2 </br>
Penalidade: 1 </br>
Custo Relativo: 1 </br>
Risco Relativo: 1 </br>
