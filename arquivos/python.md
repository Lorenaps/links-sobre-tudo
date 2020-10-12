# Python
- [Map(), Reduce(), Filter() e Lambda - Python Help](https://pythonhelp.wordpress.com/2012/05/13/map-reduce-filter-e-lambda/)
- [Operadores em Python - Programiz](https://www.programiz.com/python-programming/operators)
- [Trabalhando com muitos arquivos](http://jonathansoma.com/lede/foundations-2017/classes/working-with-many-files/class/)
- [Pyplot: LaTeX Math Env.](https://stackoverflow.com/questions/27474322/why-i-get-error-while-trying-to-use-latex-in-plots-label)
- [Modules vs Packages vs Libraries in Python](https://knowpapa.com/modpaclib-py/)
- [Pycubator - Exceções](http://df.python.org.br/pycubator/07-exceptions.html#/1)
- [How to Use Python Profilers: Learn the Basics](https://stackify.com/how-to-use-python-profilers-learn-the-basics/)
- [How to profile memory usage in Python](https://www.pluralsight.com/blog/tutorials/how-to-profile-memory-usage-in-python)
- [Um pacote massa pra laços longos](https://tqdm.github.io/)
- [Acesso ao Unicode Database](https://docs.python.org/3/library/unicodedata.html)

  - Exemplo de uso:

    ~~~python
    remover_acentos = lambda s: unicodedata.normalize('NFKD',str(s)).encode('ASCII','ignore').decode('utf-8')
    
    s = 'óbvio'
    print(remover_acentos(s))
    # obvio
    
    ~~~

- Similaridade entre strings:
  - [SequenceMatcher](https://stackoverflow.com/questions/17388213/find-the-similarity-metric-between-two-strings)
  - [Levenshtein & Cosine Similarity](https://towardsdatascience.com/calculating-string-similarity-in-python-276e18a7d33a)
  - [Levenshtein *vs*. SequenceMatcher](https://stackoverflow.com/questions/6690739/high-performance-fuzzy-string-comparison-in-python-use-levenshtein-or-difflib)

## Pandas 

- [Lendo csv com Pandas](https://medium.com/@kadek/elegantly-reading-multiple-csvs-into-pandas-e1a76843b688)
- [Concatenando data frames](https://gist.github.com/abladon/72c4eb17546a3c195978)
- [Working with missing data](https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html)
- [Pandas Select rows by condition and String Operations](https://kanoki.org/2019/03/27/pandas-select-rows-by-condition-and-string-operations/)
- [Python Pandas Groupby Tutorial](http://www.pybloggers.com/2018/12/python-pandas-groupby-tutorial/)

## Jupyter

- [Parametrizando notebooks](https://papermill.readthedocs.io/en/latest/)
- [Embedding Matplotlib Animations](http://louistiao.me/posts/notebooks/embedding-matplotlib-animations-in-jupyter-notebooks/)
  - `ffmpeg` MovieWriter [issue](https://stackoverflow.com/questions/13316397/matplotlib-animation-no-moviewriters-available) 
- [nbviewer - A simple way to share Jupyter Notebooks](https://nbviewer.jupyter.org/)
- [Binder - Executando notebooks pelo navegador](https://mybinder.org/)

### Google Colab

- [Importing a library that is not in Colaboratory](https://colab.research.google.com/notebooks/snippets/importing_libraries.ipynb#scrollTo=iDu3Slhq2zyh)

## RegEx

- Usando RegEx para encontrar números primos:
  - Código `python` [aqui](https://stackoverflow.com/a/33951990)
  - Explicação detalhada [aqui](https://iluxonchik.github.io/regular-expression-check-if-number-is-prime/)
  


