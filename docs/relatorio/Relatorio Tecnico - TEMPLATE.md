# Informações do Projeto
`Plataforma para auxiliar mais velhos a aprender tecnologias`  


`Engenharia de Software` 



## Participantes

Bruno Castanheira Marquezine

Daniel Bezerra Alves

Fernando Lucio Mello do Couto

Filipe Faria Melo


# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Muitos idosos apresentam dificuldades para conseguir usar o telefone, tablet ou computadores. Muitas vezes precisam pedir ajuda para os filhos ou netos que nem sempre estão disponíveis ou estão com paciência. 
Além de cair em diversos golpes em meios digitais.


## Objetivos

Pensando no problema mencionado acima, será desenvolvido uma plataforma digital em que irá ter como objetivo ensinar os idosos a realizar tarefas que envolvem tecnologia de forma cada vez mais autonoma. Além de fornecer ferramentas para os mesmo saberem onde procurar e se interar dos assuntos desse meio. Para que eles tenham cada vez menos dificuldades para realizar as tarefas por conta própria.


## Justificativa

Escolhemos essa aplicação pois é nítido para o nosso grupo que todas as tarefas estão sendo cada vez mais realizadas por meio de aparelhos eletrônicos. E já notamos diversos casos na nossa família ou de pessoas próximas de idosos que possuem dificuldades para realizar essa atividades. E esse fato se confirmou cada vez mais durante as entrevistas que realizamos durante essa sprint
Dessa maneira, escolhemos esse projeto devido a possibilidade que ele irá ter de impactar diversas pessoas que compartilham do mesmo problema.

## Público-Alvo

![Mapa de Stakeholders](imaages/../images/Stakeholders.png)
 
# Especificações do Projeto

1-Personas e Mapa de Empatia: feitos com base nas entrevistas e nos highlights das mesmas;

2-Historias de Usuário: feitos com base nas entrevistas;

3-Requisitos (Funcionais e Não-Funcionais): feitos com base nas nossas ideias para o programa e as necessidades dos usuários;

4-Restrições: descobertas apartir de reuniões e discussões sobre o projeto;


## Personas e Mapas de Empatia



![Persona Chico](imaages/../images/persona-chico.png)
![Empatia Chico](imaages/../images/mapa-chico.png)
![Persona Maria](imaages/../images/persona-maria.png)
![Empatia Maria](imaages/../images/mapa-maria.png)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema    | Acessar o glossário.               | Verificar o signifcando de um termo    |
|Usuário do sistema    | Acessar os tutorias escritos       | Aprender algo no celular, ou computador|
|Usuário do sistema    | Ver os centros de ensino/ogns      | Descobri o mais perto que eu possa ir. |
|Usuário do sistema    | Assistir videos sobre tecnológia   | Poder ficar cada vez mais por dentro.  |
|Administrador do sistema | Inserir tutoriais  | Usuários aprenderem.  |
|Administrador do sistema | Excluir tutoriais obsoletos  | Retirar tutoriais de tecnologias que tornaram-se obsoletas ou inutilizáveis.  |
|Administrador do sistema | Cadastrar/Alterar/Excluir permissões no sistema  | Gerir as permissões do sistema.  |
|Usuário do sistema | Compartilhar tutoriais  | discutir com amigos e conhecidos temas de interesse.  |



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve apresentar, para cada tipo de tecnologia correspondente, imagens e descrição | MÉDIA | 
|RF-002| A página inicial do site deverá conter botões que direcione o usuário para o tutorial desejado | ALTA |
|RF-003| O site deverá conter informações sobre tipos de tecnologias | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser compatível com os principais navegadores do mercado | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s | BAIXA | 
|RNF-003| O sistema deverá ser desenvolvido em linguagem HTML | ALTA |
|RNF-004| O sistema deve ser responsivo para rodar em dispositivos móveis | MÉDIA |




## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho|


# Projeto de Interface

Apresentamos aqui a visão geral da interação do usuário através das telas do sistema, bem como os protótipos das telas com as suas funcionalidades.

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia
Descreveremos aqui nossa metodologia de trabalho, incluindo as ferramentas para controle de versão, gerenciamento de projeto, apresentação e edição de código, bem como as metodologias que utilizamos na elaboração do projeto.

## Divisão de Papéis

Apresente a divisão de papéis entre os membros do grupo.

- Product Owner
   - Daniel Bezerra Alves
- Scrum Master
   - Filipe Faria Melo
- Desenvolvedores
   - Fernando Lucio Mello do Couto
- Designer
   - Bruno Castanheira Marquezine



## Ferramentas


As ferramentas empregadas no projeto são:

|              Ambiente             |             Plataforma          |
|-----------------------------------|---------------------------------|
| Gerenciamento do Projeto          | GitHub                          |
| Projeto de Interfaces e Wireframes| Miro                            |
| Editor de Código                  | Visual Studio Code              |
| Documentos de Apresentação        | Google Slides                   |
| Repositório de Código Fonte       | GitHub                          |
| Hospedagem                        | Heroku                          |


O editor de código foi o visual studio code porque ele possui uma integração com o git, além de já utilizarmos ele em outras matérias. As ferramentas de comunicação utilizadas foram o canvas e whatsapp, visto que são palataformas que todos já possuiam. Quanto aos wireframes foi utilizado o próprio miro já que é uma plataforma dinâmica no qual foi possível uma grande interação entre o time para confecção das telas de acordo em comum. O framework vai ser o bootstrap visto que a maioria do time já tem conhecimento do mesmo, além de que ele irá facilitar bastante a responsividade do projeto. A hospedagem será feita no heroku devido ao seu fácil uso, além de ser gratuito.

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o Git, sendo que o Github foi utilizado como repositório remoto..
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
