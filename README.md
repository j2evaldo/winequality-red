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

**TSS**
A soma dos quadrados total , denotada SST , é a diferença quadrática entre a variável dependente observada e sua média . Você pode pensar nisso como a dispersão das variáveis ​​observadas em torno da média – bem como a variância nas estatísticas descritivas .
É uma medida da variabilidade total do conjunto de dados.
Nota lateral : Existe outra notação para o SST . É TSS ou soma total de quadrados.

**RSS**
O segundo termo é a soma dos quadrados devido à regressão , ou SSR . É a soma das diferenças entre o valor previsto e a média da variável dependente . Pense nisso como uma medida que descreve quão bem nossa linha se ajusta aos dados.
Se esse valor de SSR for igual à soma dos quadrados total , significa que nosso modelo de regressão captura toda a variabilidade observada e é perfeito. Mais uma vez, temos que mencionar que outra notação comum é ESS ou soma de quadrados explicada .

**ESS**
O último termo é o erro da soma dos quadrados , ou SSE . O erro é a diferença entre o valor observado e o valor previsto.
Geralmente queremos minimizar o erro . Quanto menor o erro, melhor o poder de estimação da regressão . Por fim, devo acrescentar que também é conhecido como RSS ou soma de quadrados residual . Residual como em: remanescente ou inexplicável.
Estas três métricas de erro são muito importantes pois é através delas que poderemos calcular o R2 . Vale lembrar que quanto mais próximo de 1, melhor tende a ser nosso modelo. 

R2 = 1 - (SSE / SST)

**Considerações Finais**
Para termos um bom modelo de regressão linear é importante notar que temos que ter alguns pré-requisitos: 
1) Relação linear entre minhas variáveis preditoras e variável alvo.
2) Ausência de correlação entre todas as variáveis preditoras. 
3) Os erros devem ter a variância constante. Homocedasticidade. Não pode conter Heterocedasticidade
4) Os erros não podem ser correlacionados.
5) A variável alvo e os erros devem ter uma distribuição normal.

