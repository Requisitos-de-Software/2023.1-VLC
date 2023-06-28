<div class="body">

# Matriz de Rastreabilidade

## Introdução 

<div align="justify">

&emsp;&emsp;Este artefato tem como objetivo listar de maneira mais organizada todos os requisitos que foram trabalhados em ambos os documentos de pós-rastreabilidade: <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/pos_rastreabilidade/backward_from.md">Backward-from</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/pos_rastreabilidade/forward_from.md">Forward-from</a>. 

</div>

## Metodologia

<div align="justify">

&emsp;&emsp;A metodologia aplicada consiste em uma matriz (ou tabela) composta por 5 colunas, especificadas abaixo, as quais buscam apresentar os dados do requisito de maneira organizada e sucinta.

&emsp;&emsp;Colunas que serão utilizadas na matriz de rastreabilidade:

- ID: Coluna de identificação do requisito.
- Descrição: Breve explicação do requisito.
- Elicitação: Metodo pelo qual o requisito foi elicitado.
- Artefatos: Documentos que foram desenvolvidos a partir desse requisito.
- Implementação: O requisito esta implementado, incompleto ou não implementado na aplicação.

</div>

## Mapeamento

<div align="justify">

&emsp;&emsp;Serão apresentados na Tabela 1, o mapeamento dos documentos e sua referência dos artefatos apresentados em seguida.

| Legenda | Descrição                 |
| ------- | ------------------------- |
| US      | História usuário          |
| ADD     | Análise de Documentos     |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| INT     | Introspecção              |
| QUE     | Questionário              |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div style="text-align: center">
<p> Tabela 1: Legenda do mapeamento de requisitos (Fonte: BOSI, Rafael. 2023).</p>
</div>

</div>

## Matriz Geral

<div align="justify">

&emsp;&emsp;A Tabela 2 abaixo representa todos os requisitos elicitados e suas respectivas descrições e rastreabilidades. Além disso, a tabela indica se os requisitos estão implementados, incompletos ou não implementados. 

| ID | Descrição | Elicitação | Artefatos | Implementação |
| ----------- | ---------- | --------- | --------- | --------- |
| RF01 | Suporte a uma ampla variedade de formatos de áudio e vídeo | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD01</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT01</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST15</a> |  | Implementado |
| RF02 | Possibilidade de adicionar legendas e selecionar faixas de áudio | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT13</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE13</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST04</a> |  | Implementado |
| RF03 | Lista de reprodução e funcionalidades de biblioteca de mídia | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD03</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST08</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST13</a> |  | Implementado |
| RF04 | Suporte a vários idiomas e localizações | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD06</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE23</a> |  | Implementado |
| RF05 | Capacidade de lidar com arquivos de mídia de grande porte e alta resolução | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD08</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT19</a> |  | Implementado |
| RF06 | Suportar streaming de mídia | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT03</a> |  | Implementado |
| RF07 | Permitir a captura de tela e a gravação de vídeo | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT05</a> |  | Inexistente |
| RF08 | Permitir a conversão de formatos de arquivo | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT04</a> |  | Inexistente |
| RF09 | Deve ser possível personalizar a aparência da interface do usuário | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT12</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE09</a> |  | Implementado |
| RF10 | Deve ser possível personalizar a aparência da interface do usuário | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT14</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE07</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE11</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE20</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST05</a> |  | Implementado |
| RF11 | Aperfeiçoar a função de zoom do aplicativo | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE05</a> |  | Implementado |
| RF12 | Eu, como usuário, gostaria de reproduzir vídeos | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST01</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST03</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST12</a> |  | Implementado |
| RF13 | Eu, como usuário, gostaria de realizar edições ao meu vídeo | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST06</a> |  | Implementado |
| RF14 | Eu, como usuário, gostaria de salvar meus vídeos para vê-los em outros dispositivos | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST09</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST10</a> |  | Inexistente |
| RF15 | Eu, como usuário, gostaria de compartilhar os vídeos | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST11</a> |  | Implementado |
| RF16 | Eu, como usuário, gostaria de que o aplicativo tenha suporte ao usuário | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST17</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST18</a> |  | Incompleto |
| RNF01 | Sistemas operacionais suportados: Android e iOS | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD04</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT06</a> |  | Implementado |
| RNF02 | Interface do usuário intuitiva e fácil de usar | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD05</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT09</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE01</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE15</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST07</a> |  | Implementado |
| RNF03 | Preservar a privacidade e segurança dos dados do usuário | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD09</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD10</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT17</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST16</a> |  | Implementado |
| RNF04 | Deve ser de código aberto e gratuito | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT08</a> |  | Implementado |
| RNF05 | Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT10</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT16</a> |  | Implementado |

<b>Tabela 2:</b> Matriz geral de rastreabilidade (Fonte: BOSI, Rafael. 2023).

</div>

## Referências Bibliográficas

- SERRANO, Milene. Slides da aula 26. Aula 26 da disciplina Requisitos de Software. Universidade de Brasília, Brasília, acesso em 27 de junho de 2023

- POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals. 2ª ed. New York: Springer, 2010.

## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 27/06/2023 | `1.0` | Criação do artefato | [Rafael Bosi](https://github.com/StrangeUnit28) | 28/06/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
| 28/06/2023 | `1.1` | Adicionando pré-rastreabilidade  | [Rafael Bosi](https://github.com/StrangeUnit28) | 28/06/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |

</div>