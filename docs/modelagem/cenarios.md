# Cenários

## Introdução

<p align="justify"> Os cenários são descrições extremamente detalhadas do ambiente e da interação do usuário com a aplicação. Segundo Carroll, a propriedade que melhor define um cenário é o fato do mesmo projetar uma descrição concreta de uma atividade em que o usuário se engaja no momento em que está realizando uma tarefa específica. Sob essa ótica, essa técnica é utilizada para descrever situações de uso, que permitem elicitar comportamentos e cenários onde os usuários passarão. Dessa forma, é uma estratégia que elicita a parte comportamental do software. Além de que os cenários não são apenas poderosos, também são uma ferramenta importante no processo geral de design porque representam um investimento de custo e tempo menor em comparação com os protótipos. </p>

## Metodologia

<p align="justify">Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste artefato será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2]. Dessa maneira, para a padronização e guia na construção dos cenários criamos um modelo a ser seguido, que está representado na _Tabela 1_.</p>


### **Título: identifica o cenário.**

| Item      | Descrição |
| --------- | --------- |
| Objetivo  | Estabelece a finalidade de um cenário. O cenário deve descrever de que modo este objetivo deve ser alcançado. |
| Contexto  | Descreve o estado inicial de um cenário, suas précondições, o local (físico) e tempo. |
| Atores    | Pessoas ou estruturas organizacionais que tem um papel no cenário. |
| Recursos  | Identifica os objetos passivos com os quais lidam os atores. |
| Episódios | Cada episódio representa uma ação realizada por um ator onde participam outros atores utilizando recursos disponíveis. |
| Exceção   | É o tratamento para uma situação excepcional ou de erro.|

<figcaption align="center">Tabela 1: Descrição dos itens dos cenários (Fonte: Penha, Igor 2023).</figcaption>

## Cenários

<p align="justify">As tabelas a seguir referem-se aos cenários desenvolvidos a partir de alguns requisitos funcionais priorizados como "Requisitos de Alta Prioridade", a partir do método _First Things First_.</p>

### C01 - Suporte ao usuário Android.

| Item      | Descrição  |
| :-------: | :--------- |
| Objetivo  | Utilizar o suporte ao usuário do aplicativo VLC |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado na versão android. |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário está com dúvidas em utilizar determinas funções que o aplicativo fornece<br>Usuário quer esclarecer suas dúvidas<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de _More_(...)<br>Usuário clica em _ABOUT_(ⓘ), canto superior direito<br>Usuário clica em _Feedback forum_ |
| Exceção   | Smartphone descarregado<br>Perda de conexão com a internet |

<figcaption align="center">Tabela 2: Cenário 1 (Fonte: RIBEIRO, Bruno; PENHA, Igor 2023).</figcaption>

---

### C02 - Suporte ao usuário IOS.

| Item      | Descrição  |
| :-------: | :--------- |
| Objetivo  | Utilizar o suporte ao usuário do aplicativo VLC |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado na versão IOS. |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário está com dúvidas em utilizar determinas funções que o aplicativo fornece<br>Usuário quer esclarecer suas dúvidas<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de Configurações(⚙)<br>Usuário clica em Sobre, canto superior esquerdo<br>Usuário clica em Suporte ao usuário |
| Exceção   | Smartphone descarregado<br>Perda de conexão com a internet |

<figcaption align="center">Tabela 2: Cenário 1 (Fonte: RIBEIRO, Bruno; PENHA, Igor 2023).</figcaption>

---

### C03 - Privacidade do usuário e coleta de dados invasiva(REFAZER)

| Item      | Descrição |
| :-------: | :--------- |
| Objetivo  | Entrar deseja dificultar o acesso de outras pessoas ao seu aplicativo |
| Contexto  | Local: lugares públicos e privados<br>Tempo: durante o dia e/ou noite<br>Pré-condições: ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone |
| Episódios | Usuário está em horário livre<br>Usuário deseja que outras pessoas não tenham acesso aos seus conteúdos dentro do aplicativo<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de Configurações(⚙)<br>Usuário vai à área de privacidade do aplicativo<br>Usuário encontra e clica em "Fórum de suporte"<br>Usuário é redirecionado para o site do fórum |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o link para "Fórum de suporte" |

<figcaption align="center">Tabela 4: Cenário 3 (Fonte: Autores, 2023).</figcaption>

---

### C04 - Interface intuitiva e fácil de usar.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  |  |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios |  |
| Exceção   |  |

<figcaption align="center">Tabela 5: Cenário 4 (Fonte: Autores, 2023).</figcaption>

---

### C05 - facilidade de instalar e usar.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  |  |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios |  |
| Exceção   |  |

<figcaption align="center">Tabela 6: Cenário 5 (Fonte: Autores, 2023).</figcaption>

---

