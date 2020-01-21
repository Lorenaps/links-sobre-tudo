# Links sobre tudo
Pra facilitar minha vida de encher o Hangouts/e-mail dos amigos de links e ter que dar Ctrl+f nas mensagens depois <3

## Funções reutilizáveis
todo: Reoganizar estrutura de arquivos

~~~python
def listar_registros_nulos(df, campo_null, campo_id ):
    
    lista_id = repo.loc[repo[campo_null].isna()][campo_id]
    return df.loc[repo[campo_id].isin(lista_id)]
~~~
