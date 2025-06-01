# TPC7

## Metadata

| Title | Date | AuthorId | AuthorName | UcSigla | UcNome |
|:-----:|:----:|:--------:|:----------:|:-------:|:------:|
| TPC7  |      | PG56010  | Rui Pinto  | SPLN    | Scripting no Processamento de Linguagem Natural |

## Resumo

Este trabalho consiste na criação e exploração de um modelo Word2Vec treinado sobre o texto de *Harry Potter and the Chamber of Secrets*. Utilizando o `gensim`, foi treinado um modelo para aprender representações vetoriais de palavras com base no contexto de uso no livro. O objetivo é analisar relações semânticas entre termos, calcular similaridades e visualizar a estrutura semântica do universo de Harry Potter.

O modelo final encontra-se guardado nos ficheiros `harry_potter_word2vec.model`, `vectors.bin` e `harry_potter_word2vec.wordvectors`.

A exploração é feita no notebook `harrypotter.ipynb`, onde são realizadas análises como:
- Palavras mais semelhantes a um termo dado;
- Operações vetoriais semânticas (ex: `king - man + woman ≈ queen`);
- Visualização de palavras em 2D com redução de dimensionalidade (t-SNE ou PCA).
