+++
title =  "Workshop UFMS"
tags = ["apresentacoes", "datascience"]
date = "2020-06-23"
+++

## Sobre a Apresentação

**Tema:** Ciência de Dados para a área Jurídica

Com objetivo de introduzir ao público universitário as oportunidades e desafios de uma carreira de Cientista de Dados, a palestra apresenta como a ciência de dados é aplicada no dia a dia de grandes empresas, como se preparar para a carreira de cientista de dados e um caso de uso da Semantix em sua plataforma de IA para jurimetria.

## Vídeo

O vídeo da apresentação está disponível no YouTube, no canal do evento, e a apresentação inicia no instante 1:36:09.

{{< youtube n5LO9WQjybg >}}

## Perguntas dos participantes

#### Pergunta 1
A IA (Inteligência Artificial) e o background dela que um matemático tem, possui algum foco diferente de quem viu num curso de computação?

Acredito que isto pode variar mais com o instituto do que com o curso em si. Na Unifesp, os professores que minstravam as disciplinas eram os mesmos, então a profundidade era mesma, independente do curso. Se você for cursar esta disciplina no [IMPA](https://impa.br/noticias/a-matematica-da-inteligencia-artificial/), por exemplo, pode esperar um rigor matemático bem maior. Os conceitos tem bases matemáticas, então é sempre possível aprofundar bastante o assunto.

#### Pergunta 2
Aron quais suas dicas para quem está entrando na área de ciência de dados para conseguir a primeira experiência profissional?

Como eu mostrei no slide sobre o nível de formação, o mercado contrata bastante mestres e doutores, portanto esta pode ser uma boa porta de entrada, mas é importante que seja em uma área próxima, como Aprendizado de Máquina ou Inteligência Artificial. Cursos na área e certificações (existem umas específicas de Ciência de Dados) também são bem vindos.

#### Pergunta 3
Para quem vem de outra formação, como marketing, você acha que é possível se tornar cientista de dados?

Sempre é possível, mas a curva de aprendizado pode ser um pouco maior. Existe uma carga boa de exatas e de programação para ser absorvida. Você poderá gastar alguns anos se preparando. Se este é o foco você pode ir migrando aos poucos. Eu sugeriria começar aprendendo a programar, procura um trabalho na área que requeira apenas a programação, depois se aprofunda nos conceitos de probabilidade e estatística... Uma hora você chega lá!

#### Pergunta 4
Aron, qual metodologia ágil especificamente você tem utilizado? Scrum? Kanban? Híbrido?

Respondido no vídeo.

#### Pergunta 5
Qual a melhor linguagem de programação para entrar nesse mundo de data science?

Existe uma disputa de torcida entre R e Python. Estas são as mais comuns e mais fáceis, então recomendo começar por elas. Outras de mais baixo nível como Scala, também podem ser usada. Depende muito da empresa e do que está sendo desenvolvido.

#### Pergunta 6
Para o mercado, vale mais uma pós na área ou uma formação DSA?

Acho que pós-graduação stricto sensu em uma área relacionada tenham uma visibilidade maior. Mas tem alguns cursos bem completos hoje que eu acredito dar uma formação boa, só não sei como o mercado está reconhecendo estes cursos.

#### Pergunta 7
Em questão de banco de dados, como eu posso iniciar estudando nesse assunto?

Se você não conhece nada, recomendo começar a aprender algum banco relacional. Em geral é bem simples. Pra aprender o básico não demora muito. Depois você pode procurar outros bancos NoSQL.

#### Pergunta 8
Aron, eu estudo engenharia elétrica e análise de sistemas. A trilha para a formação de um cientista de dados é muito alterada? Neste caso, qual seria?

Estes cursos que você faz possuem uma bagagem bastante ampla, então recomendo a você prestar bastante atenção nos conteúdos que eu citei na apresentação que você vai ter uma base muito boa. Recomendo você pegar algumas disciplinas eletivas de Aprendizado de Máquina, Inteligência Artificial, Mineração de Dados, ou algo do tipo. Mais importante do que a formação, é dominar os temas, e as empresas acabam percebendo isto. Conheço pessoas que não tem pós-graduação, por exemplo, e são excelentes profissionais.

#### Pergunta 9
A análise se restringe aos dados capturados a partir do Tribunal onde tramita o processo?

Sim. Falando específicamente do AIJUS, a primeira etapa é caputrar os dados. Se ele não foi capturado ou enviado pela empresa, não irá aparecer na ferramenta.

#### Pergunta 10
Quais as principais diferenças entre o cientista de dados e o analista de BI?

Tem bastante gente que já falou sobre isto, então acho mais fácil te recomendar alguns links ([1](http://datascienceacademy.com.br/blog/qual-a-diferenca-entre-o-analista-de-bi-e-o-cientista-de-dados/), [2](https://towardsdatascience.com/data-science-vs-business-intelligence-same-but-completely-different-1d5900c9cc95), [3](https://www.opservices.com.br/qual-a-diferenca-entre-business-intelligence-e-data-science/)). Resumeno em um tweet, eu diria que o Analista de BI está muito focado em trazer a visualização dos dados, enquanto que o Cientista de Dados, está mais preocupado em entender os padrões, treinar modelos e fazer predições. 

#### Pergunta 11
Onde vocês conseguiram os dados para treinar os modelos? O Judiciário disponibiliza alguma API onde se possa requisitar ou foi utilizado apenas dados dos seus clientes?

Infelizemente não. A aquisição de dados é um dos grandes desafios. O judiciário está se movimentando neste sentido atualmente, mas ainda estamos muito longe de conseguir trabalhar desta forma. Hoje a aquisição que fazemos é basicamente através de "scraping".

#### Pergunta 12
Para a solução de PNL de vocês é utilizado um woed2vec e ferramentas one primise ou utilizam o watson ou Amazon?

Todos os modelos são construídos dentro da empresa. Ferramentas como o SageMaker da Amazon e o Watson acabam saindo por um custo bastante elevado. Nós temos muitos modelos usando PNL clássico e já migramos alguns para RN (BERT, por exemplo).