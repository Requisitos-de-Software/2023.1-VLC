<div class="body">

# Forward-From

## Introdução

<div align="justify">

&emsp;&emsp;A rastreabilidade é uma técnica utilizada para determinar o relacionamento entre os requisitos, a arquitetura e a implementação final de um produto, auxiliando na compreensão dos artefatos. É importante ressaltar que os requisitos não podem ser gerenciados efetivamente sem a rastreabilidade. A rastreabilidade pode ser dividida em pré-rastreabilidade, que está relacionada à ligação dos requisitos às suas fontes, e pós-rastreabilidade, que envolve a ligação dos requisitos aos artefatos criados durante o ciclo de vida do produto de software. A pós-rastreabilidade também é conhecida como Gerência de Desenvolvimento de Software baseado em Baseline.

&emsp;&emsp;A pré-rastreabilidade permite que os desenvolvedores identifiquem a origem dos requisitos, ou seja, a qual documento ou fonte eles estão associados. Essa informação é fundamental para entender o contexto e a justificativa de cada requisito. Além disso, a pré-rastreabilidade também facilita a detecção de inconsistências, redundâncias ou omissões nos requisitos, permitindo que sejam feitas correções e melhorias antes do início do desenvolvimento.

&emsp;&emsp;Já a pós-rastreabilidade é responsável por estabelecer as relações entre os requisitos e os artefatos gerados durante o desenvolvimento do software. Isso inclui a identificação de quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão relacionadas a cada requisito. Essa informação é valiosa para garantir a consistência e a completude do sistema, além de auxiliar na manutenção e evolução do software ao longo do tempo.

</div>

## Metodologia

<div align="justify">

&emsp;&emsp;A metodologia utilizada para estabelecer a rastreabilidade entre os requisitos e os artefatos foi o "forward-from" (para frente, a partir de). Essa abordagem de pós-rastreabilidade envolve a criação de informações de rastreabilidade entre os requisitos e os artefatos gerados nas atividades de desenvolvimento subsequentes. 

&emsp;&emsp;No contexto da rastreabilidade entre requisitos, o "forward-from" consiste no mapeamento das dependências entre os requisitos. Isso significa identificar se um requisito refina outro requisito, generaliza ou substitui algum requisito anterior. Por exemplo, um requisito pode ser uma evolução de outro requisito existente, incorporando novas funcionalidades ou modificando as existentes. Essa relação de dependência é importante para entender como os requisitos se relacionam entre si e para garantir que todos sejam adequadamente atendidos durante o desenvolvimento do software.

&emsp;&emsp;Além disso, o "forward-from" também envolve a rastreabilidade entre os requisitos e os artefatos de implementação, como código-fonte, documentação técnica e testes. Essa rastreabilidade permite identificar quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão relacionadas a cada requisito. Essas informações são cruciais para garantir a integridade do sistema e facilitar a manutenção futura.

&emsp;&emsp;Em resumo, o uso da abordagem "forward-from" na rastreabilidade de requisitos e artefatos é fundamental para estabelecer relações claras e consistentes entre os elementos do sistema, facilitando a compreensão, a manutenção e a evolução do software ao longo do seu ciclo de vida.

</div>

## Mapeamento

<div align="justify">

&emsp;&emsp;A pós-rastreabilidade dos requisitos para sua implementação é demonstrada nas tabelas a seguir, onde cada artefato está associado aos respectivos requisitos. A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.

