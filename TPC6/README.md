# TPC6

## Metadata

| Title | Date | AuthorId | AuthorName | UcSigla | UcNome |
|:-----:|:----:|:--------:|:----------:|:-------:|:------:|
| TPC6  |      | PG56010  | Rui Pinto  | SPLN    | Scripting no Processamento de Linguagem Natural |

## Resumo

Este trabalho consiste na extração automática de artigos do site *Natura* usando técnicas de web scraping com `requests` e `BeautifulSoup`. O script `natura.py` percorre as páginas de índice, segue os links dos artigos e extrai informações como o título, autor, data de publicação e conteúdo principal. Os artigos são guardados localmente em ficheiros `.txt` individuais. Para otimizar o processo e evitar requisições repetidas, utiliza-se uma cache persistente via `shelve`.

