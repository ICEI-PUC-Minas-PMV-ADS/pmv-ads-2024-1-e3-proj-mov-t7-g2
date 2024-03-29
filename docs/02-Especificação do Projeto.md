# Especificações do Projeto



## Personas

<img src="img/persona1.png" width="280px" height="200px">

Matheus Ferreira de 25 anos estudante de ADS  sempre foi apaixonado por videogames, mas à medida que os jogos se tornavam mais complexos e exigentes em termos de hardware,Matheus se via incapaz de acompanhar as últimas tendências,desanimado, ele um dia tropeçou em um site de jogos retro. Intrigado, acessou o site e foi recebido por uma gama de jogod antigos, desde o clássicos sonic e Mario.Os controles simples e os gráficos pixelados o cativaram instantaneamente. Matheus encontrou uma plataforma que não apenas resgatou suas memórias de juventude, mas também o ajudou a superar a frustração de não conseguir jogar os títulos modernos. Ele mergulhou em aventuras retrô, redescobrindo o prazer puro de jogar, livre das complexidades dos jogos atuais.




<img src="img/persona2.png" width="280px" height="200px">

Maria Pires de 20 anos estudante de direito sempre foi uma entusiasta dos videogames, mas à medida que o tempo passava, a vida adulta trouxe responsabilidades e pouco tempo para acompanhar as novidades tecnológicas. Sentindo-se excluída do mundo dos jogos, Maria quase desistiu de sua paixão.Um dia, seu amigo Nathan recomendou a ela uma plataforma online dedicada a jogos retro. Cética, Maria deu uma chance e ficou surpresa ao encontrar uma vasta coleção de clássicos. Desde Super Mario Bros. até Snake, ela podia reviver os jogos que moldaram sua infância.A simplicidade dos controles e a familiaridade dos personagens a fizeram esquecer as frustrações dos jogos modernos. A plataforma retro tornou-se seu refúgio nostálgico, onde ela podia escapar da vida agitada e se perder nas aventuras que a fizeram apaixonar-se por videogames em primeiro lugar.

<img src="img/persona3.png" width="280px" height="200px">

Lucas Silva de 17 anos que esta cursando  o ensino medio, um jovem que sempre quis se perder nos mundos dos jogos, viu seus sonhos frustrados devido à sua deficiência física, que limitava seu acesso aos modernos controles complexos. Determinado a superar esse obstáculo, ele encontrou um site de jogos antigos aonde os controles eram bem simples e que não o impediam de passar horas jogando.Esse site traduzia os jogos que antes tinham comandos complexos em comandos mais simples e acessíveis. Lucas finalmente pôde jogar os jogos sem barreiras. A magia do site não apenas lhe permitiu explorar novos mundos virtuais, mas também inspirou outros jogadores com limitações físicas a seguir sua paixão

<img src="img/persona4.png" width="280px" height="200px">

Marcio de 32 anos, um trabalhador de escritório pai de 2 filhos, sentia-se desconectado do mundo dos videogames modernos devido à falta de tempo e recursos. Um dia, ao limpar seu sótão, deparou-se com seu antigo console Sega Genesis e uma coleção empoeirada de cartuchos porem o console ja estva muito ultrapassado e não funcionava mais.Vendo a frustração de seu pai os filhos de Marcio o apresentaram um site de jogos retro de facil acesso e baixa complexibilidade,movido pela nostalgia, Marcio se interresou pelo site  dedicou seu tempo livre para redescobrir a alegria dos jogos retrô. À noite, após um longo dia de trabalho, ele mergulhava nas aventuras pixeladas de Sonic, Pacman e outros clássicos. Esses momentos proporcionaram a Marcio uma pausa bem-vinda da vida agitada e uma conexão com suas paixões passadas e uma nova forma de se divertir com seus filhos.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
| Jogador amante de jogos classicos     | Diversas opções de jogos classicos                        | Relembrar momentos marcantes da infância, reviver a sensação e desafio proporcionada pelos jogos clássicos é algo que conecta e emociona                           |
| Jogadores casuais     | Registro rapidamente e de facil acesso                        | Para jogadores que buscam uma experiencias fáceis de aprender e jogar, tornando-os ideais para quem quer se divertir sem ter que passar horas aprendendo regras complexas.                               |
| Jogadores hardcore         | Ranking de pontuação                    | Aprimoram suas habilidades, estudando estratégias e dominando os meandros dos jogos.                               |
## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuario se registre no site e efetue o login e logoff. | ALTA | 
|RF-002| Acesso funcional aos Jogos  | ALTA |
|RF-003| A aplicação deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar os jogos.   | MÉDIA |
|RF-004| Sistema de ranking (pontuaçao) para algumas aplicaçoes na soluçao.  | MÉDIA |
|RF-005| Usuário poderar alterar o nome do perfil. | MÉDIA |
|RF-006| Usuário poderar alterar a foto de perfil. | MÉDIA |
|RF-007| Usuário poderar alterar alterar o email. | MÉDIA |
|RF-008| Usuário poderar alterar a senha. | MÉDIA |
|RF-009| Usuário tera acesso ao tutorial de cada jogo na aplicação | BAIXA |
|RF-010|

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser compatível com os navegadores. O site deve ser compatível com os principais navegadores do mercado. | ALTA | 
|RNF-002| O site deve carregar em menos de 3 segundos para 90% dos usuários.| ALTA | 
|RNF-003| O jogo deve rodar a pelo menos 30 quadros por segundo em todas as plataformas suportadas.| ALTA |
| RNF-004 |  Usabilidade e Interface Amigável: Garantir que a interface seja intuitiva e fácil de usar, atendendo a jogadores de diferentes níveis de habilidade técnica.                     | ALTA    | 
| RNF-005|  Disponibilidade e Escalabilidade: Assegurar que a plataforma esteja disponível 24 horas e seja escalável para lidar com um grande número de jogadores registrados.                      | ALTA    |
| RNF-006 |  Segurança de Dados: Armazenar os dados dos jogadores com segurança, protegendo informações pessoais e preferências de jogo contra violações.                      | ALTA    | 




## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A equipe não pode terceirizar o desenvolvimento da solução. |
|02| Acesso por país: O site pode ser restrito a determinados países ou regiões. |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

## Diagrama de Casos de Uso
![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e3-proj-mov-t7-g2/assets/128400414/0f35ef0a-a65e-417d-8c42-92ed79ac270a)





## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 




# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
