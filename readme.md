# London Smart Energy project analysis

### English

Since the data science world is all about "Big data", I decided to look at the different ways to manipulate datasets that are too large to be loaded into the memory of my laptop. So far I've covered:
1. The `chunksize` parameter of pandas `read_csv`. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Pandas%20chunksize%20-%20London%20Smart%20Energy%20EN.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Pandas%20chunksize%20-%20London%20Smart%20Energy%20EN.pdf)
1. The Dask library. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Dask%20-%20London%20Smart%20Energy%20EN.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Dask%20-%20London%20Smart%20Energy%20EN.pdf)
1. PySpark API with Apache Spark. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/PySpark%20-%20London%20Smart%20Energy%20EN.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/PySpark%20-%20London%20Smart%20Energy%20EN.pdf)
1. Talend Open Studio [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Talend%20-%20London%20Smart%20Energy%20EN.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Talend%20-%20London%20Smart%20Energy%20EN.pdf)
1. PostgreSQL [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/PostgreSQL%20-%20London%20Smart%20Energy%20EN.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/PostgreSQL%20-%20London%20Smart%20Energy%20EN.pdf)

The repository contains notebooks and pdf versions, both in English and French.

**NB** - The first exercise (Pandas `chunksize`) does not remove duplicates, unlike all the others. I only realised after the first exercise that the dataset contained duplicates (rookie error!), and the `chunksize` method is far too slow and inefficient to handle the process in a reasonable time.

### Français

Puisque le "Big data" est un élément principal du monde de data science, j'ai décidé de regarder les moyens différents pour traiter les jeux de données qui sont trop grands pour être chargés en la mémoire de mon laptop.

Jusqu'ici j'ai fait:
1. Le paramètre `chunksize` de la méthode `read_csv`. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Pandas%20chunksize%20-%20London%20Smart%20Energy%20FR.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Pandas%20chunksize%20-%20London%20Smart%20Energy%20FR.pdf)
1. La bibliothèque Dask. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Dask%20-%20London%20Smart%20Energy%20FR.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Dask%20-%20London%20Smart%20Energy%20FR.pdf)
1. PySpark API avec Apache Spark. [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/PySpark%20-%20London%20Smart%20Energy%20FR.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/PySpark%20-%20London%20Smart%20Energy%20FR.pdf)
1. Talend Open Studio [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/Talend%20-%20London%20Smart%20Energy%20FR.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/Talend%20-%20London%20Smart%20Energy%20FR.pdf)
1. PostgreSQL [Notebook](https://github.com/jlad26/london-smart-energy/blob/master/PostgreSQL%20-%20London%20Smart%20Energy%20FR.ipynb) [Pdf](https://github.com/jlad26/london-smart-energy/blob/master/PostgreSQL%20-%20London%20Smart%20Energy%20FR.pdf)

Le répertoire contient des notebooks et des versions pdf, tous les deux en Anglais et en Français.

**NB** Veuillez noter que les doublons ne sont pas supprimés dans le premier exercice, contrairement à tous les autres. Je me suis rendu compte seulement après le premier exercice que le jeu de données contenait des doublons (erreur de débutant!), et la méthode `chunksize` est beaucoup trop lente et inefficace pour traiter les données dans un délai raisonnable.