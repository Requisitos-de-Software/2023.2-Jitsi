# ***Backward-From***

## **Introdução**
<p align="justify">
&emsp;&emsp; A rastreabilidade é um aspecto fundamental no desenvolvimento de software, permitindo que os desenvolvedores compreendam como os requisitos são implementados e como as mudanças afetam o sistema como um todo. Um dos métodos de rastreabilidade que será tratado nesse artefato, é o "backward-from", que liga requisitos às suas fontes.
</p>

## **Objetivo**
<p align="justify">
&emsp;&emsp; Registrar, organizar e priorizar requisitos identificados ao longo do ciclo de vida do projeto.Visando manter uma visão abrangente das necessidades do cliente, facilitando a adaptação a mudanças, aprimorando a rastreabilidade e fornecendo uma base dinâmica para o desenvolvimento iterativo e incremental.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp; No desenvolvimento do artefato, foram utilizados os requisitos funcionais não implementados e os requisitos não funcionais. Para essa construção, foi empregado o Meta-modelo de Toranzo, que classifica as informações a serem rastreadas em quatro niveis:
<li>Ambiental: informações oriundas do contexto no qual a organização
está inserida;</li>
<li> Organizacional: informações pertencentes à organização (missão,
objetivos e estratégias); </li>
<li> Gerencial: informações que auxiliam a gerência do projeto </li>
<li>Desenvolvimento: informações associadas aos diversos artefatos
gerados ao longo do processo de desenvolvimento (artefatos de
requisitos, diagramas, códigos, casos de teste e outros)</li>
</p>

## **Objetivo**
<p align="justify">
&emsp;&emsp; O objeto do Backward-From é rastrear as origens de cada requisito, fazer conexões entre os requisitos. Essa abordagem de pós-rastreabilidade é de grande importância para o entendimento da motivação por trás de cada requisito, ajudando em garantir que todos os requisitos sejam atendidos adequadamente. 

</p>

