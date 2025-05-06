# Opala bebedor

![_](cover.jpg)

[Explicação](https://youtu.be/d0nlVzjtMBE)

## Ação

Um amigo lhe deu a velocidade média do carro dele em km/h, o tempo da viagem em minutos e o consumo de um carro em litros e pediu que você faça um programa que calcule o desempenho do motor em km por litro.

## Dica

- O tempo em hora eh tempo em minutos/60
- A distancia percorrida é velocidade vezes tempo em horas
- O desempenho é distancia / consumo.

### Entrada

- Velocidade em km/h
- Tempo em minutos
- Consumo em litros

### Saída

- Desempenho com duas cadas decimais.

## Exemplos

``` py
>>>>>>>> INSERT corsa
100
60
10
======== EXPECT
10.00
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT fusca
60
40
10
======== EXPECT
4.00
<<<<<<<< FINISH
```

## Dica

Para imprimir em **c ou c++** com duas casas decimais use:

```C
//c ou c++
#include <stdio.h>
float a = 4.3243255;
float b = 3.4334344;
printf("a=%.2f e b=%.3f", a, b); //a=4.32 e b=3.433
```

Em  **Python**, você tem várias possibilidades.

```py
a = 4.3243255
b = 3.4334344
print("a={:.2f} e b={:.3f}".format(a, b)) //a=4.32 e b=3.433
```
[Veja outras opções na documentação oficial](https://docs.python.org/pt-br/3/tutorial/inputoutput.html#fancier-output-formatting)
