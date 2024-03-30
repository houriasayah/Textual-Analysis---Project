# Textual-Analysis---Project

## Contexte :
Ce projet s'inscrit dans le cadre de notre formation, Master 1 MIASHS à Paul Valéry. 
Le groupe est composé de :
- Guilhem Dardé
- Florian Dubois
- Houria Sayah
- Alvin Vedel

## Les données :
- Les données utilisées se présentent sous la forme d'un corpus de texte de paroles de chansons. Le jeu de données initial *"song.csv"* qui se trouvent dans l'onglet Data nous a servi de base. Il contient les titres des chansons ainsi que le nom de l'artiste et le genre musical. 
- Ces informations nous ont permis de récupérer les paroles des chansons en les scrappant à l'aide la librairie BeautifulSoup depuis le site *Genius* (https://genius.com/). Les chansons ainsi obtenus représentent des textes de longueur variable dans des langues différentes (anglais, espagnol, français, ...)
Le script de scrapping est disponible dans l'onglet Scripts

## L'analyse :

### Apprentissage supervisé :
Une des bases de notre analyse consiste à prédire le genre musical uniquement avec les paroles, c'est une tâche de classification supervisée. Au cours de ce projet nous explorerons les différents algorithmes et leurs performances.

Bien que cela ne figure pas dans nos données, les analyses de sentiments sont particulièrement intéressantes notamment dans le cadre des chansons afin d'analyser la corrélation entre le genre et les sentiments prédominants. A l'aide de librairie possédant déjà de gros volumes de données, nous pourrons effectuer cette analyse de manière supervisée.

### Apprentissage non-supervisé :
L'apprentissage non-supervisé peut nous ouvrir des perspectives d'analyses nouvelles. Des algorithmes de clustering comme le LDA peuvent être intéressants à appliquer afin d'identifier des ressemblances entre les chansons.