## Beispielhaftes Content Recommendation System 
Empfiehlt, ausgehend von einem beispielhaften Film, fünf andere aus den Top 1000 Filmen der IMDB.

### Grundlage
[Beispielarchitektur](https://towardsdatascience.com/hands-on-content-based-recommender-system-using-python-1d643bf314e4) von Piero Paialunga

### Relevante Software und Packages
 - Python 3
 - Jupyter 
 - matplotlib
 - Numpy
 - SentenceTransformer
 - Pandas
 - Seaborn
 - scikit-learn

### Anleitung
1. Vollständiges Ausführen (`Run all`) des Notebooks trainiert Neuronales Netz
2. Neu-Ausführen des 7. Blocks führt zu neuen Empfehlungen für 4 zufällig ausgewählte Filme
3. Befehl `give_recommendations(i,True,True)`, wobei i+1 die Nummer des Filmes in [imdb_top_1000.csv](imdb_top_1000.csv) ist, generiert Empfehlungen für den Film