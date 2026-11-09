## Glossário

- **Interação:** Processo de comunicação e troca de ações entre o usuário e o sistema computacional.
- **Interface:** Superfície de contato e mediação que serve de suporte e apoio para as interações.
- **Stakeholder:** Indivíduo ou instituição que possui interesse, impacto ou necessidade em relação ao sistema (não apenas com a interface, mas com o projeto como um todo).
- **Affordance:**  Uma propriedade perceptível que emerge da relação entre o sujeito e o objeto.
- **Usuário:** Pessoa que utiliza o sistema para atingir objetivos específicos por meio de uma sequência de tarefas dentro de um contexto de uso.
- **Sistema Interativo:** Combinação de hardware e software projetada especificamente para que um usuário possa interagir e realizar ações.
- **Acessibilidade:** Propriedade que determina o quanto uma interface é adequada para ser utilizada por qualquer pessoa, independentemente de suas capacidades motoras, visuais, auditivas ou cognitivas.
- **Protótipo:** Representação conceitual, total ou parcial, de um sistema, utilizada para testar, avaliar e validar ideias antes do desenvolvimento da versão final.
- **Nível de Fidelidade:** Grau de realismo do protótipo (baixa, média ou alta fidelidade) que indica o quão próximo ele está do comportamento, visual e funcionamento do sistema final.
- **Comunicabilidade:** Capacidade da interface de transmitir de forma clara ao usuário a lógica de design, as intenções do desenvolvedor e como o sistema deve ser utilizado.
- **Ciclo Enativo:** Processo contínuo de cognição onde o _input_ (entrada) alimenta o _output_ (saída), que por sua vez altera o ambiente e gera um novo _input_ (ação e percepção acopladas).
- **Usabilidade**: O quão fácil é usar uma interface.

## Evolução de IHC

- **Anos 1950 (Foco no Hardware e Ergonomia):** O computador era visto como um fenômeno técnico voltado para cálculos complexos, operado apenas por especialistas. A interação limitava-se à programação direta da máquina. As preocupações eram puramente **ergonômicas e físicas**, focadas no conforto e no esforço humano para operar os painéis e dispositivos.
- **Anos 1980 (Foco na Cognição):** Com a chegada dos computadores pessoais, o foco mudou para a mente do usuário. Surgiram as preocupações **cognitivas**, estudando a carga mental, a memória do operador e os canais de transmissão de informação para que pessoas comuns pudessem entender os sistemas.
- **Anos 2000 (Foco no Contexto e Cultura):** A tecnologia expandiu-se para além dos escritórios. As pesquisas passaram a considerar o usuário inserido em seu **contexto social e cultural**, analisando como as pessoas utilizam os artefatos digitais em suas rotinas e os significados subjetivos atribuídos a eles.
- **Anos 2010 até Hoje (Foco na Complexidade e Onipresença):** O cenário tornou-se altamente complexo com a chegada da Inteligência Artificial (IA) e da Internet das Coisas (IoT). A tecnologia tornou-se **onipresente**, gerando uma coleta massiva e ininterrupta de dados.

## Teorias de  IHC 

### 1. Lei de Hick-Hyman

**Foco:** Tempo de **decisão**.
- **Conceito:** Quanto mais opções (N), maior o tempo de escolha (relação logarítmica).
- **Fórmula:** `T = k * log2(N + 1)` _(onde k ≈ 150ms)_.
- **Aplicação em IHC:** Evitar excesso de opções simultâneas; usar menus enxutos e categorizados. _(Ligação com o princípio: "Não me faça pensar!")_

### 2. Lei de Fitts

**Foco:** Tempo de **movimento**.
- **Conceito:** O tempo para apontar para um alvo depende da **distância (D)** e do **tamanho (S)** do alvo. Alvos maiores e mais próximos são mais rápidos.
- **Fórmula:** `T = k * log2(D/S + 0,5)` _(onde k ≈ 100ms)_.
- **Aplicação em IHC:** Botões grandes; menus no topo da tela (ex: Mac OS), pois a borda da tela "para" o mouse, tornando o alvo infinito.

### 3. Teoria da Ação (Norman) e GOMS

