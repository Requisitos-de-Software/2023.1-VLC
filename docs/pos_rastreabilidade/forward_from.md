# Forward From

## Introdução

A rastreabilidade é uma técnica utilizada para determinar o relacionamento entre os requisitos, a arquitetura e a implementação final de um produto, auxiliando na compreensão dos artefatos. É importante ressaltar que os requisitos não podem ser gerenciados efetivamente sem a rastreabilidade. A rastreabilidade pode ser dividida em pré-rastreabilidade, que está relacionada à ligação dos requisitos às suas fontes, e pós-rastreabilidade, que envolve a ligação dos requisitos aos artefatos criados durante o ciclo de vida do produto de software. A pós-rastreabilidade também é conhecida como Gerência de Desenvolvimento de Software baseado em Baseline.

A pré-rastreabilidade permite que os desenvolvedores identifiquem a origem dos requisitos, ou seja, a qual documento ou fonte eles estão associados. Essa informação é fundamental para entender o contexto e a justificativa de cada requisito. Além disso, a pré-rastreabilidade também facilita a detecção de inconsistências, redundâncias ou omissões nos requisitos, permitindo que sejam feitas correções e melhorias antes do início do desenvolvimento.

Já a pós-rastreabilidade é responsável por estabelecer as relações entre os requisitos e os artefatos gerados durante o desenvolvimento do software. Isso inclui a identificação de quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão relacionadas a cada requisito. Essa informação é valiosa para garantir a consistência e a completude do sistema, além de auxiliar na manutenção e evolução do software ao longo do tempo.

## Metodologia

A metodologia utilizada para estabelecer a rastreabilidade entre os requisitos e os artefatos foi o "forward-from" (para frente, a partir de). Essa abordagem de pós-rastreabilidade envolve a criação de informações de rastreabilidade entre os requisitos e os artefatos gerados nas atividades de desenvolvimento subsequentes. 

No contexto da rastreabilidade entre requisitos, o "forward-from" consiste no mapeamento das dependências entre os requisitos. Isso significa identificar se um requisito refina outro requisito, generaliza ou substitui algum requisito anterior. Por exemplo, um requisito pode ser uma evolução de outro requisito existente, incorporando novas funcionalidades ou modificando as existentes. Essa relação de dependência é importante para entender como os requisitos se relacionam entre si e para garantir que todos sejam adequadamente atendidos durante o desenvolvimento do software.

Além disso, o "forward-from" também envolve a rastreabilidade entre os requisitos e os artefatos de implementação, como código-fonte, documentação técnica e testes. Essa rastreabilidade permite identificar quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão relacionadas a cada requisito. Essas informações são cruciais para garantir a integridade do sistema e facilitar a manutenção futura.

Em resumo, o uso da abordagem "forward-from" na rastreabilidade de requisitos e artefatos é fundamental para estabelecer relações claras e consistentes entre os elementos do sistema, facilitando a compreensão, a manutenção e a evolução do software ao longo do seu ciclo de vida.


## Mapeamento

A pós-rastreabilidade dos requisitos para sua implementação é demonstrada nas tabelas a seguir, onde cada artefato está associado aos respectivos requisitos. A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História de Usuário       |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| Q       | Questionário              |
| GLO     | Glossário                 |
| ADD     | Análise de Documentos     |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div style="text-align: center">
<p> Tabela 1: Legenda (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

Nas tabelas subsequentes, são apresentadas as relações entre os requisitos e os artefatos correspondentes, como mostrado nas Tabela 2 e 3. Cada linha representa um requisito e cada coluna representa um tipo de artefato. Através desse mapeamento, é possível visualizar quais artefatos estão associados a cada requisito, fornecendo uma visão clara das dependências e do contexto de implementação.

O mapeamento dos requisitos para os artefatos é essencial para garantir a integridade e a consistência do sistema. Por exemplo, as histórias de usuário (US) são utilizadas para descrever as necessidades e objetivos dos usuários, enquanto os casos de uso (UC) detalham as interações entre os atores e o sistema. Os cenários (C) fornecem exemplos concretos de como o sistema deve se comportar em diferentes situações, e a especificação suplementar (ES) detalha requisitos adicionais que complementam as histórias de usuário e casos de uso.

Além disso, a introspecção (INT), o questionário (Q), a análise de documentos (ADD) e outras técnicas de levantamento de requisitos são utilizadas para obter informações mais detalhadas dos stakeholders e validar os requisitos levantados. O léxico (L) e o glossário (GLO) auxiliam na definição de termos e conceitos do domínio do sistema, facilitando a comunicação entre os membros da equipe.

Em suma, o mapeamento dos requisitos para os artefatos proporciona uma visão abrangente e estruturada do desenvolvimento do software, permitindo que a equipe compreenda as relações entre os elementos e tome decisões embasadas durante todo o processo.

| ID do requisito funcional | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Tema | Tema do Backlog |
| História de Usuário | História de usuário |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| Artefatos | Artefatos relacionados |
| Comentários | Como está o requisito atualmente no app |

<div style="text-align: center">
<p> Tabela 2: Modelo (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>


### Requisitos Funcionais


<div style="text-align: center">
<p> Tabela 3: RF01 (Fonte: ALVISSUS, Giovanni. 2023).</p>
</div>

### Requisitos Não Funcionais


## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 28/06/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 28/06/2023

## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 27/06/2023 | `1.0` | Criação do artefato | [Rafael Bosi](https://github.com/StrangeUnit28) | 28/06/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
| 28/06/2023 | `1.1` | Atualizando metodologia | [Giovanni Alvissus](https://github.com/giovanni1106) | 28/06/2023 | [Rafael Bosi](https://github.com/StrangeUnit28) |