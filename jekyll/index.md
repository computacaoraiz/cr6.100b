---
layout: page
title: Home
---

# 1. Bem-vindo!
Esta é a disciplina **CR6.100B: Introdução à Ciência da Computação**, para
estudantes de ciência da computação, sistemas de informação, análise e
desenvolvimento de sistemas, engenharia da computação e, na verdade, qualquer
pessoa interessada, com ou sem experiência anterior em programação e/ou
computação.

Este curso ensina você a **resolver problemas**, com e sem código, com ênfase em
correção, design e estilo. Os tópicos incluem pensamento computacional,
abstração, algoritmos, estruturas de dados e ciência da computação de forma mais
ampla. PSETs (conjuntos de problemas) inspirados nas artes, humanidades,
ciências sociais e ciências. Mais do que ensinar você a programar em uma
determinada linguagem, este curso ensina os **fundamentos da computação** e os
**fundamentos da programação**, de forma que você consiga, por conta própria,
ensinar a você mesmo novas linguagens no final das contas. O curso começa com
uma linguagem tradicional, mas onipresente, chamada **C**, que foi uma
precursora e fundamento para as linguagens de programação mais modernas, através
da qual você aprenderá não apenas sobre funções, variáveis, condicionais, loops
e mais, mas, também, sobre como os computadores funcionam por "baixo do capô",
memória e tudo mais. Em seguida, o curso faz a transição para a **Python**, uma
linguagem de alto nível mais moderna que você compreenderá muito mais por causa
do C. No final o curso introduz a **SQL**, através do qual você pode armazenar
dados em bancos de dados, juntamente com **HTML**, **CSS** e **JavaScript**,
através dos quais você pode criar aplicativos web e móveis. O curso culmina em
um projeto final.