</div>

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História de Usuário       |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| QUE     | Questionário              |
| ADD     | Análise de Documentos     |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div style="text-align: center">
<p> Tabela 1: Legenda (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

<div align="justify">

&emsp;&emsp;Nas tabelas subsequentes, são apresentadas as relações entre os requisitos e os artefatos correspondentes, como mostrado nas Tabela 2 e 3. Cada linha representa um requisito e cada coluna representa um tipo de artefato. Através desse mapeamento, é possível visualizar quais artefatos estão associados a cada requisito, fornecendo uma visão clara das dependências e do contexto de implementação.

&emsp;&emsp;O mapeamento dos requisitos para os artefatos é essencial para garantir a integridade e a consistência do sistema. Por exemplo, as histórias de usuário (US) são utilizadas para descrever as necessidades e objetivos dos usuários, enquanto os casos de uso (UC) detalham as interações entre os atores e o sistema. Os cenários (C) fornecem exemplos concretos de como o sistema deve se comportar em diferentes situações, e a especificação suplementar (ES) detalha requisitos adicionais que complementam as histórias de usuário e casos de uso.

&emsp;&emsp;Além disso, a introspecção (INT), o questionário (Q), a análise de documentos (ADD) e outras técnicas de levantamento de requisitos são utilizadas para obter informações mais detalhadas dos stakeholders e validar os requisitos levantados. O léxico (L) e o glossário (GLO) auxiliam na definição de termos e conceitos do domínio do sistema, facilitando a comunicação entre os membros da equipe.

&emsp;&emsp;Em suma, o mapeamento dos requisitos para os artefatos proporciona uma visão abrangente e estruturada do desenvolvimento do software, como é visto nas Tabelas de 4 a 24, permitindo que a equipe compreenda as relações entre os elementos e tome decisões embasadas durante todo o processo.

</div>

| ID do requisito funcional | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Tema | Tema do Backlog |
| História de Usuário | História de usuário |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| Artefatos de elicitação | Artefatos que elicitaram o requisito |
| Comentários | Como está o requisito atualmente no app |

<div style="text-align: center">
<p> Tabela 2: Modelo para requisito funcional (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| ID do requisito não funcional | Descrição do requisito |
| :-: | :-: |
| NFR | Softgoals relacionado |
| Especificação Suplementar | Critério da especificação |
| Comentários | Como está o requisito atualmente no app |                   

<div style="text-align: center">
<p> Tabela 3: Modelo para requisito não funcional (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

### Requisitos Funcionais

<div align="justify">

A seguir será apresentado as tabelas correspondentes aos requisitos funcionais. Sendo um requisito funcional uma declaração de como um sistema deve se comportar, definindo o que o sistema deve fazer para atender às necessidades ou expectativas do usuário. Os requisitos funcionais podem ser pensados ​​como recursos que o usuário detecta.

</div>

| RF01 | Suporte a uma ampla variedade de formatos de áudio e vídeo |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US12](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=ver-diferentes-formatos-de-v%c3%addeo) |
| Léxico  | [LV01: Assistir](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lv01-assistir) |
| Casos de uso | [UC03](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc03-%c3%81udio) e [UC05](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc05-v%c3%addeo) |
| Cenários | --- |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD01</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT01</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST15</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 4: Rastreabilidade do RF01 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF02 | Possibilidade de adicionar legendas e selecionar faixas de áudio |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Gerenciamento de legendas](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US17](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=adicionar-legenda) |
| Léxico  | [LO03: Legenda](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo03-legenda) |
| Casos de uso | [UC03](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc03-%c3%81udio) e [UC04](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc04-legenda) |
| Cenários | [C15 - Adicionar legenda aos vídeos](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c15-adicionar-legenda-aos-v%c3%addeos) |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT13</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE13</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST04</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 5: Rastreabilidade do RF02 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF03 | Lista de reprodução e funcionalidades de biblioteca de mídia |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Biblioteca de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US13](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=playlists) |
| Léxico  | [LO06 - Playlist](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo06-playlist) |
| Casos de uso | [UC01](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc01-media) e [UC02](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc02-playback) |
| Cenários | [C05 - Criando playlists](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c05-criando-playlists) |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD03</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT02</a>, <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST08</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling.md">ST13</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 6: Rastreabilidade do RF03 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF04 | Suporte a vários idiomas e localizações |
| :-: | :-: |
| Épico | --- |
| Tema | [Personalização](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US04](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=mudar-o-idioma) |
| Léxico  | [LO03 - Legenda](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo03-legenda) |
| Casos de uso | [UC04](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc04-legenda) |
| Cenários | [C15 - Adicionar legenda aos vídeos](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c15-adicionar-legenda-aos-v%c3%addeos) |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD06</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario.md">QUE23</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 7: Rastreabilidade do RF04 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF05 | Capacidade de lidar com arquivos de mídia de grande porte e alta resolução |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US19](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=reprodu%c3%a7%c3%a3o-de-m%c3%addia-de-alta-resolu%c3%a7%c3%a3o) |
| Léxico  | [LO07 - Qualidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo07-qualidade) |
| Casos de uso | [UC01](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc01-media) e [UC05](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc05-v%c3%addeo) |
| Cenários | --- |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos.md">ADD08</a> e <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT19</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 8: Rastreabilidade do RF05 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF06 | Suportar streaming de mídia |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | --- |
| Léxico  | --- |
| Casos de uso | [UC01](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc01-media) |
| Cenários | --- |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT03</a> |
| Comentários | Implementado |

