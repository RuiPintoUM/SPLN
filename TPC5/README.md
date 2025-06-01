# TPC5

## Metadata

| Title | Date | AuthorId | AuthorName | UcSigla | UcNome |
|:-----:|:----:|:--------:|:----------:|:-------:|:------:|
| TPC5 |      | PG56010  | Rui Pinto  | SPLN    | Scripting no Processamento de Linguagem Natural |

## Resumo

Este trabalho tem como objetivo extrair correspondências terminológicas entre o português e o tétum a partir de documentos estruturados ou semi-estruturados. Para isso, foi definida uma gramática Lark capaz de identificar linhas contendo definições nas duas línguas, figuras e outros conteúdos não reconhecidos. O script `pt-tt.py` utiliza esta gramática para segmentar o texto, transformar os dados com recurso a um `Transformer`, e guardar os elementos não reconhecidos num ficheiro `unknown.txt`. As correspondências válidas são apresentadas em formato tabular.
