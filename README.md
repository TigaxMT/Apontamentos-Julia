# Apontamentos-Julia (Em construção)

Colocarei aqui todos os notebooks que vou escrevendo com apontamentos retirado do [manual](https://docs.julialang.org/en/v1/manual/getting-started/) da linguagem Julia.

***Nota***: Tudo escrito em português !


# REPL

Durante os meus apontamentos acabei por não falar do REPL (pelo menos, até agora). REPL siginifica (***R***ead-***E***val-***P***rint ***L***oop) e ele é bastante idêntico ao IDLE do Python, é uma forma de usar a linguagem interactivamente.

A parte mais interessante do REPL em júlia é que podemos aceder à documentação diretamente. Basta abrir um terminal e escrever: `julia` e assim entraremos no REPL. Agora basta escrevermos: `?` e de seguida a função, simbolo etc que queremos entender o que siginfica e o que faz. 

Por exemplo: `?sum` irá explicar-me o que o sum faz e vai-me dar alguns exemplos, tudo vindo diretamente da documentação!


# Como utilizar um Jupyter Notebook com Julia

Primeiramente precisam instalar o Jupyter Notebook ou o Jupyter Lab. Podem fazê-lo por [aqui](https://jupyter.org/install)

***Nota***: Não importa se instalarem com o pip (gestor de pacotes do Python), vai funcionar igual.

Depois basta abrir o REPL, escrever: `]` e de seguida escrever: `IJulia` e esperam instalar. Voilá! Têm o vosso Jupyter Notebook pronto a utilizar Kernels de Julia.

***Nota***: O `]` abre o modo de instalação de pacotes, para sairem deles basta clicarem no `BACKSPACE`.