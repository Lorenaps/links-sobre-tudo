# Limpeza de Dados

## Lidando com datas

```
def conversao_string_datetime(df, coluna):
    
    df[coluna] = pd.to_datetime(df[coluna], dayfirst=True)
    
    df[coluna + '_mes'] = df[coluna].dt.month_name(locale='pt_BR.UTF-8')
    df.astype({colunaNova + '_mes': 'category'}).dtypes

    df[coluna + '_mes_numero'] = df[coluna].dt.month
    df.astype({colunaNova + '_mes_numero': 'category'}).dtypes

    df[coluna + '_ano'] = df[coluna].dt.year
    df.astype({colunaNova + '_ano': 'category'}).dtypes

    return df
```
## Limpeza de strings

- [Usar as funções do str](https://docs.python.org/2/library/stdtypes.html#string-methods)

Exemplo:
    ```
    dados['nome_cidade'].str.lower().str.rstrip().str.lstrip()
    ```
    
Onde:
- lower() - Coloca toda a string como minúscula
- rstrip() - Sem parâmetro retira apenas os espaços em branco do lado direito da string. Com parâmetro tenta extrair apenas do lado direito aquilo que foi passado.
- lstrip() - Funciona igual ao rstring porém aplicando a transformação no lado esquerdo da string.
