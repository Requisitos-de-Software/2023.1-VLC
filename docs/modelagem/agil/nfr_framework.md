<div class="body">

# NFR Framework

## <a>Introdução</a>

<div align="justify">

O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão. Tais características incluem Requisitos Não-funcionais, Requisitos funcionais, prioridades e carga de trabalho. Esses fatores determinam a escolha de alternativas de desenvolvimento para um determinado sistema. [1]

O NFR Framework utiliza requisitos não funcionais (*Non Functional Requirements*) para conduzir o processo geral de design, colocando os requisitos não funcionais em primeiro lugar. O framework tem como principal objetivo oferecer uma estrutura de representação, para o armazenamento do desenho e do racional do processo de desenvolvimento de requisitos através de grafos chamados softgoal interdependency graphs(SIGs).

Softgoal é uma característica abstrata, a qual se deseja considerar na análise, visando saber se a mesma será cumprida ou não cumprida, ou seja, escolhida ou não escolhida para ser implementada.

Os softgoals podem ser separados em três tipos, são eles:

* **Softgoals NFR:** representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto. [1]

* **Softgoals de Operacionalização:** representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema alvo para atender às necessidades indicadas pelos softgoals NFR e de operacionalização. [1]

* **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão. [1]

Cada um dos softgoals apresentados podem ser decompostos e refinados, seguindo os tipos de decomposição abaixo:

* **Decomposição de Softgoal NFR:** refina/divide um softgoal NFR em outros. Ajuda a dividir problemas em partes menores, sendo útil para lidar com ambiguidades e prioridades. [2]

* **Decomposição de Operacionalização:** subdivide um softgoal de operacionalização em outros mais específicos, sendo útil para definir soluções gerais e transformá-las em soluções mais específicas. [2]

* **Decomposição de Afirmação (*claims*):** refina um softgoal de afirmação em outros. É útil para apoiar ou não justificativas de projeto. [2]
* **Priorização:** refina um softgoal em outro, com o mesmo tipo e tópicos, junto a uma prioridade associada. [2]

## 2. Metodologia

Neste documento o NFR framework é utilizado para representar os Requisitos Não-Funcionais presentes no projeto. Com esse objetivo criamos alguns diagramas que buscam atingir funcionalidades específicas do VLC, a partir da análise das possíveis situações, levando em consideração as aplicações e tecnologias que já existem no aplicativo do VLC. Na produção, utilizamos o artefato de [Especificação Suplementar](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/especificacao_suplementar) como auxílio para a elaboração, além de utilizar os artefatos de elicitação de requisitos, [Análise de Documento](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos?id=tabela-de-requisitos), [storyTelling](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) e [Questionário](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario?id=requisitos-elicitados). 

Analisados os requistos, conclui-se que, no geral, os requisitos do projeto buscam englobar as seguintes softgoals:

- Confiabilidade;
- Desempenho;
- Suportabilidade;
- Usabilidade.

A partir da análise e das definições das softgoals, foi definido um padrão(<i>imagem 1</i>) de representação, que serviu de guia para a elaboração e confecção dos diagramas.

## 3. Legenda
Anteriormente já mencionada, a legenda é o padrão de representação, que auxilia no entedimento e confecção dos diagramas realizados.

<figcaption align='center'>
 <h4> <b>imagem 1 – Legenda</b><br>
	 <img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_legenda.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023 </h4>
</figcaption>

## 4. NFRs

A seguir irá ser apresentado os SIG(Softgoal Interdependency Graph) elaborados sobre Confiabilidade(imagem 2 e 3), Desempenho(imagem 4 e 5), Suportabilidade(imagem 6 e 7) e Usabilidade(imagem 8 e 9). Foi utilizado a ferramenta <a href="https://app.diagrams.net">draw.io</a> para a criação dos SIGs.

### <a>Confiabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 4 – Diagrama SIG 02 - Confiabilidade</b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_confiabilidade.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption>

### <a>Análise Confiabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 5 – Análise diagrama SIG 02 - Confiabilidade </b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_confiabilidade_check.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption> <br><br>

### <a>Desempenho</a>

<figcaption align='center'>
 <h4> <b>imagem 4 – Diagrama SIG 02 - Desempenho</b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_desempenho.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption>

### <a>Análise Desempenho</a>

<figcaption align='center'>
 <h4> <b>imagem 5 – Análise diagrama SIG 02 - Desempenho </b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_desempenho_check.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption> <br><br>

### <a>Suportabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 6 – Diagrama SIG 03 - Suportabilidade</b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_suportabilidade.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption>

### <a>Análise Suportabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 7 – Análise diagrama SIG 03 - Suportabilidade </b><br> 
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_suportabilidade_check.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption> <br><br>

### <a>Usabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 8 – Diagrama SIG 04 - Usabilidade</b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_usabilidade.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption>

### <a>Análise Usabilidade</a>

<figcaption align='center'>
 <h4> <b>imagem 9 – Análise diagrama SIG 04 - Usabilidade </b><br>
	<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/nfr_framework/NFR_usabilidade_check.png" width="100%">
  Fonte: RIBEIRO, Bruno; PENHA, Igor. 2023</h4>
</figcaption> <br><br>

## Conclusão
Em vista do documento realizado, é possível analisar a partir dos diagramas realizado que o aplicativo do VLC conseguiu atender por totalidade a suportabilidade, os diagramas de usabilidade e desempenho o VLC atendeu ambos quase por completo deixando apenas e no diagrama de confiabilidade identificamos os softgoals que foram mais insatisfeitos em que o aplicativo do VLC ainda pode melhorar no quesito de suporte ao usuário, principalmente, usuário com sistema IOS e a falta de de notificações ao realizar novos logins.

</div>

### Referências
[1] Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em 26 de Dezembro de 2022

[2] SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 25 de Dezembro de 2022

### Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| 21/05/2023 | `1.0`  | Criação do documento de NFR | [Igor Penha](https://github.com/igorpenhaa)  | 22/05/2023 | [Lucas Gobbi](https://github.com/lucasbergholz) |
| 22/05/2023 | `1.1`  | add diagramas | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa) | 22/05/2023 |[Lucas Gobbi](https://github.com/LucasBergholz) |
| 02/07/2023 | `2.0`  | Correções do artefato | [Igor Penha](https://github.com/igorpenhaa) e [Bruno Ribeiro](https://github.com/BrunoRiibeiro) | 03/07/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |

</div>
