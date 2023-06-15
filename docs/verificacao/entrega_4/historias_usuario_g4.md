<div class="body">

# Verificação do artefato "História de Usuário"

## Introdução

<div align="justify">

&emsp;&emsp;A técnica de verificação de artefatos é uma etapa crucial no processo de avaliação de documentos, projetos ou produtos desenvolvidos em diversas áreas, incluindo na área de Requisitos de Software. Essa técnica visa analisar minuciosamente o conteúdo, a estrutura e as características específicas de um artefato, a fim de avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos propostos.

&emsp;&emsp;Esse documento tem como objetivo fazer uma verificação do artefato "História de Usuário" desenvolvido pelo Grupo 4 da matéria de Requisitos de Software.

</div>

## Metodologia

<div align="justify">

&emsp;&emsp;A metodologia para verificar o artefato em questão será baseado, principalmente, nos critérios de avaliação do artefato, disponível como prévia no livro [Engenharia_de_Software_Uma_Abordagem_Profissional](https://aprender3.unb.br/pluginfile.php/2523118/mod_resource/content/3/Engenharia_de_Software_Uma_Abordagem_Pro.pdf) e mais detalhado na avaliação de apresentação, podendo ser complementado pelo documento de avaliação entregue pelos monitores da disciplina sobre a qualidade do artefato. Além de também ser verificado critérios gerais, como a padronização conforme as diretrizes do repositório.

&emsp;&emsp;Para tal, a verificação será dividida em duas etapas, a primeira sendo a verificação do conteúdo esperado no artefato e a segunda questões de padronização, estrutura, referências, entre outras.

</div>

## Conteúdo esperado

### Verificação

<div align="justify">

&emsp;&emsp;Neste documento, espera-se requisitos do aplicativo em formato de histórias de usuário, mostrando como os fluxos de tarefas pelos usuários. 

&emsp;&emsp;Sendo assim, foi elaborada a tabela 1 abaixo relacionando as especificações ideais do artefato, se ele possue ou não e a qualidade da entrega, onde a qualidade é baseada na seguinte classificação:

- Excelente (Cumpre com todo conteúdo esperado na avaliação).
- Boa (Possue parte do conteúdo esperado na avaliação).
- Incompleta (Passa brevemente pelo conteúdo esperado na avaliação).

</div>

| ID | Conteúdo | Possui | Qualidade | Observação |
| - | - | - | - | - |
| 1 | Os títulos das histórias de usuário são auto-explicativos? | Sim | Excelente |  |
| 2 | O "quem", "o que" e o "por que" estão definidos na história de usuário? | Sim | Excelente |  |
| 3 | A história possui critérios de aceitação? | Sim | Excelente | |
| 4 | Os critérios de aceitação das histórias foram definidos? | Sim | Excelente | |
| 5 | A participação do cliente e/ou persona na elicitação de requisitos? | Sim | Excelente | |
| 6 | Todas as histórias de usuário podem ser testadas? | Sim | Boa | As histórias relacionadas a boletos e pagamentos podem dificultar os testes do grupo. |
| 7 | Uma fonte de onde foram retiradas as histórias? | Sim | Excelente | |

<b>Tabela 1</b>: Relação do conteúdo (Fonte: ALVISSUS, Giovanni. 2023).

A seguir o Gráfico 1 para representar a média da qualidade do artefato:

<body>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <canvas id="chart"></canvas>

    <script>
        // Dados da tabela
        var data = [
            { qualidade: "Excelente", cor: "#00ff00", quantidade: 6 },
            { qualidade: "Boa", cor: "#ffff00", quantidade: 1 },
            { qualidade: "Incompleta", cor: "#ff0000", quantidade: 0 }
        ];

        // Configuração do gráfico
        var config = {
            type: 'pie',
            data: {
                datasets: [{
                    data: data.map(item => item.quantidade),
                    backgroundColor: data.map(item => item.cor)
                }],
                labels: data.map(item => item.qualidade)
            },
            options: {
                responsive: true
            }
        };

        // Renderiza o gráfico
        var ctx = document.getElementById('chart').getContext('2d');
        new Chart(ctx, config);
    </script>
</body>

<b>Gráfico 1</b>: Gráfico de qualidade (Fonte: ALVISSUS, Giovanni. 2023).

### Conclusão

<div align="justify">

&emsp;&emsp;De modo geral o artefato contém um conteúdo condizente com o esperado, contudo algumas histórias podem resultar em dificuldades para o grupo testa-las futuramente.

</div>

## Critérios gerais

### Verificação

<div align="justify">

&emsp;&emsp;Para verificação dos critérios gerais foi elaborada a lista abaixo com os tópicos principais de concordância do artefato baseadas tanto nos critérios gerais do plano de ensino que todo artefato deve possuir quanto em normas ABNT.

</div>

1. Padronização:
   - [✅] O artefato segue as diretrizes de formatação especificadas.
   - [✅] A fonte e o tamanho do texto estão consistentes em todo o documento.
   - [❌] As margens e os espaçamentos estão corretos.
   - [✅] O uso de negrito, itálico e sublinhado está adequado e consistente.
   - [❌] Os parágrafos estão todos justificados.

2. Estrutura:
   - [✅] O artefato possui uma introdução clara e contextualizada.
   - [✅] As seções estão organizadas de forma lógica e coerente.
   - [✅] Os títulos e subtítulos estão bem definidos e formatados corretamente.
   - [❌] O artefato possui uma conclusão que sintetiza os principais pontos abordados.
   - [❌] O artefato possui histórico de versão com autor e revisor com as respectivas datas.

3. Referências:
   - [✅] Todas as referências citadas no texto estão presentes na lista de referências.
   - [❌] As referências estão formatadas corretamente, seguindo o estilo especificado.

### Conclusão

<div align="justify">

&emsp;&emsp;A estrutura do documento ficou coerente e bem elaborada, porém faltam alguns detalhes para melhorar o documento.

</div>

## Correções e ajustes sugeridos

<div align="justify">

&emsp;&emsp;Justificar os textos e melhorar a bibliografia, além de adicionar uma conclusão no artefato para sintetizar o estudo realizado. Sobre o conteúdo é interessante reavaliar as histórias cujo os testes possam ser inviaveis a longo prazo.

</div>

## Bibliografia

- [1] PRESSMAN. Engenharia de Software Uma Abordagem Profissional. Disponível em: https://aprender3.unb.br/pluginfile.php/2523005/mod_resource/content/27/Plano_de_Ensino%20RE%20202301%20Turma%202.pdf. Acesso em 14 de junho de 2023.

- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. ABNT. Disponível em: <https://www.abnt.org.br/>. Acesso em: 03 jun. 2023.


## Histórico de Versões

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 13/06/2001 | `1.0` | Iniciando o documento | [Giovanni Alvissus](github.com/giovanni1106) | - | [-](-) |
| 14/06/2001 | `1.1` | Finalizando a criação do documento | [Giovanni Alvissus](github.com/giovanni1106) | 14/06/2023 | [Rafael Bosi](https://github.com/strangeunit28) |

</div>
