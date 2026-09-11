# Aula 01 - Introdução à Eletrônica

O presente exercício tem como objetivos a revisão dos conceitos de Circuitos Elétricos e a aprendizagem de utilização da plataforma Falstad.

## Exercício 01
Implemente o circuito abaixo e responda as questões que seguem.
<img width="342" height="227" alt="image" src="https://github.com/user-attachments/assets/9b02ba02-7660-418e-9aaf-f5d9f8a7ff4f" />

### Questão 1
Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad → Arquivo
→ Exportar como Link)
> [Link da simulação](https://www.falstad.com/s.php?s=G12HGt)

### Questão 2
Calcule a tensão e a corrente que passa pelo resistor de 1k.
> Como o resistor de 1kΩ está ligado em paralelo com a fonte de 5V, a tensão sobre ele é igual à tensão da fonte:
> V = 5V.
> Para calcular a corrente, utilizamos a Lei de Ohm:
> I = V/R.
> Substituindo os valores, temos:
> I = 5/1000 = 0,005 A.
> Convertendo para miliampères -> 5mA.
> Logo, a tensão sobre o resistor de 1kΩ é 5V e a corrente que passa por ele é 5mA.

### Questão 3
Com o auxílio de um multímetro na função de amperímetro, meça a corrente que
passa pelo resistor de 1k. LEMBRE-SE que o amperímetro deve ser ligado em série
com o ramo do circuito.
> Na simulação, o amperímetro foi conectado em série com o ramo do resistor de 1kΩ, conforme orientado. O valor medido foi de aproximadamente 5mA.

### Questão 4
Compare o valor medido com o valor calculado.
> Os valores comparados são praticamente iguais, o que confirma o resultado obtido pelo cálculo.

### Questão 5
Se tivéssemos utilizando um circuito com elementos reais (e não simulados), a corrente
calculada seria exatamente a mesma da calculada? Justifique.
> Não necessariamente. Isso ocorre porque, em um circuito real, os componentes não são ideais e possuem tolerâncias e pequenas variações em seus valores. Além disso, a fonte e os instrumentos de medição também podem apresentar pequenas diferenças em relação aos valores ideais.

## Exercício 02 — Carga e descarga de capacitores
A Figura 2 apresenta um circuito RC com uma malha para carregar e descarregar o capacitor.
Quando a chave encontra-se na posição A, o capacitor é carregado. Quando na posição B,
o capacitor é descarregado.
<img width="376" height="264" alt="image" src="https://github.com/user-attachments/assets/54b11352-c10f-496b-af6f-206150d3f5a8" />

### Questão 1
Envie o arquivo da simulação como um link Falstad (Circuit Simulator Falstad →
Arquivo → Exportar como Link)
>[Circuito 2](https://www.falstad.com/s.php?s=b9EuMU)

### Questão 2
Calcule a constante de tempo do circuito RC.
> A constante de tempo de um circuito RC é calculada pela fórmula τ=R⋅C. Considerando R = 220.000Ω
C=22μF=22×10
−6
F.
> Temos: τ=(220.000)(22×10
−6
)
$$ \boxed{\tau=4,84s} $$
Resposta: A constante de tempo do circuito é 4,84 s.

### Questão 3
Utilizando a simulação, faça a permuta da chave para a posição A e meça o tempo
que levou para a tensão sobre o capacitor sair de 0V e alcançar 1,9 V.

### Questão 4
Discuta os seguintes questionamentos:
a. O tempo medido foi similar à constante de tempo do circuito RC? Sabe por
quê?
b. Se a resistência do circuito da Figura 2 for alterada para um valor de 100k, o
tempo para a tensão do capacitor chegar em 1,9V é maior ou menor que o
tempo medido com a resistência 220k? Justifique.
#### a.

#### b.

### Questão 5
Retorne a chave para a posição B e observe o comportamento da tensão do capacitor.
Explique o que acontece.
