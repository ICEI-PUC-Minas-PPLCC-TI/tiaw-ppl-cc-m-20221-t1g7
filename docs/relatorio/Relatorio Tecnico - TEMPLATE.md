# <a name = "informações-do-projeto"><a/> 📝 Informações do Projeto

`TÍTULO DO PROJETO`
   
   EasyCode

`CURSO` 

   Ciência da Computação - disciplina trabalho interdisciplinar de aplicações web

##  <a name = "participantes"><a/> 👤 Participantes

   - André Menezes Resende

   - Camila Viana Dolabela
    
   - Clara Oliveira Mello Monteiro

#  <a name = "estrutura-do-documento"><a/> 📃 Estrutura do Documento

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
   
   A programação é o processo de escrita, teste e manutenção de um programa de computador. Desenvolvida primeiramente na década de 30, atualmente é composta por diversas linguagens que são constituídas de comandos, que quando utilizados corretamente, executam uma ação.
   
  Tendo em vista a complexidade da linguagem de programação, foi pensado um programa/ website que ameniza as dificuldades iniciais de alguém que busca aprender a programar. Nesse documento é registrado os passos principais para a realização desse projeto.

## Problema

Para estudantes de programação, um dos principais recursos utilizados para realizar seus estudos são locais de pesquisa e aprendizado sobre as diversas linguagens utilizadas na área.
   
Entretanto, ao pesquisar na internet por tais locais, dificilmente serão encontrados conteúdos que além de gratuitos, também sejam de qualidade.
   
Além do mais, um programador iniciante usualmente possui dificuldade em entender certos termos técnicos utilizados por programadores mais experientes, o que dificulta na procura de soluções para algum erro de código, ou no entendimento da solução em sí.

## Objetivos

Nesse projeto, o principal objetivo será suprir parte da falta de conteúdo gratuito sobre programação, além de descomplicar o entendimento de programadores iniciantes sobre a área.
   
Para isso, um site será construído que objetiva auxiliar o estudante em sua pesquisa e lhe ajudar caso ocorrer dúvidas.
   
Uma área do site dedicada a responder perguntas básicas e pré-selecionadas será criada para auxiliar o estudante que ainda está iniciando na área e não possui conhecimento prévio algum.
   
Ademais, além de seu próprio conteúdo, o site também irá guiar e indicar o estudante a fontes confiáveis e de qualidade, para que possa expandir suas pesquisas além do escopo determinado do site.

## Justificativa

Como programadores iniciantes, nossa entrada na área da programação iniciou-se com um grande bloqueio, sendo essa não só a falta de conteúdo gratuito de qualidade, mas também a dificuldade de entender textos sobre linguagens e soluções para eventuais erros.
   
Ademais, durante a realização de uma pesquisa de campo, foi se percebido que esse problema não atingia apenas a nós, mas também a diversas outras pessoas que entrevistamos.
   
E por fim, vimos que diversos estudantes até sabiam onde procurar por soluções para seus erros ou conteúdos didáticos da área, mas que frequentemente eram feitos com linguagem rebuscada e confusa para iniciantes.
   
Portanto, o tema foi escolhido de forma a tentar solucionar essa situação, que assola não só os próprios membros do grupo, mas também diversos outros estudantes.

## Público-Alvo

O público-alvo escolhido serão pessoas de qualquer gênero, entre 16 e 26 anos, que já são familiarizados com tecnologia, e possuem interesse, mas não possuem experiência ou conhecimento algum na área da programação.
 
# Especificações do Projeto

A seguir há uma sequência de passos que ajudaram no entendimento das necessidades do público alvo e, então, 
no desenvolvimento de pequenos objetivos que atendem cada demanda apresentada.

Para conseguir realizar as especificações com mais clareza, ulizou-se a plataforma Miro (miro.com)

## <a name = "personas-e-mapas-de-empatia"><a/> 👥 Personas e Mapas de Empatia

 - ### Murilo

![Murilo persona](imaages/../images/PMurilo.png)

![Vitória mapa de empatia](imaages/../images/MEMurilo.jpg)

 - ### Vitória
  
![Vitória persona](imaages/../images/PVitória.png)

![Vitória mapa de empatia](imaages/../images/MEVitória.jpg)

 - ### Kauã

![Kauã persona](imaages/../images/PKauã.png)

![Kauã mapa de empatia](imaages/../images/MEKauã.jpg)


Com as personas e os mapas 
de empatia, foi possível compreender possíveis problemas de usuários e determinar quais funções do 
programa são essenciais ou não (requisitos funcionais e não funcionais).

## <a name = "histórias-de-usuários"><a/> 📚 Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Murilo       | Aprender programação                  | Conseguir trabalhos simples e aumentar a renda |
|Vitória      | Direcionamento na área de programação | Conseguir aprofundar seus conhecimentos por conta própria |
|Kauã         | Conhecer mais sobre programação       | Descobrir se possui vocação/ interesse |

