# Léxicos

## Introdução

<div align="justify">

&emsp;&emsp;O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo dos engenheiros de requisitos é buscar frases e símbolos do domínio da aplicação. Cada um desse símbolo é descrito com uma noção e um impacto, sendo a noção relacionada com o símbolo e o impacto com a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.

</div>
</br>

## Metodologia

<div align="justify">

&emsp;&emsp;Os léxicos do <a href="https://www.videolan.org/">VLC Media Player</a> foram identificados a partir do uso do aplicativo e dos requisitos elicitados em etapas anteriores. Na tabela 1 abaixo temos o exemplo de como os léxicos serão apresentados e descritos:

</div>

|     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
| :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
| Nome do Léxico | Autor do Léxico | Símbolos | Descrição do efeito | Sinônimo(s) | Verbo/Objeto/Estado |

<div style="text-align: center">
<p> Tabela 1: Modelo dos léxicos (Fonte: BOSI, Rafael. 2023).</p>
</div>

<div align="justify">

&emsp;&emsp;As descrições seguem o princípio circular e o princípio do vocabulário mínimo. O princípio da circularidade torna cada extensão da descrição ou a conotação, referindo-se a outros símbolos da linguagem, ou seja, durante as descrições dos léxicos os mesmos serão ligados a outros léxicos. A parte não simbólica da descrição deve vir de um subconjunto reduzido de palavras com significado claro (vocabulário mínimo), no caso desse documento, um sinônimo do léxico apresentado.

</div>

</br>

## Descrição dos Léxicos

<div align="justify">

&emsp;&emsp;Abaixo estão as tabelas de 2 a 29 que representam os léxicos do aplicativo em análise. Tais léxicos foram divididos em três categorias sendo elas: Estado, Objeto e Verbo. Cada léxico de cada categoria recebeu uma forma de simbolização específica, sendo elas:

- LE -> Léxico de Estado
- LO -> Léxico de Objeto
- LV -> Léxico de Verbo

</div>

<div align="justify">

&emsp;&emsp;Léxico de Estado: Os léxicos de estado referem-se aos termos que descrevem as condições, estados ou propriedades do sistema ou dos elementos nele contidos.

</div>

<div align="justify">

&emsp;&emsp;Léxico de Objeto: Os léxicos de objeto englobam os termos que representam os elementos tangíveis ou virtuais do sistema com os quais os usuários interagem

</div>

<div align="justify">

&emsp;&emsp;Léxico de Verbo: Os léxicos de verbo consistem em palavras ou frases que descrevem ações que podem ser executadas pelos usuários ou pelo sistema.

</div>
</br>