**Foco:** O **ciclo cognitivo** e a **previsão** de comportamento.
- **Propósito da Teoria da Ação:** Reduzir os "golfos" para criar **sistemas intuitivos** (fáceis de usar, onde o usuário sabe o que fazer e o que esperar).
- **O Ciclo de Ação (7 etapas):** Objetivo -> Intenção -> Especificação -> Execução (Ação) -> Percepção -> Interpretação -> Avaliação.
    - **Golfo de Execução:** Distância entre a intenção e a ação permitida. _(O usuário sabe o que fazer?)_
    - **Golfo de Avaliação:** Distância entre o estado do sistema e a compreensão do usuário. _(O usuário entendeu o feedback?)_
- **Modelo GOMS (Goals, Operators, Methods, Selection Rules):** Derivado da Teoria da Ação e do Processador Humano. É um modelo preditivo para calcular o tempo que um usuário experiente leva para realizar uma tarefa, permitindo comparar designs antes de implementá-los.

## Base Semiótica em IHC (Melhorar) 

> **Ideia central:** A interação humano-computador é um caso particular de **comunicação humana mediada** por sistemas computacionais. O foco está na comunicação entre **designer, sistema e usuário**.

### 1. Fundamentação: Semiótica de Peirce

_(A base teórica que dá origem à engenharia semiótica)_

- **Signo:** É a menor unidade de sentido.
- **Relação Triádica:** O signo conecta o objeto que ele representa ao intérprete (processo mental de interpretação em um dado contexto).
- **Tipos de signos:**
    - **Ícone:** Representa por semelhança (ex: um desenho de uma pessoa).
    - **Índice:** Indica algo por conexão causal (ex: fumaça indica fogo).
    - **Símbolo:** Representa por convenção/arbitrário (ex: a palavra "cadeira").
- **Premissa:** A realidade é subjetiva e socialmente construída.

### 2. Engenharia Semiótica (Clarisse de Souza)
- **A Interface é uma Mensagem:** O sistema não é apenas uma ferramenta, é um artefato de comunicação. A interface é a **metamensagem** que o designer envia ao usuário.
- **Paráfrase da Metamensagem:** _"Este é o meu (designer) entendimento de quem você (usuário) é, do que você quer fazer e de como prefere fazer. Este é o sistema que projetei para você e é assim que você deve usá-lo."_
- **Dois Níveis de Comunicação:**
    1. **Comunicação usuário-sistema:** A interação direta (clicar, digitar).
    2. **Metacomunicação designer-usuário:** O que o designer "fala" através das escolhas de design da interface.


## Cebola

A ideia é que a realidade e as regras sociais existem em camadas, do mais subjetivo (informal) ao mais engessado (técnico):

1. **Informal (O "boca a boca" / Cultura):** É o nível das convenções sociais, hábitos e interpretações subjetivas.
    - _Exemplo:_ "Alguém disse que você precisa estar de chapéu para ver as aulas." (É uma fofoca, um costume, não é uma regra oficial e pode ter várias interpretações).
2. **Formal (A Instituição / Lei):** É o nível das regras escritas, normas e burocracias. A interpretação é mais restrita.
    - _Exemplo:_ "A coordenação do BCC disse que é obrigatório usar chapéu." (Virou uma regra formal, delimitada).
3. **Técnico (O Sistema / Código):** É o nível da máquina, do código e do hardware. **Não há interpretação, apenas execução binária** (cumpriu a condição, funciona; não cumpriu, bloqueia).
    - _Exemplo:_ "Uma porta eletrônica verifica se você está de chapéu; se não estiver, ela não abre." (Não tem choro nem negociação, o sistema apenas roda).

**Por que isso importa em IHC?**
- O sistema computacional é o nível **Técnico**.
- Mas ele é projetado para resolver problemas dos níveis **Formal** e **Informal**.
- O design ideal alterna entre esses níveis para entender o contexto. Se você só olha para o nível técnico (código), você faz uma **"análise simplista"** (como está escrito no seu caderno). A realidade não é simplista, mas o modelo que a gente cria para o sistema muitas vezes é.


## Tipos de Design
### 1. Design Centrado no Usuário (DCU)
- **Foco:** O **"quem"** (Quem é o usuário e como é sua utilização).
- **Conceito:** O usuário é o centro do processo. Ele **deve ser consultado e estar presente** durante o desenvolvimento.
- **Objetivo:** Entender as necessidades reais de quem vai usar o sistema, e não apenas as metas técnicas ou de negócio.

