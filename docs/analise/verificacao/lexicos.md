|Versão| Autor | O que fez |  Quando | Onde |
|------|------| --------  |-------- | -----|
|1.0| Letícia Karla | Criou o documento. |04/11/2019| Remoto, via Google Drive|

# Léxicos (Verificação) 

## 1. Sumário

1. Sumário
2. Introdução
3. Metodologia
4. Checklist
5. Resultados
6. Conclusão
7. Referências

## 2. Introdução

Verificação é o processo para determinar se um artefato preenche os requisitos estabelecidos, se ele está internamente completo, consistente e correto, para possibilitar a passagem para fase seguinte.

## 3. Metodologia

Para realizar a inspeção em cima do documento foi elaborado um checklist com as características necessárias para um léxico correto. Uma tabela, também foi levantada, com a definição de possíveis erros encontrados.


![UC_RequisitosYellow](/img/analise/verificacao/TblErros.png)


## 4. Checklist

* Elicita o significado do símbolo/objeto (sign), não funcionalidade?
* As noções (denotação) são compreensíveis para pessoas fora do domínio de informações?
* Os impactos (conotação) são compreensíveis para pessoas fora do domínio de informações? 
* Os léxicos propostos estão dentro do universo de informação?
* Os léxicos possuem ligações entre si (HyperLex)?
* Segue o padrão de modelo para os léxicos elicitados?
* Usa a estrutura de dicionário (verbo, objeto, estado)?

Caso verbo (noção):

* Possui quem realiza?
* Possui quando acontece?
* Possui os procedimentos envolvidos?

Caso verbo (Impacto)

* Possui reflexos da ação?
* Possui o novo estado?

Caso Objeto (Noção)

* Definiu objeto?
* Mostra os objetos que se relacionam?

Caso Objeto (Impacto)

* Define ações que podem ser aplicadas ao objeto?

Caso Estado (Noção)

* Define o estado?
* Mostra o que levou ao estado?

Caso Estado (Impacto)

* Mostra outros estado e ações que decorrem a partir do estado descrito?

## 5. Resultados

Após a aplicação do checklist foi elaborada uma tabela com os léxicos levantados e possíveis erros identificados em negrito e itálico.


| Item | Sim | Não | Tipo de Erro | Qtde de Erros (%) | Léxicos a serem arrumados|
| - | - | - | - | - | - |
| **Elicita o significado do símbolo/objeto (sign), não funcionalidade?**  | 13 | 0 |-|-|-|
|**As noções (denotação) são compreensíveis para pessoas fora do domínio de informações?**|13|0|-|-|-|
|**Os impactos (conotação) são compreensíveis para pessoas fora do domínio de informações?**|13|0|-|-|-|
|**Os léxicos propostos estão dentro do universo de informação?**|13|0|-|-|-|
|***Os léxicos possuem ligações entre si (HyperLex)?***|***0***|***13***|***1***|***100%***|***-***|
|**Segue o padrão de modelo para os léxicos elicitados?**|13|0|-|-|-|
|**Usa a estrutura de dicionário (verbo, objeto, estado)?**|13|0|-|-|-|
|**(Verbo - Noção) Possui quem realiza?**|5|0|-|-|-|
|***(Verbo - Noção) Possui quando acontece?***|***4***|***1***|***1***|***20%***|***Transferir para amigos***|
|***(Verbo - Noção) Possui os procedimentos envolvidos?***|***4***|***1***|***1***|***20%***|***Pedir Reembolso***|
|**(Verbo - Impacto) Possui reflexos da ação?**|5|0|-|-|-|
|***(Verbo - Impacto) Possui o novo estado?***|***4***|***1***|***1***|***20%***|***Recarga de Celular***|
|**(Objeto - Noção) Definiu objeto?**|7|0|-|-|-|
|***(Objeto - Noção) Mostra os objetos que se relacionam?***|***5***|***2***|***1***|***71,40%***|***Patinete, Bike, Histórico de Corrida, Central de Ajuda e Termos de Uso***|
|***(Objeto - Impacto) Define ações que podem ser aplicadas ao objeto?***|***5***|***2***|***1***|***28,60%***|***Patinete e Bike***|
|**(Estado - Noção) Define o estado?**|1|0|-|-|-|
|**(Estado - Noção) Mostra o que levou ao estado?**|1|0|-|-|-|
|**(Estado - Impacto) Mostra outros estado e ações que decorrem a partir do estado descrito?**|1|0|-|-|-|


## 6. Conclusão

Utilizando o checklist foi possível gerar um gráfico com com indicadores, sobre onde está os principais erros dos léxicos.

![UC_RequisitosYellow](/img/analise/verificacao/GrafIndicador.png)


## 7. Referências

1. SAYÃO , Miriam; VON STAA , Arndt; SAMPAIO DO PRADO LEITE , Julio Cesar. Qualidade em Requisitos. 2003. 31 f. Monografia (Bacharel em Ciências da Computação) - Faculdade de Ciências da Computação, Rio de Janeiro, 2003.
2. LEITE, J. C. S. P.; FRANCO, ANA. A strategy for conceptual model acquisition. Proceedings of the International Symposium on Requirements Engineering. San Diego, 1993.   