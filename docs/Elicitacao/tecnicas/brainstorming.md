# ***Brainstorming***

## **Introdução**
<p align="justify">
&emsp;&emsp;Brainstorming é uma técnica eficaz de coletar informações sobre as preferências e necessidades dos usuários em relação à um sistema. O processo consiste em realizar uma conversa informal reunindo usuários de diversas áreas, onde cada um expõe seus desejos e necessidades, e assim pode identificar os requisitos e explorar novas funcionalidades para o desenvolvimento do sistema, principalmente na fase inicial. Durante a conversa deve-se evitar críticas, para não gerar constrangimento entre os usuários. Se os participantes permitirem a sessão pode ser gravada, e todas as ideias devem ser registradas para uma posterior seleção com base em sua relevância.


</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp; Para realizar o brainstorming, reunimos presencialmente dois membros da equipe para serem o moderador e o secretário e quatro usuários do aplicativo (ver tabela 1). Para realizar o brainstorming foi utilizada a ferramenta miro, nela foram feitos alguns quadros com perguntas(ver tabela 2)  para guiar a discussão e ajudar a elicitar os requisitos baseados nas necessidades dos usuários .
</p>

## **Participantes**
<p align="justify">
&emsp;&emsp; A tabela 1 representa os participantes da atividade de brainstorming
</p>

<center>

| Nome                                                      | Função     |
| --------------------------------------------------------- | ---------- |
| [Júlia Souza](https://github.com/JuliaSSouza)             | Mediadora  |
| [Carolina Barbosa](https://github.com/CarolinaBarb)       | Secretária |
| <span style = "color: purple"> Caio Pacheco Santos</span>        | Usuário    |
| <span style = "color: purple"> Gabriel Morais Santana</span>     | Usuário    |
| <span style = "color: purple"> Guilherme Almeida Quirino </span>  | Usuário    |
| <span style = "color: purple"> Henrique Pucci da Silva Pinto </span>     | Usuário    |

</center>

<p align="justify">
<h6 align = "center"> Tabela 01: Participantes.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>
</p>

## **Perguntas**
<p align="justify">
&emsp;&emsp; A tabela 2 representas as perguntas utilizadas para guiar o desenvolvimento do brainstorming:
</p>

| Perguntas                                                      
| ------------------------------------------------------------------- |
| Quais recursos ou funcionalidades você considera essenciais para uma experiência de chamada de vídeo satisfatória                 |
| Que tipo de integrações você gostaria que o aplicativo de chamadas tivesse com outras ferramentas ou serviços, por exemplo, calendários e aplicativos de mensagens?              |
| Como o aplicativo do Jitsi poderia fornecer uma experiência de usuário mais agradável e intuitiva, de modo a facilitar a navegação?           |

<p align="justify">
<h6 align = "center"> Tabela 02: Perguntas.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>
</p>

## **Brainstorm**
<p align="justify">
&emsp;&emsp; A imagem 01 representa as perguntas e respostas dos participantes da atividade de brainstorming
</p>

<figure markdown>
<img src= "https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Jitsi/main/docs/assets/Brainstorm.jpg" alt="Brainstorm" style="float: none; margin: auto"> 
</figure>
<p align="justify">
<h6 align = "center"> Imagem 01: Perguntas e respostas.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>
</p>

## **Requisitos Elicitados**
<p align="justify">
&emsp;&emsp;Legenda da tabela 1: 
<li> RF(Requisitos Funcionais): descrevem as funcionalidades e operações que o sistema deve realizar para atender às necessidades dos usuários. </li>
<li> RNF(Requisitos Não Funcionais): definem a qualidade e o desempenho de um sistema. </li>
<li> Identificação(BR + N°) : Requisito Elicitado pela Brainstorming + Número
</p>
<p align="justify">
&emsp;&emsp;A tabela 1 representa os Requisitos Elicitados pela técnica de Brainstorming
</p>

| Identificação  | Descrição  | Categoria | 
|-----|---------------------------------------------------------|-------|
|BR01| Deve haver uma funcionalidade de quadro de anotações disponível  | RF |
|BR02| O usuário deve ser capaz de compartilhar sua tela durante as reuniões | RF|
|BR03| Deve permitir a gravação de reuniões  | RF |
|BR04| O usuário deve ser capaz de alterar seu fundo em uma chamada de vídeo | RF |
|BR05| O sistema deve ser capaz de transcrever uma chamada| RF|
|BR06| Deve permitir que o anfitrião de uma reunião consiga desligar o microfone e a câmera de qualquer participante. |RF|
|BR07| Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião. | RF|
|BR08| Deve ser possível fazer o download das gravações das reuniões| RF|
|BR09| Deve possuir um mecanismo de busca a partir da data da reunião| RF|
|BR10| Deve permitir que o anfitrião exclua particpantes | RF|
|BR11| Deve fornecer ao usuário a capacidade de visualizar todas as salas em que ele participou anteriormente. | RF |
|BR12| O anfitrião deve ser capaz de controlar a entrada em uma sala por meio de senha|RF|
|BR13| Deve ser possível ingressar em uma reunião sem a necessidade de um login | RNF |
|BR14| O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião | RF |
|BR15| Deve ser possível a integração com outros sistemas afim de possibilitar a abertura de arquivos no próprio aplicativo| RNF |
|BR16| Deve ser possível a integração com aplicativos de calendário afim de possibilitar a vsiualização dos compromissos do usuario no aplicativo| RNF |
|BR17| Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade | RF |
|BR18| Deve oferecer uma interface simples e objetiva | RNF |
|BR19| Deve oferecer configurações claras e intuitivas | RF |
|BR20| Deve possuir um bom contraste entre as cores afim aprimorar a legibilidade | RNF |

<h6 align = "center"> Tabela 03: Requisitos Elicitados
<br> Autor(a):<a href="https://github.com/CarolinaBarb">Carolina Barbosa</a>, <a href="https://github.com/catlenc">Catlen Cleane</a>, <a href="https://github.com/JuliaSSouza">Julia Souza</a> e <a href="https://github.com/Juhvitoria4">Julia Vitoria</a></h6>
</center>
</p>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 04 representa o histórico de versão do documento.
</p>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 02/10/2023 | Introdução e Ideias Iniciais | [Carolina Barbosa](https://github.com/CarolinaBarb), [Catlen Cleane](https://github.com/catlenc), [Júlia Souza](https://github.com/JuliaSSouza) e [Júlia Vitória](https://github.com/Juhvitoria4)|[Pedro Siqueira](https://github.com/PedroSiq) |
| `1.1`  | 03/10/2023 | Elicitação dos Requisitos e conclusão | [Carolina Barbosa](https://github.com/CarolinaBarb), [Catlen Cleane](https://github.com/catlenc), [Júlia Souza](https://github.com/JuliaSSouza) e [Júlia Vitória](https://github.com/Juhvitoria4)|[Pedro Siqueira](https://github.com/PedroSiq) |
<h6 align="center"> Tabela 04: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>

## **Bibliografia**
> <a href="https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-brainstorming">[1]</a> Brainstorming em Retrainig. Acesso em 02 de Outubro de 2023.
> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/brainstorming/">[2]</a> Brainstorming em Bilheteria Digital. Acesso em 02 de Outubro de 2023.
> [3]</a> 1.BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.