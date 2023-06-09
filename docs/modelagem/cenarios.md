# Cenários

## Introdução

<p align="justify"> Os cenários são descrições extremamente detalhadas do ambiente e da interação do usuário com a aplicação. Segundo Carroll, a propriedade que melhor define um cenário é o fato do mesmo projetar uma descrição concreta de uma atividade em que o usuário se engaja no momento em que está realizando uma tarefa específica. Sob essa ótica, essa técnica é utilizada para descrever situações de uso, que permitem elicitar comportamentos e cenários onde os usuários passarão. Dessa forma, é uma estratégia que elicita a parte comportamental do software. Além de que os cenários não são apenas poderosos, também são uma ferramenta importante no processo geral de design porque representam um investimento de custo e tempo menor em comparação com os protótipos. </p>

## Metodologia

<p align="justify">Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste artefato será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2]. Dessa maneira, para a padronização e guia na construção dos cenários criamos um modelo a ser seguido, que está representado na Tabela 1.</p>


### **Título: identifica o cenário.**

| Item      | Descrição |
| --------- | --------- |
| Objetivo  | Estabelece a finalidade de um cenário. O cenário deve descrever de que modo este objetivo deve ser alcançado. |
| Contexto  | Descreve o estado inicial de um cenário, suas précondições, o local (físico) e tempo. |
| Atores    | Pessoas ou estruturas organizacionais que tem um papel no cenário. |
| Recursos  | Identifica os objetos passivos com os quais lidam os atores. |
| Episódios | Cada episódio representa uma ação realizada por um ator onde participam outros atores utilizando recursos disponíveis. |
| Restrições | Possíveis impedimentos às ações dos usuários     |
| Exceção   | É o tratamento para uma situação excepcional ou de erro.|

<figcaption align="center">Tabela 1: Descrição dos itens dos cenários (Fonte: Penha, Igor 2023).</figcaption>

## Cenários

<p align="justify">As tabelas de 2 a 16 a seguir referem-se aos cenários desenvolvidos a partir de alguns requisitos funcionais priorizados como "Requisitos de Alta Prioridade", a partir do método _First Things First_.</p>

### C01 - Suporte ao usuário Android.

| Item      | Descrição  |
| :-------: | :--------- |
| Objetivo  | Utilizar o suporte ao usuário do aplicativo VLC |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado na versão android. |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário está com dúvidas em utilizar determinas funções que o aplicativo fornece<br>Usuário quer esclarecer suas dúvidas<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de _More_(...)<br>Usuário clica em _ABOUT_(ⓘ), canto superior direito<br>Usuário clica em _Feedback forum_ |
| Restrições | Fluxo de navegação não intuitivo     |
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
| Restrições | Fluxo de navegação não intuitivo     |
| Exceção   | Smartphone descarregado<br>Perda de conexão com a internet |

<figcaption align="center">Tabela 2: Cenário 1 (Fonte: RIBEIRO, Bruno; PENHA, Igor 2023).</figcaption>

---

### C03 - Informações sobre o projeto

| Item      | Descrição |
| :-------: | :--------- |
| Objetivo  | Encontrar informações sobre o projeto e a aplicação |
| Contexto  | Local: lugares públicos e privados<br>Tempo: durante o dia e/ou noite<br>Pré-condições: ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone |
| Episódios | Usuário está em horário livre<br>Usuário deseja encontrar informações sobre o projeto da aplicação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de _More_(..)<br>Usuário clica no ícone _ABOUT_(ⓘ)<br>Usuário escolhe quais informações deseja ver sobre o projeto dentre as listadas |
| Restrições | Fluxo de navegação não intuitivo     |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet |

<figcaption align="center">Tabela 4: Cenário 3 (Fonte: RIBEIRO, Bruno 2023).</figcaption>

---

### C04 - Relatar um bug do app.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Enviar descrição de bug do aplicativo |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário identifica uma irregularidade na aplicação<br>Usuário deseja reportar um bug<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário clica no ícone de Configurações(⚙)<br>Usuário rola a página e encontra a área de fale conosco<br>Usuário clica em "Relatar um bug"<br>Usuário descreve o bug detalhadamente |
| Restrições | Fluxo de navegação não intuitivo, não ter email cadastrado. |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Usuário não encontra o ícone de Configurações(⚙)<br>Usuário não encontra a área de fale conosco<br>Usuário não encontra o local para relatar um bug |

<figcaption align="center">Tabela 5: Cenário 4 (Fonte: PENHA, Igor 2023).</figcaption>

---

### C05 - Criando playlists.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Criar uma nova playlist a partir de um video em execução |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet ou ter o video previamente na memória do dispositivo, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário está vendo um video<br>Usuário clica no no ícone (...) no canto inferior direito<br>Usuário clica em _Save Playlist_<br>Usuário escreve um nome para sua nova playlist<br>Usuário tem uma playlist com o video desejado criada |
| Restrições | Não se aplica    |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet |

