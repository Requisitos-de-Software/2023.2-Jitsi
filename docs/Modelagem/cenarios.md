# **Cenários**

## **Introdução**
<p align="justify">
&emsp;&emsp;Cenários são utilizados para descrever as <b>situações de uso</b> do sistema pelos usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos.
</p>

## **Objetivo**
<p align="justify">
&emsp;&emsp; O objetivo deste artefato é representar e documentar os cenários de uso do sistema de maneira eficaz, utilizando uma abordagem que emprega linguagem natural. Isso visa proporcionar uma compreensão clara e abrangente das interações do usuário com o sistema, facilitando a validação dos requisitos pelo usuário final.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp; Escolhemos representar os cenários conforme o modelo abaixo, tabela 1. A forma escolhida utiliza a linguagem natural para melhor entendimento de cada cenário e validação dos requisitos por parte do usuário.
</p>


|Item | Descrição |
|-----|-----------|
|Título|Identifica o cenário |
|Objetivo|Estabelece a finalidade de um cenário |
|Contexto|Descreve o estado inicial de um cenário, suas pré-condições, o local (físico) e tempo. Na sua definição podem ser especificadas restrições sobre estes elementos|
|Recurso|Identifica os objetos passivos com os quais lidam os atores. Na sua definição podem ser especificadas restrições sobre os objetos a serem lidados pelo cenário.|
|Ator|Pessoa ou estrutura organizacional que tem um papel no cenário.|
|Episódio| Cada episódio representa uma ação realizada por um  ator onde participam outros atores utilizando recursos disponíveis. Um episódio também pode se referir a outro cenário. Episódios podem conter restrições e exceções. |
|Exceção|Uma exceção é o tratamento para uma situação excepcional ou de erro.|

<h6 align="center"> Tabela 1: Modelo de Tabela de Cenário.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Cenários Identificados**
<p align="justify">
&emsp;&emsp; Os cenários foram determinados a partir de requisitos funcionais priorizados como "Alta Prioridade" documentados na Priorização Three Level Scale. Eles podem ser observados por meio das tabelas abaixo.
</p>

## **C01 - Gravação de Chamadas**
<p align="justify">
&emsp;&emsp;A tabela 2 representa o primeiro cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Gravação de chamadas|
|Objetivo|Permitir a gravação de chamadas|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma chamada no aplicativo Jitsi <br /> 2. O usuário ativa a gravação durante a chamada <br /> 3. O sistema do Jitsi registra a chamada <br /> 4. O usuário desativa a gravação quando a chamada termina <br /> 5. O sistema do Jitsi armazena a gravação|
|Exceções|1. Falha na gravação devido a problemas técnicos <br /> 2. Usuário não tem permissão pata gravar chamadas no aplicativo Jitsi|

<h6 align="center"> Tabela 2: Cenário 01.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C02 - Compartilhar Telas Durante Chamadas**
<p align="justify">
&emsp;&emsp;A tabela 3 representa o segundo cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Compartilhar telas durante chamadas|
|Objetivo|Os usuários devem poder compartilhar suas telas durante as chamadas|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma chamada no aplicativo Jitsi <br /> 2. Durante a chamada, o usuário deseja compartilhar sua tela <br /> 3. O usuário ativa a função de compartilhar tela no aplicativo. <br/>4.O aplicativo inicia o compartilhamento da tela do usuário. <br/> 5.Os outros participantes da chamada visualizam a tela compartilhada em tempo real. <br/> 6.O usuário encerra o compartilhamento da tela quando desejar. |
|Exceções|1.O aplicativo encontra problemas técnicos e não consegue iniciar o compartilhamento da tela. <br/> 2.A conexão à internet é perdida, resultando na interrupção do compartilhamento de tela. <br/> 3.Alguns participantes da chamada não conseguem visualizar a tela compartilhada <br/> 4.O usuário ativa a função de compartilhamento de tela sem querer e precisa desativá-la imediatamente. |

<h6 align="center"> Tabela 3: Cenário 02.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C03 - Remover Participante Específico Da Reunião**
<p align="justify">
&emsp;&emsp;A tabela 4 representa o terceiro cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Remover participante específico da reunião |
|objetivo|Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1. O usuário inicia uma reunião no aplicativo <br/> 2.Durante a reunião, o usuário identifica um participante que deseja remover.<br/>3. O anfitrião do usuário ativa a função de remoção para o participante selecionado. <br/> 4.O sistema do aplicativo remove o participante da reunião.|
|Exceções|1. Falha na remoção devido a problemas técnicos ou falhas no sistema <br/> 2.O anfitrião do usuário não tem permissão para remover participantes, possivelmente devido a configurações de privacidade ou funções restritas.|

