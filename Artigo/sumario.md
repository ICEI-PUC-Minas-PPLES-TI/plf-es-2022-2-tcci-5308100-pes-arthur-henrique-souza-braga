# O Processo de Teste de Mutação Combinado com o Desenvolvimento Orientado a Testes melhora a precisão dos casos de teste em capturar bugs?

1. Arthur Henrique Souza Braga

* Cleiton Silva Tavares
* Jose Laerte Pires Xavier Junior
* Simone de Assis Alves da Silva

## Introdução

1. A área da Engenharia de _Software_ tratada neste trabalho é Teste de Software TDD combinado à mutação de teste
2. O problema que este trabalho busca resolver nessa área é descobrir se times que utilizam as duas técnicas combinadas escrevem casos de testes mais precisos em capturar falhas
3. Resolver este problema é relevante por que poucos estudos unem as duas técnicas com o objetivo de encontrar melhores padrões de qualidade de _software_ e a avaliam se a combinação das duas melhora a precisão de casos de testes
4. O objetivo geral desta pesquisa  é explorar se a combinação das duas práticas resultaria em menores taxas de defeitos e falhas, e se a união de ambas resultaria em melhores benefícios para o desenvolvimento de software.
5. Os objetivos espec ́ıficos s ̃ao metrificar a qualidade geral dos testes e a capacidade dos mesmos em encontrar defeitos e falhas nos projetos de desenvolvimento software em ambientes de testes como pre-produção e ambiente de desenvolvimento.

## Fundamentação Teórica

1. O Teste de Software é dos pilares da Engenharia de Software e tem como sua responsabilidade, investigar e fornecer informações sobre a Qualidade de Software pelo autor Myers 2011
2. O termo Qualidade na área é bastante amplo e possui diferentes definições na literatura, porém, o Glossário da IEEE define a Qualidade como "Grau de conformidade de um sistema, componente ou processo com as necessidades e expectativas de clientes ou usuários" pela IEEE 1990.
3. Test Driven Development (TDD) ou em português Desenvolvimento guiado por testes é uma técnica de desenvolvimento de _software_ que tem como objetivo principal, criar casos de teste antes da implementação do Software propriamente pelo autor Kent 2002.
4. Mutação de teste também é uma técnica e prática da área de Teste de {\itshap software} que tem como seu objetivo testar a qualidade dos testes pelo autor Woodward 1993.

## Trabalhos Relacionados

1. O trabalho mais relacionado é Roman e Mnich _Test-driven development with mutation testing – an experimental study_, publicado no ano 2021, por que propõe estudar a utilização de TDD com Mutação de Teste.
2. O segundo trabalho mais relacionado é Derezínska e Trzpil _Mutation Testing Process Combined with Test-Driven Development in .NET Environment_, publicado no ano 2015, por que por que propõe estudar a utilização de TDD com Mutação de Teste porém em ambiente .NET apenas.
3. O terceiro trabalho mais relacionado é Veloso e Hora _Characterizing High-Quality Test Methods: A First Empirical Study_, publicado no ano 2022,  por que propões estudar a qualidade dos casos de teste.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é uma pesquisa descritiva, baseada em casos de estudos participativos com objetivo de coletar dados qualitativos acerca da utilização das duas práticas combinadas de TDD e mutação de teste e TDD isoladamente.
2. Os materiais utilizados neste trabalho são X equipes da disciplina de Laboratório de Programação Modular do curso de Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais (PUC Minas)
3. Durante a execução da pesquisa, é utilizado um software como base que os alunos desenvolvem X métodos com os mesmos requisitos para os dois grupos, com a criação de testes unitários. O grupo 1 utiliza TDD e o grupo 2 utiliza TDD com mutação de teste. Para o projeto é utilizado a linguagem de programação Java JDK 18 (Java devoloper kit), o framework de teste JUnit e o Pitest para os testes de mutação.
4. Número de bugs encontrados por cada grupo: Respondendo a RQ1 e RQ2, como foi mencionado anteriormente, é entregue um software previamente construído com alguns requisitos faltantes a serem implementados. Este mesmo software também é entregue com alguns bugs conhecidos. Capacidade dos casos de teste em capturar bugs: Respondendo as RQ1 e RQ 2, os casos de teste são avaliados pelos pesquisadores após execução da pesquisa para avaliar quais bugs foram encontrados por cada grupo de alunos Número de bugs encontrados anteriormente a entrega final: Respondendo a RQ3, é avaliado durante a execução da pesquisa a agilidade em termos de minutos o quão rápido cada grupo encontra os bugs introduzidos previamente ou novos durante o desenvolvimento. Capacidade dos casos testes em se manter resilientes a mudanças introduzidas nos requisitos: Respondendo a RQ4 Algumas mudanças é introduzida durante a execução da pesquisa que os alunos devem implementar, provocando assim alteração no código que possa provocar quebra nos testes previamente de-senvolvidos.
5. Para conduzir o estudo, este é o cronograma e atividades a serem realizadas. 1. Desenvolvimento da aplicação para a pesquisa (a) Desenvolvimento do CRUD de usuário (6) Desenvolvimento do CRUD de livros (c) Desenvolvimento do empréstimo de livro 2. Elaboração da dinâmica da pequisa 3. Teste da aplicação da pesquisa (a) Coleta de dados do teste piloto 4. Aplicação da pesquisa com os alunos (a) Execução (b) Analise dos dados
