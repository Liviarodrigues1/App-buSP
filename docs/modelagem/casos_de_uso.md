# Casos de Uso
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|-|-|
| 1.0 | 24/05 | Criação da seção Casos de Uso | Lívia Rodrigues |

*Tabela 1: Versionamento*

<div id="introducao"></div>

## Introdução
<p align="justify">&emsp;&emsp;Também chamados de diagramas comportamentais, na notação da UML, os casos de uso são usados para descrever um conjunto de ações (uses cases - casos de uso) que um sistema ou um conjunto de sistemas (subject - sujeito) deve desempenhar em colaboração com um ou mais indivíduos externos ao sistema (actors - atores). Cada caso de uso deverá prover algum resultado observável e de valor para os atores ou outros interessados do sistema.</p>

## Metodologia
<p align="justify">&emsp;&emsp; Tabela descritiva, sendo composta de:</p>

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------- |
| 1   | Versão                | Versão do caso de uso                                                                              |
| 2   | Autor                 | Nomes dos autores envolvidos nessa descrição de caso                                               |
| 3   | Descrição             | Breve descrição do caso de uso                                                                     |
| 4   | Atores                | Lista dos atores envolvidos no caso de uso                                                         |
| 5   | Pré-condições         | Todas as restrições que devem ser atendidas antes que o caso de uso possa iniciar sua execução     |
| 6   | Pós-condições         | Lista do estado em que o [sistema](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#buSP) se encontrará imediatamente após a execução do cenário principal |
| 7   | Cenários Principais   | Descrição do cenário, ou fluxo, principal do caso de uso                                           |
| 8   | Cenários alternativos | Descrição dos [cenários](https://liviarodrigues1.github.io/App-buSP/modelagem/cenarios/#introducao), ou fluxos, alternativos do caso de uso                                     |
| 9   | Cenários de exceção   | Descrição dos cenários, ou fluxos, de exceção do caso de uso                                       |                                                         |


## Casos de Uso e Especificações

<div id="cadastro"></div>

### 1 - Caso de Uso: Fazer cadastro

*Autor: Livia Rodrigues* 

| Item | Sigla | Definição |
| :-- | :-------------------- | :----------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                                        |
| 2   | Autor                 | Lívia Rodrigues                                                                           |
| 3   | Descrição             | O usuário deverá conseguir fazer cadastro de sua conta                                     |
| 4   | Atores                | Usuário                                                                                    |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto   |
| 6   | Pós-condições         | Usuário estar devidamente cadastrado no sistema com sua conta                              |
| 7   | Cenários Principais   | Usuário selecionar a opção fazer criar conta                                              |
| 8   | Cenários alternativos | Usuário selecionar a opção fazer cadastro                            |    
| 9   | Cenários de exceção   | Usuário preencher algum dos campos de forma inválida ou não preencher um campo obrigatório | 
| 10  | Rastreabilidade       | RF01                                                                                       |

*Tabela 2: Descrição do Diagrama Fazer Cadastro*

<div id="login"></div>

### 2 - Caso de Uso: Fazer login

*Autor: Livia Rodrigues * 

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                                                            |
| 2   | Autor                 | Lívia Rodrigues                                  |
| 3   | Descrição             | O usuário deverá conseguir logar em sua conta                                               |
| 4   | Atores                | Usuário                                                                     |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto   |
| 6   | Pós-condições         | Usuárioestar logado no sistema com sua conta                                |
| 7   | Cenários Principais   | Usuário selecionar a opção fazer login                                                                         |
| 8   | Cenários alternativos | Usuário abrir a aba lateral e selecionar a opção fazer login                                                   |
| 9   | Cenários de exceção   | Usuário digitar a senha ou e-mail errados                                                                      |


*Tabela 3: Descrição do Diagrama Assinar Plano*

### 3 - Caso de Uso: Ver mapa e localização atual do usuário com os pontos de ônibus

*Autor: Livia Rodrigues * 

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                |
| 2   | Autor                 | Lívia Rodrigues                                                    |
| 3   | Descrição             | O usuário deverá conseguir ver o mapa com os pontos                   |
| 4   | Atores                | Usuário                                                                                                        |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto                       |
| 6   | Pós-condições         | Usuário visualizar as [ônibus disponíveis](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#bicleta-disponivel) em cada estação na localiação desejada                            |
| 7   | Cenários Principais   | Usuário navegar até a localização desejada                                                                     |
| 8   | Cenários alternativos | -                                                                                                              |
| 9   | Cenários de exceção   | Mapa estar indisponível                                                                                        |


## Referências Bibliográficas
<p> POHL, Klaus; RUPP, Chris. Fundamentos da Engenharia de Requisitos. Massachusetts: Rockynoock, 2012. (Páginas 92 - 98). Acesso em 25 Fevereiro de 2022.</p>