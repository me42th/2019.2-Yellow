# MÓDULO 1
## SLIDES
 * Engenharia de Software
	- conceitos relevantes
	- ciclo de vida
 * Engenharia de Requisitos
	- conceitos básicos
	- requisitos funcionais e não funcionais
	- atividades elementares

* Processos de produção de produtos de software ainda bastante insatisfátorios. (orientado, meta)
* A engenharia de Software se preocupa em impedir falhas causadas por esses sistemas ainda insatisfatórios, evoluindo cada vez mais tais processos.
* O Software funciona como um produto. E para esse produto funcionar devidamente, é necessário realizar uma correta identificação dos aspectos inerente ao software e dos aspectos inerentes ao universo onde ele irá atuar.

* A ideia é atinger um nível de alta qualidade exigido visando o menor custo possível.

* **Teoria geral dos sistemas:** Teoria desenvolvida em meados do século vinte visando tratar ciências distintas de maneira interdisciplinar. Ludwig von Bertallanffy propôs um arcabouço teórico, no qual diferentes conhecimentos poderiam ser integrados (relevante para produtos de software complexos).
* Características básicas de um sistema: **propósito** (objetivo), **globalismo **(~~qualquer mudança feita em qualquer parte do sistema, por menor que ela seja, altera o sistema como um todo~~), **entropia** (um sistema tende a degenerar com o passar do tempo),** homeostasia** (todo sistema busca se adequar ao seu meio, tendendo a um equilíbrio).

* **Teoria geral dos sistemas**:
	* Objetos e relações: objetos são unidades base. Descrever suas relações é essencial.
	* Limites: fronteira de um sistema.
	* Pontos de vista: desenvolvimento baseado em diferentes perspectivas.
	* Nível de abordagem: nível de detalhamento do sistema.
	* Hierarquia: divisão de um sistema maior e mais complexo em partes menores. Conhecido como modularização.
	* Meio ambiente: um sistema sempre é um subsistema de um sistema maior ainda. Ele comunica-se com macrosistemas através de entradas e saídas.

* O software sempre é feito para atuar em um contexto que visa atender um público alvo.
*  18
* **Ciclo de vida:** desenvolvimento e manuntenção como macrofases.
* **Desenvolvimento:** 
	* Cascata: requisitos, modelagem, análise, projeto (arquitetura e solução computacional), implementação (código), teste (validação e verificação de que tudo está de acordo com o planejado).
	* Prototipagem: elicitação de requisitos, desenho rápido, construção do protótipo, avaliação do protótipo junto ao cliente, refinamento do protótipo, programação.
	* Espiral: requisitos, projeto, implementação, teste.
	* Iterativo-incremental: Scrum

* Manuntenção: custos altos e demanda tempo.
	* corretiva: correção de erros oriundos do processo de construção.
	* evolutiva: novas funcionalidades exigidas pelo ambiente externo.
	* preventiva: alterações visando a facilidade de mudanças futuras.
	* adaptativa: alterações necessárias em função das mudanças das plataformas de suporte, ou de hardware ou de software.
	* de suporte: visando, principalmente, monitoramento do desempenho do software.
	
* O ideal pode ser inviável.

---------------------------------------------------------------------------------------
* Engenharia de Requisitos: disciplina que procura sistematizar o processo de definição de requisitos, necessária uma vez que a complexidade dos sistemas exige mais atenção ao correto entendimento do problema, antes de pensar na solução. Assim, faz parte da fase inicial dos projetos. ~~Difere de um processo ad hoc~~
* Quanto mais nos distanciamos da definição do produto e nos aproximamos de um produto concreto, mais custoso será corrigir problemas bem como adicionar novas funcionalidades.
// 8/56 
## SWEBOK

## ATIVIDADES
### Atividade 01
**1) O que é o SWEBOK? Para que ele foi escrito? Por quem ele foi escrito?**
**R:** **(pág. xxxi do livro)** SWEBOK, um acrônimo para Software Engineering Body of
Knowledge, escrito pelo Conselho de Atividades Profissionais da IEEE Computer Society,
consiste em um guia que reúne diversas informações da área de Software. A obra foi criada
para alcançar os seguintes objetivos principais, que seguem abaixo:

• Promover uma visão consistente da engenharia de software no mundo todo;

• Especificar o escopo e esclarecer o local da engenharia de software em relação a
outras disciplinas, como ciência da computação, gerenciamento de projetos,
engenharia da computação e matemática.

• Caracterizar o conteúdo da disciplina de engenharia de software

• Para fornecer um ambiente de acesso ao corpo de conhecimento de engenharia de
software

• Fornecer uma base para o desenvolvimento curricular e para o material de certificação
e licenciamento individual

**2) O que é IEEE? Qual a missão e visão do IEEE?**
**R:**  IEEE (Instituto de Engenheiros Eletricistas e Eletrônicos) consiste em uma organização
profissional sem fins lucrativos dos Estados Unidos. O grupo dedica-se em desenvolver mais e
mais a tecnologia em benefício da humanidade. A missão principal deles é promover a
inovação tecnológica e a excelência em serviço desta para o ser humano, e carregam o
propósito de ser essencial para a comunidade técnica global, sendo reconhecido
universalmente com suas contribuições tecnológicas.

**3) O que é IEEE Computer Society?**
**R:**  IEE Computer Society representa um subgrupo da organização anteriormente citada, a IEE. Essa, por sua vez, é destinada especificadamente a questões ligadas aos computadores.

**4) A respeito de que se trata a área de conhecimento de Requisitos de Software (Software Requirements knowledge area)?**
**R:** **(pág. 1-1 do livro)** Os requisitos de software expressam as necessidades e restrições impostas a
um produto de software que contribua para a solução de algum problema do mundo real.
A área de conhecimento de Requisitos de Software está preocupada com a elicitação, análise,
especificação e validação de requisitos de software bem como a gestão de requisitos durante todo o
ciclo de vida do produto de software. É amplamente reconhecido entre os pesquisadores e profissionais
da indústria que projetos de software são criticamente vulneráveis quando as atividades relacionadas
aos requisitos são mal executadas.

**5) O que os requisitos de software devem apresentar do software?**
**R:** **(pág. 1-1 do livro) **A área de conhecimento de Requisitos de Software está preocupada com a
elicitação, análise, especificação e validação de requisitos de software bem como a gestão de requisitos
durante todo o ciclo de vida do produto de software. É amplamente reconhecido entre os
pesquisadores e profissionais da indústria que projetos de software são criticamente vulneráveis
quando as atividades relacionadas aos requisitos são mal executadas.

**6) A área de conhecimento de Requisitos de Software se relaciona com quais outras áreas de conhecimento?**
**R: (pág. 1-1 do livro) **A área se relaciona diretamente com Design de Software, Teste de
Software, Manutenção de Software, Configuração de Gerenciamento de Software,
Gerenciamento de Engenharia de Software, Processo de Engenharia de Software, Programas
Modelos e Métodos de Engenharia de Software e Qualidade de Software KAs.
