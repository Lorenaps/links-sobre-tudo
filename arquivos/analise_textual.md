# Análise textual | Regex

## Vocabulário
- [Sinônimos brasileiros: portuguese-brazilian-synonyms by Rafael Stavarengo e ferramenta TeP2.0](https://github.com/stavarengo/portuguese-brazilian-synonyms)
- [Ferramenta TeP2.0](http://www.nilc.icmc.usp.br/tep2/busca.php)


## Regex
- Pegar todo texto depois de `de` ou `d e` :`(?:(?<=de)|(?<=d e))([\\s\\S]*)$"`. Se relaciona com erros de *look-behind requires fixed-width pattern*
  - Referências:
    - [Link 1](https://www.vivaolinux.com.br/artigo/Expressoes-Regulares-Entenda-o-que-sao-Lookahead-e-Lookbehind)
    - [Link 2](https://stackoverflow.com/questions/20089922/python-regex-engine-look-behind-requires-fixed-width-pattern-error)
