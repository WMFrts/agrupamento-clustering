<h3> <center>CLUSTERIZAÇÃO</center> </h3>
<hr size="1" width="100%" align="center" noshade> 



<h3> SOBRE </h3>


<p align = "JUSTIFY"> Clustering ou clusterização é uma técnica de mineração de dados para realização de agrupamentos de dados (Hartigan, 1975). Segundo JAIN et al. (1999), o processo de clusterização é a classificação não-supervisionada de dados, formando agrupamentos ou clusters. Representa uma das principais etapas de processos de análise de dados, denominada análise de clusters.  De uma forma geral, Clusterização consiste em agrupar elementos de uma determinada base de dados em subgrupos, onde esses elementos que compartilham as mesmas características estarão agrupadas em um mesmo cluster </p> <br>

<p align = "JUSTIFY"> Visto a importância e utilidade dessa técnica para a compreensão do comportamento de dados, este projeto aplica o algoritmo K-means, Agrupamento Hierárquico e Clusterização Espacial Baseada em Densidade de Aplicações com Ruído, bem como a comparação entre as aplicações dessas técnicas em duas bases de dados; uma sobre idade relacionada à salário e outra sobre cartão de crédito. </p><br>
  
<p align = "JUSTIFY"> Abaixo, segue um dos dendogramas que constam nesse projeto. Quanto maior a distância entre os números do eixo x, maior é a diferença entre os dados. Para definir o número de cluster, deve ser escolhida a maior barra vertical, a barra escolhida deve ter o menor número de cruzamento. Escolhida a barra, traça-se uma linha horinzontal a esta e conta-se o número de barras que foram tocadas - nesse caso, serão 3; então, 3 clusters </p>

<img src="https://github.com/WMFrts/agrupamento-clustering/blob/main/dendograma.png?raw=true">

<h3>BIBLIOTECAS/IMPORTAÇÕES</h3>

* plotly.express
* plotly.graph_objs   
* numpy
* KMeans
* make_blobs
* PCA
* dendrogram
* AgglomerativeClustering
* DBSCAN
* matplotlib.pyplot 

<br>

<h3>ÍNDICE</h3>

<dl>
  
<dt>1 AGRUPAMENTO COM K-MEANS</dt>
<dt>1.1 BIBLIOTECA</dt>
<dt>1.2 BASE IDADE E SALÁRIO</dt>
<dt>1.3 TESTE RANDÔMICO</dt>
<dt>1.4 BASE CARTÃO DE CRÉDITO</dt>
<dt>2 AGRUPAMENTO HIERÁRQUICO</dt>
<dt>2.1 BASE SALÁRIO</dt>
<dt>2.2 BASE CARTÃO DE CRÉDITO</dt>
<dt>3 DBSCAN</dt>
<dt>3.1 BASE SALARIO E IDADE</dt>
<dt>3.2 BASE CARTÃO DE CRÉDITO</dt>
<dt>4 K-MEANS, HIERÁRQUICO E DBSCAN - COMPARAÇÕES</dt>
<dt>4.1 BASE DE DADOS PREDEFINIDAS</dt>
<dt>4.2 K-MEANS</dt>
<dt>4.3 HIERÁRQUICO</dt>
<dt>4.4 DBSCAN</dt>

  
</dl>

<br>
<h3>REFERÊNCIAS</h3>


<p align = 'JUSTIFY'>Hartigan, J.A. (1975). “Clustering Algorithms”, John Wiley.


<p align = 'JUSTIFY'> Jain, A. K., Murty, M. N. and Flynn, P. J. (1999). “Data clustering: a review”. ACM
Computing Surveys, 31(3), 264 – 323.
