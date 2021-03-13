# Geração de imagens GASF-GADF-MTF para classificação por aprendizagem profunda residual (ResNet)

Trabalho feito na tentativa extrair a capacidade das ConvNets em classificação de imagens para classificação de séries temporais.

<b>Imaging.ipynb</b><br/>
Produz imagens Gramian Angular Fields Summation Fields (GASF), Gramian Angular Difference Fields (GADF) e Markov Transition Fields (MTF). As imagens são salvas em arquivos .pkl no formado (y,x,x,3), sendo y a quantidade de séries temporais e x o tamanho do PAA ou da série temporal. 
<br/><br/>

<b>ResNet.ipynb</b><br/>
Executa a classificação pela ResNet a partir das imagens salvas em .pkl
<br/><br/>

O formato de dados das séries temporais para geração das imagens pelo Imaging.ipynb podem ser encontrados em http://www.cs.ucr.edu/~eamonn/time_series_data/
