# Aulas 02 e 03 — Conceitos de Semicondutores e Diodo

## Experimento 01 — Polarização direta versus polarização reversa de diodos

### Questão 1

Monte o circuito da Figura 1, ligue a fonte de tensão e observe o comportamento do LED. Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad → Arquivo → Exportar como Link). Qual o comportamento do LED?

> O LED acende, pois o diodo está polarizado diretamente. Nessa condição, o diodo permite a passagem de corrente pelo circuito, fazendo com que o LED seja acionado.
>
> [Circuito 1](https://www.falstad.com/s.php?s=roeAQ2)

### Questão 2

Meça a tensão em cima do resistor de 1k. Qual o valor encontrado? Explique o porquê da tensão ser menor que 5V.

> A tensão medida sobre o resistor de 1 kΩ é aproximadamente 2,8 V.
> Ela é menor que os 5 V da fonte porque parte da tensão é utilizada pelo diodo e pelo LED. 

### Questão 3

Calcule a corrente que passa pelo resistor 1k considerando que o LED vermelho opera em nível de tensão de 1,7V e o diodo com 0,7V. O valor calculado é igual ao medido no circuito simulado? Explique.

> A tensão no resistor é:
>
> V = 5 - 1,7 - 0,7 = 2,6 V
>
> Pela Lei de Ohm:
>
> I = V/R = 2,6/1000 = 0,0026 A = 2,6 mA
>
> Portanto, a corrente calculada é 2,6 mA. Na simulação, a corrente medida foi de 2,8 mA. Os valores são próximos, mas não iguais, devido às características dos modelos dos componentes utilizados na simulação.

### Questão 4

Monte o circuito da Figura 2, ligue a fonte de tensão e observe o comportamento do LED. Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad → Arquivo → Exportar como Link). Qual o comportamento do LED?

> O LED permanece apagado, pois o diodo está polarizado reversamente. Nessa condição, o diodo bloqueia a passagem da corrente pelo circuito.
>
> [Circuito 2](https://www.falstad.com/s.php?s=2jDS1x)

### Questão 5

De acordo com os comportamentos observados nos itens 1 e 4, qual é a diferença entre os dois circuitos de polarização?

> Na polarização direta, o diodo permite a passagem da corrente e o LED acende. Na polarização reversa, o diodo bloqueia a passagem da corrente e o LED permanece apagado.

### Questão 6

Refaça o circuito sem o diodo e observe o comportamento do LED sem o diodo. Houve alguma diferença? Qual o motivo?

> Sim. Sem o diodo, o LED continua acendendo, mas a corrente no circuito aumenta, pois não existe mais a queda de tensão de aproximadamente 0,7 V causada pelo diodo.

### Questão 7

Monte o circuito da Figura 3. Configure o gerador de sinais para gerar uma função senoidal de 5V de pico e frequência de 1Hz. Responda os seguintes itens:

#### a. O LED acende em algum momento? Com que frequência acontece?

> Sim. O LED acende durante o semiciclo positivo da onda senoidal, quando o diodo fica polarizado diretamente. Como a frequência do sinal é de 1 Hz, isso acontece uma vez por segundo.

#### b. O que acontece com a tensão no resistor 1k quando o sinal senoidal permanece no eixo da tensão negativa? Qual o motivo deste comportamento?

> Quando o sinal fica na parte negativa da senoide, o diodo fica polarizado reversamente e bloqueia a passagem da corrente. Por isso, a tensão no resistor fica aproximadamente em 0 V.

## Experimento 02 — Portas lógicas com diodos

### Questão 1

Monte o circuito da Figura 4. Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad → Arquivo → Exportar como Link).

> O circuito da Figura 4 foi montado no Circuit Simulator Falstad.
>
> [Circuito 4](https://www.falstad.com/s.php?s=hJNZAS)

### Questão 2

A alteração das chaves SW1 e SW2 para a posição 2 (sinal de tensão 5 V) representa o nível lógico 1. O nível lógico 0 é representado pela posição 1 (sinal de 0 V) das chaves. Observando o comportamento da carga (o LED) no circuito da Figura 4, qual porta lógica o circuito representa?

> O circuito representa uma porta lógica OR (OU). O LED acende quando pelo menos uma das entradas está em nível lógico 1. Ele só permanece apagado quando as duas entradas estão em nível lógico 0.
>
> A tabela-verdade é:
>
> | SW1 | SW2 | LED |
> |---|---|---|
> | 0 | 0 | 0 |
> | 0 | 1 | 1 |
> | 1 | 0 | 1 |
> | 1 | 1 | 1 |

### Questão 3

Monte o circuito da Figura 5 e analise o comportamento. Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad → Arquivo → Exportar como Link).

> O circuito da Figura 5 foi montado e analisado no Circuit Simulator Falstad.
>
> [Circuito 5](https://www.falstad.com/s.php?s=AHEKTN)

### Questão 4

A alteração das chaves SW1 e SW2 para a posição 2 representa o nível lógico 1. O nível lógico 0 é representado pela posição 1 das chaves. Observando o comportamento da carga (o LED) no circuito da Figura 4, qual porta lógica o circuito representa?

> O circuito representa uma porta lógica XNOR (OU-Exclusivo Negado). O LED acende quando as duas entradas possuem o mesmo nível lógico e permanece apagado quando as entradas são diferentes.
>
> A tabela-verdade é:
>
> | SW1 | SW2 | LED |
> |---|---|---|
> | 0 | 0 | 1 |
> | 0 | 1 | 0 |
> | 1 | 0 | 0 |
> | 1 | 1 | 1 |
