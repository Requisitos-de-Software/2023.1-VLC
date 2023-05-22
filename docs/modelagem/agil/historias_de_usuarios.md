# Histórias de Usuário

## Introdução

&emsp;&emsp;Histórias de Usuários são um componente essencial no contexto dos Requisitos de Software. Elas representam uma abordagem centrada no usuário para especificar os itens do [backlog de um projeto](). Diferentemente de uma especificação tradicional, as histórias de usuários são registros concisos que descrevem os requisitos de forma clara e objetiva, focando no "o que" precisa ser alcançado, ao invés de detalhar o "como" será implementado. Essa abordagem promove uma compreensão aprofundada das necessidades e expectativas dos usuários, permitindo que os desenvolvedores construam soluções que realmente atendam às demandas reais. 

&emsp;&emsp;Ao utilizar histórias de usuários, os requisitos são expressos de maneira mais acessível, facilitando a comunicação e a colaboração entre as equipes de desenvolvimento e os stakeholders do projeto. 

## Metodologia

&emsp;&emsp;As histórias de usuário devem ser curtas, detalhadas e específicas. Além disso, seguiram a seguinte estrutura:

- ### Nome

    - **ID:** Identificação da história para futura rastreabilidade (USXX)

    - **Origem:** Requisito do qual a história deriva

    - **Descrição:** "Eu, como **papel**, desejo **o que**"

    - **Motivo:** O porque dessa história

    - **Critérios de Aceitação:**

        - Descrição dos critérios de aceitação 

    - **Válida:** O usuário validou a história

&emsp;&emsp;Para desenvolver as histórias de usuários utilizamos os requisitos elicitados em etapas anteriores que seriam de interesse do usuário, além disso para validar as histórias contamos com um usuário do VLC mídia player.

&emsp;&emsp;O usuário que colaborou com a validação das histórias... 

## Especificação das histórias de usuário

- ### Usar o app em diferentes sistemas

    - **ID:** US01

    - **Origem:** INT06

    - **Descrição:**  Eu , como usuário, desejo utilizar o aplicativo em dispositivos Android e/ou IOS.

    - **Motivo:** Caso eu mude de telefone, quero continuar usando a aplicação.

    - **Critérios de Aceitação:**

        - A aplicação deve funcionar nos sistemas operacionais Android e IOS.

    - **Válida:** -

- ### Segurança de dados

    - **ID:** US02

    - **Origem:** ADD10

    - **Descrição:** Eu, como usuário, desejo o que não corra risco de violação de privacidade e coleta de dados invasiva.

    - **Motivo:** Tenho dados nos quais não quero que sejam compartilhados sem minha autorização.

    - **Critérios de Aceitação:**

        - O aplicativo não deve conter coleta de dados sem permissão; do usuário.

        - Deve ser seguro contra fraudes e violações.

    - **Válida:** -

- ### Receber feedback do vídeo

    - **ID:** US03

    - **Origem:** INT14

    - **Descrição:**  Eu , como usuário, desejo saber quanto tempo do vídeo já foi percorrido.

    - **Motivo:** Eu possa pular para a parte que eu desejar ver.

    - **Critérios de Aceitação:**

        - A opção deve estar presente durante a execução do vídeo;

        - A opção deve estar presente como uma barra de progresso clicável. 

    - **Válida:** -

- ### Mudar o idioma

    - **ID:** US04

    - **Origem:** ADD06

    - **Descrição:**  Eu , como usuário, desejo saber mudar o idioma do aplicativo.

    - **Motivo:** Gostaria de mudar para minha língua nativa.

    - **Critérios de Aceitação:**

        - A opção deve estar presente em configurações;

        - Deve ser possível modificar a qualquer momento, independente de acesso a internet ou não. 

    - **Válida:** -

