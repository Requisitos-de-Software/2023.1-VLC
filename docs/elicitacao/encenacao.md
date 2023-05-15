<div class="body">

# Encenação

## Introdução

<div align="justify">A encenação é uma técnica de elicitação de requisitos que tem como objetivo principal obter uma compreensão mais profunda das necessidades e expectativas dos usuários em relação a um sistema ou software. Também conhecida como role-playing, essa abordagem envolve a criação de cenários fictícios ou simulações da interação entre os usuários e o sistema.
</div>

<div align="justify">Essa técnica permite que os analistas de requisitos obtenham informações detalhadas sobre como o sistema deve funcionar na prática, levando em consideração as diferentes perspectivas dos usuários envolvidos. Ao atuar em situações simuladas, os participantes podem expressar suas necessidades e preferências de uma maneira mais concreta e tangível, facilitando a identificação de requisitos essenciais.
</div>
</br>

## Metodologia

<div align="justify">Para o desenvolvimento e realização da encenação, foram utilizadas as personas desenvolvidas e a observação de objetivos, sentimentos e tarefas dos usuários dentro de suas histórias e contexto. Por fim, elencamos alguns dos requisitos.
</div>
</br>

## Execução da Encenação


</br>

### Transmissão de conhecimento 

<div align="justify"> <a href="https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf">Caius Lucius</a> é professor de literatura para ensino médio, que sempre teve o sonho e objetivo de vida compartilhar com os mais novos, seus aprendizes, o máximo de conhecimento que conseguisse. Porém, depois de anos lecionando, começou a sentir que o que ele fazia ainda não era o bastante, Caius queria fazer mais por seu queridos alunos, mas não sabia como.
</div>

<div align="justify">Certo dia, decidiu ir à um congresso de ensino, onde vários palestrantes falavam sobre técnicas de ensino e como essas técnicas poderia ser ministradas para um melhor desempenho no aprendizado dos alunos. Caius ficou encantado, pricipalmente, com uma técnica que utilizava um software livre portátil de mídia de streaming, o VLC.
</div>

<div align="justify">Depois de ter ido a esse congresso que surgiu a ideia de passar contúdos com vídeos, os quais os alunos poderiam ter acesso depois, além de poder compartilhar uma de suas paixões que antes era quase impossível, agora Caius conseguiria passar em aula vídeos de peças relacionadas ao conteúdo ministrado. Dessa maneira, sentiu-se orgulhoso de que com esse novo aprendizado conseguiu, por intermédio do VLC, lecionar com mais qualidade e interatividade, além de realizar um sonho.
</div>
</br>
</br>

### Musica entre amigos 

<div align="justify">Em sua faculdade, <a href="https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf">Marcus Androcius</a>, é muito popular pelo seu vasto conhecimento na área musical, sempre que há uma reunião de amigos da faculdade é o próprio Marcus que fica responsável por escolher as músicas que irão tocar na noite. Porém quando Marcus não está presente a reunião não é a mesma, pois eles não sabem os nomes das músicas nem quais eram as versões das músicas que deviam ser escolhidas. 
</div>

<div align="justify">Como o jovem estudante de música gosta muito de seus amigos, começou a procurar soluções que pudessem resolver e como gostaria de atender a todos estava a procura de algo que fosse gratuito para que ninguém tivesse problema. Foi então, que um colega de classe o recomendou o VLC para que ele conseguisse montar playlist das músicas e, dessa maneira, quando ele não estivesse presente, bastaria alguem ter acesso a playlist criada pelo Marcus, que a festa estaria salva.
</div>

<div align="justify">De primeira mão Marcus ficou receoso de utilizar um aplicativo, ao qual nunca tinha ouvido falar, mas quando começou a usar percebeu a que esse aplicativo poderia ajudá-lo bastante, já que iria trazer versatilidade, como, juntar músicas parecidas em uma playlist e quando seus amigos com aquele gosto musical quisessem poderia acessar e desfrutar de boas músicas que foram reunidas por alguém que tem conhecimento no assunto.
</div>
</br>
</br>

### Lembranças 

<div align="justify"><a href="https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf">Cordelia Macbeth</a> uma médica aposentada de 72 anos, que cuida de seus netos e acabou de perder o marido para o cancer, ficou muito abalada, mas tentava não transparencer para que seus netos não ficassem tristes e seguissem tendo uma vida feliz. Após um tempo a médica já não conseguia escoder sua tristeza e sempre acabava a chorar quando fazia algo que lembrasse dele.
</div>

