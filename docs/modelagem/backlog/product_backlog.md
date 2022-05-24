# Backlog do produto

## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|-|-|
| 1.0 | 24/05 | Criação do backlog do produto | Lívia Rodrigues |


*Tabela 1: Versionamento*
<br>

## Introdução
<p style="text-align: justify;"> Product backlog é uma framework de desenvolvimento Scrum que fornce uma lista completa dos requisitos ou funcionalidades com suas priorizações que serão entregues ao sistema gerando um valor ao produto, podendo haver alteração ou adição de novas funcionalidades em qualquer momento. Essa lista de funcionalidade a serem entregues será construída/definida pelo Product Owner(P.O) de sua equipe. </p> 

<p style="text-align: justify;">O aplicativo analisado é mobile, disponivel para aparelhos android e IOS, sendo desenvolvido em objC/Swift e Flutter respectivamente. </p> 
<br>

## Metodologia
<p style="text-align: justify;"> O backlog foi construído modelando e agrupando os requisitos do projeto em diferentes níveis de granularidade: as Histórias de Usuário, representativas dos requisitos que geram valor ao produto, foram agrupadas em Features, ou seja, as funcionalidades propriamente ditas do sistema, que por sua vez foram agrupadas em Épicos, conjunto de funcionalidades que possuem objetivo ou resultado comum específico. Dessa forma, o documento seguiu o seguinte modelo: </p>
<br>

### Épico ZZ - Nome do épico
|**Feature**|**ID**|**História de usuário**| **Prioridade** |
|:----------:|:----:|:----------------------| --------- |
|  Feature XX - Nome da feature  | USYY | Ojetivo da US | Priorização |

||Legenda||
|:----------:|:----:|:----------------------|
| **ZZ** | Número do épico ||
| **US** | História de Usuário ||
| **XX** | Número da feature ||
| **YY** | Número da história ||
| **Priorização** | Classificação definida pela técnica MoSCoW ||

*Tabela 2: Metodologia de apresentação*
<br><br>

## Épicos

### Épico 01 - Autenticação
<div id="epico1"></div>

|**Feature**|**ID**|**História de usuário**| **Prioridade** |
|:----------:|:----:|:----------------------| --------- |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature1">Feature 01 - Cadastro</a> | US01 | Criação do cadastro do usuário | MUST |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature2">Feature 02 - Login </a> | US02 </br></br>  US03 </br></br> US04 | Fazer login </br></br> Acesso por leitura facial ou digital </br></br> Alterar/recuperar senha esquecida | MUST </br></br> SHOULD </br></br> MUST|
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature3">Feature 03 - Logout</a> | US05 | Fazer logout | MUST |

*Tabela 3: Épico 01*
<br><br>

### Épico 03 - Viagens
<div id="epico3"></div>

|**Feature**|**ID**|**História de usuário**| **Prioridade** |
|:----------:|:----:|:----------------------| --------- |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature6">Feature 06 - Mapa</a> | US11 </br></br> US12</br></br> US13 | Visualizar o mapa </br></br> Visualizar a quantidade de ônibus </br></br> Visualizar a quantidade de vagas | MUST </br></br> MUST </br></br> MUST |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature7">Feature 07 - Localização</a> | US14 </br></br> US15 | Localização em tempo real </br></br> Estações próximas ao usuário ou ao seu destino | SHOULD </br></br> MUST|
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature8">Feature 08 - Retirada</a> | US16 </br></br> US17 </br></br> US18 | Retirar ônibus em determinado local </br></br> Retirar ônibus pelo QR code </br></br> Retirar ônibus pelo código no aplicativo | MUST </br></br> SHOULD </br></br> SHOULD |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature9">Feature 09 - Devolução</a> | US19 | Devolução da ônibus | MUST|

*Tabela 5: Épico 03*
<br><br>

### Épico 04 - Ajuda
<div id="epico4"></div>

|**Feature**|**ID**|**História de usuário**| **Prioridade** |
|:----------:|:----:|:----------------------| --------- |
| <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/backlog/historias_de_usuario/#feature10">Feature 10 - Central de atendimento</a> | US20 </br></br> US21 </br></br> US22 </br></br> US23 | Regras de utilização do aplicativo </br></br> Retirada de Dúvidas </br></br> Entrar em contato com atendente </br></br> Relatar problema | MUST </br></br> SHOULD </br></br> SHOULD </br></br> SHOULD |

*Tabela 6: Épico 04*
<br><br>

## Referências

<p>SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 24 de maio de 2022.</p>
