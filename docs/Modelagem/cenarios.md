# **Cenários**

## **Introdução**
<p align="justify">
&emsp;&emsp; Cenários são utilizados para descrever as situações de uso do sistema pelos usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp; Escolhemos representar os cenários conforme o modelo abaixo, tabela 1. A forma escolhida utiliza a linguagem natural para melhor entendimento de cada cenário e validação dos requisitos por parte do usuário.

</p>


|item | descrição |
|-----|-----------|
|titulo|identifica o cenário |
|objetivo|Estabelece a finalidade de um cenário |
|contexto|Descreve o estado inicial de um cenário, suas pré-condições, o local(físico) e tempo. Na sua definiçào podem ser especificadas restrições sobre estes elementos|
|recurso|Identifica os objetos passivos com os quais lidam os atores. Na sua definição podem ser especificadas restrições sobre os objetos a serem lidados pelo cenário.|
|ator|Pessoa ou estrutura organizacional que tem um papel no cenário.|
|episódio| Cada episódio representa uma ação realizada por um  ator onde participam outros atores utilizando recursos disponíveis. Um episódio também pode se referir a outro cenário. Episódios podem conter restrições e exceções. |
|exceção|Uma exceção é o tratamento para uma situação excepcional ou de erro.|

## **Cenários identificados**
<p align="justify">
&emsp;&emsp; Os cenários foram determinados a partir de requisitos funcionais priorizados como "Alta Prioridade" documentados na Priorização Three Level Scale. Eles podem ser observados por meio das tabelas abaixo.
</p>

## C01 - Gravação de chamadas 

|item | descrição |
|-----|-----------|
|tiulo|Gravação de chamadas|
|objetivo|Permitir a gravação de chamadas|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma chamada no aplicativo Jitsi <br /> 2. O usuário ativa a gravação durante a chamada <br /> 3. O sistema do Jitsi registra a chamada <br /> 4. O usuário desativa a gravação quando a chamada termina <br /> 5. O sistema do Jitsi armazena a gravação|
|Exceções|1. Falha na gravação devido a problemas técnicos <br /> 2. Usuário não tem permissão pata gravar chamadas no aplicativo Jitsi|

## C02 - Compartilhar telas durante chamadas

|item | descrição |
|-----|-----------|
|tiulo|Compartilhar telas durante chamadas|
|objetivo|Os usuários devem poder compartilhar suas telas durante as chamadas|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma chamada no aplicativo Jitsi <br /> 2. Durante a chamada, o usuário deseja compartilhar sua tela <br /> 3. O usuário ativa a função de compartilhar tela no aplicativo. <br/>4.O aplicativo inicia o compartilhamento da tela do usuário. <br/> 5.Os outros participantes da chamada visualizam a tela compartilhada em tempo real. <br/> 6.O usuário encerra o compartilhamento da tela quando desejar. |
|Exceções|1.O aplicativo encontra problemas técnicos e não consegue iniciar o compartilhamento da tela. <br/> 2.A conexão à internet é perdida, resultando na interrupção do compartilhamento de tela. <br/> 3.Alguns participantes da chamada não conseguem visualizar a tela compartilhada <br/> 4.O usuário ativa a função de compartilhamento de tela sem querer e precisa desativá-la imediatamente. |

## C03 - Remover participante específico da reunião

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||


## C04 - Baixar as gravações das reuniões

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||

## C05 - O usuário conceder permissões diferentes a cada participante para a utilização das ferramentas durante a reunião

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||

## C06 - Compartilhar durante reuniões

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||

## C07 - Modo claro ou escuro como parte das funcionalidades

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||


## C08 - Criar videoconferência

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||


## C09 - Anfitrião ter a capacidade de remover um participante específico da reunião

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||


## C10 - Opção de mutar audio 

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||

## C10 - Usuário deve configurar seu perfil, com nome de usuário e foto

|item | descrição |
|-----|-----------|
|tiulo||
|objetivo||
|Contexto||
|Recurso||
|Ator|Usuário|
|Episódio||
|Exceções||

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 3 representa o histórico de versão do documento.
</p>

| Versão | Data       | Descrição           | Autor(es)                                                                                           | Revisor(es)                                     |
|--------|------------|---------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------|
| `1.0`  | 24/10/2023 | Criação do artefato |[Júlia Vitória](https://github.com/Juhvitoria4)| [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.1`  | 24/10/2023 | Inicio da criação dos cenários | [Júlia Vitória](https://github.com/Juhvitoria4) | [Pedro Siqueira](https://github.com/PedroSiq) |


<h6 align="center"> Tabela 3: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Bibliografia**
> <a href="http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf">[1]</a> Cenários - Rastreamento de Cenários. Acesso em 24 de Outubro de 2023.