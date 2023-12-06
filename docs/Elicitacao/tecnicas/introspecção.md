# ***Introspecção***

## **Introdução**
<p align="justify">
&emsp;&emsp;A introspecção é uma técnica na qual o Engenheiro de Requisitos <b>se coloca no lugar</b> do usuário e antecipa como o aplicativo será utilizado. Com base nessa análise, são formulados os requisitos essenciais para o correto funcionamento do sistema.
</p>

## **Objetivo**
<p align="justify">
&emsp;&emsp;O objetivo desta introspecção é <b>elicitar os requisitos funcionais e não funcionais</b> da aplicação móvel <b><i>Jitsi</i></b>. Ao utilizar a perspectiva de um membro da equipe de desenvolvimento, visa, por meio de um ponto de vista diferente do usuário, definir requisitos <b>precisos</b>, <b>melhorar a experiência</b> com usuário, <b>evitar retrabalho</b> e, consequentemente, <b>reduzir os custos</b>.
</p>

## **Cronograma**
<p align="justify">
</p>
<p align="justify">
&emsp;&emsp;A tabela 1 apresenta o Cronograma
</p>

| Nome | Data | Hora | Função |
|----|----|----|-----|
|[Catlen Cleane](https://github.com/catlenc)|03/10/2023|18:40| Desenvolvedor|
|[Pedro Siqueira](https://github.com/PedroSiq)|03/10/2023| 18:40| Desenvolvedor|
|Jaqueline|03/10/2023|18:40| Usuário(Persona)|
<h6 align = "center"> Tabela 1: Cronograma
<br> Autor(a): <a href="https://github.com/PedroSiq">Pedro Siqueira</a></h6> <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp;Consiste na criação de uma <b>simulação</b> que mostra a forma como os usuários interagem com o aplicativo. Através da elaboração de uma narrativa de um usuário, são analisados seus objetivos, tarefas e preferências, permitindo a identificação dos diferentes caminhos que os usuários podem seguir. Com base nessa análise, são definidos os requisitos funcionais e não funcionais do sistema. Essa técnica pode não ser adequada para representar fielmente os interesses reais dos interessados.
</p>


## **Narrativa**
<p align="justify">
&emsp;&emsp;Os funcionários de uma empresa trabalham remotamente e têm a necessidade de realizar reuniões por vídeoconferência com outros participantes. Essas reuniões envolvem discussões de <b>informações sigilosas</b> e, portanto, requerem uma solução segura para garantir a proteção desses <b>dados confidenciais</b>. O aplicativo deve ter um controle para garantir que apenas participantes autorizados tenham acesso às conversas virtuais. A empresa também valoriza a <b>facilidade</b> de uso e a <b>estabilidade</b> da plataforma de vídeoconferência, pois isso contribuirá para a eficiência das reuniões e para a experiência positiva dos usuários. Durante essas reuniões pode ser necessário a apresentação de materiais como textos e vídeos, daí a importância de permitir que os usuários compartilhem suas telas. Além disso, para acomodar aqueles que não puderam estar presentes ou para fins de revisão posterior, é essencial que as reuniões possam ser gravadas. Durante as interações, podem surgir pontos que necessitem ser registrados, sendo, portanto, útil ter uma funcionalidade de quadro de anotações disponível para esse propósito.
</p>

## **Requisitos Elicitados**
<p align="justify">
&emsp;&emsp;Legenda da tabela 1: 
<li> RF(Requisitos Funcionais): descrevem as funcionalidades e operações que o sistema deve realizar para atender às necessidades dos usuários. </li>
<li> RNF(Requisitos Não Funcionais): definem a qualidade e o desempenho de um sistema. </li>
<li> Identificação(IN + N°) : Requisito Elicitado pela Introspecção + Número
</p>
<p align="justify">
&emsp;&emsp;A tabela 2 representa os Requisitos Elicitados pela técnica de Introspecção.
</p>

| Identificador | Requisito | Categoria | Implementado | 
| ------------- | -------------------- | --------- | ------- | 
|IN01| Deve permitir a configuração de controles de acesso | RF | Sim | 
|IN02| Os usuários devem poder compartilhar suas telas durante as chamadas | RF| Sim | 
|IN03| Deve permitir a gravação de chamadas | RF | Não | 
|IN04| Deve permitir a utilização de quadro de anotação durante a chamada | RF | Não |
|IN05| Ser compatível com sistemas operacionais Android e IOS | RNF | Sim | 
|IN06| Deve ter acesso facilitado para instalação, sem levar mais de 30 segundos de pesquisa direta para encontrar a aplicação nas lojas de aplicativos | RNF | Sim | 
|IN07| Deve ser de código aberto e gratuito | RNF | Sim | 
|IN08| Deve ser possível deletar reuniões armazenadas | RF | Sim |
|IN09|Deve possuir um mecanismo de busca a partir da data da reunião | RF | Não |
|IN10| Deve permitir que o anfitrião tenha a capacidade de remover um participante específico da reunião | RF | Não | 
|IN11| Deve garantir a segurança dos dados confidenciais compartilhados durante as reuniões por vídeoconferência | RNF | Sim |
|IN12| Deve ser estável, tendo no máximo 1 queda de funcionamento por dia  | RNF | Sim |
|IN13| Deve oferecer um desempenho responsivo, se adaptando mediante o tamanho da tela | RNF | Sim | 

<h6 align = "center"> Tabela 2: Requisitos Elicitados.
<br> Autor(a): <a href="https://github.com/fulanodetal"><a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 3 representa o histórico de versão do documento.
</p>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 02/10/2023 | Introdução e Metodologia | [Catlen Cleane](https://github.com/catlenc) e [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Souza](https://github.com/JuliaSSouza) |
| `1.1`  | 02/10/2023 | Elicitação de Requisitos | [Catlen Cleane](https://github.com/catlenc) e [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Souza](https://github.com/JuliaSSouza) |
| `1.2`  | 03/10/2023 | Atualização do artefato | [Catlen Cleane](https://github.com/catlenc) e [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Souza](https://github.com/JuliaSSouza) |

<h6 align = "center"> Tabela 3: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/catlenc">Catlen Cleane</a></h6>


## **Bibliografia**
> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/">[1]</a> Introspecção Bilheteria Digital. Acesso em 02 de Outubro de 2023.

> <a href="https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf">[2]</a> Requisitos - Aula 07. Acesso em 02 de Outubro de 2023.