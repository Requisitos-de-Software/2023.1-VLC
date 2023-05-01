# Análise de documentos

## Introdução

<div style="text-align:justify">
Este documento tem como objetivo elicitar e documentar os requisitos de software para o aplicativo VLC, utilizando a técnica de análise de documentos. O VLC é um reprodutor multimídia gratuito e de código aberto, amplamente utilizado para reproduzir arquivos de mídia em vários formatos. O aplicativo é executado em várias plataformas, incluindo Windows, Mac, Linux e dispositivos móveis.
</div>

## Técnica Utilizada

<div style="text-align:justify">
A técnica utilizada neste documento é a análise de documentos. Essa técnica é particularmente útil quando os requisitos do software estão implícitos em documentos existentes e podem ser extraídos por meio de uma análise cuidadosa do conteúdo. A análise de documentos é uma técnica complementar a outras técnicas de elicitação de requisitos, como entrevistas com usuários e observação de usuários. Além disso, a análise de documentos pode ser utilizada em conjunto com outras técnicas, como prototipagem e modelagem de processos, para obter uma visão abrangente dos requisitos do software.
</div>

## Elicitação de Requisitos do Aplicativo VLC

### Funcionalidades e Recursos

- Reprodução de mídia:
  - Suporte a uma ampla variedade de formatos de áudio e vídeo [VLC Documentation](https://www.videolan.org/vlc/features.html)
  - Possibilidade de adicionar legendas e selecionar faixas de áudio [VLC User Guide](https://wiki.videolan.org/VLC_User_Guide/)
  - Lista de reprodução e funcionalidades de biblioteca de mídia

### Requisitos Técnicos

- Sistemas operacionais suportados: Android e iOS [VLC Download Page](https://www.videolan.org/vlc/index.html)
- Suporte a formatos de mídia: consulte a [lista completa de formatos suportados](https://www.videolan.org/vlc/features.html)

### Requisitos de Usabilidade e Acessibilidade

- Interface do usuário intuitiva e fácil de usar [VLC User Reviews](https://www.trustpilot.com/review/vlc-media-player.en.softonic.com)
- Suporte a vários idiomas e localizações

### Requisitos de Desempenho e Escalabilidade

- Reprodução eficiente de mídia em dispositivos com recursos limitados [VLC Performance Analysis](https://www.researchgate.net/profile/Siddharth_Rautaray/publication/49587944_A_Vision_based_Hand_Gesture_Interface_for_Controlling_VLC_Media_Player/links/5437c1820cf2d5fa292b58f4/A-Vision-based-Hand-Gesture-Interface-for-Controlling-VLC-Media-Player.pdf)
- Capacidade de lidar com arquivos de mídia de grande porte e alta resolução

### Requisitos de Segurança e Privacidade

- Proteção contra vulnerabilidades e exploits de segurança conhecidos [VLC Security Bulletins](https://www.videolan.org/security/)
- Respeito à privacidade do usuário e ausência de rastreamento ou coleta de dados invasiva [VLC Privacy Policy](https://www.videolan.org/vlc/privacy.html)

## Tabela de requisitos

<div style="text-align:justify;">
A tabela 1 disposta abaixo representa todos os requisitos levantados durante a análise de documentos, identificados com 'ADD' + numero do requisito, e com a seguinte legenda de categoria:
</div>

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

- RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

- RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.

- RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.

- RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

| Identificação | Descrição | Categoria |
| --- | --- | --- |
| ADD01 | Suporte a uma ampla variedade de formatos de áudio e vídeo. | RF |
| ADD02 | Possibilidade de adicionar legendas e selecionar faixas de áudio. | RF |
| ADD03 | Lista de reprodução e funcionalidades de biblioteca de mídia. | RF |
| ADD04 | Sistemas operacionais suportados: Android e iOS. | RNF |
| ADD05 | Interface do usuário intuitiva e fácil de usar. | RI |
| ADD06 | Suporte a vários idiomas e localizações. | RI |
| ADD07 | Reprodução eficiente de mídia em dispositivos com recursos limitados. | RPR |
| ADD08 | Capacidade de lidar com arquivos de mídia de grande porte e alta resolução. | RPR |
| ADD09 | Risco de vulnerabilidades e exploits de segurança conhecidos. | RR |
| ADD10 | Risco de violação de privacidade do usuário e coleta de dados invasiva. | RR |
| ADD11 | Testes para garantir que os formatos de mídia suportados funcionem corretamente. | RT |
| ADD12 | Testes para garantir que a interface do usuário seja intuitiva e fácil de usar. | RT |
| ADD13 | Testes para garantir que o software tenha um bom desempenho em dispositivos com recursos limitados. | RT |
| ADD14 | Testes para garantir que o software seja seguro contra vulnerabilidades e exploits conhecidos. | RT |
| ADD15 | Testes para garantir que o software respeite a privacidade do usuário e não colete dados invasivamente. | RT |
<div style="text-align: center;"><p>Tabela 1 - Tabela dos requisitos levantados (Fonte: ALVISSUS, Giovanni. 2023).</p></div>

## Bibliografia

- VideoLAN. *VLC Media Player: Features*. Disponível em: <https://www.videolan.org/vlc/features.html>. Acesso em: 29 abr. 2023.
- VideoLAN. *VLC User Guide*. Disponível em: <https://wiki.videolan.org/VLC_User_Guide/>. Acesso em: 29 abr. 2023.
- Trustpilot. *VLC Media Player Reviews*. Disponível em: <https://www.trustpilot.com/review/vlc-media-player.en.softonic.com>. Acesso em: 29 abr. 2023.
- ResearchGate. *Performance Analysis of VLC Media Player*. Disponível em: <https://www.researchgate.net/profile/Siddharth_Rautaray/publication/49587944_A_Vision_based_Hand_Gesture_Interface_for_Controlling_VLC_Media_Player/links/5437c1820cf2d5fa292b58f4/A-Vision-based-Hand-Gesture-Interface-for-Controlling-VLC-Media-Player.pdf>. Acesso em: 29 abr. 2023.
- VideoLAN. *VLC Security Bulletins*. Disponível em: <https://www.videolan.org/security/>. Acesso em: 29 abr. 2023.
- VideoLAN. *VLC Privacy Policy*. Disponível em: <https://www.videolan.org/vlc/privacy.html>. Acesso em: 29 abr. 2023.

## Histórico de Versão

| Versão | Data de execução  | Data de revisão |  Descrição    | Autor(es)     |  Revisor(es)  |
| :----: | :---------------: | :-------------: | :-----------: | :-----------: | :-----------: |
| `1.0` | 29/04/2023 | 30/04/2023 | Criando o artefato | [Giovanni Alvissus](https://github.com/giovanni1106) | [Rafael Bosi](https://github.com/StrangeUnit28) |




