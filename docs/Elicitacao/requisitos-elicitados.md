# ***Requisitos Elicitados***

## **Introdução**
<p align="justify">
&emsp;&emsp;Este artefato apresenta todos os requisitos que foram elicitados durante a aplicação das técnicas: <a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">brainstorming</a>, <a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">entrevista</a>, <a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/">introspecção</a> e <a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">observação</a>.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp;A tabela 1 apresenta os requisitos funcionais e não funcionais que foram elicitados em todas as técnicas citadas cima, cada uma contendo o seu identificador, descrição, hyperlink de rastreabilidade (direciona ao(s) artefato(s) aonde o requisito foi elicitado) e se foi implementado na aplicação ou não.
</p>
<p align="justify">
&emsp;&emsp;Legenda para cada sigla utilizada na tabela:
<ul>
<li>RF: Requisito Funcional</li>
<li>RNF: Requisito Não-Funcional nº</li>
<li>BRx: Requisito nºx elicitado pela Brainstorming</li>
<li>ENTx: Requisito nºx elicitado pela Entrevista</li>
<li>INx: Requisito nºx elicitado pela Introspecção</li>
<li>OBx: Requisito nºx elicitado pela Observação</li>
</p>

| Identificador | Requisito | Categoria | Implementado | 
| ------------- | -------------------- | --------- | ------- | 
| ENT01, IN02, OB07, BR02 | Os usuários devem poder compartilhar suas telas durante as chamadas | RF | Sim | 
| ENT02| Os usuários devem ser capazes de criar uma videoconferência | RF | Sim |
| ENT03, OB09 | Os usuários devem poder compartilhar emojis pré-definidos durante as chamadas | RF | Sim |
| ENT04, IN03, OB05, BR03 | Deve permitir a gravação de chamadas | RF | Não | 
| ENT05, BR05 | Deve permitir a transcrição do áudio da chamada | RF | Não | 
| ENT06, IN04, BR01 | Deve permitir a utilização de quadro de anotação durante a chamada | RF | Não |
| ENT07, BR04 | O usuário deve ser capaz de alterar seu fundo em uma chamada de vídeo | RF | Não | 
| ENT08, BR19, OB18 | Deve ter uma interface clara e intuitiva, permitindo que o usuário consiga realizar qualquer atividade com menos de 5 cliques | RNF | Sim |
|IN01| Deve permitir a configuração de controles de acesso | RF | Sim | 
|IN05| Ser compatível com sistemas operacionais Android e IOS| RNF | Sim | 
|IN06| Deve ter acesso facilitado para instalação, sem levar mais de 30 segundos de pesquisa direta para encontrar a aplicação nas lojas de aplicativos | RNF | Sim | 
|IN07| Deve ser de código aberto e gratuito | RNF | Sim | 
|IN08| Deve ser possível deletar reuniões armazenadas | RF | Sim |
|IN09, BR09 | Deve possuir um mecanismo de busca a partir da data da reunião | RF | Não |
|IN10, BR10 | Deve permitir que o anfitrião exclua participantes | RF | Sim | 
|IN11, OB12| Deve garantir a segurança dos dados confidenciais compartilhados durante as reuniões por vídeoconferência | RNF | Sim |
|IN12| Deve ser estável, tendo no máximo 1 queda de funcionamento por dia | RNF | Sim |
|IN13| Deve oferecer um desempenho responsivo, se adaptando mediante o tamanho da tela  | RNF | Sim | 
|OB01| Deve permitir fazer autenticação através de outros aplicativos, como Google ou Facebook | RF | Sim |
|OB02| Dever permitir convidar participantes através de compartilhamento de link por meio de outros aplicativos| RF | Sim |
|OB03| Deve possuir um link de ajuda para explicar como se convida outros participantes | RF | Não | 
|OB04| Deve possuir a opção de mutar o áudio | RF | Sim | 
|OB06| Deve permitir enviar mensagem de texto durante a videochamada | RF | Sim | 
|OB08, BR15| Os usuários devem poder compartilhar arquivos durante as reuniões | RF | Não | 
|OB10| O anfitrião deve conseguir, através do compartilhamento de tela, interagir no celular de outro usuário | RF | Não | 
|OB11| Deve permitir que o usuário configure seu perfil, com nome de usuário e foto | RF | Sim | 
|OB13| Deve possuir um calendário com chamadas agendadas | RF | Sim | 
|OB14| Deve permitir que o calendário de um usuário seja sincronizado ao de outros | RF | Não | 
|OB15| Deve permitir agendar reuniões com outros usuários através do calendário | RF | Não | 
|OB16| Deve possuir uma lista das reuniões que o usuário já participou | RF | Sim | 
|OB17| Deve ser um aplicativo que ocupe menos de 100mb de memória | RNF | Sim |


<h6 align = "center"> Tabela 1: Requisitos Elicitados.
<br> Autor(a): <a href="https://github.com/PedroSiq">Pedro Siqueira</a></h6>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 2 representa o histórico de versão do documento.
</p>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 04/10/2023 | Criação do artefato | [Pedro Siqueira](https://github.com/PedroSiq) | [Bruno Henrique](https://github.com/BrunoHenrique00)|
<h6> Tabela 2: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/PedroSiq">Pedro Siqueira</a></h6>

## **Bibliografia**
> <a href="https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/entrevista/">[1]</a>  Repositório Lichess. Acesso em 04 de Outubro de 2023.

> <a href="https://aprender3.unb.br/pluginfile.php/2692771/mod_resource/content/3/Elicitacao%20de%20Req%202.pdf">[2]</a> VAZQUEZ, Carlos; SIMÕES, Guilherme. Engenharia de requisitos. Editora Brasport, 10 ago. 2016.