- ### Reprodução de mídia

    - **ID:** US05

    - **Origem:** ST01

    - **Descrição:** Eu, como usuário, desejo reproduzir meus vídeos.

    - **Motivo:** Quero poder assistir aos vídeos armazenados no meu dispositivo usando o aplicativo VLC.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve fornecer suporte para reprodução de vídeos de diversos formatos, como MP4, AVI, MKV, entre outros;

        - Os vídeos devem ser reproduzidos com qualidade e sem perda de sincronia de áudio e vídeo;

        - O VLC deve oferecer controles de reprodução, como pausar, reproduzir, avançar e retroceder;

        - O usuário deve ser capaz de ajustar o volume durante a reprodução do vídeo;

        - O aplicativo deve permitir que o usuário reproduza vídeos em tela cheia para uma experiência de visualização. 

    - **Válida:** -

- ### Reprodução de mídia sem internet

    - **ID:** US06

    - **Origem:** ST02

    - **Descrição:** Eu, como usuário, gostaria de poder reproduzir vídeos sem precisar de uma conexão com a internet.

    - **Motivo:** Quero poder assistir aos vídeos do meu dispositivo, mesmo quando estou offline, sem depender de uma conexão ativa com a internet.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve suportar a reprodução de vídeos armazenados localmente no dispositivo do usuário, sem a necessidade de uma conexão com a internet;

        - Os vídeos armazenados localmente devem ser facilmente acessíveis e reproduzíveis dentro do próprio aplicativo, sem a necessidade de usar aplicativos ou serviços externos;

        - O aplicativo deve suportar uma ampla variedade de formatos de vídeo populares, garantindo que os vídeos sejam reproduzidos corretamente, mesmo sem acesso à internet;

        - A reprodução de vídeos sem internet deve ser estável e suave, garantindo uma experiência de visualização de alta qualidade.

    - **Válida:** -

- ### Ver o tutorial

    - ID: US07

    - **Origem:** ST18

    - **Descrição:**  Eu , como usuário, desejo ver um tutorial sobre a usabilidade do aplicativo.

    - **Motivo:** Aprender como utilizar o aplicativo.

    - **Critérios de Aceitação:**

        - O tutorial deve aparecer na primeira utilização da aplicação;
        - A opção deve estar presente a qualquer momento na aba de ajuda;
        - O tutorial deve possuir uma linguagem de fácil entendimento. 

    - **Válida:** -

- ### Lista de reprodução

    - **ID:** US08

    - **Origem:** ST03

    - **Descrição:** Eu, como usuário, gostaria de navegar pelos vídeos de meu dispositivo.

    - **Motivo:** Quero poder ver todos os vídeos disponíveis para reprodução em uma lista organizada.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve fornecer uma lista de reprodução que exiba todos os vídeos disponíveis no dispositivo do usuário;

        - A lista de reprodução deve ser organizada e apresentar informações relevantes sobre os vídeos, como título, duração, tamanho do arquivo ou outras informações úteis;

        - O usuário deve ser capaz de navegar pela lista de reprodução, rolando verticalmente e visualizando todos os vídeos disponíveis;

        - Ao selecionar um vídeo na lista de reprodução, o aplicativo deve iniciar a reprodução desse vídeo;

        - Deve haver opções de filtragem e classificação para ajudar o usuário a encontrar vídeos específicos na lista de reprodução.

    - **Válida:** -

- ### Interface amigavel

    - **ID:** US09

    - **Origem:** ST07

    - **Descrição:** Eu, como usuário, gostaria de uma interface de fácil navegação.

    - **Motivo:** Quero poder utilizar o aplicativo sem dificuldades, encontrando rapidamente as opções e recursos que necessito para reproduzir e gerenciar minha mídia.

    - **Critérios de Aceitação:**

        - A interface do aplicativo deve seguir as melhores práticas de design de interface de usuário (UI);

        - A interface deve ser intuitiva e fácil de entender, com uma disposição clara dos elementos e uma estrutura organizada;

        - Os principais recursos e funcionalidades do aplicativo devem ser facilmente acessíveis, através de menus, ícones ou atalhos adequados;

        - Deve haver uma consistência visual e de interação em toda a interface do aplicativo;

        - A interface deve ser responsiva, adaptando-se a diferentes tamanhos de tela e dispositivos.

    - **Válida:** -