### **Requisitos Funcionais**
<p align="justify">
&emsp;&emsp;A tabela 1 apresenta os Requisitos Funcionais
</p>
| Id   | Requisito                                                       | Origem | Elos | Implementado |
|------|-----------------------------------------------------------------|--------|--------------|--------------|
| RF01 | Os usuários devem poder compartilhar suas telas durante as chamadas | [ENT01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E08 |Sim |
| RF02 | Os usuários devem ser capazes de criar uma videoconferência         | [ENT02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) | |Sim |
| RF03 | Os usuários devem poder compartilhar emojis pré-definidos durante as chamadas | [ENT03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [OB09](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | E09 |Sim |
| RF04 | Deve permitir a gravação de chamadas                                | [ENT04](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB05](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E01 |Não |
| RF05 | Deve permitir a transcrição do áudio                               | [ENT05](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [BR05](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E02|Não |
| RF06 | Deve permitir a utilização de quadro de anotação durante a chamada  | [ENT06](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN04](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E03|Não |
| RF07 | O usuário deve ser capaz de alterar seu fundo em uma chamada de vídeo | [ENT07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [BR04](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E04|Não |
| RF08 | Deve permitir a configuração de controles de acesso                  | [IN01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) | Sim |
| RF09 | Deve ser possível deletar reuniões armazenadas                       | [IN08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) | Sim |
| RF10 | Deve possuir um mecanismo de busca a partir da data da reunião       | [IN09](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR09](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E05|Não |
| RF11 | Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião | [IN10](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E06|Não |
| RF12 | Deve permitir fazer autenticação através de outros aplicativos, como Google ou Facebook | [OB01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF13 | Dever permitir convidar participantes através de compartilhamento de link por meio de outros aplicativos | [OB02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF14 | Deve possuir um link de ajuda para explicar como se convida outros participantes | [OB03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Não |
| RF15 | Deve possuir a opção de mutar o áudio                                | [OB04](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF16 | Deve permitir enviar mensagem de texto durante a videochamada         | [OB06](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF17 | Os usuários devem poder compartilhar arquivos durante as reuniões    | [OB08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR15](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E10 |Não |
| RF18 | O anfitrião deve conseguir, através do compartilhamento de tela, interagir no celular de outro usuário | [OB10](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Não |
| RF19 | Deve permitir que o usuário configure seu perfil, com nome de usuário e foto | [OB11](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF20 | Deve possuir um calendário com chamadas agendadas                   | [OB13](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Sim |
| RF21 | Deve permitir que o calendário de um usuário seja sincronizado ao de outros | [OB14](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | E07|Não |
| RF22 | Deve permitir agendar reuniões com outros usuários através do calendário | [OB15](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | E07|Não |
| RF23 | Deve permitir que o anfitrião de uma reunião consiga desligar o microfone e a câmera de qualquer participante | [BR06](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Não |
| RF24 | Deve ser possível baixar as gravações das reuniões                 | [BR08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Sim |
| RF25 | Deve fornecer ao usuário a capacidade de visualizar todas as salas em que ele participou anteriormente | [BR10](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Sim |
| RF26 | O anfitrião deve ser capaz de controlar a entrada em uma sala por meio de senha de acesso | [BR11](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Sim |
| RF27 | O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião | [BR13](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Sim |
| RF28 | Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade | [BR16](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Não |

<h6 align="center"> Tabela 1: Requisitos Funcionais.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6> e <a href="https://github.com/BrunoHenrique00">Bruno Henrique</a></h6>

### **Requisitos Não Funcionais**
<p align="justify">
&emsp;&emsp;A tabela 2 apresenta os Requisitos Não Funcionais
</p>

| Id    | Requisito                                                                                                                                        | Origem                                                                                                                                                                                                                                                                                                                                                            | Elo   | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|--------------|
| RNF01 | Deve permitir que o usuário consiga realizar qualquer atividade com menos de 5 cliques                  | [ENT08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [OB17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | E08 e E10| Sim          |
| RNF02 | Ser compatível com sistemas operacionais Android (7.0 ou mais recente) e IOS (12.4 ou mais recente)                                                                           | [IN05](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados)                                                                                                                                                                                                                                   | - | Sim          |
| RNF03 | Deve ter acesso facilitado para instalação, sem levar mais de 30 segundos de pesquisa direta para encontrar a aplicação nas lojas de aplicativos | [IN06](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados)                                                                                                                                                                                                                                   | - | Sim          |
| RNF04 | Deve ser de código aberto e gratuito                                                                                                             | [IN07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados)                                                                                                                                                                                                                                   | - | Sim          |
| RNF05 | Deve garantir a segurança dos dados confidenciais compartilhados durante as reuniões por vídeoconferência                                        | [IN11](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB12](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados)                                                                                                              | E09 | Sim          |
| RNF06 | Deve ser estável, tendo no máximo 1 queda de funcionamento por dia                                                                               | [IN12](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados)                                                                                                                                                                                                                                   | -| Sim          |
| RNF07 | Deve oferecer um desempenho responsivo, se adaptando mediante o tamanho da tela                                                                  | [IN13](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados)                                                                                                                                                                                                                                   | - | Sim          |
| RNF08 | Deve ser um aplicativo que ocupe menos de 100mb de memória                                                                                       | [OB16](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados)                                                                                                                                                                                                                                               | - | Sim          |
| RNF09 | Deve ser possível ingressar em uma reunião sem a necessidade de um login                                                                         | [BR12](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)                                                                                                                                                                                                                                            | - | Sim          |
| RNF10 | Deve possuir um bom contraste entre as cores a fim de aprimorar a legibilidade                                                                   | [BR18](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)                                                                                                                                                                                                                                            | E10 | Sim          |


<h6 align="center"> Tabela 2: Requisitos Não Funcionais.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>

### **Elos**
Para Desenvolver os elos, foi levado em consideração os principais elos de rastreabilidade: 

 <li>Satisfação: classe origem tem dependência de satisfação com a classe destino.</li>
 <li>Recurso: classe origem tem dependência de recurso com a classe destino.</li>
  <li>Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.</li>
  <li>Representação: captura a representação ou modelagem dos requisitos em outras linguagens.</li>
  <li>Alocado: classe origem está relacionada à classe destino, que representa um subsistema.</li>
  <li>Agregação: indica “composição” de elementos.</li>

#### **Elos Funcionais**
 <p align="justify">
&emsp;&emsp; A tabela 3 a seguir representa os elos dos requisitos não funcionais.
</p>

| ID    |  Requisitos    |Tipo de Elo      |
|-------|-------------------|-------------------|
| E01   |[ENT04](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN03](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB05](/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR03](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Rpresentação: [ENT04](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [IN03](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) e [OB05](/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR03](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)|
|E02| [ENT05](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [BR05](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação: [ENT05](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [BR05](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)|
|E03|  [ENT06](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN04](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR01](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação:  [ENT06](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [IN04](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) e [BR01](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)|
|E04| [ENT07](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [BR04](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) |Representação: [ENT07](/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [BR04](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) |  
|E05| [IN09](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR09](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação : [IN09](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) representa [BR09](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)| 
|E06| [IN10](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [BR07](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação: [IN10](/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) representa [BR07](/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | 
|E07| [OB14](/Elicitacao/tecnicas/observacao #requisitos-elicitados) , [OB15](/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Recurso: [OB15](/Elicitacao/tecnicas/observacao/#requisitos-elicitados) depende de um recurso de [OB14](/Elicitacao/tecnicas/observacao #requisitos-elicitados) , [OB15](/Elicitacao/tecnicas/observacao/#requisitos-elicitados)|
|E08|  [ENT01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [IN02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação:  [ENT01](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [IN02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB07](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) e [BR02](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming #requisitos-elicitados) |
|E09| [ENT03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [OB09](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados)| Representação: [ENT03](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [OB09](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados)| 
|E10| [OB08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR15](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)| Representação: [OB08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) representa [BR15](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)|
                                                                                                                                                                                                        

<h6 align="center"> Tabela 3: Elos requisitos funcionais.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>

#### **Elos Não Funcionais**
<p align="justify">
&emsp;&emsp; Todos os requisitos não funcionais são classificados no nível de desenvolvimento dentro do meta-modelo de Toranzo. Os requisitos são parte dos artefatos gerados durante o processo de desenvolvimento do sistema.
</p>

<p align="justify">
&emsp;&emsp; A tabela 4 a seguir representa os elos dos requisitos não funcionais.
</p>
| ID    |  Requisitos    |Tipo de Elo      |
|-------|-------------------|-------------------|
| E08   |[ENT08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados), [OB17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados), [BR17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados) | Representação: [ENT08](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados) representa [OB17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) e [BR17](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)|
|E09   | [IN11](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados), [OB12](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) | Representação: [IN11](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados) representa  [OB12](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados) |
|E10|  [BR18](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados), RNF01| Recurso: RNF01 depende de um recurso provido da  [BR18](https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados)                                                       

<h6 align="center"> Tabela 4: Elos requisitos não funcionais.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>


## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 5 representa o histórico de versão do documento.
</p>

| Versão | Data       | Descrição                       | Autor(es)                                            | Revisor(es)                                         |
|--------|------------|---------------------------------|------------------------------------------------------|-----------------------------------------------------|
| `1.0`  | 19/11/2023 | Criação do artefato             | [Júlia Souza](https://github.com/JuliaSSouza)        | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.1`  | 20/11/2023 | Adição Introdução e Metodologia | [Júlia Souza](https://github.com/JuliaSSouza)        | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.2`  | 20/11/2023 | Tabela Requisitos Funcionais    | [Bruno Henrique](https://github.com/BrunoHenrique00) | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.3`  | 20/11/2023 | Adição dos elos não-funcionais | [Júlia Souza](https://github.com/JuliaSSouza)        | [Pedro Siqueira](https://github.com/PedroSiq)|
| `1.4`  | 21/11/2023 | Adição dos elos funcionais | [Júlia Souza](https://github.com/JuliaSSouza)        | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.5`  | 21/11/2023 | Adição de todos os requisitos funiconais e objetivo | [Júlia Souza](https://github.com/JuliaSSouza) | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.6` | 06/12/2023 |Criação de objetivo | [Catlen Cleane](https://github.com/catlenc)| [Carolina Barbosa](https://github.com/CarolinaBarb)|




<h6 align="center"> Tabela 5: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/JuliaSSouza">Júlia Souza</a></h6>
## **Bibliografia**

> <a href="https://aprender3.unb.br/pluginfile.php/2692771/mod_resource/content/3/Elicitacao%20de%20Req%202.pdf">[1]</a> VAZQUEZ, Carlos; SIMÕES, Guilherme. Engenharia de requisitos. Editora Brasport, 10 ago. 2016. </a> 
> <a href="https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf">[2] Slides aula 26 Professora Milene Serrano Acesso em: 20/11/23. 2023. </a> 