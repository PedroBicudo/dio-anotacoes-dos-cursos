# Anotações do Curso Projetos Ágeis com Scrum

## Definições Úteis

### Ágil
- Você responde rapidamente a mudanças;
- Você se adapta com facilidade;

## Tipos de Gerenciamento

### Modelo Waterfall
- O escopo é definido no inicio;
- Você só avança para a próxima fase após terminar a atual;
- Uma vez definido os requisitos, não é possível mudar mais;
- O cliente só vê o projeto no fim.

### Modelo Ágil
- O software é construído em partes incrementais que duram no máximo um mês;
- O escopo do projeto é adaptado durante o andamento;
- O projeto é controlado por funcionalidades entregues;
- O projeto é transparente para o cliente do começo ao fim;
- O foco é o cliente, não o projeto.

## Scrum
- É um framework de gerenciamento de projeto.

### Pilares do Scrum

#### Transparência
- Feedback constante.
  
#### Adaptação
- Você tem que ser ágil.

#### Inspeção
- Você aprende progressivamente.

### Por que usar o Scrum?
- Você entrega o software em partes menores que se complementam.
- Tem menos incertezas (gerenciamento de riscos), pois você foca em funcionalidades e não na aplicação como um todo.

### Cargos
- Não existe diferença hierarquica entre esses cargos.

#### Product Owner (P.O)
- Representa a área de negócios
- Define as funcionalidades do Backlog
- Prioriza as funcionalidades de acordo com o valor
- Garante que todos entendam o que deve fazer

#### Scrum Master
- Garante o uso correto do Scrum
- Age como um facilitador da comunicação do P.O com o time desenvolvimento.

#### Time de desenvolvimento
- Responsável pelo design e implementação da aplicação.

### Conceitos úteis no Scrum

#### Timebox
- Tempo máximo para uma cerimônia.

#### Tema
- O tipo de aplicação a ser desenvolvida(um site compras).

#### Épico
- Um objetivo macro a ser atingido dentro do tema (pagina do produto).

#### Estória
- É um detalhamento do épico (O usuário pode ver as avaliações, O usuário pode ver as fotos do produto, etc).

#### Task
- São as tarefas necessárias para atingir uma estória. (adicionar o carrossel para a visualizar das imagens, etc).

#### Sprint
- É o evento principal do Scrum. Ele dura no máximo um mês.

#### Product Backlog
- É um modelo que quebra o produto em tema, épico, estória e task.
- Normalmente nunca acaba, pois as inspeções após as sprints gerão mais épicos.

### Cerimônias do Sprint
As cerimônias seguem a ordem top-bottom.

#### __Sprint Planning__
- time box: 8 horas
    - 4 horas
        - Product Owner apresenta as estórias e tira todas as dúvidas do time de desenvolvimento. O time não deve supor nada.
    - 4 horas
        - O time de desenvolvimento gera as tasks a partir das estórias.
        - O P.O não participa.
- Que participa:
    - P.O
    - Scrum Master
    - Time de desenvolvimento

#### __Daily Meeting__
- time box: 15 min
- Que participa:
    - Scrum Master
    - Time de desenvolvimento
    - P.O (opcional, mas recomendado)
- Todos ficam em pé
- Três perguntas:
    - O que eu fiz ontém?
    - O que eu vou fazer hoje?
    - Eu tive algum problema?

#### __Spring Review__
- time box: 4 horas
- Que participa:
    - P.O
    - Time de desenvolvimento
- É uma cerimônia que envolve **todos os interessados** na entrega.
- A ideia principal desta cerimônia é:
    - Ver o que está sendo entregue
    - Validar o que foi solicitado inicialmente
    - Validar se houve mudança no meio do fluxo
    - Se agrega valor ao negócio
- O time desenvolvimento mostra o trabalho que cada um desenvolveu para os clientes tirando dúvidas técnicas sobre o que cada um fez.
- Dúvidas de negócio devem ser tiradas com o P.O.

#### __Restropectiva da Sprint__
- time box: 3 horas
- Reunião da equipe para lições aprendidas

### Estimativa de planejamento
### Planning Poker
- É uma estratégia para fazer estimativas de quanto tempo vai durar para que a task seja completa.
- **Funcionamento**
    - Cada desenvolvedor recebe um deck de cartas com a sequência fibonacci.
    - Depois de ver todas as tasks, ele votam jogando uma das cartas, falando qual o tamanho daquela atividade.
    - Você deve levar em conta:
        - Complexidade da tarefa
        - Trabalho manual
        - Tempo
    - Existem tarefas não complexas mas que requerem muito trabalho manual, e isso aumenta a complexidade.
    - Se a tarefa tem mais de 20 pontos, o time quebra essa tarefa em mais estórias ou tarefas.
    - Quem escolhe a maior e menor nota deve justificar o porquê, pois eles podem ter pensado em algo que o time não pensou.

### Planning T-shirt size
- É uma estratégia para estimar o tempo que uma tarefa vai tomar, mas usando o tamanho da camisa.
- As regras são as mesmas do planning poker:
    - Menor e maior justificam
    - Levar em consideração a complexidade, esforço e tempo.