- ### Reprodução de músicas

    - **ID:** US10

    - **Origem:** ST12

    - **Descrição:** Eu, como usuário, gostaria de ouvir músicas.

    - **Motivo:** Quero ter a capacidade de reproduzir minhas músicas no mesmo aplicativo, para uma experiência de reprodução de mídia integrada.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve suportar a reprodução de mídias de áudio, como arquivos MP3, WAV, FLAC, entre outros formatos populares.

        - Deve haver uma interface clara e intuitiva para adicionar e selecionar as músicas a serem reproduzidas.

        - O aplicativo deve oferecer controles de reprodução, como reproduzir, pausar, avançar, retroceder e ajustar o volume.

        - O VLC deve suportar a reprodução contínua de músicas, permitindo a criação de listas de reprodução e a reprodução em sequência.

        - O aplicativo deve fornecer informações sobre a música em reprodução, como título, artista, álbum e duração.

    - **Válida:** -

- ### Aba de ajuda

    - **ID:** US11

    - **Origem:** ST17

    - **Descrição:** Eu, como usuário, gostaria de tirar minhas dúvidas sobre o aplicativo dentro dele.

    - **Motivo:** Quero rápido acesso às minhas respostas.

    - **Critérios de Aceitação:**

        - O aplicativo deve possuir botão de ajuda;
        - A aba de ajuda deve possuir dúvidas frequentes e suas respostas;
        - A aba de ajuda deve possuir uma opção de contato direto ao SAC(suporte ao consumidor).

    - **Válida:** -

- ### Ver diferentes formatos de vídeo

    - **ID:** US12

    - **Origem:** ST15

    - **Descrição:** Eu, como usuário, gostaria de tirar ver vídeos de diferentes formatos dentro do aplicativo.

    - **Motivo:** Recebo vídeos de diferentes formatos, e quero vê-los no mesmo local.

    - **Critérios de Aceitação:**

        - O app deve reproduzir com qualidade vídeos de formatos diferentes;
        - O app deve declarar quais tipos de vídeo são suportados.

    - **Válida:** -

- ### Playlists

    - **ID:** US13

    - **Origem:** ST13

    - **Descrição:** Eu, como usuário, gostaria de criar playlists para organizar e reproduzir minha mídia de forma sequencial.

    - **Motivo:** Quero ter a capacidade de criar uma sequência personalizada de reprodução para facilitar o acesso e a reprodução contínua de diferentes arquivos de mídia.

    - **Critérios de Aceitação:**

        - O aplicativo deve fornecer uma funcionalidade de criação de playlists;

        - Deve ser possível adicionar arquivos de mídia (áudio) à playlist;

        - A playlist deve permitir reordenar as faixas de mídia para personalizar a sequência de reprodução;

        - O aplicativo deve oferecer opções para salvar e carregar playlists;

        - A reprodução das faixas de mídia na playlist deve ser suportada;

        - O aplicativo deve fornecer controles de reprodução básicos, como reproduzir, pausar, avançar e retroceder.

    - **Válida:** -

- ### Compartilhar arquivos

    - **ID:** US14

    - **Origem:** ST11

    - **Descrição:** Eu, como usuário, gostaria de compartilhar meus vídeos e áudios.

    - **Motivo:** Quero mandar para conhecidos os arquivos que estão no meu dispositivo.

    - **Critérios de Aceitação:**

        - O app deve possuir um botão de compartilhamento de fácil acesso;
        - Deve compartilhar para outros aplicativos, como whatsapp, telegram, gmail, dentre outros;
        - Deve compartilhar o vídeo com o mesmo tamanho e formato que ele possui.

    - **Válida:** -

- ### Mudar a velocidade de reprodução

    - **ID:** US15

    - **Origem:** ST05

    - **Descrição:** Eu, como usuário, gostaria de mudar a velocidade de reprodução do vídeo ou áudio.

    - **Motivo:** Quero poder acelerar ou desacelerar trechos de meu interesse do vídeo.

    - **Critérios de Aceitação:**

        - Deve estar disponível dentro da reprodução do vídeo;
        - Deve possibilitar mudar para algumas velocidades diferentes, como 0.75x, 1.5x, 2x, dentre outras;
        - Deve possibilitar tanto desacelerar quanto acelerar.

    - **Válida:** -