### C06 - Enxergando detalhes.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Dar zoom em um vídeo em reprodução |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet ou vídeo baixado, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet ou vídeo baixado |
| Episódios | Usuário está com tempo livre<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário assiste um vídeo<br>Usuário sente dificuldade em enxergar um detalhe no vídeo<br>Usuário deseja aumentar a imagem do vídeo<br>Usuário faz um formato de pinça com os dedos polegar e indicador<br>Usuário em movimento de abertura deslisa os dedos sobre a tela<br>Usuário da zoom no vídeo |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet durante o _download_ do vídeo |

<figcaption align="center">Tabela 7: Cenário 6 (Fonte: RIBEIRO, Bruno; PENHA, Igor 2023).</figcaption>

---

### C07 - Legendas nos vídeos.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Legendar um vídeo |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet ou ter vídeos salvos na memória do celular, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário clica no ícone _Browse_<br>Usuário seleciona o vídeo desejado<br>Usuário clica no ícone de legendas<br>Usuário seleciona o idioma desejado ou o texto a ser adicionado |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma |

<figcaption align="center">Tabela 8: Cenário 7 (Fonte: RIBEIRO, Bruno 2023).</figcaption>

---

### C08 - Deve ser possível personalizar a aparência da interface do usuário. (no ios tem funcao escuro e claro)

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Mudar o contraste de cor do aplicativo entre escuro e claro |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: ter o aplicativo instalado |
| Atores    | 
| Episódios | Usuário está assistindo um vídeo no app<br>Usuário sente um desconforto nos olhos devido a luz branca<br>Usuário clica no ícone _More_(...)<br>Usuário clica no ícone _SETTINGS_(⚙)<br>Usuário clica no ícone _Interface_<br>Usuário clica no ícone _DayNight mode_<br>Usuário seleciona o tema de contraste de cor desejado |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma |

<figcaption align="center">Tabela 9: Cenário 8 (Fonte: RIBEIRO, Bruno 2023).</figcaption>

---

### C09 - Registro do usuário

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Criar uma conta para o usuário |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário tem vontade de criar uma conta no VLC para conseguir acessar seus dados do aplicativo em qualquer dispositivo e qualquer lugar<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário tem a possibilidade de login ou de se registrar<br>Usuário clica em registrar-se<br>Usuário informa o e-mail que deseja utilizar como login<br>Usuário escolhe uma senha para o aplicativo<br>Usuário confirma a senha<br>Usuário poderá logar em qualquer dispositivo|
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Usuário não encontra o registrar-se<br>Usuário digita a confirmação de senha errada |

<figcaption align="center">Tabela 10: Cenário 9 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C10 - Só acessa com a senha.

| Item      | Descrição     |
| :-------: | :------------ |
| Objetivo  | Apenas quem souber a senha terá acesso as funcionalidade e vídeos dentro do aplicativo |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado |
| Atores    | Usuário       |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário está em horário livre<br>Usuário quer que apenas pessoas restritas tenham acesso ao aplicativo mesmo tendo acesso ao seu smartphone<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de Configurações(⚙)<br>Usuário vai a aba de privacidade<br>Usuário clica em senha de bloqueio<br>Usuário escolhe uma senha para o aplicativo<br>Usuário confirma a senha<br>Usuário agora quando abrir o aplicativo terá de digitar a senha |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Usuário não encontra o ícone de configurações(⚙)<br>Usuário não encontra aba de privacidade<br>Usuário digita a confirmação de senha errada |

<figcaption align="center">Tabela 11: Cenário 10 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C11 - Adicionar filtro ao vídeo.

| Item      |      Descrição     |
| :-------: | :------------------ |
| Objetivo  | Adicionar filtros ao vídeo de interesse |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet ou vídeo baixado, ter o aplicativo instalado |
| Atores    | Usuário                                 |
| Recursos  | Smartphone<br>Internet ou vídeo baixado |
| Episódios | Usuário está em horário livre<br>Usuário não gosta de como está seu vídeo<br>Usuário quer adicionar um filtro ao seu vídeo<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário adicionar e abre seu vídeo no aplicativo<br>Usuário clica no ícone dos 3 pontinhos<br>Usuário clica em filtros do vídeo<br>Usuário escolhe quais filtros deseja alterar para obter o resultado de desejo<br>Usuário clica em feito<br>Usuário obtem seu vídeo com filtros. |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet durante o _download_ do vídeo<br>Usuário não encontra o ícone de 3 pontinhos<br>Usuário não encontra filtros do vídeo |

<figcaption align="center">Tabela 12: Cenário 11 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C12 - Mudar velocidade de reprodução