{% spoiler "VÍDEO: introdução da CR6.100B" %}
{% video https://www.youtube.com/watch?v=eyph1kcLnVw %}
<i class="fa-light fa-download"></i> <i class="fa-light fa-file-pdf"></i>
[Download dos slides do vídeo](/introducao_cr6100b.pdf)
{% endspoiler %}

{% spoiler "VÍDEO: introdução da CS50" %}
{% video https://www.youtube.com/watch?v=3oFAJtFE8YU %}
{% endspoiler %}


# 2. Sobre a CR6.100B
A CR6.100B é uma disciplina totalmente baseada e adaptada da famosa disciplina
[**Harvard CS50: Introduction to the Intellectual Enterprises of Computer
Science and the Art of Programming**](https://cs50.harvard.edu/x/), oferecida
gratuitamente na internet para todos os interessados.

Mas note o seguinte: a CR6.100B não é apenas uma mera tradução dos materiais da
CS50: é uma **adaptação de todo o conteúdo para as necessidades dos estudantes
brasileiros** (e de todos os estudantes que falam o português nativamente). Nós
temos certeza que você vai achar a nossa disciplina surpreendente (na verdade
estamos esperançosos de que você ache a CR6.100B até "melhor" do que a CS50, no
sentido de que está totalmente adaptada e voltada para o Brasil).

{% spoiler "VÍDEO: motivação para a CR6.100B e as diferenças com a CS50" %}
{% video https://www.youtube.com/watch?v=d7uDtdECwGg %}
<i class="fa-light fa-download"></i> <i class="fa-light fa-file-pdf"></i>
[Download dos slides do vídeo](/motivacao_diferencas.pdf)
{% endspoiler %}

## 2.1. Motivação: por que adaptar e não apenas traduzir a CS50?
Já é uma espécie de consenso de que a CS50 é uma das melhores disciplinas de
introdução à ciência da computação que existem na Internet. E melhor ainda: o
professor **David Malan** (atual responsável pela disciplina), criou uma
comunidade mundial de estudantes liberando a CS50 para qualquer pessoa! Se você
quiser estudar, basta ter um computador e uma conexão à Internet: toda a
infraestrutura é fornecida pela Universidade de Harvard, de modo gratuito. Se
você conseguir completar o curso e obter uma nota de aprovação, receberá um
certificado de conclusão diretamente de Harvard! Wow!

Entretanto não podemos deixar de ter em mente que a CS50 foi criada para ser uma
disciplina presencial para os alunos de Harvard. Se considerarmos que essa
universidade tem uma [taxa de aceitação de
4%](https://www.usnews.com/best-colleges/harvard-university-2155/applying),
podemos concluir que ela foi projetada para ser uma disciplina difícil e
desafiadora para um pequeno e seleto grupo de estudantes bem preparados, na
verdade estudantes dentre os mais bem preparados do mundo. Mais ainda: a
estrutura de suporte que Harvard coloca à disposição de seus alunos é
fantástica: laboratórios, assistentes de ensino, monitores, seminários e
monitorias extras e muito mais. Mas, infelizmente, essa não é a realidade para a
maioria dos estudantes no Brasil.

No Brasil temos alunos não tão bem preparados, alunos que trabalham o dia
inteiro para poder fazer um curso superior durante a noite, alunos que
terminaram o ensino médio com extremas deficiências em áreas exatas (ciência,
tecnologia e matemática), e alunos que não sabem estudar por conta própria e não
estão acostumados a se dedicar por muitas horas semanais para aprender (todos
conhecem a realidade: os alunos estudam para as provas, e só isso).

Por parte dos professores e das instituições, também temos algumas deficiências
sérias: a estrutura que a maioria das universidades proporcionam é "precária" em
comparação à estrutura da CS50 (na maioria das vezes temos um professor sozinho,
com um ou dois monitores, e laboratórios compartilhados que podem não estar
sempre disponíveis para os alunos). E, muitas vezes, o mesmo professor tem que
atuar em mais de uma disciplina simultaneamente, não tendo tempo para criar e
desenvolver bem cada uma das disciplinas, nem prestar um atendimento mais
individualizado aos alunos.

Por esses motivos é que, em nossa opinião, não basta apenas traduzir o conteúdo:
esse é o ponto de partida. Mas, em nossa visão, para que a disciplina seja
realmente útil para os estudantes brasileiros ela deve ser adaptada para nossa
realidade, com um ritmo mais lento, mais material e vídeos de suporte, e mais
exercícios "básicos" de programação. Esse é o foco da CR6.100B: usar a CS50 como
base, mas adaptar todo o conteúdo para o estudante brasileiro.

## 2.2. Diferenças entre a CR6.100B e a CS50
Uma das primeiras coisas que você precisa entender são as diferenças entre as
disciplinas **CS50** (a disciplina original da Universidade de Harvard) e a
**CR6.100B** (a adaptação feita pelo Computação Raiz).

A disciplina Harvard CS50 é a disciplina de introdução à ciência da computação
da Universidade de Harvard, e pode ser feita gratuitamente na Internet no
endereço [https://cs50.harvard.edu/x/](https://cs50.harvard.edu/x/). Se você
seguir a disciplina CS50 e cumprir todas as tarefas de programação, **receberá
um certificado de conclusão emitido diretamente pela Universidade de Harvard**!
Isso é excelente para seu aprendizado e para seu currículo na área da
computação. Ah!, e não é porque a disciplina é online que ela é inferior à
disciplina presencial feita pelas alunos de Harvard: é exatamente a mesma
disciplina.

A disciplina CR6.100B é uma adaptação feita especialmente para os estudantes
brasileiros (na verdade, para qualquer estudante que fale nativamente o
português). O conteúdo é o mesmo, os PSETs (_Problem Sets_) de programação são
os mesmos e o grau de dificuldade é o mesmo. O que muda é a **forma** e a
**apresentação** do material. As maiores diferenças estão mostradas abaixo:

* A CR6.100B segue em um **ritmo mais lento**: enquanto a CS50 para os
  estudantes presenciais em Harvard é uma disciplina de 11 semanas, a CR6.100B
  está programada para 23-26 semanas de estudo (um semestre inteiro). Resolvemos
  fazer essa adaptação pois a realidade dos estudantes brasileiros é muito
  diferente da realidade dos estudantes de Harvard;
* A CR6.100B tem um **material impresso mais detalhado** do que a CS50: como
  teremos muito mais tempo para o conteúdo, podemos nos aprofundar e estudar
  detalhes que são apenas citados na CS50 original;
* A CR6.100B não é apenas uma cópia ou tradução direta dos materiais e vídeos da
  CS50, é uma disciplina totalmente nova, com **materiais e vídeos
  próprios**. Obviamente tudo foi baseado na CS50 mas nada foi copiado
  diretamente: tudo foi pensado e recriado tendo como base as necessidades dos
  estudantes brasileiros;
* A CR6.100B **vai muito além das tarefas de programação** da CS50: como temos
  mais tempo para a disciplina, temos mais tarefas "teóricas" e de "fundamentos"
  da computação. Na verdade, uma parte integrante e fundamental da CR6.100B são
  os Diários de Aprendizagem, uma atividade teórico-discursiva que os alunos
  devem fazer para se auto-avaliarem e verificarem se realmente compreenderam os
  conceitos fundamentais da computação e da programação;
* Na CR6.100B alguns PSETs foram **ligeiramente alterados** para que fizessem
  mais sentido para os estudantes brasileiros (isso estará indicado); e
* A CR6.100B disponibiliza uma **máquina virtual Linux** para os alunos que
  quiserem se aprofundar no estudo desse sistema operacional (e essa máquina
  virtual também tem todas as ferramentas de programação configuradas!);
* A CR6.100B disponibiliza uma versão do conteúdo online em **arquivos PDF**,
  para os estudantes que têm maior facilidade de ler em papel do que em
  monitores.

Além das diferenças, há as semelhanças:
* A CR6.100B utiliza o ambiente online de desenvolvimento fornecido pela CS50,
  gratuitamente na Internet, o [Visual Studio Code for CS50](https://cs50.dev).
  Esse ambiente é indicado para alunos iniciantes pois já tem tudo configurado e
  pronto para uso (alunos mais avançados ou que queiram experimentar algo mais
  desafiador podem utilizar versões desktop dessa ferramenta, ou utilizar a
  máquina virtual Linux do CR6.100B); e
* A CR6.100B utiliza os autograders da CS50, ou seja: se você está acompanhando
  esta disciplina pela Internet, pode preparar e enviar suas tarefas de
  programação diretamente para a avaliação automatizada de Harvard e, assim,
  conquistar o certificado de conclusão da CS50, emitido pela própria
  Universidade de Harvard.

Uma última observação: se você estiver fazendo a CR6.100B de **modo presencial**
com o **Prof. Abrantes Araújo Silva Filho** (eu mesmo!), na [Universidade Vila
Velha](https://uvv.br), você terá à disposição duas outras ferramentas: um
ambiente virtual de aprendizagem e um autograder específico para as tarefas de
programação. Infelizmente eu não tenho condições, ainda, de liberar essas duas
ferramentas extras para todo mundo na Internet (eu não tenho uma Harvard para
bancar a infraestrutura, não é? Sou eu que banco tudo). Quem sabe no futuro?
Mas, mesmo assim, tenho certeza absoluta de que se você seguir a CR6.100B por
aqui neste site, e enviar os exercícios de programação para a avaliação da CS50,
você aprenderá tudo o que devia aprender!

{% spoiler "TEXTO: opções se você quiser uma tradução mais fiel à CS50" %}
Se você busca uma tradução mais fiel à CS50 original, com poucas adaptações e
mantendo o formato original, sugerimos as seguintes opções:

* [CC50, do Na Prática, um projeto da Fundação
  Educar](https://www.estudarfora.org.br/cursos/cc50/): esta é uma tradução
  feita por **Gabriel Guimarães**, ex-estudante do Instituto Federal do Espírito
  Santo (IFES) e da própria Harvard University, quando bolsista da Fundação
  Educar. Esta tradução está disponível para qualquer pessoa, gratuitamente,
  através do ambiente virtual online da Fundação Educar. Algumas observações:
    * A tradução está baseada em uma versão do CS50 de alguns anos atrás (mas
      isso não atrapalha o curso); e
    * Ao invés de manterem o formato original, optaram por integrar o conteúdo
      ao ambiente EAD da Fundação Educar (criando uma certa complexidade
      adicional aos estudantes, mas entendemos a necessidade da Fundação Educar
      manter o conteúdo de acordo com o formato já existente de seu EAD).
* [CS50xemportugues](https://cs50xemportugues.github.io/2023/): é um projeto
  de tradução que mantém um [repositório no
  GitHub](https://github.com/cs50xemportugues/). Algumas observações:
    * Tenta manter a estrutura e o layout original do CS50;
    * Alguns vídeos foram regravados em português (principalmente os vídeos
      acessórios e de conteúdo extra), seguindo-se exatamente o mesmo _script_
      dos vídeos originais; e
    * Parece ser uma boa opção se você quiser se ater ao formato original da
      CS50.
{% endspoiler %}

## 2.3. Agradecimentos
Nós, do **Computação Raiz**, só temos a agradecer ao prof. David Malan e a todo
o staff da CS50 por disponibilizar de modo gratuito e aberto, a todas as pessoas
do mundo, esse material de excelente qualidade. Mais ainda: por permitir que
professores do mundo todo utilizem e façam adaptações do material para atender
às necessidades de seus alunos. Obrigado, David! Nós nos esforçamos ao máximo
para adaptar a CS50 para os estudantes brasilerios (na verdade, para todos os
falantes de português ao redor do mundo) e criar uma disciplina única e
fantástica, que será perfeita para as necessidades dos nossos estudantes.


# 3. Como fazer este curso
Se você quiser fazer este curso, sugerimos o seguinte:

* Se você vai seguir a CR6.100B aqui por este site, de modo online e por conta
  própria:
  * Basta seguir o material e fazer os exercícios, laboratórios e PSETs de
    programação. Todas as atividades deverão ser enviadas para avaliação da CS50
    para a obtenção do certificado de conclusão;
  * Alguns PSETs foram ligeiramente adaptados para o Brasil e, nesse caso, não
    devem ser enviados para avaliação da CS50. Esses PSETs modificados estão
    claramente identificados e, nessa situação, você deve enviar o PSET original
    de Harvard. Minha sugestão é que você faça o PSET modificado para entender
    melhor os conceitos e, depois, faça o PSET original para obter a nota da
    CS50;
* Se você vai fazer a CR6.100B de maneira **presencial** com o
  **Prof. Abrantes**, na [Universidade Vila Velha](https://uvv.br):
  * Basta seguir o material aqui neste site **e também** o conteúdo disponível
    no ambiente virtual de aprendizagem para os alunos presenciais;
  * Você deve enviar todas as tarefas de programação no autograder exclusivo
    para os alunos presenciais, para fins de aprovação na disciplina;
  * Você **também deve enviar** as tarefas de programação para a CS50, para fins
    de obtenção do certificado de conclusão de Harvard (isso é importante para
    seu currículo). Nesse caso a observação acima sobre os PSETs adaptados deve
    ser seguida;
* Se você quiser seguir a coisa todo no original:
  * Você deve seguir a [CS50x](https://cs50.harvard.edu/x/), que é a versão
    online gratuita (com certificado emitido pela Universidade de Harvard) para
    todos os interessados ao redor do mundo. Escolha esta opção se você está bem
    preparado e se consegue entender bem inglês;

Uma das coisas interessantes que você pode fazer é o seguinte: siga e estude
todos os materiais da CR6.100B, para aprender o conteúdo. Depois (ou
simultaneamente) refaça os exercícios de programação diretamente na CS50. Assim
você terá o melhor de dois mundos: aulas e material em português, com a
avaliação da CS50 diretamente de Harvard (e certificado de conclusão!).

{% spoiler "VÍDEO: sugestões de como fazer esta disciplina" %}
{% video https://www.youtube.com/watch?v=an7aEc5du0o %}
<i class="fa-light fa-download"></i> <i class="fa-light fa-file-pdf"></i>
[Download dos slides do vídeo](/como_fazer.pdf)
{% endspoiler %}


# 4. Como ensinar a CR6.100B (ou a Harvard CS50)
## 4.1. Licença original da CS50:
Se você é um professor e quer ensinar a Harvard CS50 adotando ou adaptando o
material para o seu próprio curso, por favor siga esta
[licença](https://cs50.harvard.edu/x/license/): Creative Commons
[Attribution-NonCommercial-ShareAlike 4.0
International](https://creativecommons.org/licenses/by-nc-sa/4.0/) (CC BY-NC-SA
4.0). Abaixo segue um resumo simples para compreensão (não é um substituto da
licença original). Traduções oficiais desta licença estão disponíveis em [outros
idiomas](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode#languages).

Você é livre para:
<ul class="fa-ul">
  <li><strong>Compartilhar</strong> - copiar e redistribuir o material em
      qualquer meio ou formato</li>
  <li><strong>Adaptar</strong> - remixar, transformar e construir a partir do
      material</li>
</ul>

Sob as seguintes condições:
<ul class="fa-ul">
  <li><span class="fa-li fab fa-creative-commons-by"></span>
      <div><strong>Atribuição</strong> - você deve dar o crédito apropriado,
      fornecer um link para a licença e indicar se foram feitas alterações. Você
      pode fazê-lo de qualquer maneira razoável, mas não de uma forma que sugira
      que o licenciador o endossa ou o uso que você fez.</div></li>
  <li><span class="fa-li fab fa-creative-commons-nc"></span>
      <div><strong>Não Comercial</strong> - você não pode user o material para
      fins comerciais.</div></li>
  <li><span class="fa-li fab fa-creative-commons-sa"></span>
      <div><strong>Compartilhar Igual</strong> - se você remixar, transformar ou
      construir a partir do material, deve distribuir suas contribuições sob a
      mesma licença do original.</div></li>
  <li class="mt-3"><div><strong>Sem restrições adicionais</strong> - você não
      pode aplicar termos legais ou medidas tecnológicas que restrinjam
      legalmente outros de fazerem qualquer coisa que a licença
      permita.</div></li>
</ul>

## 4.2. Licença da CR6.100B:
Como a CS50 original utiliza a Creative Commons "BY-NC-SA 4.0", também somos
obrigados a liberar nossa adaptação sob a mesma licença. Assim, todos os nossos
materiais estão disponíveis em nosso [repositório
GitHub](https://github.com/computacaoraiz/cr6.100b), também sob a CC
"BY-NC-SA 4.0".

Caso tenha alguma dúvida, favor entrar em contato: **abrantesasf at
computacaoraiz dot com dot br**.
