# Backlog do Produto
## Introdução

<div style="text-align:justify">
<p>O backlog do produto consiste em uma lista de priorização de pendências a serem desenvolvidas pela equipe, comumente utilizada em práticas ágeis,  a listagem é advinda dos requisitos licitados. Os itens na lista do backlog devem ser ordenados de forma crescente, ou seja dos com maior prioridade para os com menor, isso permite um planejamento melhor das sprints em técnicas ágeis[1].</p>
<p>É importante salientar que novos itens importantes podem compor o backlog a qualquer etapa do desenvolvimento. Os requisitos associados ao backlog podem ser fragmentados em diferentes níveis de abstração, e hierárquicos, sendo eles épicos, temas e histórias de usuário[2].</p>
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
<p>Para a metodologia foi utilizado o microsoft excel para organizar o agrupamento, em temas e épico dos requisitos funcionais, partindo da análise e verificação dos mesmos elicitados. Posteriormente os dados foram transferidos para o artefato em questão. </p>

## Requisitos Elicitados
<div style="text-align:justify">
<p>Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de elicitação, juntamente com a rastreabilidade de cada um.</p>

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

### 3.2. Interface de Usuário

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE18 | A interface de usuário deve ser intuitiva e fácil de usar.               | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE19 | Deve possuir uma interface de usuário personalizável.                    | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE20 | A interface de usuário deve ser responsiva em diferentes tamanhos de tela. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |

### 3.3. Requisitos de Armazenamento

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE09 | O aplicativo deve ocupar um espaço de armazenamento razoável.            | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |

### 3.4. Desempenho

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE10 | Eu, como usuário, gostaria que o aplicativo seja rápido ao carregar e reproduzir vídeos. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE16 | Eu, como usuário, gostaria que o aplicativo não consuma muita bateria do dispositivo. | [ST](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/storytelling) |
| RE26 | Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes.  | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |

### 3.5. Segurança e Privacidade

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE30 | O aplicativo deve garantir a segurança dos dados do usuário.             | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE31 | Problemas de segurança relacionados à reprodução de arquivos de mídia.  | [INT](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/introspeccao) |
| RE33 | Risco de vulnerabilidades e exploits de segurança conhecidos.           | [ADD](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos) |
| RE34 | Risco de violação de privacidade do usuário e coleta de dados invasiva. | [ADD](https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/analise-de-documentos) |



<div align="center">
<p> <b>Tabela 1</b>: Requisitos funcionais elicitados (Fonte: autores, 2023). </p>
</div>

## Backlog 

### Temas 
<div style="text-align:justify">
    <p>Após a etapa de verificação e análise dos requisitos, foi observado que eles poderiam ser organizados em cinco grandes temas, que compõem o maior nível de abstração do backlog.</p>
    <ul>
        <li> Reprodução de mídia
        <li> Biblioteca de mídia
        <li> Personalização
        <li> Controles de reprodução
        <li> Gerenciamento de legendas
    </ul>
    <p>Após a definição dos temas, os requisitos foram especificados em um maior nível de abstração, por meio dos épicos. Os épicos são histórias de usuário que ainda podem ser mais especificadas e foram escritos utilizando o mesmo padrão do utilizado nas histórias de usuário.</p>
</div>

### Épicos 

## Bibliografia
[1] RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs)
[2] O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto) 

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 20/05/2023    | Criação do documento               | [Mizael Santos](https://github.com/frmiza) |  [Giovanni Alvissus](https://github.com/giovanni1106) |
