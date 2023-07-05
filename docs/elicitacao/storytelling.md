<div class="body">
  
# Storytelling (Histórias)

## Introdução

<div align="justify">

&emsp;&emsp;_Storytelling_ é uma é uma técnica utilizada para elicitar requisitos, a qual irá descrever quais são as atividades, sentimentos dos usuários e informações necessárias e as geradas pelo produto. O _storytelling_ elicita os requisitos utilizando uma narrativa de forma que quem estiver lendo tenha interesse e motivação para saber mais sobre o _software_, a partir de uma história contata pelos usuários sobre suas ações realizadas.

## Metodologia

&emsp;&emsp;Para o desenvolvimento e realização do _storytelling_, foi utilizado as personas desenvolvidas e a observação de objetivos, sentimentos e tarefas dos usuários dentro de suas histórias e contexto. Por fim, elencamos alguns dos requisitos.

## Storytelling

### Transmissão de conhecimento 

&emsp;&emsp;[Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) professor de literatura para ensino médio, que sempre teve o sonho e objetivo de vida compartilhar com os mais novos, seus aprendizes, o máximo de conhecimento que conseguisse. Porém, depois de anos lecionando, começou a sentir que o que ele fazia ainda não era o bastante, Caius queria fazer mais por seu queridos alunos, mas não sabia como.

&emsp;&emsp;Certo dia, decidiu ir à um congresso de ensino, onde vários palestrantes falavam sobre técnicas de ensino e como essas técnicas poderia ser ministradas para um melhor desempenho no aprendizado dos alunos. Caius ficou encantado, pricipalmente, com uma técnica que utilizava um software livre portátil de mídia de streaming, o VLC.

&emsp;&emsp;Depois de ter ido a esse congresso que surgiu a ideia de passar contúdos com vídeos, os quais os alunos poderiam ter acesso depois, além de poder compartilhar uma de suas paixões que antes era quase impossível, agora Caius conseguiria passar em aula vídeos de peças relacionadas ao conteúdo ministrado. Dessa maneira, sentiu-se orgulhoso de que com esse novo aprendizado conseguiu, por intermédio do VLC, lecionar com mais qualidade e interatividade, além de realizar um sonho.
</br>
</br>

### Musica entre amigos 

&emsp;&emsp;Em sua faculdade, [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf), é muito popular pelo seu vasto conhecimento na área musical, sempre que há uma reunião de amigos da faculdade é o próprio Marcus que fica responsável por escolher as músicas que irão tocar na noite. Porém quando Marcus não está presente a reunião não é a mesma, pois eles não sabem os nomes das músicas nem quais eram as versões das músicas que deviam ser escolhidas. 

&emsp;&emsp;Como o jovem estudante de música gosta muito de seus amigos, começou a procurar soluções que pudessem resolver e como gostaria de atender a todos estava a procura de algo que fosse gratuito para que ninguém tivesse problema. Foi então, que um colega de classe o recomendou o VLC para que ele conseguisse montar playlist das músicas e, dessa maneira, quando ele não estivesse presente, bastaria alguem ter acesso a playlist criada pelo Marcus, que a festa estaria salva.

&emsp;&emsp;De primeira mão Marcus ficou receoso de utilizar um aplicativo, ao qual nunca tinha ouvido falar, mas quando começou a usar percebeu a que esse aplicativo poderia ajudá-lo bastante, já que iria trazer versatilidade, como, juntar músicas parecidas em uma playlist e quando seus amigos com aquele gosto musical quisessem poderia acessar e desfrutar de boas músicas que foram reunidas por alguém que tem conhecimento no assunto.
</br>
</br>

### Lembranças 

&emsp;&emsp;[Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) uma médica aposentada de 72 anos, que cuida de seus netos e acabou de perder o marido para o cancer, ficou muito abalada, mas tentava não transparencer para que seus netos não ficassem tristes e seguissem tendo uma vida feliz. Após um tempo a médica já não conseguia escoder sua tristeza e sempre acabava a chorar quando fazia algo que lembrasse dele.

&emsp;&emsp;Os filhos de Cordelia perceberam o que estava acontecendo e perceberam que uma das atividades que ela mais gostava de fazer era relembrar dos velhos momentos com seu esposo folheando antigos álbuns. Porém ela sempre acabava olhando para os CDs e vídeos de viagens e do dia de seu casamento, mas ela não conseguia mais reproduzí-los, pois seu aparelho não funcionava mais e não conseguia encontrar onde comprar outro.

&emsp;&emsp;Percebendo a situação em que sua mãe se encontrava resolveram apresentá-la à um aplicativo chamado VLC, a qual proposta é um mídia de streaming, que poderia resolver a questão dos vídeos. Então eles se juntaram e apresentaram e ensinaram a ela como usar. Cordelia ficou extremamente feliz com o que acabava de descobrir. Depois que começou a utilizar o VLC sua vida mudou, pois com o aplicativo conseguia matar a saudade de seu falecido marido e dava forças para ela continuar a viver e dar o melhor de si.
</br>
</br>

## Requisitos elicitados

&emsp;&emsp;Os requisitos identificados com o storytelling seguem a seguir na Tabela 1:

**Legenda:**

- ST: Requisitos de <span>_Storytelling_</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>

