# Apontamentos-Julia (Em construção)

Colocarei aqui todos os notebooks que vou escrevendo com apontamentos retirados do [manual](https://docs.julialang.org/en/v1/manual/getting-started/) da linguagem Julia.

***Nota***: Tudo escrito em português !

# Uma aprendizagem mais prática

Talvez estes apontamentos sejam mais uma versão em português do manual da linguagem Julia e, poderá, haver pessoas que preferem uma abordagem mais prática.

Para essas pessoas recomendo a inscreverem-se no [Exercism](https://exercism.io/) e fazer os exercícios da trilha de Julia.

Caso queiram alguma ajuda, podem ver as minhas soluções no meu [perfil](https://exercism.io/profiles/iN127pkt), assim como as soluções da comunidade.  

# Conteúdos de Julia em Português

Caso queiram conhecer mais conteúdos desta fantástica linguagem, em português, tenho 2 recomendações:

* [Programação Dinâmica](https://www.youtube.com/channel/UC70mr11REaCqgKke7DPJoLg): Neste canal vocês podem encontrar uma playlist, onde acompanham a jornada do Hallinson, aprendendo Julia no Exercism.
Também poderão ver uma playlist, onde o mesmo implementou um algoritmo de Ray Tracing com Julia.

* [Abel Siqueira](https://www.youtube.com/channel/UCrHWmb1a2JW50QovKgkcKCQ): Aqui vão ter uma playlist só com tutoriais de Julia, assim como outras playlists, onde o Abel fala sobre tópicos mais voltados para a matemática, porém aplica-os utilizando Julia.

# Aviso
[1] Gostava de referir que ler os notebooks direto do Github tem a desvantagem de que certas coisas, como alguns símbolos do LaTeX não são mostrados ou aparecem como "Unknown".
***Para ler de forma mais confortável e completa, leia as informações abaixo de como utilizar os Jupyter Notebooks.***

[2] A numeração dos notebooks não tem de ser seguida sequencialmente, pois eu terei o cuidado de referir onde expliquei algum tópico caso esse mesmo tópico apareça em outro notebook mais à frente.

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
