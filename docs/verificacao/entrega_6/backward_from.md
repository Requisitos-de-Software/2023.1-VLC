<div class="body">

# Verificação Backward-From (VLC)

## Introdução

<div align="justify">

A técnica de verificação de artefatos é uma etapa crucial no processo de avaliação de documentos, projetos ou produtos desenvolvidos em diversas áreas, incluindo a requisitos de software. Essa técnica visa analisar minuciosamente o conteúdo, a estrutura e as características específicas de um artefato, a fim de avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos propostos.

Este artefato tem como objetivo realizar a verificação do artefato de pós-rastreabilidade [Backward-From](https://requisitos-de-software.github.io/2023.1-VLC/#/pos_rastreabilidade/backward_from.md) versão `1.0` do grupo 3.

## Metodologia

A metodologia para verificar o artefato em questão será baseado, principalmente, nos critérios de avaliação do artefato, disponível como prévia nos [slides da aula 26](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano e Maurício Serrano e pelo livro [Requirements Engineering Fundamentals](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf) de Klaus Pohl e Chris Rupp, podendo também, ser complementado pela [monografia](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf) de Miriam Sayão e Julio Cesar Sampaio. Além de também ser verificado critérios gerais, como a padronização conforme as diretrizes do repositório.

Para tal, a verificação será dividida em duas etapas, a primeira sendo a verificação do conteúdo esperado no artefato e a segunda questões de padronização, estrutura, referências, entre outras.

## Conteúdo esperado

### Verificação

Foi elaborada a tabela 1 abaixo relacionando as especificações ideais do artefato, se ele possui ou não a qualidade da entrega, onde a qualidade é baseada na seguinte classificação:

- Excelente (Cumpre com todo conteúdo esperado na avaliação).
- Boa (Possue parte do conteúdo esperado na avaliação).
- Imcompleta (Passa brevemente pelo conteúdo esperado na avaliação).

| id | Conteúdo | Referência | Possui | Qualidade | Observação |
| - | - | - | - | - | - |
| 1 | O documento em questão tem como principal objetivo ligar os requisitos elicitados às suas fontes? | slides da aula 26 | Sim | Excelente | |
| 2 | Os requisitos são rastreáveis às suas fontes bem como aos artefatos criados durante o ciclo de vida de desenvolvimento do projeto? | slides da aula 26 | Sim | Excelente | |
| 3 | São criados elos entre as mudanças realizadas e promovidas pela elicitação de requisitos e a evolução do projeto, para assim, consolidar uma base de gerenciamento do conhecimento organizacional do projeto? | livro Requirements Engineering Fundamentals | Sim | Boa | Os elos poderiam linkar aos artefatos ao invés de o mencioná-lo. |
| 4 | Dentre os elos apresentados são existem elos de satisfação/alocado? ou seja , elos que asseguram que os requitos sejam atendidos pelo sistema, de mode que cada requisito foi associado a um componente que deverá atendê-lo.  | monografia | Não | - | |
| 5 | Dentre os elos apresentados são existem elos de evolução? ou seja, elos que levam objetos existentes para objetos novos ou modificados. | monografia | Não | - | |
| 6 | Dentre os elos apresentados são existem elos de _rationale_? ou seja, elos que representam as motivações subjacentes aos objetos existentes. | monografia | Não | - | |
| 7 | Dentre os elos apresentados são existem elos de dependência/recurso? ou seja, elos que apoiam o gerenciamento de dependências entre objetos. | monografia | Sim | Excelente | |
| 8 | Dentre os elos apresentados são existem elos de responsabilidade? ou seja, elos que registram a participipação, responsabilidade e ação de pessoas sobre artefatos. | monografia | Não | - | |
| 9 | Dentre os elos apresentados são existem elos de representacão? ou seja, elos que capturam a represetação ou modelagem dos requisitos em outras linguagens. | monografia | Sim | Excelente | |
| 10 | Dentre os elos apresentados são existem elos de agregação? ou seja, elos que indicam composição de elementos. | monografia | Sim | Excelente | |
| 11 | Os requisitos foram organizados pelo meta-modelo de Toranzo em quatro níveis? sendo eles: ambiental, organizacional, gerencial e desenvolvimento. | monografia | Sim | Excelente | |
<p><b>Tabela 1</b>: Relação do conteúdo (Fonte: RIBEIRO, Bruno. 2023).</p>

### Conclusão

Com a tabela 1 como referência, pode-se realizar uma breve análise sobre questões problemáticas do artefato:

- **id4, id5, id6, id8**: Devido a não obrigatoriedade da apresentação de todos os tipos de elos não serão feitas novas sujestões.

Abaixo, segue um gráfico (figura 1) representativo das respostas obtidas na tabela 1:

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/verificacao/entrega_6/backward-from.png" width="100%">
<b>Figura 1</b>: Gráfico referente a tabela 1 (Fonte: RIBEIRO, Bruno. 2023).

</div>

## Critérios gerais

### Verificação

Para verificação dos critérios gerais foi elaborada a lista abaixo com os tópicos principais de concordância do artefato baseadas tanto nos critérios gerais do plano de ensino que todo artefato deve possuir quanto em normas ABNT.

1. Padronização:
   - [X] O artefato segue as diretrizes de formatação especificadas.
   - [X] A fonte e o tamanho do texto estão consistentes em todo o documento.
   - [X] As margens e os espaçamentos estão corretos.
   - [X] O uso de negrito, itálico e sublinhado está adequado e consistente.
   - [X] Os parágrafos estão todos justificados.

2. Estrutura:
   - [X] O artefato possui uma introdução clara e contextualizada.
   - [X] As seções estão organizadas de forma lógica e coerente.
   - [X] Os títulos e subtítulos estão bem definidos e formatados corretamente.
   - [X] O artefato possui uma conclusão que sintetiza os principais pontos abordados.
   - [X] O artefato possui histórico de versão com autor e revisor com as respectivas datas.

3. Referências:
   - [X] As citações estão corretamente formatadas de acordo com o estilo especificado.
   - [X] Todas as referências citadas no texto estão presentes na lista de referências.
   - [X] As referências estão formatadas corretamente, seguindo o estilo especificado.

4. Tabelas:
   - [x] As tabelas possuem legenda.
   - [x] As tabelas são chamadas no texto. Porém não são todas.

### Conclusão

O artefato respeita todos dos pontos estruturais analisados.

</div>

## Bibliografia

- Requirements Engineering Fundamental. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf>. Acesso em: 28 jun. 2023.

- Monografia. SAYÃO, Miriam; CESAR SAMPAIO, Julio. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf>. Acesso em: 28 jun. 2023.

- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. ABNT. Disponível em: <https://www.abnt.org.br/>. Acesso em: 03 jun. 2023.

- Documento de pós-rastreabilidade Backward-From versão `1.0` do Grupo 3 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/pos_rastreabilidade/backward_from.md> Acesso em: 28 jun. 2023.

## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 18/06/2023 | `1.0` | Criação do artefato |  [Bruno Ribeiro](https://github.com/BrunoRiibeiro) | 19/06/2023 | [Igor Penha](https://github.com/igorpenhaa) e [Lucas Gobbi](https://github.com/lucasbergholz) |

</div>