## <a name = "requisitos"><a/> ✔️ Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Conteúdos de qualidade | ALTA | 
|RF-002| Exemplos de programas   | ALTA |
|RF-003| Criação de perfis para colaboradores   | MÉDIA |
|RF-004| Indicações de materiais e sites | MÉDIA |
|RF-005| Criação do site | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Área destinada a perguntas e respostas| MÉDIA | 
|RNF-002| Site possuir exercícios |  MÉDIA |
|RNF-003| Respostas a perguntas comuns | MÉDIA|
|RNF-004| Responsividade | MÉDIA |
|RNF-005| Tutorial estilo bloco | BAIXA |
|RNF-006| Tabela de variáveis | BAIXA |
|RNF-007| Modo escuro | BAIXA |

## <a name = "restrições"><a/> ⛔ Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| Conhecimento sobre linguagens de programação limitado |

# Projeto de Interface

Primeiramente, foi criado o userflow visando atender os requisitos/ demandas descritas
anteriormente. Dessa forma, foram criadas áreas para conteúdo, exercício e exemplos. Além da possibilidade
de haver contribuidores que poderão alimentar a plataforma.

A partir do userflow, foi possível produzir os wireframes, que possuem a base do layout de todas as páginas do site.

## <a name = "user-flow"><a/> 🌐 User Flow

![User flow](imaages/../images/wireflow.jpg)

## <a name = "wireframes"><a/> 🖥️ Wireframes

 - Wireframe completo

![Wireframe](imaages/../images/WireframeComp.jpg)

Páginas mais relevantes: 

 - Página inicial

![Wireframe home](imaages/../images/Home.jpg)

 - Página que corresponde à biblioteca de linguagens disponíveis

![Wireframe linguagens](imaages/../images/Linguagens.jpg)

 - Modelo da página com conteúdo sobre determinada linguagem

![Wireframe ex de ling](imaages/../images/ExdeLing.jpg)


# Metodologia

Com o objetivo de entender o problema em tese e em como ele afeta a sociedade, 
foi utilizado o processo de Design Thinking, que consiste em analisar o problema através dos pilares de 
empatia, colaboração e experimentação. Para completar, foi utilizado o Scrum com o intuito de dividir as 
tarefas e responsabilidades para agilizar o processo de realização dos afazeres.

A divisão de papéis ficou centrada em desenvolver os frameworks em equipe e depois separar a construção do site, 
a documentação do projeto e a montagem da apresentação.

As ferramentas utilizadas foram plataformas de softwares, como GitHub e Figma, e plataformas de criação de documentos, 
como o PDF e PowerPoint.  

## <a name = "divisão-de-papéis"><a/> 🗂️ Divisão de Papéis

|ID     | Descrição do Requisito  |Pessoa |
|-------|-------------------------|-------|
|RF-001 | Conteúdos de qualidade | Clara | 
|RF-002 | Exemplos de programas   | André |
|RF-003 | Criação de perfis para colaboradores   | Camila |
|RF-004 | Indicações de materiais e sites | Camila|
|RF-005 | Criação do site | Clara |
|RNF-001| Área destinada a perguntas e respostas| Clara | 
|RNF-002| Site possuir exercícios |  Camila |
|RNF-003| Respostas a perguntas comuns | André|
|RNF-004| Responsividade | Clara|
|RNF-005| Tutorial estilo bloco | Camila|
|RNF-006| Tabela de variáveis | André|
|RNF-007| Modo escuro | André|

## <a name = "ferramentas"><a/> 🔧 Ferramentas


| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVOBuAT1c=/ | 
|Protótipo Interativo | Figma | https://www.figma.com/proto/Li6r3MoMW3qB5ZfKhj0gX2/TIAW?node-id=2%3A31&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=2%3A31 | 
|Wireframe | Figma | https://www.figma.com/file/Li6r3MoMW3qB5ZfKhj0gX2/TIAW?node-id=0%3A1 |
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PPLCC-TI/tiaw-ppl-cc-m-20221-t1g7 | 
|User flow | Wireflow | https://wireflow.co/ |
|Divisão de tarefas | Trello | https://trello.com/b/fExRjgSD/tiaw |
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 

## <a name = "controle-de-versão"><a/> 🗃️ Controle de Versão

Até o momento, não foi utilizado nenhuma ferramenta de versionamento. Está sendo utiliazado
o Github para a hospedagem do repositório e nele são feitas as mudanças da documentação.
   
Com o objetivo de garantir que todos os membros estão de acordo com as mudanças a serem
realizadas, é criado um branch (ou mais, dependendo da necessidade) que é implementado
somente após a aprovação do grupo.

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
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