<h6 align="center"> Tabela 4: Cenário 03.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>


## **C04 - Baixar As Gravações Das Reuniões**
<p align="justify">
&emsp;&emsp;A tabela 5 representa o quarto cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Baixar as gravações das reuniões|
|Objetivo|Deve ser possível baixar as gravações das reuniões|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário abre o aplicativo Jitsi.<br/>2.O usuário navega para a seção de "Gravações" ou "Reuniões Anteriores".<br/>3.O usuário seleciona a reunião que deseja baixar a gravação.<br/>4.O sistema do Jitsi permite o download da gravação.<br/>5.O usuário inicia o download da gravação.<br/>6.O sistema do Jitsi inicia o download da gravação para o dispositivo do usuário.|
|Exceções|1.Falha no download devido a problemas técnicos ou perda de conexão com a internet.<br/>2.Não há gravações disponíveis para download, pois o usuário não gravou nenhuma reunião anteriormente.|

<h6 align="center"> Tabela 5: Cenário 04.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C05 - O Usuário Deve Poder Conceder Permissões Diferentes A Cada Participante Para A Utilização Das Ferramentas Durante A Reunião**
<p align="justify">
&emsp;&emsp;A tabela 6 representa o quinto cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título| O usuário deve poder conceder permissões diferentes a cada participante para a utilização das ferramentas durante a reunião |
|Objetivo|O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário acessa o aplicativo de reunião.<br/>2.O usuário navega para a seção de gravações.<br/>3.O sistema exibe uma lista das reuniões passadas com gravações disponíveis.<br/>4.O usuário seleciona a reunião da qual deseja baixar a gravação.<br/>5.O sistema permite que o usuário faça o download da gravação.<br/>6.O usuário completa o download e a gravação é armazenada em seu dispositivo.|
|Exceções|1.Se não houver gravações disponíveis para a reunião selecionada, o sistema exibe uma mensagem informando que não há gravações para download.<br/>2.Falhas técnicas podem interromper o processo de download, nesse caso, o sistema fornece uma mensagem de erro e orientações para solucionar o problema.|

<h6 align="center"> Tabela 6: Cenário 05.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C06 - Compartilhar Arquivos Durante reuniões**
<p align="justify">
&emsp;&emsp;A tabela 7 representa o sexto cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Compartilhar arquivos durante reuniões|
|Objetivo|Os usuários devem poder compartilhar arquivos durante as reuniões|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia uma reunião usando o aplicativo.<br/>2.Durante a reunião, o usuário deseja compartilhar um arquivo.<br/>3.O usuário ativa a função de compartilhamento de arquivos no aplicativo.<br/>4.O usuário seleciona o arquivo que deseja compartilhar.<br/>5.O arquivo é compartilhado com os outros participantes da reunião.<br/>6.Os outros participantes podem visualizar o arquivo compartilhado|
|Exceções|1.Falha no compartilhamento de arquivos devido a problemas técnicos, como indisponibilidade de conexão ou falha no sistema.<br/>2.Alguns participantes da reunião não conseguem visualizar o arquivo compartilhado devido a incompatibilidades técnicas ou configurações inadequadas.|

<h6 align="center"> Tabela 7: Cenário 05.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C07 - Modo Claro Ou Escuro Como Parte Das Funcionalidades**
<p align="justify">
&emsp;&emsp;A tabela 8 representa o sétimo cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Modo claro ou escuro como parte das funcionalidades |
|Objetivo|Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia o aplicativo.<br/>2.No aplicativo, o usuário acessa as configurações de interface.<br/>3.O usuário seleciona a opção de "Modo Claro" ou "Modo Escuro" com base em suas preferências.<br/>4.O aplicativo aplica o modo de interface escolhido pelo usuário.<br/>5.O usuário utiliza o aplicativo no modo de interface selecionado|
|Exceções|1.O aplicativo encontra problemas técnicos e não consegue alternar entre os modos de interface (claro ou escuro).<br/>2.A mudança de modo de interface não é aplicada corretamente devido a erros no sistema.<br/>3.O usuário não encontra a opção de "Modo Claro" ou "Modo Escuro" nas configurações de interface, devido a limitações do aplicativo ou versão desatualizada.<br/>4.A preferência de modo de interface do usuário não é salva corretamente, resultando em uma configuração incorreta na próxima vez que o aplicativo for iniciado.|