<div style="text-align: center">
<p> Tabela 9: Rastreabilidade do RF06 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RF07 | Permitir a captura de tela e a gravação de vídeo |
| :-: | :-: |
| Épico | --- |
| Tema | --- |
| História de Usuário | --- |
| Léxico  | --- |
| Casos de uso | --- |
| Cenários | --- |
| Artefatos de elicitação | <a href="https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao.md">INT05</a> |
| Comentários | Ainda não existe no app |

<div style="text-align: center">
<p> Tabela 10: Rastreabilidade do RF07 (Fonte: BOSI, Rafael. 2023).</p>


| RF08| Permitir a conversão de formatos de arquivo |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| História de Usuário | [US18](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios) |
| Léxico  | [LO05: Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos) |
| Casos de uso | [UC05](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso) |
| Cenários | [C13 - Compartilhamento de vídeos](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios) |
| Artefatos de Elicitação | [INT04](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| Comentários | Não implementado |


<div style="text-align: center">
<p> Tabela 11: RF08 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF09| Deve ser possível personalizar a aparência da interface do usuário |
| :-: | :-: |
| Épico | [Épico 2: Interface de Usuário](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| Tema | [Personalização](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| História de Usuário | [US09](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios) |
| Léxico  | [LO02 - Interface](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos) |
| Casos de uso | [UC06](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso) |
| Cenários | [C08 - Deve ser possível personalizar a aparência da interface do usuário](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios) |
| Artefatos de Elicitação | [INT12](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) e [QUE09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario)|
| Comentários | Apenas com modo claro/escuro implementado |


<div style="text-align: center">
<p> Tabela 12: RF09 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF10| A interface deve fornecer feedback ao usuário sobre o progresso da reprodução e outras informações relevantes |
| :-: | :-: |
| Épico | [Épico 2: Interface de Usuário](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| Tema | [Controles de reprodução](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog) |
| História de Usuário | [US03](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios) |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos) |
| Casos de uso | [UC06](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso) |
| Cenários | [C12 - Mudar velocidade de reprodução](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios) |
| Artefatos de Elicitação | [INT14](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao), [QUE07](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [QUE11](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario), [QUE20](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario) e [ST05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 13: RF10 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF11| Aperfeiçoar a função de zoom do aplicativo |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US16](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=navegar-por-touch-screen) |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo05-plataforma) |
| Casos de uso | [UC01](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc01-media) |
| Cenários | [C06 - Enxergando detalhes](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c06-enxergando-detalhes) |
| Artefatos de Elicitação | [QUE05](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/questionario?id=requisitos-elicitados) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 14: RF11 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF12| Reprodução de vídeos |
| :-: | :-: |
| Épico | [Épico 1: Reprodução de Mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-1-reprodu%c3%a7%c3%a3o-de-m%c3%addia) |
| Tema | [Reprodução de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | [US16](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=navegar-por-touch-screen) |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo05-plataforma) |
| Casos de uso | [UC01](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc01-media) |
| Cenários | [C01 - Suporte ao usuário Android](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c01-suporte-ao-usu%c3%a1rio-android) e [C01 - Suporte ao usuário IOS](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c02-suporte-ao-usu%c3%a1rio-ios) |
| Artefatos de Elicitação | [ST01](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados), [ST02](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados), [ST03](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) e [ST12](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 15: RF12 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF13 | Edição de vídeo |
| :-: | :-: |
| Épico | - |
| Tema | - |
| História de Usuário | - |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo05-plataforma) |
| Casos de uso | - |
| Cenários | - |
| Artefatos de Elicitação | [ST06](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 16: RF13 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF14 | Salvar os vídeos para assistir em outros dispositivos |
| :-: | :-: |
| Épico | [Épico 3: Armazenamento](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=%c3%89pico-3-armazenamento) |
| Tema | [Biblioteca de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | - |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo05-plataforma) |
| Casos de uso | - |
| Cenários | - |
| Artefatos de Elicitação | [ST09](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) e [ST10](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) | Sim | |
| Comentários | Não implementado |


<div style="text-align: center">
<p> Tabela 17: RF14 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF15 | Compartilhar vídeos |
| :-: | :-: |
| Épico | - |
| Tema | [Biblioteca de mídia](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog?id=temas) |
| História de Usuário | - |
| Léxico  | [LO05 - Plataforma](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo05-plataforma) |
| Casos de uso | - |
| Cenários | [C13 - Compartilhamento de vídeos](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c13-compartilhamento-de-v%c3%addeos) |
| Artefatos de Elicitação | [ST11](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 18: RF15 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

| RF16 | Suporte ao usuário |
| :-: | :-: |
| Épico | - |
| Tema | - |
| História de Usuário | [US11](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/historias_de_usuarios?id=aba-de-ajuda) |
| Léxico  | [LO12 - Ajuda](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos?id=lo12-ajuda) |
| Casos de uso | [UC06](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso?id=uc06-ajuda) |
| Cenários | [C01 - Suporte ao usuário Android](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c01-suporte-ao-usu%c3%a1rio-android) e [C01 - Suporte ao usuário IOS](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios?id=c02-suporte-ao-usu%c3%a1rio-ios) |
| Artefatos de Elicitação | [ST17](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) e [ST18](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling?id=requisitos-elicitados) | Sim | |
| Comentários | Implementado |


<div style="text-align: center">
<p> Tabela 19: RF16 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

</div>

### Requisitos Não Funcionais

<div align="justify">

A seguir será apresentado as tabelas correspondentes aos requisitos não funcionais. Sendo eles requisitos relacionados ao uso da aplicação em termos de desempenho, usabilidade, confiabilidade, segurança, disponibilidade, manutenibilidade e tecnologias envolvidas. Não é preciso o cliente dizer sobre eles, pois eles são características mínimas de um software de qualidade, ficando a cargo do desenvolvedor optar por atender esses requisitos ou não.

</div>

| RNF01 | Sistemas operacionais suportados: Android e iOS |
| :-: | :-: |
| NFR | [NFR de Suportabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/nfr_framework) |
| Especificação Suplementar | [ES de Suportabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/especificacao_suplementar?id=supportability-suportabilidade) |
| Comentários | Implementado |                   

<div style="text-align: center">
<p> Tabela 20: Rastreabilidade do RNF01 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RNF02 | Interface do usuário intuitiva e fácil de usar |
| :-: | :-: |
| NFR | [NFR de Usabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/nfr_framework) |
| Especificação Suplementar | [ES de Usabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/especificacao_suplementar?id=usability-usabilidade) |
| Comentários | Implementado |                   

<div style="text-align: center">
<p> Tabela 21: Rastreabilidade do RNF02 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RNF03 | Preservar a privacidade e segurança dos dados do usuário |
| :-: | :-: |
| NFR | [NFR de Confiabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/nfr_framework) |
| Especificação Suplementar | [ES de Confiabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/especificacao_suplementar?id=reliability-confiabilidade) |
| Comentários | Implementado |                   

<div style="text-align: center">
<p> Tabela 22: Rastreabilidade do RNF03 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RNF04 | Deve ser de código aberto e gratuito |
| :-: | :-: |
| NFR | [NFR de Confiabilidade](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/nfr_framework) |
| Especificação Suplementar | --- |
| Comentários | Implementado |                   

<div style="text-align: center">
<p> Tabela 23: Rastreabilidade do RNF04 (Fonte: BOSI, Rafael. 2023).</p>
</div>

| RNF05 | Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes |
| :-: | :-: |
| NFR | [NFR de Desempenho](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/nfr_framework) |
| Especificação Suplementar | [ES de Desempenho](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/especificacao_suplementar?id=performance-desempenho) |
| Comentários | Implementado |                   

<div style="text-align: center">
<p> Tabela 24: Rastreabilidade do RNF05 (Fonte: BOSI, Rafael. 2023).</p>
</div>

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 28/06/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 28/06/2023

## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 27/06/2023 | `1.0` | Criação do artefato | [Rafael Bosi](https://github.com/StrangeUnit28) | 28/06/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
| 28/06/2023 | `1.1` | Atualizando metodologia | [Giovanni Alvissus](https://github.com/giovanni1106) | 28/06/2023 | [Rafael Bosi](https://github.com/StrangeUnit28) |
| 28/06/2023 | `1.2` | Adicionando RFs e RNFs | [Rafael Bosi](https://github.com/StrangeUnit28) | 28/06/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |

</div>