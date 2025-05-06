# Luta até a morte

![_](cover.jpg)

## Motivação

Considere o seguinte formato de dicionário que deve ser usada em seu programa:  
  
personagem = {"Vida: \*\*\*, "Ataque": \*\*\*}  
  
Usando a definição acima, crie um programa que leia os dados (vida e ataque) de dois personagens, representados por um dicionário do tipo mostrado acima, e implemente a função duelo:  
  
A função duelo recebe como entrada dois dicionários, onde cada um deles representa um personagem. Ela deve imprimir "Personagem 1" se o primeiro personagem venceu o duelo, "Personagem 2" se o segundo personagem venceu o duelo e "Empate" caso nenhum deles tenha vencido o duelo. O duelo consiste em uma sequência de rodadas onde em cada rodada o primeiro personagem ataca o segundo (tira-se da vida do 2o personagem o valor do ataque do 1o personagem) e o segundo ataca o primeiro (tira-se da vida do 1o personagem o valor do ataque do 2o personagem) ao mesmo tempo. O duelo acaba quando pelo menos um dos personagens fica com vida menor ou igual a 0.  
  
### Entrada

- 1a linha - vida do 1o personagem  
- 2a linha - ataque do 1o personagem
- 3a linha - vida do 2o personagem  
- 4a linha - ataque do 2o personagem  

## Exemplos

``` py
>>>>>>>> INSERT
100  
20  
100  
1
======== EXPECT
Personagem 1
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
100
20
100
1
======== EXPECT
Personagem 1
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
100
20
1000
10
======== EXPECT
Personagem 2
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
100
100
1000
10
======== EXPECT
Empate
<<<<<<<< FINISH
```
