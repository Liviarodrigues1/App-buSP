# Especificação Suplementar 
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 24/05 | Criação do artefato | Lívia Rodrigues |

*Tabela 1: versionamento*

## Introdução
<p align="justify">&emsp;&emsp;Trata-se de um documento em linguagem natural, no qual são descritos os requisitos não funcionais [1]. Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#software">sistema</a> a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design [2].</p>

## Metodologia
<p align="justify">&emsp;&emsp;Como metologia será usada a FURPS+, que é um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos, assim como representa atributos de Qualidade de <a href="https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#software">Software</a>, sendo ele parte do Rational Unified Process (RUP): Functionality (Funcionalidade), Usability (Usabilidade), Reliability (Confiabilidade), Performance (Desempenho), Supportability (Suportabilidade). O “+” do acrônimo engloba outros requisitos não-funcionais que devem ser lembrados [3].</p>
<p align="justify">&emsp;&emsp;O presente aretefato foi feito pelo integrante do grupo Victor Eduardo, para que se levantasse os requisitos não-funcionais do aplicativo.</p>

### Funcionalidade
&emsp;&emsp;Todas as funcionalidades do aplicativo buSP podem ser encontradas nos [casos de usos](https://liviarodrigues1.github.io/App-buSP/modelagem/casos_de_uso/) do projeto.</p>

### Usabilidade
#### Facilidade de uso
- O [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) executa ações críticas em no máximo 7 clicks.
    - Levando em conta usuários já assinantes de algum dos [planos](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#plano) do app. O número pode aumentar para usuários que não tiverem assinados algum dos planos ainda.   
- A interface gráfica possui cores que destacam para cada opção.
- A interfaze possui ícones intuitivos que direcionam o uso do usuário.
- Mapa disponível
    - Mostrando localização do [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario)
    - Mostrando estações
    - Mostrando quantidade de ônibus
    - Disponível [sem login](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#nao-logado)
#### Pequena curva de aprendizado
- Fluxos de trabalho simples e padronizados
- Usabilidade com pouca variação de uma versão para outra
#### Conhecimentos prévios
- A aplicação exigirá que o [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) saiba usar sistemas móveis Android ou iOS.
#### Feedbacks
- O [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) deve ter acesso a uma central de ajuda com
    - Perguntas feitas com frequência
- O [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) deve ter acesso a guias de uso:
    - Simples
    - De fácil entendimento

### Confiabilidade
#### Disponibilidade
- Os servidores do aplicativo devem mantê-lo disponível o maior tempo possível enquanto instalado no celular do [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario). Se houver indisponibilidade por motivos de manutenção ou atualização, o [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) deve ser previamente avisado.
#### Segurança mínima no armazenamento de dados
- O aplicativo afirma estar em conformidade com o Artigo 19 N°4 da Constituição Política a República e Lei 19.628 do Chile, sobre Proteção de Dados de Caráter Pessoal.
#### Suporte a falhas
- No caso de falhas, o aplicativo deve dar segurança ao [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) de que a falha vai ser identificada e corrigida, gerando um feedback ao [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) e relatando que não haverão consequências negativas aos dados sensíveis do [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario).

### Desempenho
#### Rapidez de Resposta
- O tempo de resposta deverá ser o mínimo possível.
#### Acessos simultâneos
- A aplicação deve ter uma lógica de balanceamento de carga de requisições ao servidor, para ser capaz de atender acessos simultâneos de diferentes [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario)s, que estiverem logados em suas contas ou não.
#### Armazenamento
- O aplicativo precisa de 60MB(megabyte) de armazenamento em sistemas Android e 59MB em sistemas iOS.

### Suportabilidade
- O sistema do [buSP](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#buSP) está disponível para plataforma Mobile. Funcionando nos sistemas operacionais mobile Android, nas versões 5.0 ou superior, e iOS nas versões iOS 12.0 ou posterior.

### Restrições de Design
#### Suporte a Idiomas
- O [sistema](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#buSP) fornece uma grande variedade de línguas, e a linguagem do app varia de acordo com a linguagem utilizada no aparelho
#### Conteúdo
- O [sistema](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#buSP) deve disponibilizar a visuzalização dos locais das estações bem como a quantidade de ônibus em cada em um mapa

### Requisitos de Sistema de Ajuda e de Documentação de [Usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) On-line
#### Sessão de Ajuda
- O aplicativo possui um botão chamado "Dúvidas", localizado na aba lateral. Ele possui um conjunto FAQ - Frequently Asked Questions -, ou seja, um conjunto de perguntas frequentes com suas soluções.

#### Demais informações
- No site do App é possível achar diversas outras informações sobre o app, e a empresa criadora desse. 

### Interfaces
#### Interfaces de [Usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario)
- O [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) utilizará as versões do aplicativo disponíveis nas lojas mobile para visualizar e utilizar sua interface.
#### Interface de Hardware
- O hardware deve ser capaz de disponibilizar a localização atual para o [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) e ter conexão com a internet para o aplicativo gerar o trajeto até uma estação, a partir da localização atual do [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario).
- O hardware deve ter conexão com a internet para mostrar ao [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) as estações e quantidade de ônibus em cada uma.
#### Interface de Software
- A interface do aplicativo é desenvolvida para atender as plataformas Mobile, que utilizam Android ou iOS. 

### Requisitos de Licenciamento
#### Termos de Uso
- O aplicativo apresenta seus termos de uso para que o [usuário](https://liviarodrigues1.github.io/App-buSP/modelagem/lexicos/#usuario) concorde em utilizar o aplicativo e suas informações dentro dos limites apresentados.


## Referências 
<p>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. 2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 24 de maio de 2022.</p>

<p>GOIS, Samily Rocha; SOBRINHO, Francisco Luiz. PHP SOFTWARE COMPANY. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 24 de maio de 2022.</p>

<p> FURPS+. QualidadeBR, 10 de julho de 2008. Disponível em: <https://qualidadebr.wordpress.com/2008/07/10/furps/#:~:text=FURPS%2B%20%C3%A9%20um%20sistema%20para,Rational%20Unified%20Process%20(RUP)%3A>. Acesso em: 24 de maio de 2022.</p>
