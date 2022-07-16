# winequality-red
Regressão Linear

## **CONCEITO DE REGERSSÃO LINEAR**

De forma bastante direta, Regressão Linear é uma técnica paramétrica onde você irá fazer a predição de um alvo contínuo. 
Este alvo contínuo pode ser a previsão do faturamento de uma empresa, o preço de cotação de uma ativo na bolsa de valores ou até mesmo o preço de um imóvel que você esteja analisando para comprar. 

A fórmula da regressão linear é a seguinte:
y = β0 + β1 * X + e. Onde:

y = É minha variável alvo. Ou seja, o preço que estou tentando prever.
β0 = É o Intercepto. Que é o ponto onde o valor no qual a linha ajustada cruza o eixo x.
β1 = Inclinação da curva da minha regressão. 
x = Minha variável preditora
e = Erro do meu modelo

Os valores de β0 e β1 são os coeficientes da nossa regressão. O β0 nós já sabemos que é o ponto onde o valor no qual a linha ajustada cruza o eixo x. Já o β1 é o cara que explica quanto a minha variável y muda dada a variação em uma unidade de x. 

Na prática você pode imaginar que seu β1 vale 1 e seu x vale 0,5. Logo seu y terá uma variação de 0,5 a cada variação de x.

Para calcular o valor de β1  temos a seguinte equação:
β1 = ( x - x )( y - y )(x - x )2
onde:
x é a minha variável preditora.
x é a média de todas as variáveis preditoras
y é a minha variável predita
y é a média das minhas variáveis preditoras.

Já o cálculo do β0 é bem mais simples. 
β0 = y  - β1( x ) 
Faltou falar do erro que tambem é bastante simples de ser calculado. Para isso temos a equação abaixo: 

 e = (y-y )2

Já que começamos a falar de erros, vamos nos aprofundar no assunto.

**TSS, RSS, ESS: Definição**
