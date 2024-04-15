# Atividade 4

## TDD
1. No desenvolvimento guiado por teste você pensa nos casos e nos dados de teste primeiro e depois parte para o desenvolvimento de uma determinada funcionalidade de software.  Assuma que você será o projetista dos casos de testes para um programa que deve realizar a leitura da idade de uma pessoa. Quais os casos e os dados de testes que você definiria para este programa? Busque gerar casos e dados de teste utilizando o texto: https://engenhariasoftware.wordpress.com/2009/05/18/desenvolvendo-a-atividade-de-teste-de-software-%E2%80%93-parte-1/

* Resposta:
    * Os testes definidos foram os seguintes:
        * ReceberIdadeInteira_VerificarSeEhNumeroInteiro_RetornaIdadeValida()
        * ReceberIdadeDecimal_VerificarSeNumeroNaoEhInteiro_RetornaIdadeInValida()
        * ReceberIdadeInteira_VerificarSeNumeroMenorQueZero_RetornaIdadeInValida()
        * ReceberIdadeInteira_VerificarSeNumeroMaiorQueCentoETrinta_RetornaIdadeInValida()
        * ReceberIdadeInteira_VerificarSeNaoEhAdulto_RetornaIdadeInValida()
    * Foi criado um repositório no GitHub com a implementação dos testes em C#
        * Código do teste:[https://github.com/hesauhugo/MBA_Metodos_Ageis_TDD/blob/main/MBAAtividade3TDD.Tests/IdadeTests.cs]
        * Projeto completo:[https://github.com/hesauhugo/MBA_Metodos_Ageis_TDD]

## Standup Meeting
2. Em seu ambiente de trabalho, realize uma stand up meeting e compartilhe suas impressões sobre esta prática.
* Resposta:
    * Foi solicitado a todos da reunião que explicassem o que fizeram na sexta feira:
        * Cada um respondeu suas atividades o que colocou a equipe a par dos projetos que estão desenvolvendo.
        * Durante a conversa foi identificado a dificuldade de cada um e os outros membros sugeriram alternativas de desenvolvimento.
    * Foi solicitado a todos que dissessem o que fariam no dia:
        * cada um respondeu suas atividades e o gestor pode identificar o que era mais prioritário