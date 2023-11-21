# ***Forward-From***

## **Introdução**
<p align="justify">
&emsp;&emsp;A rastreabilidade no contexto do desenvolvimento de software refere-se à capacidade de acompanhar e entender como os requisitos evoluem ao longo do processo de criação do software. Isso envolve a habilidade de rastrear e documentar como os requisitos são implementados e como as alterações realizadas ao longo do desenvolvimento impactam o sistema como um todo. Ela proporciona uma visão clara e organizada da relação entre os requisitos estabelecidos inicialmente e as diversas fases de desenvolvimento, garantindo uma compreensão abrangente do sistema em construção. O método que será usado nesse artefato é o Forward-From.
</p>

## **Objetivo**
<p align="justify">
&emsp;&emsp;O uso do Forward-from na pós-rastreabilidade tem como objetivo estabelecer uma conexão clara entre os requisitos do sistema e as decisões de design ou implementação tomadas durante o desenvolvimento de software. Especificamente, busca-se documentar e acompanhar como as escolhas de implementação estão alinhadas com os requisitos iniciais, permitindo uma análise retroativa que evidencia como cada componente do sistema contribui para atender às exigências estabelecidas. Dessa forma, o Forward-from atua como uma ferramenta valiosa para garantir a consistência e a transparência ao longo do ciclo de vida do software, facilitando a compreensão e a manutenção do sistema ao longo do tempo.
</p>

## **Metodologia**
<p align="justify">
&emsp;&emsp;Inicialmente, todos os documentos pertinentes foram organizados para análise e sumarização. Para abordar os requisitos funcionais, cada história de usuário foi cuidadosamente relacionada ao seu correspondente épico, tema, cenário, léxico, caso de uso, e à fonte onde foi elicitada. 
</p>

<p align="justify">
&emsp;&emsp;No caso dos requisitos não funcionais, cada requisito foi vinculado ao seu respectivo NFR, Especificação Suplementar e à fonte onde foi elicitado. Essa abordagem visa garantir uma análise abrangente e transparente da relação entre os requisitos estabelecidos e as decisões de implementação, promovendo assim uma pós-rastreabilidade eficaz ao longo do ciclo de desenvolvimento do software.
</p>

## **Mapeamento**
<p align="justify">
&emsp;&emsp;Para realizar o mapeamento dos requisitos, será utilizado a tabela 01 na qual contém todos os simbolos necessários para o bom entendimento dos tópicos abaixo:
</p>

<center>

| Legenda | Artefato                   |
|---------|----------------------------|
| BR      | Brainstorming              |
| UC      | Casos de Uso               |
| C       | Cénarios                   |
| EN      | Entrevista                 |
| ES      | Especificação Suplementar  |
| EP      | Épico                      |
| US      | Historia de Usuário        |
| IN      | Introspecção               |
| L       | Léxico                     |
| O       | Observação                 |
| Q       | Questionário               |
| RF      | Requisitos Funcionais      |
| RNF     | Requisistos Não Funcionais |
| T       | Tema                       |

</center>

<p align="justify">
<h6 align = "center"> Tabela 01: Legenda.
<br> Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a></h6>
</p>

## **Requisitos Funcionais**
<p align="justify">
&emsp;&emsp;Das tabelas 02 a 28 contém os requisitos funcionais.
</p>


<details>
   <summary>RF01 - Poder compartilhar suas telas durante as chamadas</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E02</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US02</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN02</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR02</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN01</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB07</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L05</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C02</a></td>
      </tr>
    </tbody>
  </table>
  <p>Tabela 02: RF01, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RF02 - Criar uma videoconferência</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US08</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L02</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C08</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 03: RF02, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RF03 - Compartilhar emojis pré-definidos durante as chamadas</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US11</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN03</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB09</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L10</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC03</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C06</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 04: RF03, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RF04 - Permitir a gravação de chamadas</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td> Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN03</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR03</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN04</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB05</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L04</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC02</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C01</a></td>
      </tr>
    </tbody>
  </table>
  <p>Tabela 05: RF04, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF05 - Transcrição do áudio da chamada</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR05</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN05</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C01</a></td>
      </tr>
    </tbody>
  </table>
  <p>Tabela 06: RF05, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF06 -  utilização de quadro de anotação durante a chamada</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN04</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR01</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN06</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C01</a></td>
      </tr>
    </tbody>
  </table>
  <p>Tabela 07: RF06, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF07 - O usuário deve ser capaz de alterar seu fundo em uma chamada de vídeo</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US14</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR04</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/">EN07</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 08: RF07, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF08 - Deve permitir a configuração de controles de acesso </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E5</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US15</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN01</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 09: RF08, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF09 - Deletar reuniões armazenadas</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E6</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US16</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN08</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 10: RF09, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF10 - Possuir um mecanismo de busca a partir da data da reunião</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E6</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US17</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados/">IN09</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR09</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 11: RF10, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF11 - O anfitrião tenha a capacidade de remover um participante específico da reunião</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US03</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">INT10</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados">BR07</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C03</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 12: RF11, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF12 - Fazer autenticação através de outros aplicativos, como Google ou Facebook</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US18</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados">OB01</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 13: RF12, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF13 - Convidar participantes através de compartilhamento de link por meio de outros aplicativos</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E5</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US19</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 14: RF13, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF14 - Opção de mutar o áudio</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US09</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB04</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C09</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 15: RF14, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF15 - Enviar mensagem de texto durante a videochamada</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US13</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidades de Comunicação e COlaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB06</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 14: RF15, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF16 - Compartilhar arquivos durante as reuniões</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US06</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>NFuncionalidades de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR15</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB08</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 17: RF16, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF17 - O usuário configure seu perfil, com nome de usuário e foto</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US10</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB11</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C10</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 18: RF17, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF19 - Possuir um calendário com chamadas agendadas</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US21</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB13</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 20: RF19, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF20 - O calendário de um usuário seja sincronizado ao de outros</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US22</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB14</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 21: RF20, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF21 - Agendar reuniões com outros usuários através do calendário</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US23</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Pwersonalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/">OB15</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 22: RF21, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF22 - O anfitrião de uma reunião consiga desligar o microfone e a câmera de qualquer participante</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E5</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US24</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR06</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 23: RF22, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF23 - Ser possível baixar as gravações das reuniões</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US04</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade de Comunicação e Colaboração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR08</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C04</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 24: RF23, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF24 - Fornecer ao usuário a capacidade de visualizar todas as salas em que ele participou anteriormente</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E6</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US25</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR10</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 25: RF24, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF25 - Ser capaz de controlar a entrada em uma sala por meio de senha de acesso</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E5</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US26</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR11</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">-</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 26: RF25, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF26 - O anfitrião deve ser capaz de conceder permissões diferentes, a cada participante, para a utilização das ferramentas durante a reunião</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E5</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>NPersonalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR13</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C05</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 27: RF26, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

