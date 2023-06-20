
# Verificação do artefato de Casos de Uso (VLC)

## Introdução
  
A técnica de verificação de artefatos é um processo usado para avaliar e validar a qualidade, corretude e conformidade de um determinado artefato. Esses artefatos podem incluir documentos, código-fonte, modelos de dados, projetos de design, especificações de requisitos, entre outros. Assim sendo, é uma etapa crucial no processo de avaliação de documentos, projetos ou produtos desenvolvidos em diversas áreas, incluindo a interação humano-computador. Essa técnica visa analisar minuciosamente o conteúdo, a estrutura e as características específicas de um artefato, a fim de avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos propostos.
  
## Metodologia
  
  
A metodologia para verificar o artefato em questão será baseado, principalmente, nos critérios de avaliação do artefato, disponível como prévia na [aula 13 - professora Milene e Maurício](https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf) podendo ser complementado pelo documento de avaliação entregue pelos monitores da disciplina sobre a qualidade do artefato. Além de também ser verificado critérios gerais, como a padronização conforme as diretrizes do repositório.
  
Para tal, será utilizada a técnica de Análise estática, essa técnica consiste em examinar o código-fonte ou outro tipo de artefato sem executá-lo, em busca de erros, vulnerabilidades e problemas de qualidade. A análise estática pode ser feita manualmente ou com o auxílio de ferramentas automatizadas que realizam análises de sintaxe, semântica e conformidade com padrões.
  
Desse modo, a verificação será dividida em duas etapas, a primeira sendo a verificação do conteúdo esperado no artefato e a segunda questões de padronização, estrutura, referências, entre outras.

  
## Conteúdo esperado
  
### Verificação
  
  
A tabela 1 foi elaborada com intuito de relacionar as especificações ideais do artefato e a qualidade da entrega, na qual a qualidade é baseada na seguinte classificação:
  
  - **_Excelente_** (cumpre com todo o conteúdo esperado na avaliação)
  - **_Boa_** (possue parte do conteúdo esperado na avaliação)
  - **_Imcompleta_** (passa brevemente pelo conteúdo esperado na avaliação)
 
  
| id | Conteúdo | Possue | Qualidade | Observação |
| -- | -------- | ------ | --------- | ---------- |
| 1 | O artefato possui o objetivo do documento? | Sim | Excelente |  |
| 2 | O artefato possui a metodologia utilizada e sua respectiva descrição? | Sim | Excelente |  |
| 3 | A modelagem de casos de uso é suficientemente detalhada para fornecer uma visão completa das interações entre os atores e o sistema, mas também abstrata o suficiente para não se tornar excessivamente detalhada ou técnica demais? | Sim | Excelente |  |
| 4 | O artefato apresenta um diagrama de casos de uso? | Sim | Excelente |  |
| 5 | Os casos de uso estão alinhados com os objetivos e requisitos do projeto, representando funcionalidades ou comportamentos importantes do sistema que atendam às necessidades dos usuários e stakeholders? | Sim | Excelente |  |
| 6 | Os diagramas de caso de uso focam nos requisitos funcionais do sistema? | Sim | Excelente |  |
| 7 | A modelagem de casos de uso cobre todas as principais funcionalidades e interações do sistema? | Sim | Excelente |  |
| 8 | A modelagem de casos de uso apresenta uma representação para o sistema em avaliação, sendo esta delimitada por bordas? | Sim | Excelente |  |
| 9 | Os diagramas de caso de uso apresentam as representações de atores, estes representados por bonecos palito, estando diagramados fora da borda do sistema? | Sim | Excelente |  |
| 10 | Os diagramas de caso de uso apresentam as representações de atores primários e secundários, primários do lado esquerdo do sistema (bordas) e secundários do lado direito? | Não |  | Não há representação de autores secundários. |
| 11 | Os diagramas de caso de uso apresentam as setas de _extend_ e _include_ nas direções corretas? De modo que os _includes_ tenham suas setas apontando para o caso de uso a ser incluido no análisado e os _extend_ tenham suas setas apontando para o caso em análise, vido do caso solicitado. | Sim | Excelente |  |
| 12 | Os casos de uso são consistentes entre si e com outros artefatos do projeto? | Sim | Excelente |  |
<p> <b>Tabela 1</b>: Relação do conteúdo (Fonte: RIBEIRO, Bruno. 2023). </p>
  
## Conclusão
  
  
Embora o artefato esteja, em sua maior parte, completo em relação às expectativas, algumas pequenas ressalvas são necessárias:
  
- **id 10**: Representar outros atores no processo, como por ex: sistema, subsistemas e/ou componentes.

Abaixo, segue um gráfico (figura 1) representativo das respostas obtidas na tabela 1:

<img src="https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/img/verificacao/entrega_3/casosdeuso.png" width="100%">
<p> </p><b>Figura 1</b>: Gráfico referente a tabela 1 (Fonte: RIBEIRO, Bruno. 2023). </p>

  
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
   - [X] As tabelas possuem legenda.
   - [X] As tabelas são chamadas no texto.
  
## Conclusão
    
O artefato atendeu com sucesso às regras determinadas pela ABNT e aos critérios de aceitação da disciplina.
  
## Correções e ajustes sugeridos
    
Algumas correções sugeridas são:
  
- Adicionar outros tipos de autores ao diagrama.
  
## Bibliografia
  
- SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 03 jun. 2023.

- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. ABNT. Disponível em: <https://www.abnt.org.br/>. Acesso em: 03 jun. 2023.

- Documento de casos de uso do Grupo 3 da Disciplina de Requisitos. Disponível em: <[https://github.com/Requisitos-de-Software/2023.1-Caesb/blob/main/docs/Modelagem/casos_de_uso.md](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso)>. Acesso em: 03 jun. 2023.  

- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. ABNT. Disponível em: <https://www.abnt.org.br/>. Acesso em: 03 jun. 2023.
  
## Histórico de Versões
  
| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :------------------------: | :--------------------------: | :-----------------------------: | :-----------------------------: | :-----------------------------------: | :-------------------------------: |
| 20/06/2023 | `1.0` | Criação do artefato |  [Bruno Ribeiro](https://github.com/BrunoRiibeiro) | 21/06/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |
