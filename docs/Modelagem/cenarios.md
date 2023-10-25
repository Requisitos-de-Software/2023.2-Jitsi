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
|tiulo|Remover participante específico da reunião |
|objetivo|Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma reunião no aplicativo <br/> 2.Durante a reunião, o usuário identifica um participante que deseja remover.<br/>3. O anfitrião do usuário ativa a função de remoção para o participante selecionado. <br/> 4.O sistema do aplicativo remove o participante da reunião.|
|Exceções|1. Falha na remoção devido a problemas técnicos ou falhas no sistema <br/> 2.O anfitrião do usuário não tem permissão para remover participantes, possivelmente devido a configurações de privacidade ou funções restritas.|


## C04 - Baixar as gravações das reuniões

|item | descrição |
|-----|-----------|
|tiulo|Baixar as gravações das reuniões|
|objetivo|Deve ser possível baixar as gravações das reuniões|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário abre o aplicativo Jitsi.<br/>2.O usuário navega para a seção de "Gravações" ou "Reuniões Anteriores".<br/>3.O usuário seleciona a reunião que deseja baixar a gravação.<br/>4.O sistema do Jitsi permite o download da gravação.<br/>5.O usuário inicia o download da gravação.<br/>6.O sistema do Jitsi inicia o download da gravação para o dispositivo do usuário.|
|Exceções|1.Falha no download devido a problemas técnicos ou perda de conexão com a internet.<br/>2.Não há gravações disponíveis para download, pois o usuário não gravou nenhuma reunião anteriormente.|

## C05 - O usuário conceder permissões diferentes a cada participante para a utilização das ferramentas durante a reunião

|item | descrição |
|-----|-----------|
|tiulo| O usuário conceder permissões diferentes a cada participante para a utilização das ferramentas durante a reunião |
|objetivo|O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário acessa o aplicativo de reunião.<br/>2.O usuário navega para a seção de gravações.<br/>3.O sistema exibe uma lista das reuniões passadas com gravações disponíveis.<br/>4.O usuário seleciona a reunião da qual deseja baixar a gravação.<br/>5.O sistema permite que o usuário faça o download da gravação.<br/>6.O usuário completa o download e a gravação é armazenada em seu dispositivo.|
|Exceções|1.Se não houver gravações disponíveis para a reunião selecionada, o sistema exibe uma mensagem informando que não há gravações para download.<br/>2.Falhas técnicas podem interromper o processo de download, nesse caso, o sistema fornece uma mensagem de erro e orientações para solucionar o problema.|

## C06 - Compartilhar durante reuniões

|item | descrição |
|-----|-----------|
|tiulo|Compartilhar durante reuniões|
|objetivo|Os usuários devem poder compartilhar arquivos durante as reuniões|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia uma reunião usando o aplicativo.<br/>2.Durante a reunião, o usuário deseja compartilhar um arquivo.<br/>3.O usuário ativa a função de compartilhamento de arquivos no aplicativo.<br/>4.O usuário seleciona o arquivo que deseja compartilhar.<br/>5.O arquivo é compartilhado com os outros participantes da reunião.<br/>6.Os outros participantes podem visualizar o arquivo compartilhado|
|Exceções|1.Falha no compartilhamento de arquivos devido a problemas técnicos, como indisponibilidade de conexão ou falha no sistema.<br/>2.Alguns participantes da reunião não conseguem visualizar o arquivo compartilhado devido a incompatibilidades técnicas ou configurações inadequadas.|

## C07 - Modo claro ou escuro como parte das funcionalidades

|item | descrição |
|-----|-----------|
|tiulo|Modo claro ou escuro como parte das funcionalidades |
|objetivo|Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia o aplicativo.<br/>2.No aplicativo, o usuário acessa as configurações de interface.<br/>3.O usuário seleciona a opção de "Modo Claro" ou "Modo Escuro" com base em suas preferências.<br/>4.O aplicativo aplica o modo de interface escolhido pelo usuário.<br/>5.O usuário utiliza o aplicativo no modo de interface selecionado|
|Exceções|1.O aplicativo encontra problemas técnicos e não consegue alternar entre os modos de interface (claro ou escuro).<br/>2.A mudança de modo de interface não é aplicada corretamente devido a erros no sistema.<br/>3.O usuário não encontra a opção de "Modo Claro" ou "Modo Escuro" nas configurações de interface, devido a limitações do aplicativo ou versão desatualizada.<br/>4.A preferência de modo de interface do usuário não é salva corretamente, resultando em uma configuração incorreta na próxima vez que o aplicativo for iniciado.|


## C08 - Criar videoconferência

|item | descrição |
|-----|-----------|
|tiulo|Criar videoconferência|
|objetivo|Os usuários devem ser capazes de criar uma videoconferência|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia o aplicativo.<br/>2.O usuário seleciona a opção "Criar videoconferência."<br/>3.O sistema inicia a configuração da videoconferência.<br/>4.O usuário especifica os detalhes da videoconferência, como título, participantes, data e hora.<br/>5.O sistema cria a videoconferência e gera um link de acesso.<br/>6.O usuário compartilha o link com os participantes.<br/>7.Os participantes se juntam à videoconferência no horário agendado.<br/>8.O usuário pode gerenciar a videoconferência, incluindo funções de controle, como mutar participantes ou compartilhar a tela.|
|Exceções|1.Problemas técnicos impedem a criação da videoconferência, como falhas no sistema.<br/>2.O usuário não tem permissão para criar videoconferências devido a configurações de privacidade ou permissões inadequadas.|


## C09 - Opção de mutar audio 

|item | descrição |
|-----|-----------|
|tiulo|opção de mutar o áudio|
|objetivo|Deve possuir a opção de mutar o áudio|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia uma chamada no aplicativo.<br/>2.Durante a chamada, o usuário deseja silenciar seu áudio.<br/>3.O usuário ativa a função de mutar áudio no aplicativo.<br/>4.O áudio do usuário é silenciado, tornando-o inaudível para os outros participantes.<br/>5.O usuário desativa a função de mutar áudio quando desejar, permitindo que sua voz seja ouvida novamente.|
|Exceções|1.Falha na função de mutar áudio devido a problemas técnicos.<br/>2.O usuário não tem permissão para silenciar seu áudio devido a configurações de privacidade ou permissões inadequadas.|

## C10 - Usuário deve configurar seu perfil, com nome de usuário e foto

|item | descrição |
|-----|-----------|
|tiulo| Usuário deve configurar seu perfil, com nome de usuário e foto|
|objetivo| Deve permitir que o usuário configure seu perfil, com nome de usuário e foto|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário abre o aplicativo.<br/>2.O usuário acessa a seção de configurações do perfil.<br/>3.O usuário escolhe um nome de usuário.<br/>4.O usuário tem a opção de adicionar uma foto ao perfil.<br/>5.O usuário salva as configurações do perfil.|
|Exceções|1.Falha na conexão com a internet, impedindo o usuário de salvar as configurações.<br/>2.O usuário tenta usar um nome de usuário já em uso por outro usuário.<br/>3.Problemas técnicos impedem o usuário de adicionar uma foto ao perfil.|

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 3 representa o histórico de versão do documento.
</p>

| Versão | Data       | Descrição           | Autor(es)                                                                                           | Revisor(es)                                     |
|--------|------------|---------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------|
| `1.0`  | 24/10/2023 | Criação do artefato |[Júlia Vitória](https://github.com/Juhvitoria4)| [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.1`  | 24/10/2023 | Inicio da criação dos cenários | [Júlia Vitória](https://github.com/Juhvitoria4) | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.2`  | 25/10/2023 | Finalização dos cenários | [Júlia Vitória](https://github.com/Juhvitoria4) | [Pedro Siqueira](https://github.com/PedroSiq) |


<h6 align="center"> Tabela 3: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Bibliografia**
> <a href="http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf">[1]</a> Cenários - Rastreamento de Cenários. Acesso em 24 de Outubro de 2023.