# Links sobre tudo
Pra facilitar minha vida de encher o Hangouts/e-mail dos amigos de links e ter que dar Ctrl+f nas mensagens depois <3

## Funções reutilizáveis
todo: Reoganizar estrutura de arquivos

~~~python
def listar_registros_nulos(df, campoNulo, campoChave ):
    
    listaCampochave = repo.loc[repo[campoNulo].isna()][campoChave]
    return df.loc[repo[campoChave].isin(listaCampochave)]
~~~
