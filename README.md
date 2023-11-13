# Neo4j Paper Clustering

Find relationships between documents by embedding their contents and clustering using neo4j and python. In this demo research papers were used, and the abstracts embedded, but with a few modifications it could be extended to work with any type of document.

`cluster.py` contains the code to cluster the documents given the extracted data (title, abstract, embeddings, url) in a json file. To generate this data, place your papers in the `papers` folder and run the `extract/extract_papers.py` script.