<figcaption align="center">Tabela 6: Cenário 5 (Fonte: RIBEIRO, Bruno 2023).</figcaption>

---

### C06 - Enxergando detalhes.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Dar zoom em um vídeo em reprodução |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet ou vídeo baixado, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet ou vídeo baixado |
| Episódios | Usuário está com tempo livre<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário assiste um vídeo<br>Usuário sente dificuldade em enxergar um detalhe no vídeo<br>Usuário deseja aumentar a imagem do vídeo<br>Usuário faz um formato de pinça com os dedos polegar e indicador<br>Usuário em movimento de abertura deslisa os dedos sobre a tela<br>Usuário da zoom no vídeo |
| Restrições | Falta de explicação sobre como a ferramenta funciona |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet durante o _download_ do vídeo |

<figcaption align="center">Tabela 7: Cenário 6 (Fonte: RIBEIRO, Bruno; PENHA, Igor 2023).</figcaption>

---

### C07 - Garantia de segurança mínima.

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | O usuário tem garantia de que seus dados não correm perigo por parte do uso do app |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet ou ter vídeos salvos na memória do celular, ter o aplicativo instalado |
| Atores    | Usuário |
| Recursos  | Smartphone<br>Internet |
| Episódios | Usuário inicia a aplicação pela primeira vez<br>Usuário lê os termos de privacidade e uso do app<br>Usuário concorda com os termos<br>Usuário pode ficar tranquilo que seus dados não serão coletados pelo app |
| Restrições | Fluxo de navegação não intuitivo |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma |

<figcaption align="center">Tabela 8: Cenário 7 (Fonte: RIBEIRO, Bruno 2023).</figcaption>

---

### C08 - Deve ser possível personalizar a aparência da interface do usuário. (no ios tem funcao escuro e claro)

| Item      | Descrição |
| :-------: | :-------- |
| Objetivo  | Mudar o contraste de cor do aplicativo entre escuro e claro |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: ter o aplicativo instalado |
| Atores    | Usuário | 
| Episódios | Usuário está assistindo um vídeo no app<br>Usuário sente um desconforto nos olhos devido a luz branca<br>Usuário clica no ícone _More_(...)<br>Usuário clica no ícone _SETTINGS_(⚙)<br>Usuário clica no ícone _Interface_<br>Usuário clica no ícone _DayNight mode_<br>Usuário seleciona o tema de contraste de cor desejado |
| Restrições | Não se aplica     |
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
| Episódios | Usuário tem vontade de criar uma conta no VLC para conseguir acessar seus dados do aplicativo em qualquer dispositivo e qualquer lugar<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário tem a possibilidade de login ou de se registrar<br>Usuário clica em registrar-se<br>Usuário informa o e-mail que deseja utilizar como login<br>Usuário escolhe uma senha para o aplicativo<br>Usuário confirma a senha<br>Usuário poderá logar em qualquer dispositivo |
| Restrições | Usuário não tem email para cadastrar |
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
| Restrições | Fluxo de navegação não intuitivo, não lembrar a senha    |
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
| Restrições | Não se aplica     |
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
| Restrições | Não se aplica     |
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
| Restrições | Não se aplica     |
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
| Restrições | Fluxo de navegação não intuitivo    |
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
| Restrições | Fluxo de navegação não intuitivo, não ter baixado a extensão   |
| Exceção   | Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet durante o _download_ do vídeo<br>Aluno não encontra o ícone de chat<br>Alunos não acham a legenda desejada disponível |

<figcaption align="center">Tabela 16: Cenário 15 (Fonte: PENHA, Igor 2023).</figcaption>

---

## Referências

[1] Cenários - Rastreamento de Cenários. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 10 de maio de 2023.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 10 de maio de 2023.

## Histórico de Versões
| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 10/05/2023 | `1.0` | Início do artefato de cenários | [Bruno Ribeiro](github.com/BrunoRiibeiro) e [Igor Penha](github.com/igorpenhaa) | 10/05/2023 | [Lucas Gobbi](github.com/LucasBergholz) |

| <p align="center">Data</p> | <p align="center">Versão</p> | <p align="center">Descrição</p> | <p align="center">Autor(es)</p> | <p align="center">Data de revisão</p> | <p align="center">Revisor(es)</p> |
| :--:       | :----: | :-------: | :---: | :-------------: | :-----: |
| 10/05/2023 | `1.0`  | Criação do documento | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa) | 11/05/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |
| 11/05/2023 | `1.1`  | finalização do artefato | [Bruno Ribeiro](https://github.com/BrunoRiibeiro) e [Igor Penha](https://github.com/igorpenhaa)  | 12/05/2023 | [Lucas Gobbi](https://github.com/LucasBergholz) |
| 25/06/2023 | `2.0` | Realizando correções no artefato | [Igor Penha](https://github.com/igorpenhaa)  | 26/06/2023 | [Bruno Ribeiro](https://github.com/brunoriibeiro) |
