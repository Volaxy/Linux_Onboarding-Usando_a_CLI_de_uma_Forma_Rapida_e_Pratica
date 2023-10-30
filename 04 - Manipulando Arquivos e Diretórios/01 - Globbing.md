O caractere `*` trás qualquer coisa, Ex.:

`ls file*` retorna tudo que começa com *file*, inclusive um dado que tenha nome *file*.

O caractere `?` substitui 1 caractere, Ex.:
`ls file1?` retorna tudo que comece com *file1* e tenha 1 caractere depois somente

Para definir um *range*, coloca-se os caracteres entre `[]`, Ex.:
`??[1-5]`: Busca arquivos que contenham qualquer caractere na 1ª e 2ª posição e que a 3ª posição contenha um número de 1 a 5.