### 2. Design Participativo
- **Foco:** O **"como e quem"** (Como o usuário participa).
- **Conceito:** Vai além da consulta (do DCU). Os usuários **têm poder de decisão** no projeto.
- **Objetivo:** Os usuários ajudam a decidir quais (in)tecnologias devem ser adotadas e como o sistema deve funcionar, atuando como co-designers.
### 3. Design Thinking (O Processo)

- **Foco:** O **"processo"** de desenvolvimento e planejamento. [[Design Thinking]]
- **Conceito:** É uma abordagem iterativa e centrada no humano para resolver problemas complexos. É dividido em **5 etapas**:
1. **Empatia:** Entender o contexto de uso da aplicação e as dores das pessoas.
2. **Definição:** Entender qual é o problema real (ou a existência dele)
3. **Ideação:** Gerar uma diversidade de soluções (brainstorming).
4. **Prototipação:** Evoluir as ideias mais promissoras e criar protótipos (muitas vezes de baixa fidelidade).
5. **Teste/Avaliação:** Testar a viabilidade das soluções para ver se resolvem o problema.

- **Design** é cnceber,projetar e prototipar sistemas 
intativos centrados no humano.

## Escada Semiótica (IHC)

> **O que é:** Um modelo em forma de escada que organiza a análise de um sistema em **6 camadas de diferentes níveis de abstração**. Ela ajuda a pensar o design para além do código (nível técnico) e conectá-lo aos significados e impactos sociais .

### 1. As 6 Camadas

- **1. Mundo Físico:** A infraestrutura material. Ex: _hardware, cabos, servidores, dispositivos móveis_.
- **2. Empírico:** Os padrões de sinais que viajam pela infraestrutura. Ex: _largura de banda, taxa de atualização, ruído, capacidade do canal_.
- **3. Sintático:** A estrutura formal, a linguagem e o código. Ex: _lógica do software, protocolos, modelos de coordenação_.
- **4. Semântico:** O significado dos signos na interface. Ex: _o que um ícone ou uma palavra representa; o modelo conceitual da aplicação_.
- **5. Pragmático:** A intenção e o contexto de uso. Ex: _o que o usuário quer fazer, a intenção por trás de um clique, o protocolo social_.
- **6. Mundo Social:** O impacto na sociedade, nas comunidades e nas pessoas. Ex: _consequências sociais, crenças, valores, efeitos na vida das partes interessadas_.

### 2. Para que Serve? (Aplicação)
- **Refinar Requisitos:** Ajuda a organizar requisitos de forma estruturada, garantindo que aspectos de níveis diferentes (técnicos e sociais) não sejam esquecidos .
- **Análise de Stakeholders:** É usada na fase de "Clarificação do Problema" para entender quem é afetado e como .
- **Análise Crítica de Design:** Permite avaliar se um sistema está "travado" no nível sintático (código) sem considerar a semântica (significado) ou a pragmática (intenção).
### 3. Como Usar? (Passo a Passo)
1. **Desenhe a Escada:** Crie uma tabela ou um _banner_ físico (com _post-its_) com os 6 degraus .
2. **Preencha cada degrau:** Para o sistema que você está projetando, liste os elementos de cada camada. Por exemplo, ao projetar um _app_ de transporte:
    - **Mundo Físico:** Celular do usuário e do motorista, sinal de GPS.
    - **Empírico:** Taxa de atualização do mapa em tempo real.
    - **Sintático:** O código do aplicativo, a API do Google Maps.
    - **Semântico:** O ícone do carro no mapa, a palavra "Aceitar".
    - **Pragmático:** O usuário quer chegar em casa rápido; o motorista quer ganhar a corrida.
    - **Mundo Social:** A mudança na mobilidade urbana, a relação de trabalho dos motoristas.
3. **Analise as Conexões:** Veja se as decisões técnicas (degraus de baixo) estão alinhadas com as intenções e impactos sociais (degraus de cima).


## Acessibilidade e Design Universal

> [!quote] Premissa de IHC  
> A preocupação principal não são os problemas técnicos em si, mas **como eles afetam a experiência do usuário**. Projetar para a "média" ou para um "usuário padrão" é uma atitude excludente. É preciso considerar as diferenças desde o princípio do design.

