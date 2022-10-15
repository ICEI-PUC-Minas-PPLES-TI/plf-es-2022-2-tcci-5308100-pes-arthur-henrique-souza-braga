
# Characterizing High-Quality Test Methods: A First Empirical Study


Veloso, Victor; Hora, Andre. Characterizing High-Quality Test Methods: A First Empirical Study, 9th IEEE/ACM International Conference on Mining Software Repositories (MSR'22), 5 pages, 2022. doi: [10.1145/3524842.3529092](
https://doi.org/10.48550/arXiv.2203.12085)

## 1. Fichamento de Conteúdo


O artigo consiste na realização de um estudo empírico que tem como objetivo caracterizar testes de alta qualidade através de técnicas de mutação de teste. Uma métrica válida para mensurar a qualidade de testes é a cobertura de código que consiste calcular a quantidade de caminhos lógicos e encontrar o percentual de cobertura destes caminhos via linhas de código de teste. O problema com essa prática é que ela é limitada, pois não apresenta com precisão a qualidade dos testes, e nesse momento, o estudo utilizia a mutação de teste. É mencionado também que os testes são uma importante parte da Engenharia de _Software_ e eles servem de suporte a qualidade. Para ter um _software_ de boa qualidade é necessário ter testes automatizados de alto desempenho com altas taxas de cobertura e efetividade. Através desta ótica é possível notar que é preciso realizar testes nos próprios testes, com o intuito de garantir que os mesmos desempenham o papel que é proposto. Para isto é utilizado a mutação, que consiste em mudar o código original artificialmente de modo a provocar um resultado falho, sendo assim evidenciando que se o teste não falhar, ele poderia estar mascarando um bug real. A pesquisa indica a utlização de testes de mutação no nível de metódos que se provou útil para redução de suites e avaliar a qualidade dos mesmos. O estudo avalia as técnicas e comparam testes de alto e baixa desempenho para descobrir a efetividade de cada um deles. A pesquisa mostra por evidências empíricas que existe uma diferença entre os testes, porém, pequena, identificada nos parâmetros de tamanho, número de _assertions_ e modificações.


## 2. Fichamento Bibliográfico 


* _High-quality_ (alta qualidade) é a caracterista do teste de alta qualidade (página 1).
* _Low-quality_ (baixa qualidade) é a caracterista do teste de baixa qualidade (página 1).
* _Mutation testing_ (teste de mutação) é quando o sistema é alterado com a intenção de provocar a quebra de teste (página 1).

## 3. Fichamento de Citações 


* _"Test mutation technique assesses test effectiveness in four major steps (illustrated in Figure 1-left). First, the project test suite is executed and the results are stored as the expected output. Then, a mutation testing engine (e.g., PIT [26]) parses the code and applies mutation operators on code structures generating a set of mutants."_
* _"Software testing is a key practice in software development. As a proxy of test quality, one can rely on code coverage or mutation analysis."_
* _"The mutants are separately tested by the test suite and the results form the obtained output. Lastly, each obtained output is compared to the expected output. A mutant is “killed” when at least one of the test results differs between both sets, i.e., when at least one of the test methods run on the mutants failed, meaning they properly detected the code mutations. Finally, a mutation score is computed: higher scores mean the test suite is better in catching real bugs [34]."_
