# Divergencia-serie-harmonica
Prova visual da divergência da Série Harmônica

A série harmônica é dada por:
![](https://ideiasesquecidas.files.wordpress.com/2021/10/formula-harmonic.png)

Ela tem esse nome por conta do conceito de harmônicas, em música. Imagine prender uma corda de piano a um tamanho 1, depois a metade do tamanho, 1/3 do tamanho, etc.

É um resultado conhecido desde Bernoulli, no séc XVII, que a série harmônica diverge: o somatório dos termos tende a infinito.

![](https://ideiasesquecidas.files.wordpress.com/2021/10/provavisualdivserieharmonica.png)
A prova dos livros de matemática consiste em comparar com uma série conhecidamente divergente:

1/2 + 1/2 + 1/2 + …

Se eu somar o número 1/2 infinitamente, claramente a série vai divergir.

A série harmônica é maior do que a série divergente acima, basta rearranjar os termos. A figura acima ilustra as operações envolvidas.

Embora a série harmônica divirja, ela o faz muito lentamente.

Um programinha de 4 linhas em Python, para 1000 termos:

harmonic=0
for i in range(1,1001):
 harmonic += 1/i
print(harmonic)

Para 1000 termos, a soma dá 7,48.

Para 1 milhão de termos, a soma dá 14,39.

A soma dos primeiros 1043 termos é menor do que 100, segundo a Wikipedia, cujo link consta abaixo e tem outras informações interessantes.

É como a tartaruga do conto de Esopo: parece que nunca vai chegar lá, mas lenta e consistentemente, sempre cruza a linha de chegada!


Vide código do desenho no arquivo index.html, aqui no Github.

Vide também:

https://ideiasesquecidas.com/2021/10/17/prova-visual-da-divergencia-da-serie-harmonica/

https://ideiasesquecidas.com/laboratorio-de-matematica/
