
# Does mutation testing improve testing practices?

Petrovic, Goran; Marko, Ivankovic; Fraser, Gordon; Just, René. Does mutation testing improve testing practices?, 43rd International Conference on Software Engineering (ICSE), 12 pages, 2021. doi: [10.1109/ICSE43902.2021.00087](https://ieeexplore.ieee.org/document/9402038)

## 1. Fichamento de Conteúdo


O artigo consiste na realização de um estudo que tem como objetivo responder uma pergunta; "Testes de mutação melhoram as práticas de testes?". Dois dos quatro pesquisadores trabalham na multinacional Google, os mesmos tentam responder a pergunta através de suas experiências prossifionais na empresa. É sabido que teste é uma parte essencial no desenvolvimento de _software_ e que desenvolvedores de _software_ necessitam de uma guia para saber o quanto devem testar e aonde adicionar novos testes. O estudo tenta responder a pergunta procurando entender quais são os principais estratégias e técnicas de testes praticados dentro da organização e quais são os problemas relacionados a eles. Os resultados mostram que desenvolvedores que trabalham em projetos com testes de mutação escrevem mais testes em média por períodos mais longos de tempo, em comparação com projetos que consideram apenas a cobertura de código. Testes mutantes são resultados de teste eficazes e desenvolvedores expostos a testes mutantes ajudam a escrever mais testes eficazes.

## 2. Fichamento Bibliográfico 


* _Mutation testing_ (teste mutantes) é o tipo de teste que tem como objetivo alterar a aplicação original para provocar falhas no testes, assim assegurando que o teste captura problemas reais. (página 1).
* _Dataset_ (conjunto de dados) é o conjunto de dados utilizados nos testes (página 6).
* _Tests goals_ (objetivos do teste) é a parte do teste que tenta aproximar o objetivo inicial com o resultado gerado pelo teste (página 9).

## 3. Fichamento de Citações 


* _"Testing is an essential part of software development, and software developers need guidance in how much testing they need to do, and where to add more tests. Various proxy metrics for test suite quality have been defined over time with the aim to provide this guidance."_
* _"Construct validity is concerned with the chosen proxy measures and whether these accurately measure the concepts of interest. To address this concern, we relied on proxy measures accepted in the literature, where applicable. Given that there are no comparable studies on the long-term effects of mutation testing, we had to make two notable choices. First, we measure exposure to mutants as the number of times mutants are surfaced during code review, on a per-file basis."_
* _"Since the ultimate goal is not just to write tests for mutants, but to prevent real bugs, we investigated a dataset of highpriority bugs and analyzed mutants before and after the fix with an experimental rig of our mutation testing system. In 70% of cases, a bug is coupled with a mutant that, had it been reported during code review, could have prevented the introduction of that bug."_