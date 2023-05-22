# Backlog do Produto

## Introdução

<div style="text-align:justify">
<p>&emsp;&emsp; O backlog do produto consiste em uma lista de priorização de pendências a serem desenvolvidas pela equipe, comumente utilizada em práticas ágeis,  a listagem é advinda dos requisitos licitados. Os itens na lista do backlog devem ser ordenados de forma crescente, ou seja dos com maior prioridade para os com menor, isso permite um planejamento melhor das sprints em técnicas ágeis[1].</p>
<p>&emsp;&emsp; É importante salientar que novos itens importantes podem compor o backlog a qualquer etapa do desenvolvimento. Os requisitos associados ao backlog podem ser fragmentados em diferentes níveis de abstração, e hierárquicos, sendo eles épicos, temas e histórias de usuário[2].</p>
</div>

## Vantagens de usar o backlog 
<div style="text-align:justify">
    <ul>
        <li>É uma lista organizada fácil de utilizar.
        <li>É simples de priorizar.
        <li>Pode ser alterado conforme as prioridades mudam.
        <li>Mostra e organiza imediatamente as dependências.
        <li>Considera os produtos em longo prazo, não apenas em termos de necessidades imediatas.
        <li>Agrega valor ao cliente
        <li>Pode ser estimado
    </ul>
</div>

## Metodologia
<div style="text-align:justify">
<p>&emsp;&emsp; Para a metodologia foi utilizado o microsoft excel para organizar o agrupamento, em temas e épico dos requisitos funcionais, partindo da análise e verificação dos mesmos elicitados. Posteriormente os dados foram transferidos para o artefato em questão. </p>

## Requisitos Elicitados
<div style="text-align:justify">
<p>&emsp;&emsp; Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de elicitação, juntamente com a rastreabilidade de cada um.</p>

### 3.1. Funcionalidades

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE01 | Permitir a reprodução de vídeos e áudios em diferentes formatos.         | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE02 | Suportar a reprodução de mídia em streaming.                            | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE03 | Permitir o controle de reprodução (pausar, avançar, retroceder, etc.).   | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE04 | Suportar legendas em diferentes idiomas.                                 | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE05 | Oferecer equalizador de áudio para ajustes de som.                       | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE06 | Possibilitar a reprodução em segundo plano.                              | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE11 | Permitir a criação de listas de reprodução.                              | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE12 | Oferecer opções de configuração de reprodução (velocidade, repetição, etc.). | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE13 | Suportar a reprodução em tela cheia.                                     | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE14 | Possibilitar a reprodução de mídia a partir de dispositivos externos (USB, etc.). | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE15 | Permitir o compartilhamento de mídia com outros dispositivos (DLNA, Chromecast, etc.). | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |

<div align="center">
<p> <b>Tabela 1</b>: Funcionalidades (Fonte: autores, 2023). </p>
</div>

### 3.2. Interface de Usuário

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE18 | A interface de usuário deve ser intuitiva e fácil de usar.               | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE19 | Deve possuir uma interface de usuário personalizável.                    | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE20 | A interface de usuário deve ser responsiva em diferentes tamanhos de tela. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |

<div align="center">
<p> <b>Tabela 2</b>: Interface de usuário (Fonte: autores, 2023). </p>
</div>

### 3.3. Requisitos de Armazenamento

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE09 | O aplicativo deve ocupar um espaço de armazenamento razoável.            | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |

<div align="center">
<p> <b>Tabela 3</b>: Requisitos de Armazenamento (Fonte: autores, 2023). </p>
</div>

### 3.4. Desempenho

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE10 | Eu, como usuário, gostaria que o aplicativo seja rápido ao carregar e reproduzir vídeos. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE16 | Eu, como usuário, gostaria que o aplicativo não consuma muita bateria do dispositivo. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE26 | Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes.  | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |

<div align="center">
<p> <b>Tabela 4</b>: Desempenho (Fonte: autores, 2023). </p>
</div>

### 3.5. Segurança e Privacidade

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE30 | O aplicativo deve garantir a segurança dos dados do usuário.             | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE31 | Problemas de segurança relacionados à reprodução de arquivos de mídia.  | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE33 | Risco de vulnerabilidades e exploits de segurança conhecidos.           | [ADD](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos) |
| RE34 | Risco de violação de privacidade do usuário e coleta de dados invasiva. | [ADD](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos) |

<div align="center">
<p> <b>Tabela 5</b>: Segurança e Privacidade (Fonte: autores, 2023). </p>
</div>

## Backlog 

### Temas 
<div style="text-align:justify">
    <p>&emsp;&emsp; Após a etapa de verificação e análise dos requisitos, foi observado que eles poderiam ser organizados em cinco grandes temas, que compõem o maior nível de abstração do backlog.</p>
    <ul>
        <li> Reprodução de mídia
        <li> Biblioteca de mídia
        <li> Personalização
        <li> Controles de reprodução
        <li> Gerenciamento de legendas
    </ul>
    <p>&emsp;&emsp; Após a definição dos temas, os requisitos foram especificados em um maior nível de abstração, por meio dos épicos. Os épicos são histórias de usuário que ainda podem ser mais especificadas e foram escritos utilizando o mesmo padrão do utilizado nas histórias de usuário.</p>
</div>

### Épicos 

<div style="text-align: justify">

&emsp;&emsp; Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura do backlog, os épicos estão especificados a seguir.

</div>

