# Controle Motor (Motor Control)

## O que é Controle Motor em IHC ?
**Controle motor humano**, refere-se à regulação do 
movimento pelo sistema nervoso, integrando informações 
sensoriais internas e externas para ativar os músculos 
corretos. Em IHC,o foco está em ações como digitar em um 
teclado, tocar em telas sensíveis, mover o cursor com um
 mouse ou realizar gestos no ar.
 
**Conceitos Chave**
- **End-Effector(Efetuador Final)**, *é a parte do corpo* 
diretamente *utilizada na tarefa de interação* (ex.: a ponta 
do indicador, a mão, ou o próprio cursor guiado).

- **Graus de Liberdade(Degrees of Freedom):**, o número de 
eixos independentes em que uma articulação ou dispositivo 
pode se mover (ex.: o joelho possui 1 grau de liberdade; o 
quadril ou ombro possuem 3)

- **Malha**
-> Aberta(Open-Loop), movimentos balísticos rápidos 
executados sem feedback para correção durante a ação (ex.: 
pressionar uma tecla bem conhecida).
- (Uma ação que se tornou automática)

-> Fechada(Closed-Loop), o sistema nervoso recebe e processa 
feedback sensorial (visual, tátil, proprioceptivo) *durante* 
o movimento para corrigir a trajetória e garantir precisão.

**Compromisso Velocidade-Precisão (Speed-Accuracy**
**Trade-off)**, princípio universal em que o sistema motor não pode ser simultaneamente ultra-rápido e ultra-preciso; acelerar o movimento aumenta inevitavelmente a taxa de erro ou variabilidade espacial

## Aquisição de Alvos e a Lei de Fitts
- A **aquisição de alvo** (*target acquisition*), é um 
movimento direcionado e espacialmente restrito (como o ato
de apontar e clicar em um botão).

- Proposta pelo psicólogo Paul Fitts em 1954, a Lei de Fitts 
é um dos modelos preditivos mais sólidos e validados em 
IHC. Ela prevê o *Tempo de Movimento* *médio* necessário para 
atingir um alvo unidimensional com base na sua *distância*
e sua *largura*  -> MT = a + b.ID

**Implicações Práticas de Design Derivadas de Fitts:**
- **Botões Maiores e Mais Próximos**, aumentar largura ou 
diminuir a distânica reduz o ID e torna a seleção mais 
rápida.
- **Bordas e Cantos da Tela (O "Tamanho Infinito")**, em 
interfaces de desktop, as bordas da tela impedem que o
cursor passe do limite físico. Isso torna a largura efetiva 
do alvo virtualmente "infinita", fazendo com que cantos e 
bordas sejam os alvos mais rápidos de selecionar.
- **Métrica de Throughput (Vazão)**, permite comparar o 
desempenho de diferentes dispositivos de entrada (mouse vs. 
stylus vs. touchpad) independentemente do tamanho do alvo.

## Reações Simples e Reações de Escolha
Quando os usuários interagem com eventos no ambiente, o
tempo de resposta varia conformae a complexidade do cenário:
***OBS: Possui relação com affordense ?***

- **Reação Simples**, ocorre quando existe apenas um 
**único estimulo** e uma **única resposta** possível.
(Ex: pisar no freio ao ver a luz vermelhar, ou pressionar um
botão de confirmação quando um bipe soa)

- **Reação de Escolha**, em tarefas onde o usuário deve
escolher entre **n** alternativas de resposta ao receber
um sinal, o **Tempo de Reação deEscolha** aumenta
proporcionalmente ao Ln de opções.

## Terafas de Trajetória
Nem todo moviemnto em IHC consiste apenas em clicar em 
pontos estáticos. Muitas tarefas exisgem percorrer caminhos
e desenhar formas.

- Lei de Steering, descreve o tempo necessário para guiar 
um cursos atráves de um "túnel".
- Lei de Potência da Curvatura de Viviani


