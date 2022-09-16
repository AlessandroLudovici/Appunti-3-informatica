# Esercizi

## Conversioni

- $320_4$ in base 10
	> $$0*4^0 + 2*4^1 + 3*4^2 = 56_{10}$$

- $1101_3$ in base 10
	> $$1*3^0+0*3^1+1*3^2+1*3^3 = 37_{10}$$

- $005_6$ in base 10
	> $$5*6^0 = 5_{10}$$


## Operatori Logici

- (A and B) or (B or B)

| A | B | A and B | B or B | (A and B) or (B or B) |
|:-:|:-:|:-------:|:------:|:---------------------:|
| V | V |    V    |    V   |           V           |
| V | F |    F    |    F   |           F           |
| F | V |    F    |    V   |           V           |
| F | F |    F    |    F   |           F           |

- (A xor B) and (A or not A)

| A | B | A xor B | not A | A or not A | (A xor B) and (A or not A)|
|:-:|:-:|:-------:|:-----:|:----------:|:-------------------------:|
| V | V |    F    |    F  | V          |    F                      |
| V | F |    V    |    F  | V          |    V                      |
| F | V |    V    |    V  | V          |    V                      |
| F | F |    F    |    V  | V          |    F                      |

- A or not A  (questa e' una *tautologia* ovvero una proposizione sempre vera)

| A |  not A | A or not A|
|:-:|:-:|:-:|
|V|F|V|
|F|V|V|