- #### Épico 1: Reprodução de Mídia

    - Requisitos relacionados: RE01, RE03, RE05, RE11, RE13, RE14, RE26
    - Descrição: Este épico aborda a funcionalidade principal do VLC, que é a reprodução de mídia. Ele inclui requisitos como suporte a diferentes formatos de áudio e vídeo, controle de reprodução (pausar, avançar, retroceder), equalizador de áudio, criação de listas de reprodução, reprodução em tela cheia, reprodução de mídia a partir de dispositivos externos e bom desempenho de reprodução, mesmo para arquivos grandes.

- #### Épico 2: Interface de Usuário

    - Requisitos relacionados: RE18, RE19, RE20
    - Descrição: Este épico trata da interface de usuário do VLC. Ele engloba requisitos como uma interface intuitiva e fácil de usar, capacidade de personalização da interface do usuário e responsividade em diferentes tamanhos de tela.

- #### Épico 3: Armazenamento

    - Requisitos relacionados: RE09
    - Descrição: Este épico aborda os requisitos relacionados ao armazenamento do aplicativo VLC. O único requisito incluído é que o aplicativo deve ocupar um espaço de armazenamento razoável.

- #### Épico 4: Desempenho

    - Requisitos relacionados: RE10, RE16, RE26
    - Descrição: Este épico trata dos requisitos de desempenho do VLC. Inclui requisitos como carregamento rápido e reprodução rápida de vídeos, baixo consumo de bateria do dispositivo e bom desempenho de reprodução, mesmo para arquivos grandes.

- #### Épico 5: Segurança e Privacidade

    - Requisitos relacionados: RE30, RE31, RE33, RE34
    - Descrição: Este épico aborda os requisitos de segurança e privacidade do VLC. Inclui requisitos como garantia da segurança dos dados do usuário, prevenção de problemas de segurança relacionados à reprodução de arquivos de mídia, mitigação de riscos de vulnerabilidades e exploits de segurança conhecidos, e proteção contra violação de privacidade do usuário e coleta invasiva de dados.

A tabela abaixo vai relacionar a prioridade de cada história indicando se ela é "Must" (Deve), "Could" (Poderia) ou "Would" (Gostaria).

| História de Usuário | Épico                  | Prioridade |
|--------------------|------------------------|----------------------------------------|
| US01               | Épico 3: Armazenamento | Must       |
| US02               | Épico 5: Segurança e Privacidade | Must       |
| US03               | Épico 4: Desempenho    | Must       |
| US04               | Épico 4: Desempenho    | Must       |
| US05               | Épico 1: Reprodução de Mídia | Must  |
| US06               | Épico 4: Desempenho    | Could      |
| US07               | Épico 4: Desempenho    | Could      |
| US08               | Épico 4: Desempenho    | Could      |
| US09               | Épico 2: Interface de Usuário | Must |
| US10               | Épico 4: Desempenho    | Could      |
| US11               | Épico 4: Desempenho    | Could      |
| US12               | Épico 4: Desempenho    | Could      |
| US13               | Épico 4: Desempenho    | Could      |
| US14               | Épico 4: Desempenho    | Could      |
| US15               | Épico 4: Desempenho    | Could      |
| US16               | Épico 4: Desempenho    | Could      |
| US17               | Épico 4: Desempenho    | Could      |
| US18               | Épico 4: Desempenho    | Could      |
| US19               | Épico 4: Desempenho    | Could      |
| US20               | Épico 4: Desempenho    | Could      |

<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Fonte: autores, 2023). </p>
</div>



## Conclusão

<div style="text-align: justify">

&emsp;&emsp; O desenvolvimento do VLC deve priorizar as histórias de usuário identificadas como "Must" (Deve). Essas histórias são consideradas essenciais para atender aos requisitos e alcançar os objetivos estabelecidos para cada épico.

&emsp;&emsp; As histórias de usuário classificadas como "Could" (Poderia) são opcionais, mas ainda oferecem valor significativo ao produto. Elas podem ser consideradas para inclusão no escopo do projeto, dependendo do tempo, recursos e prioridades gerais.

&emsp;&emsp; As histórias de usuário marcadas como "Would" (Gostaria) são desejáveis, mas não são consideradas prioritárias neste momento. Elas podem ser consideradas para versões futuras do VLC ou como melhorias incrementais após a conclusão das histórias de usuário de maior prioridade.

&emsp;&emsp; É importante revisar e ajustar as prioridades atribuídas às histórias de usuário de acordo com as necessidades e objetivos específicos do projeto. Essa tabela é uma base inicial e pode ser adaptada conforme a equipe e as partes interessadas revisam e refinam as prioridades e requisitos.

&emsp;&emsp; Ao seguir essa abordagem, o desenvolvimento do VLC poderá se concentrar nas funcionalidades principais, como a reprodução de mídia, a interface de usuário amigável, o desempenho eficiente e os requisitos de segurança e privacidade. Isso ajudará a garantir que o produto atenda às expectativas dos usuários e atinja os objetivos definidos.

</div>

## Bibliografia

- RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs)

- O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto) 

## Histórico de Versões
|   Data     | Versão | Descrição                   |    Autor(es)     |  Data de revisão | Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :--------------: | :---------: |
| 20/05/2023   |  `1.0`  | Criação do documento               | [Mizael Santos](https://github.com/frmiza) | 22/05/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
| 22/05/2023   |  `1.1`  | Adicionando tabelas, épicos e priorização | [Giovanni Alvissus](https://github.com/giovanni1106) | - | - |