<details>
   <summary>RF27 - Deve oferecer um modo claro ou escuro de interface como parte de suas funcionalidades de acessibilidade</summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/historias/">US07</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Personalização e Configuração</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/">BR16</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/lexico/">-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/casosDeUso/">-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/cenarios/">C07</a></td>
      </tr>
    </tbody>
  </table>
<p>Tabela 28: RF27, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>
</details>

## **Requisitos Não Funcionais**
<p align="justify">
&emsp;&emsp;Das tabelas 29 a 38 contém os requisitos não funcionais.
</p>

<details>
   <summary>RNF01 - Deve ter uma interface clara e intuitiva, permitindo que o usuário consiga realizar qualquer atividade com menos de 5 cliques </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Desempenho</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/entrevista/#requisitos-elicitados">ENT08</a> / <a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados">OB17</a> / <a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados">BR17</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 29: RNF01, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>


<details>
   <summary>RNF02 - Ser compatível com sistemas operacionais Android e IOS </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Usabilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">SU01</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN05</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 30: RNF02, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>


<details>
   <summary>RNF03 - Deve ter acesso facilitado para instalação, sem levar mais de 30 segundos de pesquisa direta para encontrar a aplicação nas lojas de aplicativos </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">DE01</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN06</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 31: RNF03, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>


<details>
   <summary>RNF04 - Deve ser de código aberto e gratuito </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">LP01</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN07</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 32: RNF04, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RNF05 - Deve garantir a segurança dos dados confidenciais compartilhados durante as reuniões por vídeoconferência </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">CO02</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN11</a> / <a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados">OB12</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 33: RNF05, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>


<details>
   <summary>RNF06 - Deve ser estável, tendo no máximo 1 queda de funcionamento por dia </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">CO01</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN12</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 34: RNF06, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RNF07 - Deve oferecer um desempenho responsivo, se adaptando mediante o tamanho da tela </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Usabilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">DE02</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/introspec%C3%A7%C3%A3o/#requisitos-elicitados">IN13</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 35: RNF07, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RNF08 - Deve ser um aplicativo que ocupe menos de 100mb de memória </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">DE03</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/observacao/#requisitos-elicitados">OB16</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 36: RNF08, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RNF09 - Deve ser possível ingressar em uma reunião sem a necessidade de um login </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Usabilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">US04</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados">BR12</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 37: RNF09, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

<details>
   <summary>RNF10 - Deve possuir um bom contraste entre as cores a fim de aprimorar a legibilidade </summary>
<table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/Agil/nfr-framework/">Usabilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-Jitsi/Modelagem/especificacaoSuplementar/">US03</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-Jitsi/Elicitacao/tecnicas/brainstorming/#requisitos-elicitados">BR18</a></td>
      </tr>
    </tbody>
  </table>

<p>Tabela 38: RNF10, Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>
</p>

</details>

## **Histórico de Versão**
<p align="justify">
&emsp;&emsp;A tabela 39 representa o histórico de versão do documento.
</p>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 20/11/2023 | Criação do Documento | [Carolina Barbosa](https://github.com/CarolinaBarb) e [Catlen Cleane](https://github.com/catlenc) |[Júlia Souza](https://github.com/JuliaSSouza) |
<h6 align="center"> Tabela 39: Histórico de Versão.
<br> Autor(a): <a href="https://github.com/CarolinaBarb">Carolina Barbosa</a> e <a href="https://github.com/catlenc">Catlen Cleane</a></h6>
</center>

## **Bibliografia**
> <a href="https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf">[1]</a> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 24. Aprender 3. Distrito Federal, 2016. 