| Item      | Descrição                  |
| :-------: | :------------------------- |
| Objetivo  | Poder escolher a velocidade de reprodução do vídeo |
| Contexto  | Local: Em casa <br> Tempo: durante a aula<br> Pré-condições: acesso à internet ou já ter o vídeo baixado, ter o aplicativo instalado |
| Atores    | Usuário           |
| Recursos  | Smartphone<br>Internet ou vídeo baixado no smartphone |
| Episódios | Usuário está com pouco tempo<br>Usuário quer aumenta a velocidade de reprodução de um vídeo <br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de Configurações(⚙)<br>Usuário encontra a área de genéricos<br>Usuário seleciona velocidade de reprodução padrão<br>Usuário escolhe qual será a velocidade padrão de seus vídeos daqui em diante |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Problemas com o _download_ do vídeo<br>Usuário não encontra o ícone de configurações(⚙)<br>Usuário não encontra a área de genéricos<br> Usuário não encontrar velocidade de reprodução padrão |

<figcaption align="center">Tabela 13: Cenário 12 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C13 - Compartilhamento de vídeos

|   Item    |     Descrição     |
| :-------: | :---------------- |
| Objetivo  | Compartilhar um vídeo assistido |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet ou ter o vídeo baixadp, ter o aplicativo instalado   |
| Atores    | Usuário                         |
| Recursos  | Smartphone<br>Internet ou vídeo já baixado |
| Episódios | Usuário está em horário livre<br>Usuário quer assistir um vídeo<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário assiste um vídeo<br>Usuário deseja compartilhar o vídeo<br>Usuário sai do vídeo<br>Usuário clica no ícone de três pontinhos no canto superior do vídeo de interesse<br>Usuário clica na função de compartilhar<br>Usuário escolhe onde quer enviar o vídeo<br>Usuário compartilha vídeo |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet enquanto baixava o vídeo<br>Usuário não encontra o ícone do três pontinhos<br>Usuário clica nos 3 botões dentro do vídeo<br>Usuário não encontra o botão para compartilhar o vídeo |

<figcaption align="center">Tabela 14: Cenário 13 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C14 - Parar reprodução depois de uma quantidade de tempo

| Item      | Descrição       |
| :-------: | :-------------- |
| Objetivo  | Depois de um determinado tempo parar a reprodução |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet ou vídeo já baixado, ter o aplicativo instalado                     |
| Atores    | Usuário         |
| Recursos  | Smartphone<br>Internet ou vídeo baixado no Smartphone |
| Episódios | Usuário quer escutar um aúdio antes de dormir<br>Usuário tem receio de dormir sem sair do áudio e ficar reproduzindo por muito tempo<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário abre o áudio de desejo no aplicativo<br>Usuário clica no ícone dos 3 pontinho na parte inferior esqueda<br>Usuário clica em cronometro para dormir<br>Usuário seleciona o tempo que deseja que a reprodução pare<br> Usuário volta a escutar o áudio sem preocupações |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet quando não tem o áudio baixado<br>Usuário não encontra o vídeo no celular<br>Usuário não encontra os 3 botões<br> Usuário não encontra o cronometro |

<figcaption align="center">Tabela 15: Cenário 14 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C15 - Adicionar legenda aos vídeos

| Item      |  Descrição  |
| :-------: | :---------- |
| Objetivo  | Ao assistir um vídeo conseguir adicionar legendas |
| Contexto  | Local: em sala<br>Tempo: durante o dia<br>Pré-condições: acesso à internet ou vídeo já baixado, ter o aplicativo instalado                 |
| Atores    | Professores e/ou alunos   |
| Recursos  | Smartphone<br>Internet ou vídeo baixado |
| Episódios | Professor em sala pede para cada aluno assistir um vídeo<br>Alunos recebem e baixam o vídeo<br>Alunos pegam o celular<br>Alunos abrem o aplicativo<br>Alunos iniciam a reprodução<br>Alunos não conseguem entender o que é falado no vídeo<br>Alunos clicam no botão com ícone de chat<br>Alunos escolhem e seleciona uma das linguagens, dentre as disponíveis<br>Alunos baixam a legenda<br>Alunos assistem o vídeo com legenda |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet durante o _download_ do vídeo<br>Aluno não encontra o ícone de chat<br>Alunos não acham a legenda desejada disponível |

<figcaption align="center">Tabela 16: Cenário 15 (Fonte: PENHA, Igor 2023).</figcaption>

---

## Referências

[1] Cenários - Rastreamento de Cenários. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 10 de maio de 2023.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 10 de maio de 2023.

## Histórico de versão

| Versão |    Data    |            Descrição           |      Autor      |     Revisor      |
| :----: | :--------: | :----------------------------: | :-------------: | :--------------: |
|  1.0   | 10/05/2023 | Início do artefato de cenários |   [Igor Penha](github.com/igorpenhaa) e [Bruno Ribeiro](github.com/brunoriibeiro)  |   [Lucas Gobbi](github.com/lucasbergholz)  |