| Identificador | Descrição                                                                          | Tipo | Implementado | Persona |
| ------------- | ---------------------------------------------------------------------------------- | ---- | ------------ | ------- |
|       ST01    |   Eu, como usuário, gostaria de reproduzir vídeos.                                 |  RF  | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST02          | Eu, como usuário, gostaria de reproduzir vídeos sem internet.                      | RF   | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST03          | Eu, como usuário, gostaria de navegar pelos vídeos de meu dispositivo.             | RF   | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST04          | Eu, como usuário, gostaria de gerar legendas, automaticamente, para meu vídeo.     | RF   | Não          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST05          | Eu, como usuário, gostaria de mudar a velocidade de reprodução.                    | RF   | Sim          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST06          | Eu, como usuário, gostaria de realizar edições ao meu vídeo.                       | RF   | Não          | [Caius Lucius e Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST07          | Eu, como usuário, gostaria de uma interface acessível com contraste de cor.        | RNF  | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST08          | Eu, como usuário, gostaria de organizar meu vídeos.                                | RF   | Sim          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST09          | Eu, como usuário, gostaria de salvar meus vídeos para vê-los em outros dispositivos. | RF | Não          | [Caius Lucius e Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST10          | Eu, como usuário, gostaria de realizar registro/login em uma conta.                | RF   | Não          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST11          | Eu, como usuário, gostaria de compartilhar os vídeos.                              | RF   | Sim          | [Caius Lucius e Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST12          | Eu, como usuário, gostaria de ouvir músicas.                                       | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST13          | Eu, como usuário, gostaria de criar playlists.                                     | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST14          | Eu, como usuário, gostaria de ajustar a qualidade do áudio.                        | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST15          | Eu, como usuário, gostaria de poder ver vídeos/áudios de diferentes formatos.      | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST16          | Eu, como usuário, gostaria de que meus vídeos estejam em segurança.                | RNF   | Sim          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST17          | Eu, como usuário, gostaria de que o aplicativo tenha suporte ao usuário.           | RF   | Não          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST18          | Eu, como usuário, gostaria de que o aplicativo tenha tutorial.                     | RF   | Sim          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST19          | Eu, como usuário, gostaria de que o aplicativo tenha acessibilidade.               | RF   | Não          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |

<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados com o Storytelling (Fonte: autor, 2023).</p>
</div>

### Gravação da elicitação

&emsp;&emsp;Para visualizar a gravação, em íntegra da reunião na qual foram elicitados os requisitos anteriores:
<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/JnVHmNPcqLY" title="Entrevista 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
<div align="center">
<p> <b>Vídeo 1</b>: Elicitação requisitos 1 (Fonte: Grupo. 2023).</p>
</div>

## Conclusão 

&emsp;&emsp;A partir da análise do artefato "StoryTelling", foi percebido algumas divergência com o conceito de StoryTelling apresentado nos slides da [aula 07](https://aprender3.unb.br/pluginfile.php/2523073/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf) da professora Milene Serrano, em que ela comenta que o StoryTelling deve ser realizado a partir da utilização de histórias em um grupo ou organizações, como um método de comunicação para que os envolvidos possam compartilhar conhecimento. Dessa forma, o condutor do método deve inspiram e motivam os participantes através de linguagens mais cotidianas, criando entretenimento durante o processo de construção do conhecimento dos participantes. Assim, os participantes são estimulados a narrar histórias relacionadascom os fatos. cujo conhecimento se quer elicitar. As histórias obtidas são compartilhadas com o grupo de pessoas envolvidos, o que resulta em compartilhamento de conhecimentos, agregação de novos conhecimentos e, por fim, em aprendizado(slide da professora Milene). </br> </br>

&emsp;&emsp;Dessa forma, percebemos que o método utilizado neste documento é mais semelhante ao método de elicitação "Encenação", em que um desenvolvedor entra no presonagem e encena como se fosse uma persona. Assim, o artefato em questão deveria conter as história que foram passadas ao grupo, além de conter uma gravação do método sendo aplicado para que, dessa maneira, houvesse a validação das história por outros integrantes o que agregaria valor na coleta de informações, as quais constumam ser mais autênticas e confiáveis, pois são formados por diferentes pontos de vista. Para que só então os requisitos fossem elicitados.</br> </br>

&emsp;&emsp;De maneira mais geral, para que o artefato obtivesse sucesso em sua realização faltou a interação com os usuários, fornecendo e estimulando que eles narrasem histórias relacionadas com os fatos para serem mais autênticas e confiáveis. E, por fim, realizar a elicitação dos requisitos a partir das histórias.

</div>

## Bibliografia

[1] Santos, V. G., Daher N., UTILIZAÇÃO DE STORYTELLING COMO FERRAMENTA DE AQUISIÇÃO DE REQUISITOS EM PROCESSO DE DESENVOLVIMENTO DE SOFTWARE APOIADOS EM MODELOS ÁGEIS: O USO APOIADO NO EXTREME PROGRAMMING, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH
</br>

[2] Storytelling do Grupo MedSUS de 2021/2. Disponível em: <https://requisitos-de-software.github.io/2021.2-MedSUS/>. Acesso em: 26 de abril de 2023.

[3] - SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523360/mod_resource/content/33/Plano_de_Ensino%20FIHC%20202301%20Turma%202.pdf>. Acesso em: 04 jul. 2023.



## Histórico de Versão

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| 26/04/2023 | `1.0`  | Criação do documento | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa) | 30/04/2023 | [Larissa Gomes](https://github.com/larigs) |
| 30/04/2023 | `1.1`  | Elicitação de requisitos | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa)  | 01/05/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |
| 24/06/2023 | `2.0` | Realizando correções no artefato | [Igor Penha](https://github.com/igorpenhaa)  | 26/06/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |
| 04/07/2023 | `2.1` | Adicionando conclusão com explicação de como o artefato deveria ter sido realizado | [Igor Penha](https://github.com/igorpenhaa)  | 04/07/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |


</div>
