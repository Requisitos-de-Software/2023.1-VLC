# Casos de Uso

## Introdução

<div style="text-align:justify">
O diagrama de casos, também chamado de diagrama comportamental, na notação da UML, tem como proposta documentar a maneira como o sistema deve se comportar do ponto de vista do usuário externo, dessa forma descrevendo um conjunto de ações do sistema, ou conjunto deles[1].
 
Dentro do diagrama de casos de uso, cada caso de uso deve provê um resultado observável para o usuário que o manuseia [1]. Certos casos que necessitam de uma maior especificação, é sugerido utilizar uma abordagem mais apelativa e voltada para a linguagem natural, tal abordagem já consolidada pela comunidade desenvolvedora é chamada de especificação de casos de uso. 

</div>

## Metodologia 
<div style="text-align:justify">
Para criação do artefato, foi utilizada uma abordagem clássica, ou seja, realizando a elaboração de um diagrama de casos de uso UML. Foi utilizada a ferramenta [LucidChart](https://www.lucidchart.com/pages/pt), que é um software voltada para diagramação no geral.
</div>

## Componentes e símbolos
<div style="text-align:justify">

Um diagrama de casos de uso possui os seguintes elementos em sua composição. Onde será explicado cada um deles para proporcionar uma maior compreensão do diagrama. 

</div>

### Atores
<div style="text-align:justify">

<p align="justify">Representam os usuários e sistemas, ou um tipo dele, normalmente são representados por bonecos (Figura 1).</p>

<p align="justify">A Figura 1 apresenta o elemento que representa os atores.</p>

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/ator-uml.png" width="100%">

<div align="center">
<p> <b>Figura 1</b>: Elemento atores (Fonte: autores, 2023). </p>
</div>

</div>

### Cenário
<div style="text-align:justify">

<p align="justify"> Nesse elemento, eh descrito os eventos que acontecem quando um usuário manuseia o sistema. Geralmente representado por uma caixa (Figura 2). </p>

<p align="justify"> Todos os casos de usos que sao descritos pelo sistema devem estar dentro do cenário, caso contrário serão considerados fora do escopo do sistema. </p>

<p align="justify">A Figura 2 apresenta o elemento que representa os cenarios.</p>

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/cenario.png" width="100%">

<div align="center">
<p> <b>Figura 2</b>: Elemento Cenário (Fonte: autores, 2023). </p>

</div>

</div>

### Caso de uso
<div style="text-align:justify">

<p align="justify">Caso de uso é uma atuação ou funcionalidade realizada pelo usuário, ator.Geralmente são definidos por um objeto na forma oval horizontal (Figura 3), onde cada representação é um uso diferente que o usuário pode ter com o sistema.Por se tratar de ações realizadas, comumente se usa o uso de verbos no infinitivo para descrevê-las. </p>

<p align="justify">A Figura 3 apresenta o elemento que representa os casos de uso.</p>

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/usecase-uml.png" width="100%">

<div align="center">
<p> <b>Figura 3</b>: Elemento casos de uso (Fonte: autores, 2023). </p>

</div>

</div>

## Comunicação (ou ação)

<p align="justify">Consiste em uma ação que o usuário irá realizar sobre o caso de uso e pode ser visualizada na Figura 4. A ação pode ser de dois tipos: </p>

<p align="justify"><b>Inclusão:</b> Quando um caso de uso precisa ter sua funcionalidade executada através de outro caso de uso. Ou seja, um caso de uso A inclui um caso de uso B, onde quando o caso de uso A é executado, o caso de uso B necessariamente será executado juntamente. </p>

<li>Notação no diagrama: <<includes>> </li>

<p align="justify"><b>Extensão:</b>O caso de uso atual irá funcionar normalmente, porém alguns casos de uso podem apresentar passos adicionais, no caso de uso estendido. Em outras palavras, se o caso de uso B é estendido pelo caso de uso A, se o primeiro for executado, o caso de uso B pode, ou não, ser executado também. </p>

<li>Notação no diagrama: <<<extends>>> </li>

<p align="justify">A Figura 4 apresenta o elemento que representa a comunicação.</p>

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/comunicacao.png" width="100%">

<div align="center">
<p> <b>Figura 4</b>: Elemento comunicação (Fonte: autores, 2023). </p>

</div>

## Casos de uso

<p align="justify">Os casos de usos mais importantes e mais utilizados encontrados no aplicativo estão representados na Figura 5. Uma melhor visualização da imagem pode ser encontrada em <a href="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/casos_uso_vlc.pdf">casos de uso vlc.</a></p>

<p align="justify">A Figura 5 apresenta o diagrama de casos de uso do aplicativo VLC.</p>

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/casos_uso_vlc.png" width="100%">

<div align="center">
<p> <b>Figura 5</b>: Elemento comunicação (Fonte: Mizael Santos, 2023). </p>
</div>

<p align="justify">A seguir, a especificação dos casos de uso identificados.</p>

### UC01. Media

| UC01 |  |
| -: | :- |
| **Atores** | <li> Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** |  |
| **Condição de entrada** |  |
| **Fluxo principal** | |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | |
| **Pós condições** | |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 1: Especificação do caso de uso: Media. (Fonte: Mizael Santos, 2023).</p>
</div>


## Bibliografia
<div text-align="justify">
[1] DevMedia. O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML. 2012. DevMedia. Disponível em: <a href=https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408>DevMedia</a>.Acessado em 13 de maio. de 2023.
[2] Ferramenta Lucidchart, disponível no <a href="https://www.lucidchart.com/pages/pt">link</a>. Acessado em 13 de maio. de 2023.
</div>

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |   10/05/2023  |        Criação inicial do documento | Mizael Santos | Rafael Bosi |
| `1.1`  |   10/05/2023  |        Criação dos casos de uso | Mizael Santos | Rafael Bosi |