A **Acessibilidade** e o **Design Universal** propõem criar soluções que se adaptem a todos, sem obrigar o usuário a se adaptar ao sistema. O objetivo é ser útil e equitativo para pessoas com as mais diversas habilidades, evitando a segregação. Para garantir isso no ambiente digital, a **W3C** atua como a principal organização a trazer diretrizes e orientações globais de acessibilidade para a tecnologia.
Para colocar esses conceitos em prática, o Design Universal alia a usabilidade através dos seguintes princípios fundamentais:
- **Uso Equitativo:** O design é útil e comercializável para pessoas com diferentes capacidades, fornecendo os mesmos meios de uso para todos ou equivalentes quando não for possível. Deve evitar segregar ou estigmatizar qualquer usuário, garantindo privacidade, segurança e atratividade iguais para todos.
- **Flexibilidade no Uso:** O design acomoda uma ampla variedade de preferências e habilidades individuais, oferecendo escolha nos métodos de utilização (ex: uso destro ou canhoto). Deve facilitar a exatidão e a precisão do usuário, além de se adaptar ao seu próprio ritmo de interação.
- **Uso Simples e Intuitivo:** Fácil de entender, independentemente da experiência, conhecimento ou nível de concentração do usuário. Evita complexidades desnecessárias e deve ser consistente com a intuição (ex: jogos com tutoriais).
- **Informação Perceptível:** O design comunica a informação necessária de forma efetiva, usando diferentes modos (pictórico, sonoro, tátil). Deve haver contraste claro entre as informações essenciais e secundárias.
- **Tolerância ao Erro:** Minimiza riscos e consequências adversas de ações acidentais. Os elementos mais usados devem ser os mais acessíveis, enquanto os elementos secundários ficam isolados ou protegidos.
- **Baixo Esforço Físico:** O sistema deve ser usado de forma confortável e eficiente, com o mínimo de fadiga. Isso envolve postura corporal neutra e a minimização de ações repetitivas.
- **Dimensão e Espaço:** O tamanho e o espaço para aproximação e uso devem ser apropriados, independentemente do tamanho do corpo, postura ou mobilidade do usuário. Deve-se considerar também o limite da área de visão para elementos importantes.

## Avaliação Heurística (AH)

> [!abstract] O que é?  
> É um **método de inspeção** (não envolve usuários) onde **3 a 5 especialistas** em IHC analisam a interface **"advogando pelo usuário"**. Eles usam um conjunto de diretrizes (heurísticas) para prever decisões erradas de design e encontrar problemas de usabilidade durante o processo iterativo.[](http://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_07_avaliacao_heuristica.pdf#1#3#1)
> 
> - **"Heurística"** vem do grego e significa "servir para descobrir". É um conhecimento prático, baseado na experiência, e não em uma comprovação científica rígida.[](http://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_07_avaliacao_heuristica.pdf#1#3#1)
>     

### Como Funciona (O Processo)

O processo ocorre da seguinte forma:
1. **Estudo da Técnica:** Entender como a AH funciona e quais heurísticas serão usadas.
2. **Estudo do Sistema:** Conhecer a interface, o público-alvo e as tarefas que ela deve suportar (o avaliador deve se colocar no lugar do usuário).
3. **Avaliação Individual:** Cada especialista inspeciona a interface sozinho, navegando pelas telas e listando todos os problemas que encontrar, associando cada um à heurística violada.
4. **Reunião Individual:** Os avaliadores se reúnem para discutir o que encontraram, alinhar as descobertas e resolver divergências.
5. **Consolidação:** Unir todos os problemas em uma única lista, remover duplicatas e definir a **gravidade** de cada um. A gravidade é essencial para priorizar o que deve ser corrigido primeiro.
6. **Apresentação dos Resultados:** Gerar um relatório final claro para a equipe de desenvolvimento, com os problemas, a gravidade e sugestões de solução.

### Escala de Severidade (Gravidade)

Após a inspeção, cada problema é classificado para que a equipe saiba o que priorizar. A escala mais comum vai de 1 a 4 (ou 5, dependendo do autor):
- **1 - Cosmético:** Não é um problema de usabilidade real; consertar apenas se houver tempo sobrando.
- **2 - Pequeno:** Baixa prioridade; consertar se possível.
- **3 - Grande:** Alta prioridade; prejudica a usabilidade e deve ser corrigido.
- **4 - Catastrófico:** Prioridade máxima; impede o usuário de realizar a tarefa. O produto não deve ser lançado antes de consertar.
