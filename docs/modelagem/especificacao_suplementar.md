| Especificação Suplementar | Versão: 1.0| 
| -------- | -------- |
| Participantes: Lucas Gomes e Julio Litwin | Data: 30/09/2019|

Introdução
===
### Finalidade

Esse documento tem por finalidade apresentar os requisitos não-funcionais relacionados a aplicação Yellow, tornando visível requisitos que não estão presentes no restante da documentação. 

### Escopo
A Yellow é uma aplicação de dispositivo móvel que visa facilitar o transporte de pessoas no meio urbano por meio do aluguel de bicicletas e patinetes por um período de tempo.


### Definições, Acrônimos e Abreviações
| Abreviação | Definição | 
|:----:|:------:|
| FURPS+ | Acrônimo para Funcionalidade, Usabilidade, Reliabilidade (Confiabilidade), Performance (Desempenho), Suportabilidade e "plus" para demais atributos. | 
| iOS | Sistema operacional móvel desenvolvimento para iPhone pela Apple. |
| Android | Sistema operacional móvel desenvolvido pela Google. |

### Referências
- **Termos e condições gerais de uso das plataformas Grow**. Disponível em: https://www.yellow.app/termos-de-uso
- **Site da Yellow** Disponível em: https://www.yellow.app/
- **Projeto de Software Floricultura Beija-FlorEspecificação Suplementar** Disponível em: https://bit.ly/2MoiQAu
- **Especificação Suplementar – Sistema de Treinamento de Pilotos-STP**. Disponível em: https://ice.unifei.edu.br/ramos/SiteTpit/DocsSTP/Gloss%E1rioSTP.doc


### Visão geral
Este documento apresenta uma introdução a aplicação Yellow. No decorrer desta especificação são expostas requisitos que foram descritas de acordo com o FURPS+.

Funcionalidade
===
As funcionalidades referentes ao aplicativo Yellow, funcionais e não-funcionais, foram expostas nos Casos de Uso e nos [Requisitos elicitados](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/requisitos_elicitados.md) de acordo com as técnicas de elicitação.

Usabilidade
===
- ### **Facilidade de uso**
A aplicação deve ser intuitiva e de fácil compreensão ao ponto de que os usuários não precisem de treinamento para fazer uso do sistema.

- ### **Idioma**
O idioma da aplicação deve estar de acordo com o que a língua falada no país ou com o idioma pré-configurado no dispositivo móvel.

Confiabilidade
===
- ### **Segurança do armazenamento de dados**
Como a aplicação trabalha com informações pessoais, tais como quantidade de créditos na carteira, número do cartão de crédio e entre outros, logo esses dados são restritos apenas ao próprio usuário dono dessas informações.

- ### **Garantia no pagamento**
Por se tratar de uma aplicação que envolve movimentação de dinheiro, então é necessário a garantia de que o usuário seja cobrado apenas o valor especificado por ele.

- ### **Garantia na transferência de crédito**
Ao solicitar a transferência de crédito para outra pessoa, é garantido de que esse crédito irá para a pessoa escolhida pelo usuário.

Desempenho
===
- ### **Tempo mínimo para desbloqueio dos veículos**
O desbloqueio dos veículos devem ocorrer de forma rápida, afim de evitar estresses por parte do usuário.

- ### **Tempo mínimo para adicionar crédito**
É necessário que o usuário receba os créditos de forma imediata logo após concluir o processo de adição de créditos.

- ### **Gargalo ao movimentar o mapa**
A aplicação deve mostrar o mínimo de gargalo possível quando o usuário movimentar o mapa em busca de algum veículo.

Suportabilidade
===
A aplicação da Yellow está disponível apenas para dispositivos móveis, mais especificamente nos sistemas operacionais iOS e Android.

Restrições de Design
===
O design da aplicação deverá estar de acordo com as diretrizes de desenvolvimento do sistema operacional que está sendo desenvolvido. E, a aplicação deve ter detalhes amarelos por conta do nome do sistema, Yellow.