- ### Navegar por Touch Screen

    - **ID:** US16

    - **Origem:** QUE07

    - **Descrição:** Eu, como usuário, gostaria de navegar pelo vídeo utilizando o touch screen do dispositivo.

    - **Motivo:** Quero mudar o zoom e onde está o vídeo apenas com toques simples.

    - **Critérios de Aceitação:**

        - Deve mudar o zoom do vídeo;
        - Deve mudar onde está o vídeo (sua duração);
        - Deve ter sensibilidade adequada, para que não ocorram mudanças drásticas com o toque.

    - **Válida:** -

- ### Adicionar legenda

    - **ID:** US17

    - **Origem:** INT13

    - **Descrição:** Eu, como usuário, gostaria de adicionar legenda ao vídeo.

    - **Motivo:** Durante a exibição de um vídeo, gostaria de colocar legenda para auxílio do entendimento dele.

    - **Critérios de Aceitação:**

        - Deve poder adicionar legendas baixadas no dispositivo;
        - Deve poder mudar a posição da legenda na tela;
        - Deve poder mudar o tempo de aparição da legenda para que encaixe com o vídeo.

    - **Válida:** -

- ### Conversão de formatos de arquivo

    - **ID:** US18

    - **Origem:** INT04

    - **Descrição:** Eu, como usuário, gostaria de ter a opção de converter formatos de arquivo de mídia.

    - **Motivo:** Quero poder converter meus arquivos de mídia para diferentes formatos, de acordo com as minhas necessidades.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve oferecer a funcionalidade de conversão de formatos de arquivo de mídia, permitindo que o usuário converta arquivos de áudio e vídeo para diferentes formatos;

        - Deve haver suporte para uma variedade de formatos de origem e formatos de destino, abrangendo os formatos de arquivo mais comuns usados em áudio e vídeo;

        - A conversão de formatos de arquivo deve ser fácil de usar e intuitiva, com opções claras para selecionar o formato de origem e o formato de destino desejado;

        - O aplicativo deve fornecer opções avançadas de configuração durante o processo de conversão, como taxa de bits, resolução, codec, entre outras, para permitir ajustes personalizados na conversão de formato;

        - O VLC deve garantir que a conversão de formatos de arquivo seja precisa e de alta qualidade, preservando a integridade do áudio e vídeo durante o processo de conversão.

    - **Válida:** -

- ### Reprodução de mídia de alta resolução

    - **ID:** US19

    - **Origem:** ADD08

    - **Descrição:** Eu, como usuário, gostaria de poder lidar com arquivos de mídia de grande porte e alta resolução.

    - **Motivo:** Quero poder reproduzir e gerenciar arquivos de mídia com qualidade de alta resolução e tamanho grande, sem problemas de desempenho ou reprodução.

    - **Critérios de Aceitação:**

        - O aplicativo VLC deve ter suporte para a reprodução de arquivos de mídia de grande porte, como vídeos em alta resolução, sem problemas de desempenho;

        - A reprodução de arquivos de mídia de alta resolução deve ser suave e sem interrupções, garantindo uma experiência de visualização de alta qualidade;

        - O aplicativo deve oferecer recursos avançados de reprodução e gerenciamento, como a capacidade de reproduzir vídeos em 4K, HDR, vídeos de 360 graus e outros formatos de alta resolução;

        - O VLC deve ser capaz de lidar com arquivos de mídia de grande tamanho, sem problemas de carregamento lento ou travamento do aplicativo.

    - **Válida:** -

## Gravação da Validação das Histórias

&emsp;&emsp;Vídeo da validação das histórias de usuários


## Bibliografia

&emsp;&emsp;SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões

| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 22/05/2023 | `1.0` | Criando o artefato | [Giovanni Alvissus](https://github.com/giovanni1106), [Rafael Bosi](https://github.com/StrangeUnit28) e [Lucas Gobbi](https://github.com/lucasbergholz) | 23/05/2023 | [Igor Penha](github.com/igorpenhaa) |