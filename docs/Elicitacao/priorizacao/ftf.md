# **First Things First**

## **Introdução**
<p align="justify">
&emsp;&emsp;A abordagem First Things First ressalta a necessidade de dar prioridade aos requisitos de maneira cuidadosa e estratégica, visando otimizar os ganhos e reduzir os riscos e custos associados ao desenvolvimento de software. Após a obtenção de vários requisitos por meio de técnicas como brainstorming, introspecção, entrevistas e observação, torna-se essencial utilizar métodos para estabelecer prioridades entre esses requisitos. Portanto, nesta seção, utiliza-se a técnica First Things First para a priorização dos requisitos.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp;Para aplicar a metodologia, é essencial desenvolver uma tabela contendo dados sobre os riscos, custos, benefícios e penalidades associadas a cada requisito do projeto. Esses aspectos devem ser avaliados em uma escala de pontuação, variando de 1 a 9, com o objetivo de equilibrar as perspectivas do cliente e do desenvolvedor. Todos os requisitos devem ser incluídos na tabela, e é necessário estimar o benefício relativo e a penalidade relativa de cada um, calcular o valor total, estimar o custo relativo e o nível de risco, e, por fim, determinar a prioridade de cada requisito.
</p>


## **Participantes**
<p align="justify">
&emsp;&emsp; A tabela 1 representa os participantes da atividade First Things First.
</p>

<center>

