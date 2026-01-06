# Análise de Agrupamento Hierárquico — Pinguins 🐧

Este projeto aplica técnicas de **clusterização hierárquica** na base de dados dos pinguins (disponível no `seaborn`).  
O objetivo é explorar padrões naturais entre as espécies e verificar se o algoritmo consegue separar grupos de forma coerente.

## Etapas realizadas
1. Seleção das variáveis quantitativas (comprimento e profundidade do bico, comprimento da nadadeira e massa corporal).
2. Eliminação de valores faltantes.
3. Padronização das variáveis (média = 0, desvio padrão = 1).
4. Agrupamento hierárquico inicial em 3 grupos.
5. Visualização com dendrograma.
6. Avaliação dos grupos:
   - Quantidade de pinguins por espécie em cada cluster.
   - Estatísticas descritivas das variáveis quantitativas.
7. Alteração do agrupamento para 5 grupos, conforme sugerido pelo dendrograma.
8. Análise dos novos clusters:
   - Espécie × cluster.
   - Espécie × sexo × cluster.
   - Interpretação dos padrões capturados (diferenças entre espécies e dimorfismo sexual).

## Conclusão
- Com 3 grupos, o algoritmo separou bem as espécies (Gentoo, Adelie e Chinstrap).
- Com 5 grupos, além da separação por espécie, o algoritmo capturou diferenças entre machos e fêmeas em Gentoo e Adelie.
- O agrupamento hierárquico refletiu padrões **naturais e biológicos** presentes nos dados.
