---
layout: page
title: "Unidade 1: computação"
---

# <i class="fa-solid fa-microchip"></i> Unidade 1: computação

Nesta unidade começaremos nosso estudo sobre computação e, mais especificamente,
sobre ciência da computação. Nosso objetivo é fazer com que você entenda os
grandes fundamentos da computação, incluindo:

* O que é ciência da computação
* Representação de dados no computador
* Algoritmos
* Pensamento computacional
* Abstração

O conteúdo desta unidade está dividido em 6 partes, sendo a primeira parte uma
visão geral do que estudaremos. Em cada parte você encontrará o vídeo da aula, o
texto correspondente e demais recursos. Utilize o sumário abaixo para navegar no
conteúdo da unidade.

**Sumário:**
- PARTE 0: [visão geral da unidade](#parte-0-visão-geral-da-unidade)
    * [Vídeo da parte 0](#parte-0-visão-geral-da-unidade)
- PARTE 1: [o que é ciência da
  computação?](#parte-1-o-que-é-ciência-da-computação)
    * [Vídeo da parte 1](#vídeo-da-parte-1-o-que-é-ciência-da-computação)
    * [Essência e conceito da ciência da
      computação](#essência-e-conceito-da-ciência-da-computação)
    * [Modelo geral da computação](#modelo-geral-da-computação)
    * [Conhecimento declarativo e
      imperativo](#conhecimento-declarativo-e-imperativo)
- PARTE 2: [representação de dados](#parte-2-representação-de-dados)
    * [Vídeo da parte 2](#vídeo-da-parte-2-representação-de-dados)
* [Diário de Aprendizagem](diario_unidade_0.pdf)


## PARTE 0: visão geral da unidade
{% video https://www.youtube.com/watch?v=XbuHXSoKZOM %}
<i class="fa-light fa-download"></i> <i class="fa-light fa-file-pdf"></i>
[Download dos slides do vídeo](unidade_1_parte_0.pdf)

Esta unidade compreende o estudo dos **fundamentos da computação** e dará a base
a partir da qual você aprenderá os pilares da computação e formará uma fundação
para as próximas unidades. Se você ainda não terminou as atividades da [Unidade
0: introdução](/unidades/0/), é importante que você não prossiga: estude
primeiro a Unidade 0 (incluindo fazer o diário de aprendizagem) e, depois,
continue aqui na Unidade 1.

Nesta Unidade 1 falaremos sobre os grandes fundamentos da computação, incluindo
discussões sobre: a) o que é ciência da computação; b) representação de dados em
um computador; c) algoritmos; d) pensamento computacional; e, por último, e)
abstração. A abstração, na verdade, é um dos componentes do pensamento
computacional mas, de tão importante, merece uma discussão detalhada em
separado. Este é o conteúdo desta unidade:

![Mapa mental da unidade 1](imagens/mapa_unidade.png)


## PARTE 1: o que é ciência da computação?
### Vídeo da parte 1: o que é ciência da computação?
{% video https://www.youtube.com/watch?v=qzxw-Tm8UgI %}
<i class="fa-light fa-download"></i> <i class="fa-light fa-file-pdf"></i>
[Download dos slides do vídeo](unidade_1_parte_1.pdf)

### Essência e conceito da ciência da computação
Existe uma certa confusão sobre o que é realmente a ciência da
computação. Muitas pessoas acreditam que computação é praticamente um sinônimo
de programação. Esse entendimento não é correto: a programação nos permite
expressar idéias e resolver problemas através de computadores mas a **essência**
da ciência da computação não depende de programação.

{% alert "primary" %}
Ciência da computação **NÃO É** sobre programação.
{% endalert %}

Outras pessoas acreditam que ciência da computação é o trabalho com
computadores. Mas essa visão também não é correta: os computadores são meras
ferramentas de trabalho, são ferramentas fantásticas que programamos para nos
ajudar a resolver problemas de forma mais rápida, mas a **essência** da ciência
da computação também não depende de computadores (na verdade, alguns dos mais
antigos e fundamentais desenvolvimentos teóricos da computação ocorreu entre
1920 e 1940, muitos anos antes do desenvolvimento dos primeiros computadores).

{% alert "primary" %}
Ciência da computação **NÃO DEPENDE** de computadores.
{% endalert %}

Alguns pensam que ciência da computação é o estudo dos usos e aplicações dos
computadores e softwares. Essa visão também não é correta: saber usar um
computador ou um software específico não é a essência da ciência da computação,
da mesma forma que saber dirigir um carro não é a essência da engenharia
automotiva.

{% alert "primary %}
Ciência da computação **NÃO É** sobre o uso de computadores e softwares.
{% endalert %}

Computadores, programação e o uso e a aplicação de softwares fazem parte do
"mundo" da computação mas não formam, isoladamente ou em conjunto, a essência da
ciência da computação.

Na realidade a ciência da computação é sobre **resolver problemas** de um certo
modo, de uma certa maneira. Mas como formalizar então qual é a **essência** da
ciência da computação? Talvez uma das melhores explicações sobre a essência da
ciência da computação foi dada por [Hal
Abelson](https://en.wikipedia.org/wiki/Hal_Abelson), um dos autores do soberbo
livro **Structure and Interpretation of Computer Programs**
([SICP: HTML
original](https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/index.html);
[SICP: HTML novo](https://sarabander.github.io/sicp/); [SICP:
PDF](https://media.githubusercontent.com/media/sarabander/sicp-pdf/master/sicp.pdf);
[SICP: Texinfo](https://www.neilvandyke.org/sicp-texi/); [SICP: PDF da versão
JS](https://sicp.sourceacademy.org/sicpjs.pdf); [SICP: Comparison
Edition](https://sicp.sourceacademy.org/)), em uma aula para funcionários da
Hewlett-Packard, em julho de 1986. Abelson explica o que é a ciência da
computação do seguinte modo:

> [A ciência da computação] Também não se trata muito de computadores. E não se
> trata de computadores no mesmo sentido em que a física não se trata realmente
> de aceleradores de partículas, e a biologia não se trata realmente de
> microscópios e placas de Petri. E não se trata de computadores no mesmo
> sentido em que a geometria não se trata realmente do uso de instrumentos
> topográficos.
>
> Na verdade, há muitos pontos em comum entre a ciência da computação e a
> geometria. A geometria, antes de mais nada, é outra disciplina com um péssimo
> nome. O nome vem de Gaia, que significa Terra, e metron, que significa
> medir. Geometria, originalmente, significava medir a Terra ou fazer
> levantamentos. E a razão para isso foi que, há milhares de anos, o sacerdócio
> egípcio desenvolveu os rudimentos da geometria para descobrir como restaurar
> os limites dos campos que foram destruídos pelas cheias anuais do Nilo. E,
> para os egípcios que fizeram isso, a geometria era realmente o uso de
> instrumentos topográficos.
> Agora, a razão pela qual pensamos que a ciência da computação trata de
> computadores é praticamente a mesma razão pela qual os egípcios pensavam que a
> geometria tratava de instrumentos de levantamento. E isto é, quando alguma
> área está apenas começando e você não a entende muito bem, é muito fácil
> confundir a essência do que você está fazendo com as ferramentas que você
> usa. E, de fato, numa escala absoluta de coisas, provavemente sabemos menos
> sobre a essência da ciência da computação do que os antigos egípcios realmente
> sabiam sobre geometria.
>
> Bem, o que eu quero dizer com essência da ciência da computação? O que quero
> dizer com essência da geometria? Veja, é certamente verdade que esses egípcios
> usavam instrumentos de topografia, mas quando olhamos para eles depois de
> alguns milhares de anos, dizemos, caramba!, o que eles estavam fazendo, a
> coisa importante que estavam fazendo [a essência da geometria], era começar a
> formalizar noções sobre espaço e tempo, para iniciar uma maneira de falar
> formalmente sobre verdades matemáticas. Isso levou ao método axiomático. Isso
> levou a que toda matemática moderna descobrisse uma maneira de falar
> precisamente sobre o chamado conhecimento declarativo, sobre o que é
> verdadeiro.
>
> Bem, da mesma forma, acho que no futuro as pessoas olharão para trás e dirão,
> sim, aqueles primitivos do século 20 estavam brincando com esses dispositivos
> chamados computadores mas, na verdade, o que eles estavam fazendo era
> começando a aprender como formalizar intuições sobre processos, sobre como
> fazer as coisas, começando a desenvolver uma forma de falar precisamente sobre
> o conhecimento de como fazer alguma coisa [conhecimento imperativo], em
> oposição à geometria que fala sobre o que é verdadeiro [conhecimento
> declarativo].

Quando achamos que ciência da computação é sobre programação e computadores,
estamos confundindo a **essência da computação** com as **ferramentas** que são
utilizadas (os computadores). Quando uma nova área de estudo está sendo
desenvolvida é fácil confundir a essência com as ferramentas, e é essa confusão
que nos faz achar que ciência da computação é sobre computadores (a ciência da
computação é muito nova). Na verdade a essência da ciência da computação é
formalizar "receitas de bolo" (chamadas de **algoritmos**) que nos permitem
saber **como fazer as coisas**, sobre **como resolver problemas**. Em resumo,
podemos dizer que:

{% alert "success" %}
**CIÊNCIA DA COMPUTAÇÃO É A CIÊNCIA QUE ESTUDA, CRIA E IMPLEMENTA ALGORITMOS
PARA SOLUCIONAR PROBLEMAS.**
{% endalert %}

Nós estudaremos em detalhes o que é um algoritmo na Parte 3 desta unidade. Por
ora basta entender que um algoritmo é como se fosse uma "receita de bolo" que
seguimos para resolver um determinado problema, para realizar um determinado
processo. A palavra **algoritmo** (bem como a palavra **algarismo**) foi criada
a partir do nome de um matemático persa que viveu entre os séculos VIII e IX
(c. 780 - c. 850) chamado de **Abū Abd Allāh Muḥammad ibn Mūsā al-Khwārizmī**
(Pai de Abdullah, Mohammed, filho de Moisés, nativo de Khwarizm). Al-Khwārizmī
foi um gênio matemático à época, e seus trabalhos introduziram os numerais
hindu-arábicos e os conceitos de álgebra na matemática ocidental. Alguns de seus
trabalhos descreviam um modo sistemático de obter soluções para equações
quadráticas, ou seja, uma "receita" a ser seguida. A foto abaixo é uma estátua
em sua homenagem, na cidade de Khiva, atual Uzbequistão:

![al-khwarizmi](imagens/alkhwarizmi.jpg)

### Modelo geral da computação
Quando falamos que a ciência da computação resolve problemas, uma pergunta óbvia
é: **como** a computação resolve os problemas? Na verdade existe um "modelo
geral" através do qual a computação resolve problemas. Esse modelo de computação
pode ser ilustrado na figura abaixo:

![Modelo geral da computação](imagens/modelo_da_computacao.png)

A partir de um determinado **problema**, fazemos o **input** (entrada) do
problema no computador. Esse problema será tratado por um **algoritmo** (a
"receita" para a solução do problema) e o computador fará o **output** (saída)
da solução. Esse modelo é muito importante: toda vez que você pretende resolver
um problema de forma computacional, você deve pensar e se fazer as seguintes
perguntas?

0. Qual é o **input** (entrada), ou seja, qual é o problema que eu quero
   resolver?
0. Qual é o **output** (saída), ou seja, qual é a solução esperada do problema?
0. E, por fim, que **algoritmo** me permite processar a entrada (o problema) e
   obter a saída correta (a solução)?

Atenção: não subestime a segunda pergunta, a solução esperada para o
problema. Muitas pessoas tendem a se focar somente no problema e não têm uma
visão clara de qual deve ser a solução correta, a solução esperada para o
problema. Se você não tem clareza em qual deveria ser a solução correta, é mais
difícil encontrar um algoritmo. Como você vai achar um algoritmo para
transformar o input no output, se você não sabe em que output quer chegar?

### Conhecimento declarativo e imperativo
Vamos voltar agora ao texto do Hal Abelson (acima). Note que ele nos diz que a
ciência da computação diz respeito a saber **como fazer** as coisas, em oposição
à saber **o que é** alguma coisa. Aqui existe uma distinção importante entre
dois "tipos" diferentes de conhecimento: o conhecimento **declarativo** e o
conhecimento **imperativo**. Para a ciência da computação, o conhecimento
imperativo é fundamental. Vamos entender melhor a diferença entre esses dois
"tipos" de conhecimento.

{% alert "info" %}
O conhecimento **declarativo** nos diz o que é verdadeiro, nos diz o que é
alguma coisa, define alguma coisa.
{% endalert %}

O conhecimento declarativo é a formalização da verdade, é o que é alguma
coisa. Por exemplo, eu quero calcular a raiz quadrada de $$33$$, ou seja, eu
quero calcular $$\sqrt{33}$$. Bom, a primeira coisa que eu preciso saber é **o
que é a raiz quadrada de um número**. A matemática nos diz exatamente o que é a
raiz quadrada:

{% alert "light" %}
$$\sqrt{x} = y\ |\ y \ge 0 \wedge y^2 = x$$
{% endalert %}

ou seja, a raiz quadrada de um número $$x$$ é o número $$y$$ tal que $$y$$ seja
maior ou igual a zero e que $$y^2$$ seja igual ao número $$x$$. Esse tipo de
conhecimento nos diz exatamente **o que é** a raiz quadrada, nos diz a
verdade. Mas não nos diz como calcular uma raiz quadrada. Ele é o "ponto de
partida", é a base a partir da qual podemos resolver um problema mas, por si só,
o conhecimento declarativo não nos diz como resolver o problema. E é aqui que
precisamos do conhecimento imperativo.

{% alert "info" %}
O conhecimento **imperativo** nos diz como fazer alguma coisa.
{% endalert %}

No caso do cálculo da $$\sqrt{33}$$, por exemplo, podemos utilizar o Método de
Newton, que diz o seguinte:

{% alert "light" %}
0. Chute um valor para $$y$$;
0. Calcule o valor de $$y^2$$;
0. Se $$y^2 = x$$, ou um valor próximo o suficiente, você achou a raiz. Termine
   o procedimento.
0. Se $$y^2 \ne x$$, ou não está próximo o suficiente, melhore a estimativa de
   $$y$$ fazendo o seguinte cálculo: novo $$y = \cfrac{y + \cfrac{x}{y}}{2}$$;
0. Retorne ao segundo passo até que você encontre a raiz ou uma aproximação
   suficiente.
{% endalert %}
   
Se seguirmos o algoritmo do Método de Newton e fizermos os cálculos manualmente,
acharemos que $$\sqrt{33} \approx 5.7445626$$.

Percebe-se então claramente a diferença entre o conhecimento declarativo e o
conhecimento imperativo:

* O conhecimento declarativo nos diz o que é alguma coisa (por exemplo, nos diz
  o que é uma raiz quadrada); e
* O conhecimento imperativo nos diz como fazer alguma coisa (por exemplo, como
  calcular a raiz quadrada de um número).

Perceba que, a partir do momento em que conseguimos estabelecer um algoritmo,
uma série de passos não ambíguos, bem ordenados, que terminam em um tempo hábil,
conseguimos achar a solução para o problema de forma "mecânica", basta apenas
seguir o algoritmo. Esta é a essência da ciência da computação: criar esses
algoritmos, essas "receitas" precisas que nos mostram como resolver um
problema.

Outro exemplo para entender a diferença entre conhecimento declarativo e
conhecimento imperativo: qual é o máximo divisor comum entre $$82$$ e $$44$$? A
primeira coisa que precisamos saber é **o que é** o máximo divisor comum entre
dois números. A matemática nos diz precisamente que (conhecimento declarativo):

{% alert "light" %}
"O máximo divisor comum ($$\text{mdc}$$) entre dois números $$a$$ e $$b$$,
$$\text{mdc}(a, b)$$, é o maior número $$x$$ que seja divisor ao mesmo tempo de
$$a$$ e $$b$$, ou seja, $$\text{rem}(a/x) = 0\ \wedge \text{rem}(b/x) = 0$$,
onde: $$a, b \in \mathbb{Z}$$ (ambos não podem ser $$0$$ ao mesmo tempo), $$x
\in \mathbb{Z}^*_+$$, $$\text{rem}$$ significa o resto do divisão, e
$$\text{mdc}(a, 0) = \text{mdc}(0, a) = |a|$$."
{% endalert %}

Sem entrar em muitos detalhes na matemática da coisa, a definição acima nos diz
que o máximo divisor comum é o maior número que divide os outros dois. Isso é
conhecimento declarativo, é o tipo de conhecimento que nos diz o que é alguma
coisa. E como calcular então o máximo divisor comum entre dois números? Para
isso precisamos de uma "receita", de um algoritmo, então precisamos do
conhecimento imperativo, o conhecimento de como fazer alguma coisa.

Para calcular o máximo divisor comum entre $$82$$ e $$44$$ usaremos o Método de
Euclides (conhecimento imperativo):

{% alert "light" %}
0. Inicie com $$\text{mdc}(a, b)$$;
0. Substitua $$\text{mdc}(a, b)$$ por $$\text{mdc}(b, \text{rem}(a/b))$$;
0. Continue substituindo até que apareça $$\text{mdc}(x, 0)$$;
0. Nesse momento $$\text{mdc}(a, b) = \vert x \vert$$.
{% endalert %}

Se seguirmos o Método de Euclides veremos que $$\text{mdc}(82, 44) = 2$$.


## PARTE 2: representação de dados
### Vídeo da parte 2: representação de dados
(em breve)