| Nome                                                      |   Função    |
| --------------------------------------------------------- |  ---------- |
| [Carolina Barbosa](https://github.com/CarolinaBarb)       | Mediadora |
| [Júlia Souza](https://github.com/JuliaSSouza)             | Desenvolvedora |
| <span style = "color: purple">Gabriela Silva Alves</span> |  Cliente  |


</center>

<p align="justify"></p>
<h6 align = "center"> Tabela 1: Participantes.
<br> Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a></h6>
</p>

## **Gravações**
<iframe width="560" height="315" src="https://www.youtube.com/embed/YcpCNRviV_0?si=mcdnPIlKCSEeaRob" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **Requisitos**
</p>
<p align="justify">
&emsp;&emsp;A Tabela 2 demonstra a versão final dos requisitos funcionais avaliados conforme a metodologia e os classifica de 1 até 9, baseado em sua importância.
</p>


| Identificador | Requisito | Benefício Relativo | Penalidade Relativa | Valor Total | Valor(%) | Custo Relativo | Custo(%) | Risco Relativo | Risco (%) | Prioridade |
| ------------- | ---------- | ------------------- | -------------------- | ----------- | -------- | -------------- | ----------- | ----------- | -------------- | ---------- |
| ENT01, IN02, OB07, BR02 | Os usuários devem poder compartilhar suas telas durante as chamadas | 9 | 8 | 26 | 5,52 | 3 | 2,63 | 2 | 2,86 |1,36 |
| ENT02 | Os usuários devem ser capazes de criar uma videoconferência | 9 | 9 | 27 | 5,73 | 3 | 2,63 | 1 | 1,43 | 1,71|
| ENT03, OB09 | Os usuários devem poder compartilhar emojis pré-definidos durante as chamadas | 3 | 0 | 6 |1,27  | 1 | 0,88 | 1 | 1,43 |0,80 |
| ENT04, IN03, OB05, BR03 | Deve permitir a gravação de chamadas | 9 | 9 | 27 | 5,73 | 3 | 2,63 | 2 | 2,86 | 1,41|
| ENT05, BR05 | Deve permitir a transcrição do áudio da chamada | 8 | 8 | 24 | 5,10 | 7 | 6,14 | 1 | 1,43 | 0,74|
| ENT06, IN04, BR01 | Deve permitir a utilização de quadro de anotação durante a chamada | 5 | 3 | 13 | 2,76 | 4 | 3,51 | 3 | 4,29 |0,49 |
| ENT07, BR04 | O usuário deve ser capaz de alterar seu fundo em uma chamada de vídeo | 3 | 0 | 6 | 1,27 | 2 | 1,75 | 2 | 2,86 | 0,40|
| IN01 | Deve permitir a configuração de controles de acesso | 9 | 9 | 27 | 5,73 | 8 | 7,02 | 2 | 2,86 | 0,68|
| IN08 | Deve ser possível deletar reuniões armazenadas | 5 | 0 | 10 | 2,12 | 2 | 1,75 | 1 |  1,43| 0,86|
| IN09, BR09 | Deve possuir um mecanismo de busca a partir da data da reunião | 2 | 0 | 4 | 0,85 | 1 | 0,88 | 2 | 2,86 |0,37 |
| IN10, BR07 | Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião | 9 | 9 | 27 | 5,73 | 4 | 3,51 | 1 | 1,43 | 1,36|
| OB01 | Deve permitir fazer autenticação através de outros aplicativos, como Google ou Facebook | 4 | 3 | 11 | 2,34 | 5 | 4,39 | 3 | 4,29 |0,36 |
| OB02 | Dever permitir convidar participantes através de compartilhamento de link por meio de outros aplicativos | 9 | 9 | 27 | 5,73 | 2 | 1,75 | 2 | 2,86 |1,80 |
| OB03 | Deve possuir um link de ajuda para explicar como se convida outros participantes | 1 | 1 | 3 | 0,64 | 1 | 0,88 | 1 | 1,43 | 0,40|
| OB04 | Deve possuir a opção de mutar o áudio | 9 | 9 | 27 | 5,73 |3 | 2,63 | 2 | 2,86 | 1,41|
| OB06 | Deve permitir enviar mensagem de texto durante a videochamada | 9 | 9 | 27 | 5,73 | 5 |4,39  | 3 | 4,29 | 0,88|
| OB08, BR15 | Os usuários devem poder compartilhar arquivos durante as reuniões | 7 | 5  | 19 | 4,03 | 6 |  5,26| 3 | 4,29 | 0,54|
| OB10 | O anfitrião deve conseguir, através do compartilhamento de tela, interagir no celular de outro usuário | 6 | 0 | 12 | 2,55 | 9 | 7,89 | 5 | 7,14 | 0,22|
| OB11 | Deve permitir que o usuário configure seu perfil, com nome de usuário e foto | 9 | 7 | 25 | 5,31 | 2 | 1,75 | 2 | 2,86 |1,67 |
| OB13 | Deve possuir um calendário com chamadas agendadas | 5 | 0 | 10 | 2,12 | 8 | 7,02 | 5 | 7,14 | 0,20|
| OB14 | Deve permitir que o calendário de um usuário seja sincronizado ao de outros | 3 | 0 | 6 | 1,27 | 8| 7,02 | 7 | 10 |0,10 |
| OB15 | Deve permitir agendar reuniões com outros usuários através do calendário | 7 | 3 | 17 | 3,61 | 8 | 7,02 | 6 | 8,57 |0,32 |
| OB16 | Deve possuir uma lista das reuniões que o usuário já participou | 3 | 7 | 13 | 2,76 | 2 | 1,75 | 1 | 1,43 | 1,12|
| BR06 | Deve permitir que o anfitrião de uma reunião consiga desligar o microfone e a câmera de qualquer participante | 7 | 2 |16  | 3,4 | 4 | 3,51 | 4 | 5,71 | 0,53|
| BR08 | Deve ser possível baixar as gravações das reuniões | 9 | 7 | 25 | 3,40 | 2 | 1,75 | 2 | 2,86 | 1,07|
| BR10 | Deve fornecer ao usuário a capacidade de visualizar todas as salas em que ele participou anteriormente. |2 | 0 |  4 | 5,31 | 2 | 1,75 | 1 | 1,43 |2,15 |
| BR11 | O anfitrião deve ser capaz de controlar a entrada em uma sala por meio de senha de acesso | 0 | 0  | 0 | 0 | 1 | 0,88| 1 | 1,43 |0 |
| BR13 | O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião | 5 | 3 | 13 | 2,76 | 5 |4,39 | 3 | 4,29 | 0,42|
| BR16 | Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade | 7 | 5 | 19 | 4,03 | 3 | 2,63| 1 | 1,43 | 0|  


<p align="justify">
<h6 align = "center"> Figura/Tabela 2: Requisitos avaliados.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a> e <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a></h6>
</p>

## **Legenda**

<p align="justify"> 
<li> RF(Requisitos Funcionais): descrevem as funcionalidades e operações que o sistema deve realizar para atender às necessidades dos usuários. </li>
<li> RNF(Requisitos Não Funcionais): definem a qualidade e o desempenho de um sistema. </li>
<li> Identificação(ENT + N°) : Requisito Elicitado pela Entrevista + Número.
<li> Identificação(BR + N°) : Requisito Elicitado pela Brainstorming + Número
<li> Identificação(IN + N°) : Requisito Elicitado pela Introspecção + Número
<li> Identificação(OB + N°) : Requisito Elicitado pela Observação + Número
</p>


## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 3 representa o histórico de versão do documento.
</p>

| Versão | Data       | Descrição           | Autor(es)                                                                                           | Revisor(es)                                     |
|--------|------------|---------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------|
| `1.0`  | 04/10/2023 | Criação do artefato | [Júlia Souza](https://github.com/JuliaSSouza) e [Carolina Barbosa](https://github.com/CarolinaBarb) | [Júlia Vitória](https://github.com/Juhvitoria4) |
| `1.1`  | 17/10/2023 | Refatoração do documento |[Carolina Barbosa](https://github.com/CarolinaBarb) e  [Júlia Souza](https://github.com/JuliaSSouza)  | [Júlia Vitória](https://github.com/Juhvitoria4) |

<h6 align="center"> Tabela 3: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Bibliografia**
> <a href="https://aprender3.unb.br/pluginfile.php/2692778/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf">[1]</a> WIEGERS, Karl, BEATTY, Joy. Software Requirements, Third Edition. Microsoft Press, Agosto, 2013. Disponível em: