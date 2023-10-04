# ***Introspecção***

## **Introdução**
<p align="justify">
&emsp;&emsp;A introspecção é uma técnica na qual o Engenheiro de Requisitos se coloca no lugar do usuário e antecipa como o aplicativo será utilizado. Com base nessa análise, são formulados os requisitos essenciais para o correto funcionamento do sistema. Com isso define-se requisitos mais precisos, melhora a experiência com usuário, evita retrabalho e consequentemente reduz os custos.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp;A metodologia consistiu na criação de uma simulação que nos mostra a forma como os usuários interagem com o aplicativo. Através da elaboração de uma narrativa de um usuário, analisamos seus objetivos, tarefas e preferências, permitindo-nos identificar os diferentes caminhos que os usuários podem seguir. Com base nessa análise, definimos os requisitos funcionais e não funcionais do sistema.
</p>

## **Narrativa**
<p align="justify">
&emsp;&emsp;Os funcionários de uma empresa trabalham remotamente e têm a necessidade de realizar reuniões por vídeoconferência com outros participantes. Essas reuniões envolvem discussões de informações sigilosas e, portanto, requerem uma solução segura para garantir a proteção desses dados confidenciais. O aplicativo deve ter um controle para garantir que apenas participantes autorizados tenham acesso às conversas virtuais. A empresa também valoriza a facilidade de uso e a estabilidade da plataforma de vídeoconferência, pois isso contribuirá para a eficiência das reuniões e para a experiência positiva dos usuários. Durante essas reuniões pode ser necessário a apresentação de materiais como textos e vídeos, daí a importância de permitir que os usuários compartilhem suas telas. Além disso, para acomodar aqueles que não puderam estar presentes ou para fins de revisão posterior, é essencial que as reuniões possam ser gravadas. Durante as interações, podem surgir pontos que necessitem ser registrados, sendo, portanto, útil ter uma funcionalidade de quadro de anotações disponível para esse propósito.
</p>

## **Requisitos Elicitados**
<p align="justify">
&emsp;&emsp;Legenda da tabela 1: 
<li> RF(Requisitos Funcionais): descrevem as funcionalidades e operações que o sistema deve realizar para atender às necessidades dos usuários. </li>
<li> RNF(Requisitos Não Funcionais): definem a qualidade e o desempenho de um sistema. </li>
<li> Identificação(IN + N°) : Requisito Elicitado pela Introspecção + Número
</p>
<p align="justify">
&emsp;&emsp;A tabela 1 representa os Requisitos Elicitados pela técnica de Introspecção
</p>

| Identificação  | Descrição  | Categoria | 
|-----|---------------------------------------------------------|-------|
|IN01| Deve permitir a configuração de controles de acesso | RF |
|IN02| O usuário deve ser capaz de compartilhar sua tela durante as reuniões | RF|
|IN03| Deve permitir a gravação de reuniões  | RF |
|IN04| Deve haver uma funcionalidade de quadro de anotações disponível | RF |
|IN05| Ser compatível com sistemas operacionais Android e IOS| RNF|
|IN06| Deve ser fácil de instalar e usar|RNF|
|IN07| Ser de código aberto e gratuíto| RNF|
|IN08| Deve ser possível deletar reuniões armazenadas | RF|
|IN09|Deve possuir um mecanismo de busca a partir da data da reunião| RF|
|IN10| Deve permitir que o anfitrião exclua particpantes | RF|
|IN11| Deve garantir a segurança dos dados confidenciais compartilhados durante as reuniões por vídeoconferência| RNF |
|IN12| Deve ser estável | RNF|
|IN13| Deve oferecer um desempenho rápido e responsivo | RNF |
|IN14| Deve ser escalável para acomodar um número crescente de participantes | RNF |

<h6 align = "center"> Tabela 01: Requisitos Elicitados
<br> Autor(a): <a href="https://github.com/fulanodetal"><a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela n representa o histórico de versão do documento.
</p>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 02/10/2023 | Introdução e Metodologia | [Catlen Cleane](https://github.com/catlenc) e [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Souza](https://github.com/JuliaSSouza) |
| `1.1`  | 02/10/2023 | Elicitação de Requisitos | [Catlen Cleane](https://github.com/catlenc) e [Pedro Siqueira](https://github.com/PedroSiq) | [Júlia Souza](https://github.com/JuliaSSouza) |
<h6> Tabela n: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>

## **Bibliografia**
> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/">[1]</a> Introspecção Bilheteria Digital. Acesso em 02 de Outubro de 2023.

> <a href="https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf">[2]</a> Requisitos - Aula 07. Acesso em 02 de Outubro de 2023.