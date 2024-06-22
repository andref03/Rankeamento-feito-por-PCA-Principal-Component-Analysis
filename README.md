# **Ranking de Distritos com PCA - Análise de Componentes Principais**

---
### **O que é PCA: Análise fatorial de Componentes Principais**

> O **PCA** é uma técnica de modelagem não supervisionada. Ou seja, não buscamos uma previsão (não há *variável alvo*).

> As variáveis serão transformadas em **fatores**, de tal forma que o *1º fator* irá explicar, sozinho, a maior parte do comportamento das variáveis. O *2º fator* irá explicar a segunda maior parte do comportamento dessas mesmas variáveis, e assim por diante com os *demais fatores*. Os últimos fatores serão muito menos explicativos.

> A **quantidade de fatores** que podemos ter em uma análise é justamente limitada à mesma **quantidade de variáveis** que possuímos em determinado *banco de dados*.

#### **Aplicações do PCA**

> Redução da dimensionalidade dos dados (diminui a qtdd de variáveis na tabela);

> Remoção da *multicolinearidade* dos dados (retira a correlação forte que talvez possa existir entre variáveis, pois os *fatores do PCA* não teram correlação entre si);

> Elaboração de rankings.
