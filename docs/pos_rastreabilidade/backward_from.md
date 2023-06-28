<div align="justify">

# Backward-From

## Introdução

Este artefato trata do método de rastreabilidade backward-from, técnica utilizada para relacionar os requisitos elicitados durante o projeto às suas respectivas fontes. A rastreabilidade, em sí, é a habilidade de rastrear os requisistos durante o curso inteiro de seu ciclo de vida no sistema.

Neste artefato e para a realização deste método, foram utilizados os [slides da aula 26](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano junto do livro [Requirements Engineering Fundamentals](https://aprender3.unb.br/pluginfile.php/2523040/mod_resource/content/2/Rastreabilidade.pdf) de Klaus Pohl e Chris Rupp.

## Metodologia

Para a execução do método de backward-from, além de suas próprias especificidades, foi utilizado o meta-modelo de Toranzo, o qual classificará os requisitos elicitados pelo grupo em níveis e elos. Com base nos [slides 19](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da aula 26 da professora Milene Serrano os níveis são:
- **_Ambiental_**: informções oriundas do ambiente e do contexto ao qual a organizcaão está inserida;
- **_Organizacional_**: informações relacionadas à organização;
- **_Gerencial_**: informações que auxiliam na gerencia do projeto;
- **_Desenvolvimento_**: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento.

Com base nos [slides 21](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da aula 26 da professora Milene Serrano os principais elos de rastreabilidade são:
- **Satisfação**: classe origem tem dependência de satisfação com a classe destino.
- **Recurso**: classe origem tem dependência de recurso com a classe destino.
- **Responsabilidade**: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- **Representação**: captura a representação ou modelagem dos requisitos em outras linguagens.
- **Alocado**: classe origem está relacionada à classe destino, que representa um subsistema.
- **Agregação**: indica “composição” de elementos

Para o auxilio da realização do meta-modelo de Toranzo, foram desenvolvidas as tabelas 1 e 2, as quais dividem os requisitos que serão rastreados em funcionais e não-funcionais.

### Legendas:

- **RF**: Requisito funcional
- **RNF**: Requisito não-funcional

## Tabelas de requisitos funcionais

| id | Descrição | Rastreabilidade | Implementado |
| :-:| :-------- | :-------------- | :----------- |
|RF01| Suporte a uma ampla variedade de formatos de áudio e vídeo | [ADD01](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT01](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [ST15](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF02| Possibilidade de adicionar legendas e selecionar faixas de áudio | [ADD02](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT02](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [INT13](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [QUE13](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [ST04](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF03| Lista de reprodução e funcionalidades de biblioteca de mídia | [ADD03](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT02](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [ST08](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST13](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF04| Suporte a vários idiomas e localizações | [ADD06](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [QUE23](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario) | Sim |
|RF05| Capacidade de lidar com arquivos de mídia de grande porte e alta resolução | [ADD08](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT19](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Sim |  
|RF06| Suportar streaming de mídia | [INT03](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Sim |
|RF07| Permitir a captura de tela e a gravação de vídeo | [INT05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Não |
|RF08| Permitir a conversão de formatos de arquivo | [INT04](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Não |
|RF09| Deve ser possível personalizar a aparência da interface do usuário | [INT12](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [QUE09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario) | Sim |
|RF10| A interface deve fornecer feedback ao usuário sobre o progresso da reprodução e outras informações relevantes | [INT14](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [QUE07](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [QUE11](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [QUE20](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [ST05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF11| Aperfeiçoar a função de zoom do aplicativo | [QUE05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario) | Sim |
|RF12| Eu, como usuário, gostaria de reproduzir vídeos | [ST01](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST02](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST03](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST12](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF13| Eu, como usuário, gostaria de realizar edições ao meu vídeo | [ST06](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF14| Eu, como usuário, gostaria de salvar meus vídeos para vê-los em outros dispositivos | [ST09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST10](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Não |
|RF15| Eu, como usuário, gostaria de compartilhar os vídeos | [ST11](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RF16| Eu, como usuário, gostaria de que o aplicativo tenha suporte ao usuário | [ST17](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling), [ST18](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Não |
<p><b> Tabela 1: Requisitos funcionais elicitados (Autore(s): RIBEIRO, Bruno; Bergholz, Lucas; PENHA, Igor. 2023)</b></p>

## Tabelas de requisitos não-funcionais

| id  | Descrição | Rastreabilidade | Implementado |
| :-: | :-------- | :-------------- | :----------- |
|RNF01| Sistemas operacionais suportados: Android e iOS | [ADD04](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT06](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Sim |
|RNF02| Interface do usuário intuitiva e fácil de usa | [ADD05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [QUE01](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [QUE15](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [ST07](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RNF03| Preservar a privacidade e segurança dos dados do usuário | [ADD09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [ADD10](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos), [INT17](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [ST16](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim |
|RNF04| Deve ser de código aberto e gratuito  | [INT08](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Sim |
|RNF05| Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes | [INT10](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [INT16](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) | Sim |
<p><b> Tabela 2: Requisitos funcionais elicitados (Autore(s): RIBEIRO, Bruno; Bergholz, Lucas; PENHA, Igor. 2023)</b></p>

## Elos
Neste tópico, serão apresentados os elos dos requisitos elicitados nas tabelas 1 e 2. A partir deles, foi montada a tabela 3 abaixo, com todos os elos envolvidos:

| id | Requisito | Tipo de Elo |
| -- | --------- | ----------- |
| ELO01 | RF01 | Representação: ADD01 representa INT01 <br> Representação: INT01 representa ST15 |
| ELO02 | RF02 | Representação: ADD02 representa INT02, e INT13 representa INT02 <br> Agregação: QUE13 agrega INT02 <br> Recurso: ST04 depende de INT02 |
| ELO03 | RF03 | Representação: ADD03 representa INT02, e ST13 representa INT02 <br> Agregação: ST08 agrega INT02 |
| ELO04 | RF04 | Representação: QUE13 representa ADD06 |
| ELO05 | RF05 | Recurso: INT19 depende de ADD08 |
| ELO06 | RF09 | Agregação: QUE09 agrega INT12 |
| ELO07 | RF10 | Agregação: QUE07, QUE11 e QUE20 agregam INT14 <br> Representação: ST05 representa QUE20 |
| ELO08 | RF12 | Recurso: ST02 depende de ST01 <br> Recurso: ST01 e ST02 dependem de ST03 <br> Agregação: ST12 agrega ST01 |
| ELO09 | RF14 | Recurso: ST09 depende de ST10 |
| ELO10 | RF16 | Agregação: ST18 agrega ST17 |
| ELO11 | RNF01 | Representação: ADD04 representa INT06 |
| ELO12 | RNF02 | Representação: ADD05 representa INT09, que representa ST07, que representa QUE15 <br> Agregação: QUE01 agrega ADD05|
| ELO13 | RNF03 | Representação: INT17, ADD19 e ADD10 representam ST16 |
| ELO14 | RNF05 | Representação: INT10 representa INT16 |

</div>
