<div class="body">

# Metodologia

## Introdução

  <p align="justify">

  Nesse projeto a equipe de desenvolvimento optou por se basear em algumas metodologia, de maneira, que a organização e o processo de desenvolvimento 
fossem o mais eficiente possível, dentro da realidade do grupo. </br >
  Importante resaltar que esse documento tem como principal objetivo descrever as metodologias em que nos baseamos durante o processo de criação.
E, também, informar o que dessas metodologias se foi abstraido.

</br>

## Motivo das Escolhas
  Após uma reunião em grupo e a discusão sobre quais ferramentas os membros teriam mais conhecimento e que melhor se encaixaria dentro do escopo do projeto que planejamos, utilizamos algumas metodologias já criadas e as adaptamos conforme achamos melhor. Assim, chegamos as seguintes metodologias:
  - SCRUM Adaptado;
  - XP (eXtreme Programming) Adaptado;
  - Domínio geral;
  - Proposta de Comunicação;
  - Encontros semanais;
  - Política de _branchs_;  
  - Política de _commits_.

## SCRUM Adaptado

A fim de assegurar uma quantidade consistente e rápida de entregas, a metodologia ágil SCRUM foi adotada para organização do tempo do time. </br>
Foi definido o timebox de uma ou duas semanas para cada sprint variado com as necessidades e prazos de entrega, iniciado e finalizado pelas reuniões semanais nas segundas-feira às 20:00.

As reuniões semanais têm como principais objetivos a realização de um  momento de review (_sprint review_) da sprint finalizada e organização das tarefas da sprint que se inicia (_sprint planning_). </br>
A atribuição das tarefas foi feita no início do projeto e encontra-se disponível no [cronograma](/docs/planejamento/Cronograma.md). 
Dessa forma, em cada _sprint planning_ será verificado com cada integrante a possibilidade de realizar a entrega à qual ele foi designado.
A verificação ocorre com a intenção de tomar as melhore decisões para o grupo sem prejudicar o projeto.

A organização das tarefas será feita por meio da criação de _issues_ e a revisão dos artefatos será feita durante o _pull request_ referente à cada funcionalidade ou documento adicionado.
Portanto, será possível manter uma rastreabilidade das alterações e revisões efetuadas.

</br>

## XP (eXtreme Programming) Adaptado

O método XP é uma metodologia ágil e pode ser aplicada para otimizar processos e gerar valor ao cliente desejado. 

Nós usamos também, o método XP pois, de maneira direta, ele tem como objetivo desenvolver sistemas de qualidade, com uma interação mais dinâmica de testagem de ciclos de desenvolvimento rápidos e de maneira constante. 

O principal inspiração na escolha desse método para nos auxiliar no projeto, já que é uma metodologia
focada em programação, foi o pareamento para que as entregas sejam feitas com mais qualidade
e, dessa maneira, mitigar os erros no projeto. Essa qualidade é visível no [cronograma planejado](/docs/planejamento/Cronograma.md).  

Nós fizemos adaptações dentro dessa metodologia ao nosso contexto. De forma que não ficassemos sobrecarregados e possamos usurfruirmos da melhor maneira possível o que a metodologia tem a oferecer.

</br>

## Domínio geral

Com o objetivo de trazer ao projeto mais qualidade e eficiencia, as nossas atividades são dividas de maneira que tenha um desenvolvedor e um Revisor(es) para que seja evitado envios e conclusões com erros. 

Durante todo o processo, de maneira constante, nós dialogamos a maioria das decisões em grupo principalmente quando o ponto de análise é importante e pertinente a todos.

Outrosim, em atividade com maior importãncia há a revisão em grupo para que todos os integrantes tenham conhecimento de maneira que todos os integrantes sempre tenham conhecimento de todo o produto.

</br>

## Proposta de Comunicação

Com o intuito de nos organizarmos e evitar problemas e divergências com as entregas das tarefas, nós nos planejamos em como seria nosso plano de comunicação.

Os membros tem acesso a todas as plataformas disponíveis e essenciais de comunicação que nós planejamos ter durante o processo de desenvolvimento, são elas: Teams, WhatsApp e github.

Assim, sempre que tiver algum imprevisto com o integrante ou possibilidade de ajuda o grupo é avisado em uma da ferramentas de comunicação rápida

</br>

## Encontros semanais

Além de todos os meios de comunicação seja por mensagens, presencial e tarefas do git, nós nos reunimos toda semana nas segundas-feira às 20 horas na plataforma "Teams", para alinharmos nossas questões, ideias e tarefas acerca do projeto.
Também organizamos nosso cronograma e planejamos as tarefas de todo o projeto e semanalmente discutimos se estam todos de acordo, verificamos se alguma tarefa está atrasada e se tiver colocamos como preferência para suprir a demanda.

E caso algum participante não possa comparecer à reunião, deixamos ela gravada e postada do YouTube, além de ter a [ata](/docs/atas) da reuniao

</br>

## Políticas

### Política de _commits_

As mensagens dos _commits_ seguirão os padrões estabelecidos pelo [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). Dessa forma, devem estar de acordo com o seguinte padrão:

```bash
git commit -m "tipoDeMudança(): descrição seguinificativa da alteração #issue"
```

> Exemplo:
>
> O _commit_ referente a criação do arquivo `metodologias.md` pode ter a mensagem `docs: criação do documento de padrões e metodologias #37`

</br>

### Política de _branchs_  

As criações das _branchs_ devem seguir o padrão:

> Nomes significativos em minusculo
> _Branch_ linkada à issue
> prefixo do que será executado na _branch_
>
> Exemplo:
> 
> A _branch_ referente a correção do arquivo `metodologias.md` o seu nome deverá ser:
 
 `redo-metodologia`
 
> e linkada a issue

</br>

## Conclusão
  Nossa equipe, de forma dinâmica e constante, busca sempre melhorar e otimizar o projeto, deixando-o mais claro, com menos possibilidade de erros. </br >
  
  Portanto, a metodologia é uma forma de padronizar e expor o que será utilizado no projeto, como as _sprints_, _issues_, _pull request_, pareamento do SCRUM.
Porém, não queriamos ficar presos a uma única metodologia, pois em certos momentos outras técnicas se encaixariam melhor como a XP. </br >

  Além de conter o dominio geral para que todos do grupo estejam cientes de todoas as etapas do trabalho, uma proposta de comunicação rápida e outra marcada com intenção de mitigar os erros. </br >
E políticas de entregas para termos o padrão, assim, conhecendo uma será capaz de conhecer todas

</br>

</div>
## Bibliografia

[1] Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.

## Histórico de Versão

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| 20/04/2023 | `1.0`  | Criação do documento | [Igor Penha](https://github.com/igorpenhaa)  | 21/04/2023 | [Bruno Ribeiro](https://github.com/brunoriibeiro) |
| 23/04/2023 | `1.1`  | Adicionando política de branch | [Igor Penha](https://github.com/igorpenhaa)  | 24/04/2023 | [Bruno Ribeiro](https://github.com/brunoriibeiro) |
| 25/04/2023 | `1.2`  | Atualizando a metodologia | [Igor Penha](https://github.com/igorpenhaa)  | 26/04/2023 | [Bruno Ribeiro](https://github.com/brunoriibeiro) |
| 24/06/2023 | `2.0` | Realizando correções no artefato | [Igor Penha](https://github.com/igorpenhaa)  | 26/06/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |

</div>