<div align="justify">Os filhos de Cordelia perceberam o que estava acontecendo e perceberam que uma das atividades que ela mais gostava de fazer era relembrar dos velhos momentos com seu esposo folheando antigos álbuns. Porém ela sempre acabava olhando para os CDs e vídeos de viagens e do dia de seu casamento, mas ela não conseguia mais reproduzí-los, pois seu aparelho não funcionava mais e não conseguia encontrar onde comprar outro.
</div>

<div align="justify">Percebendo a situação em que sua mãe se encontrava resolveram apresentá-la à um aplicativo chamado VLC, a qual proposta é um mídia de streaming, que poderia resolver a questão dos vídeos. Então eles se juntaram e apresentaram e ensinaram a ela como usar. Cordelia ficou extremamente feliz com o que acabava de descobrir. Depois que começou a utilizar o VLC sua vida mudou, pois com o aplicativo conseguia matar a saudade de seu falecido marido e dava forças para ela continuar a viver e dar o melhor de si.
</div>
</br>
</br>

## Requisitos elicitados

<div align="justify">Os requisitos identificados com o storytelling seguem a seguir na Tabela 1:
</div>

**Legenda:**

- ST: Requisitos de <span>_Storytelling_</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>

| Identificador | Descrição                                                                          | Tipo | Implementado | Persona |
| ------------- | ---------------------------------------------------------------------------------- | ---- | ------------ | ------- |
|       ST01    |   Reproduzir vídeos.                                 |  RF  | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST02          | Reproduzir vídeos sem internet.                      | RF   | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST03          | Navegar pelos vídeos do dispositivo.             | RF   | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST04          | Gerar legendas, automaticamente, para meu vídeo.     | RF   | Não          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST05          | Mudar a velocidade de reprodução.                    | RF   | Sim          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST06          | Editar vídeos.                       | RF   | Não          | [Caius Lucius e Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST07          | Interface de fácil navegação.                    | RNF  | Sim          | [Todas](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST08          | Organizar vídeos.                                | RF   | Sim          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST09          | Salvar vídeos para vê-los em outros dispositivos. | RF | Não          | [Caius Lucius e Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST10          | Realizar registro/login em uma conta.                | RF   | Não          | [Caius Lucius](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST11          | Compartilhar os vídeos.                              | RF   | Sim          | [Caius Lucius e Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST12          | Ouvir músicas.                                       | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST13          | Criar playlists.                                     | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST14          | Ajustar a qualidade do audio.                    | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST15          | Ver vídeos/áudios de diferentes formatos.      | RF   | Sim          | [Marcus Andronicus](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST16          | Vídeos em segurança.                | RNF   | Sim          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST17          | Aplicativo com suporte ao usuário.           | RF   | Não          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST18          | Aplicativo com tutorial.                     | RF   | Sim          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |
| ST19          | Aplicativo com acessibilidade.               | RF   | Não          | [Cordelia Macbeth](https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/elicitacao/personas.pdf) |

<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados com a Encenação (Fonte: autor, 2023).</p>
</div>

### Gravação da Encenação

<div align="justify">Para visualizar a gravação, em íntegra da reunião na qual foram elicitados os requisitos anteriores, clique [aqui](https://youtu.be/JnVHmNPcqLY).
</div>
</br>

## Bibliografia

[1] VASQUEZ, Carlos E; SIVOES, Guilherme S. Engenharia de Requisitos - Software orientado ao negócio.

## Histórico de Versão

| Versão | Data       | Descrição                    | Autor(es)                  |  Revisor(es)  | Data de revisão |
| ------ | ---------- | ---------------------------- | -------------------------- | ------------- |-----------------|
| `1.0`  | 26/04/2023 | Criação do documento inicial |[Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa) | [Larissa Gomes](https://github.com/larigs) | 30/04/2023 |
| `1.1`  | 30/04/2023 | Elicitação de requisitos     | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Lucas Gobbi](https://github.com/LucasBergholz) | [Igor Penha](https://github.com/igorpenhaa) | 01/04/2023 |
| `1.2`  | 15/05/2023 | Transfomação em encenação | [Rafael Bosi](https://github.com/StrangeUnit28) | [Lucas Gobbi](https://github.com/) | 16/05/2023 |

</div>