- ## Estado

    - ### LE01 - Maximizado

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :-------: | :-------: | :-----------: | :----------------: | :-------: | :--------: |
    | Maximizado | [Rafael Bosi](https://github.com/StrangeUnit28) | É quando uma página de um <a href="#video">vídeo</a> é a tela principal, tomando, assim, boa parte da tela | Quando um <a href="#video">vídeo</a> é maximizado, ele ocupa uma parte maior ou até mesmo toda a tela, reduzindo a capacidade do <a href="#usuario">usuário</a> de interagir com o aplicativo. | Expandido, Aumentado | Estado |

    <div style="text-align: center">
    <p> Tabela 2: Léxico de maximização (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LE02 - <a id="minimizado">Minimizado</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Minimizado | [Rafael Bosi](https://github.com/StrangeUnit28) | Quando um <a href="#video">vídeo</a> está em tamanho reduzido, a tela ganha espaço adicional para explorar outras áreas do <a href="#plataforma">aplicativo</a> | Enquanto assiste a um <a href="#video">vídeo</a>, o <a href="#usuario">usuário</a> tem a possibilidade de realizar outras ações dentro do <a href="#plataforma">aplicativo</a> | Reduzido, Diminuido | Estado |

    <div style="text-align: center">
    <p> Tabela 3: Léxico de minimização (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LE03 - <a id="pausado">Pausado</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Pausado | [Rafael Bosi](https://github.com/StrangeUnit28) | É quando um <a href="#video">vídeo</a> em reprodução pode ser interrompido | Durante a reprodução de conteúdo, tanto o <a href="#video">vídeo</a> quanto o áudio são interrompidos ou pausados. | Parado, Interrompido | Estado |

    <div style="text-align: center">
    <p> Tabela 3: Léxico de pausado (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LE04 - Mutado

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Mutado | [Rafael Bosi](https://github.com/StrangeUnit28) | É quando o <a href="#video">vídeo</a> não emite som | Permite o <a href="#usuario">usuário</a> <a href="#assistir">assistir</a> a <a href="#video">vídeo</a> sem som | Silenciado | Estado |

    <div style="text-align: center">
    <p> Tabela 4: Léxico de mutado (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

- ## Objeto

    - ### LO01 - Dispositivo 

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Dispositivo | [Rafael Bosi](https://github.com/StrangeUnit28) | É o aparelho que irá acessar o VLC, e onde o <a href="#usuario">usuário</a> poderá <a href="#assistir">assistir</a> e <a href="#compartilhar">compartilhar</a> o <a href="#video">vídeo</a> | O dispositivo irá realizar todas as funcionalidades do <a href="#plataforma">aplicativo</a> | Aparelho | Objeto |

    <div style="text-align: center">
    <p> Tabela 5: Léxico de dispositivo (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO02 - Interface 

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Interface | [Rafael Bosi](https://github.com/StrangeUnit28) | A interface são os elementos que aparecem na tela e como estão distribuídos | Uma interface pode interagir e ser interagida, ao <a href="#clicar">clicar</a>, por exemplo | Tela | Objeto |

    <div style="text-align: center">
    <p> Tabela 6: Léxico de interface (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO03 - Legenda

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Legenda | [Rafael Bosi](https://github.com/StrangeUnit28) | Texto escrito do áudio do <a href="#video">vídeo</a> | Uma legenda pode ser ativada ou desativada e também pode ser escolhida o idioma da legenda | Transcrição simultânea | Objeto |

    <div style="text-align: center">
    <p> Tabela 7: Léxico de legenda (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO04 - Notificação

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Notificação | [Rafael Bosi](https://github.com/StrangeUnit28) | É um aviso ao <a href="#usuario">usuário</a> | Uma notificação pode ser ativada ou desativada por um <a href="#usuario">usuário</a> | Aviso | Objeto |

    <div style="text-align: center">
    <p> Tabela 8: Léxico de notificação (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO05 - <a id="plataforma">Plataforma</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Plataforma | [Rafael Bosi](https://github.com/StrangeUnit28) | É uma forma de representar o aplicativo VLC | Quando é dito funcionalidades da "plataforma", refere-se ao que o aplicativo pode fazer | Aplicativo, Sistema | Objeto |

    <div style="text-align: center">
    <p> Tabela 9: Léxico de plataforma (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO06 - Playlist

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Playlist | [Rafael Bosi](https://github.com/StrangeUnit28) | Um conjunto de <a href="#video">vídeo</a> que pode ser tocado em uma ordem determinada ou em ordem aleatória | A playlist pode ser compartilhada, criada, e reproduzida na ordem definida ou em ordem aleatória | List de reprodução | Objeto |

    <div style="text-align: center">
    <p> Tabela 10: Léxico de playlist (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO07 - Qualidade

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Qualidade | [Rafael Bosi](https://github.com/StrangeUnit28) | A qualidade do <a href="#video">vídeo</a> é a resolução que ele será reproduzido | A qualidade de um <a href="#video">vídeo</a> poderá ser ajustada de acordo com a vontade do <a href="#usuario">usuário</a> | Resolução | Objeto |

    <div style="text-align: center">
    <p> Tabela 11: Léxico de qualidade (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO08 - Velocidade de Reprodução

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Velocidade de Reprodução | [Rafael Bosi](https://github.com/StrangeUnit28) | É uma forma do <a href="#usuario">usuário</a> aumentar ou diminuir o tempo do <a href="#video">vídeo</a> ajustando a velocidade em que ele é reproduzido | A velocidade de reprodução pode ser ajustada de acordo com a vontade do <a href="#usuario">usuário</a> | -- | Objeto |

    <div style="text-align: center">
    <p> Tabela 12: Léxico de velocidade de reprodução (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

     - ### LO09 - <a id="video">Vídeo</a> 

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Vídeo | [Rafael Bosi](https://github.com/StrangeUnit28) | É um meio de entretenimento que pode tomar diferentes assuntos e formas de produção | Pode ser assistido, <a href="#pausado">pausado</a>, resumido e compartilhado <a href="#usuario">usuário</a> | Gravação | Objeto |

    <div style="text-align: center">
    <p> Tabela 13: Léxico de vídeo (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>
    
    - ### LO10 - <a id="usuario">Usuário</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Usuário | [Rafael Bosi](https://github.com/StrangeUnit28) | Usuário é qualquer um que utiliza o <a href="#plataforma">aplicativo</a> | O Usuário pode <a href="#assistir">assistir</a>, <a href="compartilhar">compartilhar</a>, <a href="#pausar">pausar</a>, dar <a href="#play">play</a>, <a href="#maximizar">maximizar</a> ou <a href="#minimizar">minimizar</a> o <a href="#video">vídeo</a> | User, Cliente | Objeto |

    <div style="text-align: center">
    <p> Tabela 14: Léxico de usuário (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO11 - <a id="volume">Volume</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Volume | [Rafael Bosi](https://github.com/StrangeUnit28) | O volume é uma propriedades do som e se refere à intensidade com que uma nota é executada | O <a href="#usuario">usuário</a> tem autonomia para decidir a altura do som que vai ouvir | Áudio | Objeto |

    <div style="text-align: center">
    <p> Tabela 15: Léxico de volume (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LO12 - Ajuda

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Ajuda | [Rafael Bosi](https://github.com/StrangeUnit28) | É uma documentação específica para orientar o <a href="#usuario">usuário</a> | Aumenta a eficiência e a velocidade de aprendizado do <a href="#usuario">usuário</a> | Auxílio, Guia, Documentação | Objeto |

    <div style="text-align: center">
    <p> Tabela 16: Léxico de ajuda (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

- ## Verbo

    - ### LV01 - <a id="assistir">Assistir</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Assistir | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> pode assistir a um <a href="#video">vídeo</a> | Um <a href="#video">vídeo</a> é reproduzido na tela do <a href="#usuario">usuário</a> | Visualizar, Ver | Verbo |

    <div style="text-align: center">
    <p> Tabela 17: Léxico de assistir (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV02 - <a id="clicar">Clicar</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Clicar | [Rafael Bosi](https://github.com/StrangeUnit28) | É a ação de pressionar o dedo contra a tela, mais especificamente na funcionalidade que se deseja que seja ativada | A grande maioria das ações só podem ser executadas após um clique | Pressionar | Verbo |

    <div style="text-align: center">
    <p> Tabela 18: Léxico de clicar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV03 - <a id="compartilhar">Compartilhar</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Compartilhar | [Rafael Bosi](https://github.com/StrangeUnit28) | É o ato de o <a href="#usuario">usuário</a> realizar as ações necessárias dentro do <a href="#plataforma">aplicativo</a> para exportar um <a href="#video">vídeo</a> | Um <a href="#video">vídeo</a> pode ser compartilhado em diversas redes sociais fora do VLC | Distribuir | Verbo |

    <div style="text-align: center">
    <p> Tabela 19: Léxico de compartilhar (Fonte: BOSI, Rafael. 2023).</p>
    </div> 
    </br>   

    - ### LV04 - <a id="login">Login</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Login | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> se conecta a sua conta | Um <a href="#usuario">usuário</a> ao realizar  login tem acesso a diversas outras funcionalidades restritas a usuários conectados | Conectar, Entrar | Verbo |

    <div style="text-align: center">
    <p> Tabela 20: Léxico de login (Fonte: BOSI, Rafael. 2023).</p>
    </div>  
    </br>

    - ### LV05 - Logout

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Logout | [Rafael Bosi](https://github.com/StrangeUnit28) | É a ação reversa ao <a href="#login">login</a>, um <a href="#usuario">usuário</a> se desconecta de sua conta | O <a href="#usuario">usuário</a> que realiza o logout fica sem acesso as funcionalidades que requerem <a href="#login">login</a> | Desconectar, Sair | Verbo |

    <div style="text-align: center">
    <p> Tabela 21: Léxico de logout (Fonte: BOSI, Rafael. 2023).</p>
    </div> 
    </br>

    - ### LV06 - <a id="maximizar">Maximizar</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Maximizar | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> pode maximizar um <a href="#video">vídeo</a>  | Um <a href="#video">vídeo</a> se torna maximizado ao receber a ação de maximizar | Aumentar, Expandir | Verbo |

    <div style="text-align: center">
    <p> Tabela 22: Léxico de maximizar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV07 - <a id="minimizar">Minimizar</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Minimizar | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> pode minimizar um <a href="#video">vídeo</a> | Um <a href="#video">vídeo</a> se torna <a href="#minimizado">minimizado</a> ao receber a ação de minimizar | Diminuir, Reduzir | Verbo |

    <div style="text-align: center">
    <p> Tabela 23: Léxico de minimizar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV08 - <a id="pausar">Pausar</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Pausar | [Rafael Bosi](https://github.com/StrangeUnit28) | Significa que um <a href="#video">vídeo</a> que está sendo reproduzido será parado | O <a href="#video">vídeo</a> que estava sendo executado na tela será **interrompido (LE03)** | Parar, Interromper | Verbo |

    <div style="text-align: center">
    <p> Tabela 24: Léxico de pausar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV09 - Navegar

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Navegar | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> navega pelo <a href="#plataforma">aplicativo</a> em busca do <a href="#video">vídeo</a> desejado | Maior controle do <a href="#usuario">usuário</a> sobre o <a href="#plataforma">aplicativo</a> | Pesquisar, Buscar | Verbo |

    <div style="text-align: center">
    <p> Tabela 25: Léxico de Navegar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV10 - <a id="play">Play</a>

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Play | [Rafael Bosi](https://github.com/StrangeUnit28) | O <a href="#usuario">usuário</a> dá play em um vídeo ao pressionar contra tela | Um <a href="#video">vídeo</a> ao receber a ação de play sai do estado de <a href="#pausado">pausado</a> e volta a ser reproduzido | Começar | Verbo |

    <div style="text-align: center">
    <p> Tabela 26: Léxico de play (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV11 - Aumentar Volume

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Aumentar volume | [Rafael Bosi](https://github.com/StrangeUnit28) | É a ação de ampliar o som do <a href="#video">vídeo</a> | Permite ao <a href="#usuario">usuário</a> ampliar o som do <a href="#video">vídeo</a> para uma melhor audição | Ampliar som | Verbo |

    <div style="text-align: center">
    <p> Tabela 27: Léxico de aumentar volume (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV12 - Diminuir Volume

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Diminuir volume | [Rafael Bosi](https://github.com/StrangeUnit28) | É a ação de deduzir o som do <a href="#video">vídeo</a> | Permite ao <a href="#usuario">usuário</a> deduzir o som do <a href="#video">vídeo</a> para que fique em uma altura confortável | Deduzir som | Verbo |

    <div style="text-align: center">
    <p> Tabela 28: Léxico de diminuir volume (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

    - ### LV13 - Mutar

    |     Léxico     |      Autor      |   Noção  |       Impacto       |   Sinônimo  |   Classificação     |
    | :------------: | :-------------: | :------: | :-----------------: | :---------: | :-----------------: |
    | Mutar | [Rafael Bosi](https://github.com/StrangeUnit28) | É a ação de desligar ou ligar o <a href="#volume">volume</a> do <a href="#video">vídeo</a> | O <a href="#usuario">usuário</a> pode <a href="#assistir">assistir</a> ao <a href="#video">vídeo</a> sem som | Silenciar | Verbo |

    <div style="text-align: center">
    <p> Tabela 29: Léxico de mutar (Fonte: BOSI, Rafael. 2023).</p>
    </div>
    </br>

## Conclusão

<div align="justify">

&emsp;&emsp;Assim, os léxicos identificados foram procurados e reconhecidos utilizando o aplicativo, revelando elementos que podem ser interpretados como figuras de linguagem, que descrevem algo, ou como simples ícones. Com base nisso, podemos concluir que alguns desses léxicos possuem uma conexão rastreável com a atividade dos cenários, estabelecendo uma ligação entre os artefatos e permitindo uma rastreabilidade ainda mais ampla entre eles.

</div>
</br>

## Referência Bibliográfica

[1] SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.

## Histórico de Versões

| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 15/05/2023 | `1.0` | Criando o artefato | [Rafael Bosi](https://github.com/StrangeUnit28) | 16/05/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
| 03/07/2023 | `1.1` | Ajustando o artefato | [Rafael Bosi](https://github.com/StrangeUnit28) | 03/07/2023 | [Giovanni Alvissus](https://github.com/giovanni1106) |
