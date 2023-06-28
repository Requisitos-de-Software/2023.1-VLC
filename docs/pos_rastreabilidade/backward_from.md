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

Com base nos [slides 21](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da aula 26 da professora Milene Serrano os principais elos de rastreabilidadeão são:
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
|RF01| Suporte a uma ampla variedade de formatos de áudio e vídeo | ADD01, INT01, ST15 | Sim |
|RF02| Possibilidade de adicionar legendas e selecionar faixas de áudio | ADD02, INT02, INT13, QUE13, ST04 | Sim |
|RF03| Lista de reprodução e funcionalidades de biblioteca de mídia | ADD03, INT02, ST08, ST13 | Sim |
|RF04| Suporte a vários idiomas e localizações | ADD06, QUE23 | Sim |
|RF05| Capacidade de lidar com arquivos de mídia de grande porte e alta resolução | ADD08, INT19 | Sim |  
|RF06| Suportar streaming de mídia | INT03 | Sim |
|RF07| Permitir a captura de tela e a gravação de vídeo | INT05 | Não |
|RF08| Permitir a conversão de formatos de arquivo | INT04 | Não |
|RF09| Deve ser possível personalizar a aparência da interface do usuário | INT12, QUE09 | Sim |
|RF10| A interface deve fornecer feedback ao usuário sobre o progresso da reprodução e outras informações relevantes | INT14, QUE07, QUE11, QUE20, ST05 | Sim |
|RF11| Aperfeiçoar a função de zoom do aplicativo | QUE05 | Sim |
|RF12| Eu, como usuário, gostaria de reproduzir vídeos | ST01, ST02, ST03, ST12 | Sim |
|RF13| Eu, como usuário, gostaria de realizar edições ao meu vídeo | ST06 | Sim |
|RF14| Eu, como usuário, gostaria de salvar meus vídeos para vê-los em outros dispositivos | ST09, ST10 | Não |
|RF15| Eu, como usuário, gostaria de compartilhar os vídeos | ST11 | Sim |
|RF16| Eu, como usuário, gostaria de que o aplicativo tenha suporte ao usuário | ST17, ST18 | Não |
<p><b> Tabela 1: Requisitos funcionais elicitados (Autore(s): RIBEIRO, Bruno; Bergholz, Lucas; PENHA, Igor. 2023)</b></p>

## Tabelas de requisitos não-funcionais

| id  | Descrição | Rastreabilidade | Implementado |
| :-: | :-------- | :-------------- | :----------- |
|RNF01| Sistemas operacionais suportados: Android e iOS | ADD04, INT06 | Sim |
|RNF02| Interface do usuário intuitiva e fácil de usa | ADD05, INT09, QUE01, QUE15, ST07 | Sim |
|RNF03| Preservar a privacidade e segurança dos dados do usuário | ADD09, ADD10, INT17, ST16 | Sim |
|RNF04| Deve ser de código aberto e gratuito  | INT08 | Sim |
|RNF05| Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes | INT10, INT16 | Sim |
<p><b> Tabela 2: Requisitos funcionais elicitados (Autore(s): RIBEIRO, Bruno; Bergholz, Lucas; PENHA, Igor. 2023)</b></p>


</div>
