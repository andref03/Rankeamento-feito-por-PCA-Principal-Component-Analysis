# **Ranking de Distritos com PCA - Análise de Componentes Principais**

## **O que é PCA: Análise fatorial de Componentes Principais**

> O **PCA** é uma técnica de modelagem não supervisionada. Ou seja, não buscamos uma previsão (não há *variável alvo*).

> As variáveis serão transformadas em **fatores**, de tal forma que o *1º fator* irá explicar, sozinho, a maior parte do comportamento das variáveis. O *2º fator* irá explicar a segunda maior parte do comportamento dessas mesmas variáveis, e assim por diante com os *demais fatores*. Os últimos fatores serão muito menos explicativos.

> A **quantidade de fatores** que podemos ter em uma análise é justamente limitada à mesma **quantidade de variáveis** que possuímos em determinado *banco de dados*.

> Variáveis do tipo catégorico (strings) não serão utilizados no tratamento de dados por PCA. Apenas variáveis numéricas (int, float) poderão ser utilizadas.

### **Aplicações do PCA**

> Redução da dimensionalidade dos dados (diminui a qtdd de variáveis na tabela);

> Remoção da *multicolinearidade* dos dados (retira a correlação forte que talvez possa existir entre variáveis, pois os *fatores do PCA* não teram correlação entre si);

> Elaboração de rankings.

---
# Sobre o rankeamento dos distritos do município de São Paulo

> O banco de dados, arquivo ```distritos_sp.csv```, possui informações gerais sobre distritos do município de São Paulo. Essas informações podem ser reduzidas, de forma que consideraremos alguns "fatores" que as "agrupam" e, então, podemos representar o mesmo banco de dados com menos informações. Ou seja, diminuiremos a dimensionalidade desse banco de dados. Isso é feito através da **técnica de PCA**.

> Após a redução de dimensionalidade (variáveis), podemos rankear quais são os distritos que apresentam melhores condições, destacando também quais necessitam de mais atenção por parte do governo. 

> Esse ranking pode ser visto em tabela, mas também pode ser visto em forma de um "mapa de calor" (ou "heat map"), que é possível com a **biblioteca geopandas**. Ao final deste projeto, temos um mapa em formato ```.html``` adicionado neste repositório: ```rankings.html```.
