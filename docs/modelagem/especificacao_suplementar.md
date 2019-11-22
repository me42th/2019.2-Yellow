|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|1.0| Lucas Gomes | Criou o documento. |30/09/2019| Remoto, via Google Drive|
|1.1| Lucas Gomes | Atualizou o documento. |18/11/2019| Remoto, via Google Drive|
|1.2| Lucas Gomes | Atualizou a rastreabilidade. |22/11/2019| Remoto, via Google Drive|

# Especificação Suplementar

**Finalidade**

Esse documento tem por finalidade apresentar os requisitos não-funcionais relacionados a aplicação Yellow, tornando visível requisitos que não estão presentes no restante da documentação. 

**Escopo**

A Yellow é uma aplicação de dispositivo móvel que visa facilitar o transporte de pessoas no meio urbano por meio do aluguel de bicicletas e patinetes por um período de tempo.


**Definições, Acrônimos e Abreviações**

| Abreviação | Definição |
|:----:|:------:|
| FURPS+ | Acrônimo para Funcionalidade, Usabilidade, Reliabilidade (Confiabilidade), Performance (Desempenho), Suportabilidade e "plus" para demais atributos. |
| iOS | Sistema operacional móvel desenvolvimento para iPhone pela Apple. |
| Android | Sistema operacional móvel desenvolvido pela Google. |



## Visão geral
Este documento apresenta uma introdução a aplicação Yellow. No decorrer desta especificação são expostas requisitos que foram descritas de acordo com o FURPS+.

## Funcionalidade

As funcionalidades referentes ao aplicativo Yellow, funcionais e não-funcionais, foram expostas nos [Casos de Uso](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/modelagem/casos_de_uso_v2.md) e no [Product Backlog](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/modelagem/agil_v2.md) de acordo com as técnicas de elicitação.

## Usabilidade

- ### **Facilidade de uso**
A aplicação deve ser intuitiva e de fácil compreensão e memorização ao ponto de que os usuários não precisem de treinamento para fazer uso do sistema.

Rastreabilidade: [Brainstorm](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/brainstorm_v1.md)

- ### **Idioma**
O idioma da aplicação deve estar de acordo com o que a língua falada no país ou com o idioma pré-configurado no dispositivo móvel.

Rastreabilidade: [Storytelling #7](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/storytelling_v1.md/#storytelling-7)

## Confiabilidade

- ### **Segurança do armazenamento de dados**
Como a aplicação trabalha com informações pessoais, tais como quantidade de créditos na carteira, número do cartão de crédio e entre outros, logo esses dados são restritos apenas ao próprio usuário dono dessas informações.

Rastreabilidade: [Brainstorm](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/brainstorm_v1.md)

- ### **Garantia no pagamento**
Por se tratar de uma aplicação que envolve movimentação de dinheiro, então é necessário a garantia de que o usuário seja cobrado apenas o valor especificado por ele.

Rastreabilidade: [Brainstorm](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/brainstorm_v1.md), [Observação](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/observacao.md) e [Storytelling #4](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/storytelling_v1.md/#storytelling-4)

- ### **Garantia na transferência de crédito**
Ao solicitar a transferência de crédito para outra pessoa, é garantido de que esse crédito irá para a pessoa escolhida pelo usuário.

Rastreabilidade: [Análise de Protocolo](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/analise_protocolo.md), [Instropecção](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/introspeccao.md) e [Observação](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/observacao.md)

## Desempenho

- ### **Tempo mínimo para desbloqueio dos veículos**
O desbloqueio dos veículos devem ocorrer de forma rápida, afim de evitar estresses por parte do usuário.

Rastreabilidade: [Entrevista](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/entrevista.md)

- ### **Tempo mínimo para adicionar crédito**
É necessário que o usuário receba os créditos de forma imediata logo após concluir o processo de adição de créditos.

Rastreabilidade: [Brainstorm](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/brainstorm_v1.md), [Entrevista](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/entrevista.md), [Observação](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/observacao.md) e [Storytelling #4](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/storytelling_v1.md/#storytelling-4)

- ### **Gargalo ao movimentar o mapa**
A aplicação deve mostrar o mínimo de gargalo possível quando o usuário movimentar o mapa em busca de algum veículo.

Rastreabilidade: Não possui

- ### **Consumo de memória**
É necessário que a aplicação tenha um consumo de memória razóavel para evitar gargalos em dispositivos cujo o sistema operacional não seja atual.

Rastreabilidade: Não possui

## Suportabilidade

- ### **Compatibilidade**
A aplicação da Yellow está disponível apenas para dispositivos móveis, mais especificamente nos sistemas operacionais iOS e Android.

Rastreabilidade: Não possui

- ### **Escalabilidade**
A aplicação deve suportar uma grande quantidade de acesso simultâneo sem prejudicar o uso pela parte do usuário.

Rastreabilidade: Não possui

## Restrições de Design

O design da aplicação deverá estar de acordo com as diretrizes de desenvolvimento do sistema operacional que está sendo desenvolvido. E, a aplicação deve ter detalhes amarelos por conta do nome do sistema, Yellow.

Rastreabilidade: [Análise de Protocolo](https://github.com/Requisitos-de-Software/2019.2-Yellow/blob/master/docs/elicitacao/requisitos/analise_protocolo.md)


### Referências
- **Termos e condições gerais de uso das plataformas Grow**. Disponível em: https://www.yellow.app/termos-de-uso
- **Site da Yellow** Disponível em: https://www.yellow.app/
- **Projeto de Software Floricultura Beija-FlorEspecificação Suplementar** Disponível em: https://bit.ly/2MoiQAu
- **Especificação Suplementar – Sistema de Treinamento de Pilotos-STP**. Disponível em: https://ice.unifei.edu.br/ramos/SiteTpit/DocsSTP/Gloss%E1rioSTP.doc
