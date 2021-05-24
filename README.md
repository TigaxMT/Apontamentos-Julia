# Apontamentos-Julia (Em construção)

Colocarei aqui todos os notebooks que vou escrevendo com apontamentos retirados do [manual](https://docs.julialang.org/en/v1/manual/getting-started/) da linguagem Julia.

***Nota***: Tudo escrito em português !

# Aviso
Gostava de referir que ler os notebooks direto do Github tem a desvantagem de que certas coisas, como alguns símbolos do LaTeX não são mostrados ou aparecem como "Unknown".
***Para ler de forma mais confortável e completa, leia as informações abaixo de como utilizar os Jupyter Notebooks.***

# REPL

Durante os meus apontamentos acabei por não falar do REPL (pelo menos, até agora). REPL siginifica (***R***ead-***E***val-***P***rint ***L***oop) e ele é bastante idêntico ao IDLE do Python. É uma forma de usar a linguagem interativamente.

A parte mais interessante do REPL em Julia é que podemos aceder à documentação diretamente do REPL. 

Basta abrir um terminal e escrever: `julia` e assim entraremos no REPL. Agora basta escrevermos: `?` e de seguida a função, variável, símbolo etc... que queremos entender o que siginfica e o que faz. 

Por exemplo: `?sum` irá explicar-me o que a função `sum` faz e vai-me dar alguns exemplos. Tudo isso vindo diretamente da documentação!


# Como utilizar um Jupyter Notebook com Julia

Primeiramente precisam instalar o Jupyter Notebook ou o Jupyter Lab. Podem fazê-lo por [aqui](https://jupyter.org/install).

***Nota***: Não importa o método de instalação, pode ser com o pip (gestor de pacotes do Python), vai funcionar igual.

Depois basta abrir o REPL, escrever: `]` e de seguida escrever: `add IJulia` e esperam instalar. Voilá! Têm o vosso Jupyter Notebook pronto a utilizar Kernels de Julia.

***Nota***: O `]` abre o modo de instalação de pacotes, para sairem deles basta clicarem na tecla `BACKSPACE`.