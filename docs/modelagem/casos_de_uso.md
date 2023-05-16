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

| UC01 | Mídia |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Abrir ambiente de mídias |
| **Condição de entrada** | O usuário seleciona uma das opções de abrir mídia, diretorio ou stream |
| **Fluxo principal** | <ol> <li> O usuário clicka em mídia <li> O usuário escolhe se vai abrir uma mídia, um diretorio ou stream ou salvar uma playlist <li> Abrir uma mídia pausada por default </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em abrir uma mídia</b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega entre as pastas mostrando mídias disponíveis <li> O usuário escolhe uma mídia <ul> <li> A mídia selecionada abre no aplicativo pausada por padrão </ul> </ol> <b> Fluxo 2: O usuário clicka em abrir um diretorio</b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega mostrando as pastas disponíveis </ol> <b> Fluxo 3: O usuário abre uma stream</b> <ol> <li> O Sistema abre uma janela de configurações da stream <ul> <li> O usuários pode configurar a URL de stream <li>O usuário pode configurar o arquivo <li> O usuário pode configurar a qualidade da stream </ul> <li> O usuário da play na stream </ol> <b>Fluxo 4: O usuário clicka em abrir recentes</b> <ol> <li> O sistema mostra em uma menu de cascata as mídias recentes <li> O usuário escolhe a mídia <li> O sistema inicia a mídia </ol> <b> Fluxo 5: O usuário clicka em salvar uma playlist </b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega entre as pastas disponíveis <li> O usuário escolhe a pasta <li> O usuário salva a playlist em formato de um arquivo </ol>|
| **Pós condições** | O usuário tem acesso a eventos de playback |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 1: Especificação do caso de uso: Mídia. (Fonte: Mizael Santos, 2023).</p>
</div>

| UC02 | Playback |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Manipular mídias abertas |
| **Condição de entrada** | O usuário seleciona uma das opções do player, pausar, iniciar, anterior, proximo, timestemp |
| **Fluxo principal** | <ol> <li> O usuário clicka em uma das opções  <li> O  sistema responde o escolha manipulando a mídia </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em iniciar a mídia</b> <ol> <li> O sistema responde pausando a mídia <li> O sistema atualiza o estado do botão para pausar </ol> <b> Fluxo 2: O usuário clicka em próximo</b> <ol> <li> O sistema abre a próxima mídia disponível na playlist </ol> <b> Fluxo 3: O usuário clicka em anterior</b> <ol> <li> O sistema abre a mídia anterior disponível na playlist </ol> <b>Fluxo 4: O usuário clicka em mudar velocidade</b> <ol> <li> O sistema mostra em uma menu de cascata com as velocidades disponíveis <ul> <li> Rápido <li> Normal <li> Lento </ul> <li> O usuário escolhe a velocidade <li> O sistema modifica a velocidade da mídia </ol> |
| **Pós condições** | Não há |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 2: Especificação do caso de uso: Playback. (Fonte: Mizael Santos, 2023).</p>

| UC03 | Áudio |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Manipular o áudio da mídia executada |
| **Condição de entrada** | O usuário seleciona uma das opções do stereo ou dispositivos |
| **Fluxo principal** | <ol> <li> O usuário clicka em uma das opções <li> O  sistema responde o escolha manipulando o áudio </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em dispositivos</b> <ol> <li> O sistema mostra em uma menu de cascata com os dispositivos de saída disponíveis <li> O usuário escolhe o dispositivos de saída que deseja </ol> <b> Fluxo 2: O usuário clicka em stereo </b> <ol> <li> O sistema mostra em uma menu de cascata com os modos de áudio disponíveis <ul> <li> Mono <li> Stereo <li> Esquerda <li> Direita <li> Stereo reverso </ul> </ol> |
| **Pós condições** | Não há |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 3: Especificação do caso de uso: Áudio. (Fonte: Mizael Santos, 2023).</p>
</div>

</div>

| UC04 | Legenda |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Requisitos** | Manipular as legendas da mídia |
| **Condição de entrada** | O usuário seleciona uma das opções de legenda disponível para a mídia executada |
| **Fluxo principal** | <ol> <li> O usuário clicka em escolher a legenda ou adicionar um arquivo de legenda  <li> O  sistema responde atualizando a legenda da mídia executada </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em adicionar uma legenda</b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega entre as pastas mostrando os arquivos de legenda disponíveis </ol> <b> Fluxo 2: O usuário clicka em selecionar uma legenda </b> <ol> <li> O sistema abre uma janela em cascata que mostra as legendas disponíveis pela mídia por padrão </ol> |
| **Pós condições** | O usuários visualiza a nova legenda na tela |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 4: Especificação do caso de uso: Legenda. (Fonte: Mizael Santos, 2023).</p>
</div>

| UC05 | Vídeo |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Requisitos** | Manipular opções do vídeo, resoluçao, tela cheia, zoom |
| **Condição de entrada** | O usuário seleciona uma das opções para a mídia executada |
| **Fluxo principal** | <ol> <li> O usuário clicka em uma das opções de ajuste de tela </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka tela cheia</b> <ol> <li> O sistema muda para tela cheia </ol> <b> Fluxo 2: O usuário clicka em selecionar uma das opções de zoom </b> <ol> <li> O sistema abre uma janela em cascata que mostra as opções disponíveis para ampliar a imagem da mídia executada <ul> <li> 1:4 <li> 1:2 <li> 1:1 Original <li> 2:1 </ul> </ol> <b> Fluxo 3: O usuários clicka em ajuste de tela</b> <ol> <li> O sistema abre uma janela em cascata que mostra as opções disponíveis para ajustar o tamanho de tela do dispositivo <ul> <li> Caso o usuário não selecione um tamanho de tela, o sistema usa um tamanho de tela padronizado pelo dispositivo em que é executado </ul> </ol> |
| **Pós condições** | O usuários visualiza a nova as novas modificações do sistema |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 5: Especificação do caso de uso: Vídeo. (Fonte: Mizael Santos, 2023).</p>
</div>

| UC06 | Ajuda |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Requisitos** | Ajudar o usuário |
| **Condição de entrada** | O usuário seleciona uma das opções, ajuda ou sobre o aplicativo |
| **Fluxo principal** | <ol> <li> O Usuário clicka em uma das opções <li> O sistema responde abrindo janelas informativas </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em ajuda </b> <ol> <li> O sistema abre uma janela de ajuda </ol> <b> Fluxo 2: O usuário clicka em sobre </b> <ol> <li> O sistema abre uma janela de que traz a informações sobre o aplicativo <ul> <li> Autores <li> Licensa <li> Creditos </ul> </ol> |
| **Pós condições** | O usuários visualiza a nova as novas modificações do sistema |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** |  |

<div style="text-align: center">
<p> Tabela 6: Especificação do caso de uso: Ajuda. (Fonte: Mizael Santos, 2023).</p>
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
| `1.2`  |   10/05/2023  |        Criação das tabelas de casos de uso | Mizael Santos | Rafael Bosi |
