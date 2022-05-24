# Cenários
## Versionamento

| Versão | Data | Descrição | Autor |
| -- | -- | -- | -- |
| 1.0 | 24/05 | Criação do documento | Lívia Rodrigues |


*Tabela 1: Versionamento*

<div id="introducao"></div>

## Introdução
<div align="justify">&emsp;&emsp; Um cenário se trata de uma descrição curta de como um evento (ou eventos futuros) pode impactar as operações de um sistema. Eles constituem exemplos da vida real de como o sistema é ou será utilizado.
</div>
<div align="justify">&emsp;&emsp; Os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações pontuais do usuário com o sistema, onde cada cenário cobre um pequeno número das possíveis variações de determinada interação.
</div>
<div align="justify">&emsp;&emsp; Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em diferentes níveis de detalhamento sobre o sistema. Neste artefato estão registrados todos os cenários criados.
</div>

## Metodologia
<div align="justify">&emsp;&emsp; Cada cenário descreve uma situação de uso do sistema e é representado por uma tabela conforme o seguinte formato:</div>

| Título | Título do Cenário |
| -- | -- |
| Objetivo | Objetivo/meta do cenarios |
| Contexto | pré-condição:<br>pós-condição: |
| Atore | Atores envolvidos |
| Recursos | Recursos envolvidos |
| Episódios | Detalhes do cenários |
| Restrições | Descrição da retrição | 
| Exceção | Descrição da exceção |


### C01 - Cadastrar usuário por email
| Título | Cadastrar usuário por email |
| -- | -- |
| Objetivo | Criar perfil para o usuário no buSP utilizando email |
| Contexto | pré-condição: Possuir email válido<br>pós-condição: Perfil do usuário é criado |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário não cadastrado acessa o aplicativo buSP<br>2. O usuário não cadastrado seleciona a opção de criar conta<br>3. O usuário não cadastrado insere email e senha e seleciona o botão "Continuar"<br> |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 2: Descrição do Cenário Cadastrar usuário por email*

<div id="login"></div>

### C02 - Acessar a conta
| Título | Acessar a conta |
| -- | -- |
| Objetivo | Acessar a conta usuário no buSP |
| Contexto | pré-condição: Não estar logado na conta<br>pós-condição: Usuário logado no buSP |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Possuir conta criada |
| Episódios | 1. O usuário acessa o aplicativo buSP<br>2. O usuário seleciona a opção de "Fazer seu login"<br>3. O usuário insere email e senha e seleciona o botão "Continuar"<br> |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 3: Descrição do Cenário Acessar a conta*

<div id="sair"></div>

### C03 - Sair da Conta
| Título | Sair da Conta |
| -- | -- |
| Objetivo | Sair da conta logada no app |
| Contexto | pré-condição: Usuário logado no buSP<br>pós-condição: Logout da conta |
| Atore | Usuário |
| Recursos | Acesso à internet<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Sair" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 4: Descrição do Cenário Sair da Conta*

<div id="ajuda"></div>

### C04 - Escolher Ajuda
| Título | Escolher Ajuda |
| -- | -- |
| Objetivo | Consultar informações sobre os serviços do buSP |
| Contexto | pré-condição: Usuário logado no buSP<br>pós-condição: Ver informações sobre o funcionamento do app |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Ajuda"<br>3. O usuário seleciona o tópico que quer consultar |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 5: Descrição do Cenário Escolher Ajuda*

<div id="bicicleta-disponivel"></div>

### C05 -  Vizualizar ônibus disponíveis
| Título |  Vizualizar Bicicletas Disponíveis |
| -- | -- |
| Objetivo | Poder ver os ônibus disponíveis em cada estação |
| Contexto | pré-condição: App instalado<br>pós-condição: Ver localização das estações e os ôninus disponíveis em cada uma |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário acessa o buSP<br>2. O usuário navega pelo mapa da tela inicial |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 6: Descrição do Cenário Vizualizar Bicicletas Disponíveis*
