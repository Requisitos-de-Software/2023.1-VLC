# Introspecção de Requisitos de Software - VLC

## Introdução

<div style="text-align:justify;">
O VLC é um dos players multimídia mais populares e de código aberto do mundo. Ele é conhecido por sua capacidade de reproduzir praticamente qualquer formato de arquivo de mídia, além de ser gratuito e multiplataforma. O objetivo deste documento é fornecer uma introspecção de requisitos de software para o VLC, descrevendo os objetivos do projeto, os stakeholders envolvidos, os requisitos funcionais e não-funcionais, as restrições do projeto, os riscos envolvidos, os testes e validações necessários, e o cronograma do projeto. Este documento é destinado a fornecer uma visão geral dos requisitos de software do VLC e servir como guia para o desenvolvimento contínuo do software.
</div>


## O que é Introspecção de Requisitos de Software?

<div style="text-align:justify;">
A introspecção de requisitos de software é o processo de examinar, analisar e documentar os requisitos de software de um projeto. É uma etapa importante no desenvolvimento de software, pois ajuda a garantir que todos os requisitos do projeto sejam identificados e documentados antes do início do desenvolvimento. A introspecção de requisitos de software pode incluir a identificação de requisitos funcionais e não-funcionais, restrições do projeto, riscos, stakeholders envolvidos, cronograma do projeto e testes e validações necessários. Um documento de introspecção de requisitos de software pode servir como um guia para o desenvolvimento contínuo do software e ajudar a garantir que o projeto seja concluído com sucesso.
</div>

## Objetivos do Projeto
- O objetivo do projeto VLC é fornecer uma solução de player multimídia de código aberto, gratuita e multiplataforma.
- O projeto busca atender às necessidades de reprodução de mídia de uma ampla gama de usuários, desde aqueles que desejam assistir a um vídeo ocasional até os que precisam de recursos mais avançados, como streaming de mídia e conversão de formato.

## Stakeholders
- Usuários finais que desejam um player multimídia gratuito, de código aberto e fácil de usar.
- Desenvolvedores que desejam colaborar no desenvolvimento e aprimoramento contínuo do software.
- Empresas e organizações que desejam usar o VLC em seus sistemas.

## Tabela de requisitos

<div style="text-align:justify;">
A tabela 1 apresentada abaixo é uma lista dos requisitos de software levantados durante a introspecção do projeto VLC, cujo a identificação segue o formato 'INT' + o numero do requisito. Cada um foi identificado por uma identificação exclusiva e uma descrição detalhada. Além disso, cada requisito foi classificado em uma das seis categorias:
</div>

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

- RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

- RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.

- RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.

- RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

| Identificação | Descrição | Categoria |
| --- | --- | --- |
| INT01 | Reproduzir arquivos de vídeo e áudio em uma ampla variedade de formatos. | RF |
| INT02 | Permitir a criação de listas de reprodução e a seleção de faixas de áudio e legendas. | RF |
| INT03 | Suportar streaming de mídia. | RF |
| INT04 | Permitir a conversão de formatos de arquivo. | RF |
| INT05 | Possibilitar a reprodução de discos de DVD e Blu-ray. | RF |
| INT06 | Permitir a captura de tela e a gravação de vídeo. | RF |
| INT07 | Deve ser compatível com sistemas operacionais Windows, Mac OS e Linux. | RNF |
| INT08 | Deve ser fácil de instalar e usar. | RNF |
| INT09 | Deve ser de código aberto e gratuito. | RNF |
| INT10 | Deve ter uma interface de usuário amigável e intuitiva. | RNF |
| INT11 | Deve ter um bom desempenho de reprodução, mesmo para arquivos grandes. | RNF |
| INT12 | A interface do usuário deve ser fácil de navegar e permitir a seleção de arquivos de mídia. | RI |
| INT13 | Deve ser possível personalizar a aparência da interface do usuário. | RI |
| INT14 | Deve ser possível selecionar faixas de áudio e legendas. | RI |
| INT15 | A interface deve fornecer feedback ao usuário sobre o progresso da reprodução e outras informações relevantes. | RI |
| INT16 | O VLC deve ser de código aberto e gratuito. | RPR |
| INT17 | O software deve ser compatível com Windows, Mac OS e Linux. | RPR |
| INT18 | O VLC deve ter um bom desempenho em uma ampla variedade de sistemas. | RPR |
| INT19 | Problemas de compatibilidade com sistemas operacionais ou hardware específicos. | RR |
| INT20 | Concorrência de outros players multimídia. | RR |
| INT21 | Problemas de desempenho com arquivos grandes ou em sistemas mais antigos. | RR |
| INT22 | Problemas de segurança relacionados à reprodução de arquivos de mídia. | RR |
| INT23 | O VLC deve ser testado em uma ampla variedade de sistemas e com uma ampla variedade de formatos de arquivo de mídia. | RT |
| INT24 | Os testes devem incluir a reprodução de arquivos grandes e a transmissão de mídia pela rede. | RT |
| INT25 | O software deve ser validado em relação aos requisitos funcionais e não-funcionais listados acima. | RT |
<div style="text-align: center;"><p>Tabela 1 - Tabela dos requisitos levantados (Fonte: ALVISSUS, Giovanni. 2023).</p></div>

## Bibliografia

- VideoLAN. *VLC Media Player: Features*. Disponível em: <https://www.videolan.org/vlc/features.html>. Acesso em: 29 abr. 2023.

- VideoLAN. *VLC Security Bulletins*. Disponível em: <https://www.videolan.org/security/>. Acesso em: 29 abr. 2023.

- 1library. *Engenharia de Requisitos*. Disponívem em: <https://1library.org/article/an%C3%A1lise-de-documentos-t%C3%A9cnicas-para-elicita%C3%A7%C3%A3o-de-requisitos.qor9dxjq>. Acesso em: 29 abr. 2023.

## Histórico de Versão

| Versão | Data de execução  | Data de revisão |  Descrição    | Autor(es)     |  Revisor(es)  |
| :----: | :---------------: | :-------------: | :-----------: | :-----------: | :-----------: |
| `1.0` | 29/04/2023 | 30/04/2023 | Criando o artefato | [Giovanni Alvissus](https://github.com/giovanni1106) | [Rafael Bosi](https://github.com/StrangeUnit28) |