<h6 align="center"> Tabela 8: Cenário 07.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C08 - Criar Uma Videoconferência**
<p align="justify">
&emsp;&emsp;A tabela 9 representa o oitavo cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Criar uma videoconferência|
|Objetivo|Os usuários devem ser capazes de criar uma videoconferência|
|Contexto|Local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia o aplicativo.<br/>2.O usuário seleciona a opção "Criar videoconferência."<br/>3.O sistema inicia a configuração da videoconferência.<br/>4.O usuário especifica os detalhes da videoconferência, como título, participantes, data e hora.<br/>5.O sistema cria a videoconferência e gera um link de acesso.<br/>6.O usuário compartilha o link com os participantes.<br/>7.Os participantes se juntam à videoconferência no horário agendado.<br/>8.O usuário pode gerenciar a videoconferência, incluindo funções de controle, como mutar participantes ou compartilhar a tela.|
|Exceções|1.Problemas técnicos impedem a criação da videoconferência, como falhas no sistema.<br/>2.O usuário não tem permissão para criar videoconferências devido a configurações de privacidade ou permissões inadequadas.|

<h6 align="center"> Tabela 9: Cenário 08.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C09 - Emudecer o Áudio** 
<p align="justify">
&emsp;&emsp;A tabela 10 representa o nono cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título|Emudecer o áudio|
|Objetivo|Deve possuir a opção de emudecer o áudio|
|Contexto|Local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário inicia uma chamada no aplicativo.<br/>2.Durante a chamada, o usuário deseja silenciar seu áudio.<br/>3.O usuário ativa a função de mutar áudio no aplicativo.<br/>4.O áudio do usuário é silenciado, tornando-o inaudível para os outros participantes.<br/>5.O usuário desativa a função de mutar áudio quando desejar, permitindo que sua voz seja ouvida novamente.|
|Exceções|1.Falha na função de mutar áudio devido a problemas técnicos.<br/>2.O usuário não tem permissão para silenciar seu áudio devido a configurações de privacidade ou permissões inadequadas.|

<h6 align="center"> Tabela 10: Cenário 09.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **C10 - Usuário Deve Poder Configurar Seu Perfil**
<p align="justify">
&emsp;&emsp;A tabela 11 representa o décimo cenário identificado.
</p>

|Item | Descrição |
|-----|-----------|
|Título| Usuário deve poder configurar seu perfil|
|objetivo| Deve permitir que o usuário configure seu perfil, com nome de usuário e foto|
|Contexto|local: no trabalho ou em casa <br /> Tempo: em qualquer horário <br />Pré-condições: acesso à internet, ter o aplicativo instalado|
|Recurso|Smartphone <br /> internet|
|Ator|Usuário|
|Episódio|1.O usuário abre o aplicativo.<br/>2.O usuário acessa a seção de configurações do perfil.<br/>3.O usuário escolhe um nome de usuário.<br/>4.O usuário tem a opção de adicionar uma foto ao perfil.<br/>5.O usuário salva as configurações do perfil.|
|Exceções|1.Falha na conexão com a internet, impedindo o usuário de salvar as configurações.<br/>2.O usuário tenta usar um nome de usuário já em uso por outro usuário.<br/>3.Problemas técnicos impedem o usuário de adicionar uma foto ao perfil.|

<h6 align="center"> Tabela 11: Cenário 10.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 12 representa o histórico de versão do documento.
</p>

| Versão | Data       | Descrição           | Autor(es)                                                                                           | Revisor(es)                                     |
|--------|------------|---------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------|
| `1.0`  | 24/10/2023 | Criação do artefato |[Júlia Vitória](https://github.com/Juhvitoria4)| [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.1`  | 24/10/2023 | Inicio da criação dos cenários | [Júlia Vitória](https://github.com/Juhvitoria4) | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.2`  | 25/10/2023 | Finalização dos cenários | [Júlia Vitória](https://github.com/Juhvitoria4) | [Pedro Siqueira](https://github.com/PedroSiq) |
| `1.3`  | 26/10/2023 | Revisão do documento e alterações finais | [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Vitória](https://github.com/Juhvitoria4) |


<h6 align="center"> Tabela 12: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/Juhvitoria4">Júlia Vitória</a></h6>

## **Bibliografia**
> <a href="http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf">[1]</a> Cenários - Rastreamento de Cenários. Acesso em 24 de Outubro de 2023.