# Especificação Suplementar

### Intrudução

A especificação suplementar tem como objetivo apontar requisitos do sistema, os quais não foram explicitados pela modelagem de  casos uso. Dessa forma, somando-se ambas, torna-se possível definir todos os requisitos do sistema.

Este método, tem como pilares os seguintes critérios:

	- funcionalidade
	- usabilidade
	- confiabilidade
	- desempenho
	- suportabilidade

### Metodologia

Consoante ao tópico anterior, o modelo utilizado para este artefato é o FURPS+, metodologia a qual define reqisitos de um sistema dnetro de um dos cinco pilares citados anteriormente.

- *F* - _Functionality_: são os aspectos funcionais do sistema, os quais estão explicitados nos [casos de uso](casos_de_uso.md).
- *U* - _Usability_: o quão fácil é para o usuário realizar suas demandas via o software.
- *R* - _Reliability_: o quão confiável foi desenhado o software.
- *P* - _Performance_: como é o desempenho do software.
- *S* - _Supportability_: requisitos que agrupam caracteristicas como: manutenibilidade, adaptabilidade, internacionalização, portabilidade e outros aspectos relevantes.
- *+*: símbolo que emgloba outros requisitos não funcionais, os quais não se encaixam nos pilares listados, como: design, implementação, interface, físico.

##

### _Functionality_ (Funcionalidades)

Os requisitos funcionais estão descritos nos casos de uso.

### _Usability_ (Usabilidade)

Diz respeito para com a facilidade de uso do usuário com o sistema.

#### Facilidade de uso

As operações feitas no sistema são relativamente simples, o que o torna um aplicativo de fácil uso. Assim, para a realização de ações críticas do sistema bastam aproximadamente cinco cliques.

#### Disponibilidade

O sistema pode funcionar independente da conexão com internet, o que o torna um sistema com alta disponibilidade.

#### Interface

O sistema possui uma interface simplificada, que auxilia o uso do usuário em suas principais ações dentro da aplicação.

### _Reliability_ (Confiabilidade)

Diz respeito a garantias de segurança do usuário para com o sistema.

#### Garantia de segurança mínima no armazenamento de dados

O aplicativo não salva os dados do usuário, esses são acessados apenas durante a execução do mesmo, respeitando o termo de privacidade da aplicação.

#### Garantia de disponibilidade

O sistema deve funcionar 24h por dia e sete dias por semana, independente de acesso ou não à internet.

### _Performance_ (Desempenho)

Diz respeito a performace do software.

#### Armazenamento

O usuário deverá possuir aproximadamente 100MB para instalar o aplicativo.

#### Tempo de resposta

O sistema deve ter um tempo de comunicação com o aparelho movel de no máximo 7 segundos.

### _Supportability_ (Suportabilidade)

Diz respeito a aspectos técnicos como manutenibilidade, adaptabilidade, internacionalização, portabilidade e outros aspectos relevantes.

#### Sistemas operacionais (OS)

O aplicativo pode ser utilizado nos seguintes sistemas:

iOS 9.0 ou superior, Android 4.2 ou superior.

O aplicativo pode ser instalado nas seguintes maquinas:

iPhone, iPad, iPod, Apple TV, celulares Android, etc.

#### Idiomas

A aplicação suporta mais de 40 idiomas, entre eles: português, inglês, espanhol, alemão, francês, italiano, chines, japonês, entre outros.

### +

Diz respeito a outros tipos de requisitos como design, implementação, interface e físicos.

#### Design

O aplicativo segue uma paleta de cores fixa com as cores predominantes sendo perto, cinza, laranja e branco, podendo variar entre três temas de fundo (DayNight, Light theme, Black theme).

#### Físico

O aplicativo é construido nas seguintes linguagens:

Android: Kotlin, Java.

iOS: Objective-C, Swift.

## Bibliografia

[1] SALLES, André. Plano de ensino da disciplina. Disponível em: [slides](https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 15 de maio de 2023.

[2] VideoLAN. Disponível em: [link](https://www.videolan.org/vlc/libvlc.html). Acesso em 15 de maio de 2023.

### Histórico de versão

| Versã0 | Data | Data de revisão | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | :-------------: | :-------: | :-------: | :---------: |
| `1.0` | 15/05/2023 | 15/05/2023 | Criação do artefato | [Bruno Riberio](https://github.com/BrunoRibeiro) e [Lucas Gobbi](https://github.com/LucasBerholz) | [Igor Penha](https://github.com/igorpenhaa) e [Giovanni Alvissus](https://github.com/gitovanni1106) |
