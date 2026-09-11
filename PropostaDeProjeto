# Comedouro Doméstico Inteligente com RFID

## 1. Proposta

Desenvolvimento de um comedouro doméstico inteligente capaz de identificar individualmente os animais por meio de etiquetas RFID presentes em suas coleiras e liberar uma quantidade de ração adequada para cada animal.

O sistema também deverá registrar os momentos em que cada animal se alimentou e disponibilizar essas informações por meio de uma interface conectada à internet.

## 2. Problema

Em residências com mais de um animal, pode ser difícil controlar individualmente a alimentação de cada um. Animais diferentes podem possuir necessidades distintas de quantidade de ração e, em alguns casos, um animal pode consumir a comida destinada a outro.

O projeto busca solucionar esse problema por meio da identificação individual dos animais e do controle automatizado da quantidade de alimento disponibilizada.

## 3. Objetivo geral

Desenvolver um comedouro inteligente capaz de identificar animais por RFID e liberar automaticamente uma quantidade de ração definida para cada animal, registrando também os eventos de alimentação em uma interface conectada à internet.

## 4. Funcionamento

O funcionamento proposto será:

1. O animal se aproxima do comedouro.
2. O leitor RFID identifica a etiqueta presente na coleira.
3. O microcontrolador identifica qual animal está associado àquela etiqueta.
4. O sistema verifica a quantidade de ração configurada para aquele animal.
5. O mecanismo do comedouro libera a quantidade correspondente de ração.
6. O sistema registra o horário e o animal que se alimentou.
7. As informações são enviadas pela internet para uma interface de acompanhamento.

O sistema também poderá verificar se o animal já recebeu sua porção naquele período, evitando a liberação de uma segunda porção.

## 5. Exemplo de funcionamento

Um exemplo seria:

- Animal 1: 4 kg → 50 g de ração
- Animal 2: 8 kg → 80 g de ração

Quando o Animal 1 for identificado pelo RFID, o sistema libera a quantidade configurada para ele. Quando o Animal 2 for identificado, o sistema libera a quantidade correspondente ao segundo animal.

As quantidades serão previamente configuradas de acordo com as características de cada animal, como idade e peso.

## 6. Componentes e tecnologias

A implementação poderá utilizar:

- ESP32 como microcontrolador;
- Leitor RFID;
- Etiquetas RFID adaptadas às coleiras;
- Servo motor ou motor DC para controlar a liberação da ração;
- Sensor para auxiliar na medição da quantidade de ração;
- Reservatório para armazenamento da ração;
- Conexão Wi-Fi;
- Interface web para acompanhamento das informações.

## 7. Interface

A interface permitirá acompanhar informações relacionadas à alimentação dos animais, como:

- Animais cadastrados;
- Peso e idade;
- Quantidade de ração configurada;
- Horário da última alimentação;
- Histórico de alimentações;
- Quantidade de ração fornecida.

## 8. Comunicação com a Internet

O ESP32 será responsável pela comunicação do comedouro com a internet.

Após cada alimentação, o sistema poderá enviar os dados para a interface, permitindo acompanhar os eventos de alimentação em tempo real.

## 9. Propósito

O propósito do projeto é automatizar e individualizar a alimentação de animais domésticos, permitindo controlar a quantidade de ração fornecida para cada animal e acompanhar seus hábitos alimentares remotamente.

## 10. Fluxo básico do sistema

Animal se aproxima
↓
Leitura da etiqueta RFID
↓
Identificação do animal
↓
Verificação da quantidade de ração
↓
Liberação da ração
↓
Registro da alimentação
↓
Envio dos dados pela Internet
↓
Visualização na interface
