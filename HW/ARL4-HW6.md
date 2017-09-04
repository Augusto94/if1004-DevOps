HW6
===================

----------

No artigo as pesquisas foram elaboradas para explorar 3 questões referentes aos erros de compilação:
-------------

    

 - Com que frequência as compilações falham?
 - Porque as compilações falham?
 - Quanto tempo demora para consertar compilações falhadas?

## **Resultados**

Com que frequência as compilações falham?
> 
Por desenvolvedor a porcentagem média de falhas em C++ é de 38% e em Java 28%. Desses foram investigados os devs que obtiveram maior taxa e menor taxa de falhas em suas compilações.
Daqueles que tiveram menor taxa de erros, a média de compilações por mês era de 41 a 45, já daqueles que tiveram maior taxa de erros nas compilações a quantidade média por mês era de 22 a 27 compilações.
Ambos possuiam uma diferença discrepante dos demais devs que tinham uma média de 101 a 147 compilações por mês.

Porque as compilações falham? 
> 
Para saber as razões dos erros foram coletadas e analisadas as mensagens de logs. A maiores causas de falhas estão relacionadas aos erros de sintaxe, quando o compilador não entende determinado “símbolo”  e com relação às dependências entre os componentes.

Quanto tempo demora para consertar compilações que falharam?
> 
O modo para calcular o tempo para corrigir um erro de compilação foi definido entre o momento em que a primeira compilação falhou até o início da compilação que teve sucesso.
No geral para resolver um erro de compilação em C++ o tempo era de 5 minutos e em Java o tempo para resolver era de 12 minutos.

## **Conclusão**
> 
> A fase build é uma etapa fundamental no processo de desenvolvimento de software em que os desenvolvedores utilizam ferramentas para gerar um executável do seu código. O autor do artigo fala também que quanto maior a velocidade de compilação de um código maior será a produtividade do desenvolvedor. Se menos erros de compilação ocorrer está diretamente relacionado com a produtividade do desenvolvedor.
Esse artigo através de métricas faz um estudo para mapear os principais fatores que influenciam nos erros de compilação, para através dos resultados identificar quais são os fatores cruciais e tomar medidas para mitigar esse problema de erros de compilação na indústria de software, visto que erros de compilação sempre vão acontecer e o objetivo é minimizar o máximo.
