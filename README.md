# Projeto Fonte

Como primeiro trabalho da disciplina Eletrônica Para Computação, desenvolvemos e montamos uma fonte de tensão ajustável, que tem a tomada como fonte de tensão fornecendo uma corrente alternada de 127 Volts, que será retificada e resultará em uma corrente contínua, fornecendo uma faixa de tensão idealmente entre 3 e 12 volts.

## Alunos
- #### Pedro Calciolari Jardim Nº USP: 11233668
- #### João Pedro de Matos Deus Nº USP:
- #### Henrique Nº USP:
- #### Marcos Nº USP: 

## Lista de Componentes

| Componente       | Valor (R$) | Quantidade |
|------------------|:----------:|:----------:|
| Transformador    |            |      1     |
| Potenciômetro 5k |            |      1     |
| Capacitor        |            |      1     |
| LED              |            |      1     |
| Diodo Zener      |            |      1     |
| Transistor       |            |      1     |
| Fusível          |            |      1     |
| Resistor         |            |      3     |
| Diodo            |            |      4     |
| Total:           |      x     |            |


## Componentes e Valores Escolhidos

-   #### Transformador:
    Precisamos transformar a tensão de 127 volts que vem da tomada para os 12 volts que teremos na saída, sabemos que a razão de saída de um transformador é dada por:
    
    $ R = \frac{V_{out}}{V_{in}}$
    
    $ R = \frac{12}{127} = 0,1 $
    
    Por isso foi escolhido um transformador de XXXXXXXXXXXXX

- ### Capacitor:
    Queremos um ripple de 10%, para isso temos a fórmula:
    
    $ V_{ripple} = \frac{i}{2 f C} $
    
    Cálculo de i, a corrente total:
    
    $ i = i_{carga} + i_{RZener} + i_{pot} $

    Calculamos cada termo individualemente:
    - $ i_{carga} = \frac{V_{zener} - V_{be}}{R_{carga}} = XXX $
    - $ i_{RZener} = \frac{V_{medio} - V{zener}}{1000} = XXX $
    - $ i_{pot} = \frac{V_{zener}}{X} = XXX $
    
    Logo:
    - $ i = i_{carga} + i_{RZener} + i_{pot} = XXXX $
    
    Voltando à fórmula do ripple:
    $ C = \frac{i}{2 f V_{ripple}} = ETC $


## Circuito no Falstad

## Esquemático PCB

## Imagem PCB no EAGLE/PROTEUS

## Circuito na Protoboard

## Vídeo com simulação e explicação
