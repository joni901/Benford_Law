A Lei de Benford, também conhecida como Lei dos Primeiros Dígitos, é um fenômeno estatístico que descreve a distribuição de dígitos em muitos conjuntos de dados do mundo real. A lei afirma que, em muitas coleções de números, o primeiro dígito significativo (o dígito à esquerda) não é uniformemente distribuído, como seria esperado intuitivamente, mas segue uma distribuição logarítmica específica.

De acordo com a Lei de Benford, a probabilidade P(d) de que um número comece com o dígito d (onde d varia de 1 a 9) é dada por:

P(d)=log10(1+1/d)

Essa distribuição implica que o dígito 1 deve ser o primeiro dígito significativo com maior frequência, seguido pelo 2, 3 e assim por diante, com o dígito 9 sendo o menos frequente.

A tabela de frequência esperada, de acordo com a Lei de Benford, seria algo como:


|Dígito	|Primeiro dígito|Segundo dígito|Terceiro dígito|Quarto dígito|	
|-------|---------------|--------------|---------------|-------------|
|0|Não se aplica|0,12|0,102|0,1|
|1|0,301|0,114|0,101|0,1|
|2|0,176|0,109|0,1|0,1|
|3|0,125|0,104|0,099|0,1|
|4|0,097|0,1|0,099|0,1|
|5|0,079|0,097|0,098|0,1|
|6|0,067|0,093|0,098|0,1|
|7|0,058|0,09|0,097|0,1|
|8|	0,051|0,088|0,097|0,1|
|9|0,046|0,085|0,096|0,1|
