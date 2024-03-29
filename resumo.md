# Métodos ágeis
## Livros recomendados

* CAMARGO, Robson Alves de; RIBAS, Thomaz. Gestão ágil de projetos. São Paulo: Saraiva, 2019. E-book. ISBN 9788553131891.

* COUTINHO, Heitor. Estratégia ágil além da prática. São Paulo: Saraiva, 2021. E-book. ISBN 9786587958224.

* RUBIN, Kenneth S. Scrum essencial: um guia prático para o mais popular processo ágil. Rio de Janeiro: Alta Books, 2017. E-book. ISBN 9788550804118.

## Definindo métodos ágeis

* <img src="definindo_metodos_ageis_mapa.png"/>

## Doze princípios do manifesto ágil

* <img src="doze_principios_manifesto_agil.png"/>

* site [https://agilemanifesto.org/]

## Participantes do manifesto ágil

* <img src="participantes_manifesto_agil.png"/>

## Visão Geral Extrem programming

* <img src="extreme_program.png"/>

## Processos ágeis - definicões 

### Metáforas

* Você na escola e a professora solicita uma redação.

* que procedimento você adotaria para escrever um bom texto?

* começar explorando o assunto, mentalmente, tentando organizar os tópicos.

* Em seguida, começaria a escrever as primeiras linhas

* após alguns parágrafos, você faria algumas alterações em trechos já escritos, visando o aprimoramento

* ao final, você faria uma re-leitura, corrigiria algumas partes, retocaria alguns trechos, até que o texto tivesse adequado

* escrever uma redação éuma atividade, puramente, intelectual.

* a pintura se encaixa na mesma premissa, quando um pinto cria  um novo quadro é comum começar com alguns esboços, produzir sucessivas e evoluções até chegar ao produto final.

* ambas as atividades, escrita e pintura, não são desenvolvidas de forma linear

* ausência de linearidade nos leva ao não determinismo. não é possível prever os caminhos que nos leva ao produto final

* porém existem regras para toda criação?
    - redação: regras gramaticais, números de linhas

* resumindo, uma obra intelectual possui:
    - necessidade de revisões;
    - ausência de linearidade;
    - ausência de determinismo.

* até certo ponto, o ato de desenvolver software é uma atividade intelectual e incorpora as características supra citadas.

* assim como o ato de pintar e escrever, durante o desenvolvimento do software, o cliente aprende com a manipulação do produto - feedback

* a principal premissa de um processo ágil é o feeedback.
    * por meio desta técnica o cliente e a qeuipe aprendem, o que o software deve manipular no contexto sistêmico
    * característica evolucionária do processo. 

## valores do extreme program

* Feedback
* comunicação
* simplicidade
* coragem

### Feedback

* <img src="extreme_program_feedback.png"/>

* no xp o cliente atual como produtor e consumidor, permatente de requisitos.

1. o cliente produz uma ideia nova, rapidamente, apresenta a equipe.

2. a equipe consome a ideia, produzindo as alterações no software.

3. e as apresenta para o cliente.

4. retorna ao passo 1.

5. condição de parada: cliente satisfeito.

* o feedback garante uma forte comunicação entre cliente e equipe, este fato pode diminuir os erros de interpretação, visto que o cliente está proximo do ciclo de produção

* forma de comunicação adotada pelo xp, mantenha a proximidade com o cliente.

* interação - cliente e a equipe

### Comunicação

* feeadback, intimamente, ligado a comunicação intensiva.

* formas de comunicação:
    * face-a-face
    * telefone
    * e-mail
    * msn, skype
    * etc

* a forma de comunicação influencia a capacidade de compreensão

* no xp, o objetivo da documentação é registrar o trabalho que já foi executado, ao invés de descrever o que deve ser feito.

* a explicação do que precisa ser feito é feita de forma iterativa. Utilização cartão de estórias

### Simplicidade

* para se obter um bom feedback é necessário que as ações dos membros da equipe sejam simples.

* com a simplicidade o feedback ocorre rapidamente, pois o cliente entende o que está acontecendo.

* ao solicitar uma funcionalidade:
    * implemente somente o que foi pedido;
    * o suficiente para atender o cliente;
    * funcionalidade simples, os desenvolvedores economizam em especulações;
    * especulações devem ocorrer junto ao cliente, em funcionalidades que ele não tem certeza;
    * não assuma que o cliente terá novas necessidades no futuro, pergunte a ele sobre isto.

* o prinipal objetivo da simplicidade é evitar o retrabalho, que muitas vezes resulta da precipitação da equipe de desenvolvimento.
    * se implementamos uma funcionalidade com mais detalhes, sem termos certeza, estamos investindo tempo e dinheiro em algo incerto.

### Coragem
* o xp é um processo de software que contraria os processos tradicionais de desenvolvimento de software. sendo assim a adoção do xp exige que a equipe de desenvolvimento tenha coragem para:
1. desenvolver software de forma evolucionária
2. manter o software simples;
3. permitir que o cliente priorize as funcionalidades
4. fazer os desenvolvedores trabalhar em par
5. investir tempo em refactoring
6. investir tempo em testes automatizados
7. estimar as estórias na presença do cliente
8. expor o código a todos os membros da equipe
9. integrar o software várias vezes ao dia
10. adotar ritmo sustentável
11. abrir mão de documentações que servem como defesa
12. propor contrados de escopo variável
13. propor a adoção de um novo processo por parte da equipe

## Atividade 1

1. Relacione os 12 princípio ágeis com os valores delineados com XP. Quais dos princípios são aglutinados no XP? Procure buscar evidências textuais para justificar as relações.

2. Abaixo você encontra dois microlearning, Existe alguma relação entre os microlearnings? Se sim qual? 

    a) a agilidade está na atitude: 
    [https://engenhariasoftware.wordpress.com/2020/08/27/a-agilidade-encontra-se-na-atitude/]


    b) Capacidade, Agilidade e Perseverança…
    [https://engenhariasoftware.wordpress.com/2015/04/29/capacidade-agilidade-e-perseveranca/]

## Programação em par    
* Deve ser trabalhada em sistemas complexos. 
* programação em par ou pair-programming.
* o desenvolvedor nunca trabalha sozinho
* técnica na qual dois programadores trabalham em um mesmo problema, ao mesmo tempo e em um mesmo computador
* Enquanto uma pessoa (o condutor) assume o teclado e digita os comandos que farão parte do programa, a outra ( o navegador) acompanha fazendo o trabalho de estrategista.
* Revisão de código (navegador). Pequenos erros são corrigidos no ato.
* modelagem do programa pode ficar mais otimizada, pois existem dois programadores trabalhando em conjunto.
* a modelagem do programa é, geralmente, mais simples.
* questões apresentadas sobre a programação em par
    * por que colocar duas pessoas para fazer o trabalha de uma?
    * não estamos desperdiçando uma pessoa?
    * e como desperdiçar uma pessoa com os prazos apertados, fato este frequente em um projeto de software?
* porém a programação em par traz vários benefícios relacionados a produtividade, veja só o exemplo:
    *  Um desenvolvedor trabalhando dozinho, gasta um dia para implementar uma funcionalidade.
    * se a funcionalidade for implementada em par, o tempo gasto é menor.
    * resultados comprovados no artigo de `laurie williams`
    * a curto prazo os benefícios são pequenos, porém a longo prazo eles são enormes (pouquíssimo errosno código). futuramente, menos tempo para descobrir as causas do defeito.
* alguns problemas podem afetar a atividade de programação:
    * cansaço
    * desânimo
    * desmotivação
    * frequentes interrupções:
        * e-mail,
        * mensagens instantâneas
        * telefonemas
* a programação em par corrige tais problemas, quando programador está acompanhado de outra pessoa, ele deixa de ter um compromisso somente consigo mesmo.
    * Focos de distração são eliminados.
*  Exemplo 1
    * você está programando com alguém ao seu lado.
    * de repente, você decide consultar seus e-mails
    * como você vai fazer isto tendo alguém ao seu lado
    * certamente, você pode fazer, mas é estranho, não?
    * você não se entirá a vontade. correto
    * pois você tem uma responsabilidade compartilhada.
* Exemplo 2
    * você programando e depara com aquele problema
    * você não está disposto a solucionar, naquele momento.
    * seu par irá te ajudar, incentivando, assumindo o teclado, substituindo você na condução da programação.
* Troca de lugar. O condutor assume o lugar do navegador e o navegador assume o lugar do condutor.

* Troca de pares

* Lembre-se. É necessário estipular regras para estas trocas. 

* Disseminação de conhecimento
    * A programação em par provê a homogeneidade do conhecimento na equipe de desenvolvimento
    * Imagine que você é programador mais experiente e está fazendo par  com um novato
    * suponha que o novato seja o condutor
    * diversas vezes pode identificar pontos de melhoria no trabalho do colega, pois você é mais experiente.
    * você está contribuindo com o aumento do conhecimento do colega.
    * a programação em par equaliza o conhecimento dentro da equipe
    * quem sabe mais, ensina quem sabe menos.
    * a equipe é nivelada por alto
    * a programação em par permite que novos ( recém chegados) membros na equipe tomem conhecimento sobre o projeto do software.
    * nos processos tradicionais, para ter conhecimento sobre projeto, os novos membros devem ler a documentação do projeto
    * já na programação em par a transferencia de conhecimento se dá dentro de cum contexto bem definido
    * exemplo:
        * suponha que ao implementar uma funcionalidade, você tenha que alterar algumas partes do código que já estão prontas.
        * você não conhece tais partes.
        * seu par irá transferir este conhecimento para você.
    * o apredizado por meio de documentação é menos eficaz
    * pois você não estará aprendendo algo para resolver um problema bem definido.
    * você não tem uma necessidade bem definida para aplicar a informação que está lendo.
    * o documento é frio e se limita àquilo que seu autor decidiu escrever. já o parceiro é vivo e irá explicar tudo aquilo que for necessário para você compreender o assunto.
*  desafio da programação em par
    * organização do escritório, mesa deve lugar para dois desenvolvedores
    * A visão gerencial:
        * desafio a vencer: porque ter progração em pares, se eu posso produzir o código, somente com uma pessoa?
    * O relacionamento humano
        * conciliar vicões diferentes entre desenvolvedores.
        * insegurança e medo que outra pessoa veja seu código.
        * medo que as pessoas descubram que você não é tão bom assim.
    * Alguns programadores acham que são muito superiores aos seus colegas
    * este tipo de pessoa costuma ter problemas com a idéia da programação em par.
    * este tipo de pessoa acredita que é perda de tempo dividir o trabalho com outra pessoa.
    * a arrogância é, extremamente, prejudicial à prática da programação em par. 
    * todos os membros da equipe necessitam exercitar a humildade.
    * é necessário ser paciente em certa ocasiões, pois, as vezes você percebe que poderia solucionar o problema de uma melhor forma se estivesse sozinho.
    * lembre-se que seu colega está no meio de um aprendizado.
    * competição:
        * algo que definitivamente não pode existir em um projeto XP
        * em um ambiente competitivo as pessoas não se ajudam
        * algumas empresas fomentam este tipo de ambiente, quando estabelecem sistemas de incentivos baseados em desempenho individual

* concluindo
    * os efeitos sobre a produtividade;
    * a pressão do par
    * o revezamento
    * a disseminação do conhecimento
    * os desafios da programação em par.
* Artigos:
    * <a href="QuandoAProgramacaoEmParesDeveSerAdotadaEmUmAmbienteEmpresarial.pdf" target="_blank">Quando a Programacao em Pares Deve Ser Adotada em Um Ambiente Empresarial</a>
    * <a href="StrengtheningTheCaseForPairProgramming.pdf" target="_blank">Strengthening The Case For Pair Programming</a>

## Padrão de código

* programadores com estilos diferenciados em relação a programação.
* Exemplo:
```javascript
    public int soma (int a,int b){
        return a+b;
    }

    public int soma(int a, int b)
    {
        return a+b;
    }
```
* as diferenças no estilo, dificultam a compreensão do código pelos membros da equipe
* fato que pode ser evitado de todos adotarem o mesmo padrão para codificação.
* o xp recomenda que se adote um padrão no início do projeto.
* possibilidade de construção de um padrão ou utilizar um já existente.
* java code convention.
* procure adotar um padrão que seja fácil e simples. isto evita resitência facilita a compreensão.
* topicos que devemos considerar em um padrão para codificação:
    * identação:
        * mesma largura na tabulação
        * mesmo posicionamento das chaves
        * sempre faça identação de um código que esteja subordinado ao outro.
        * 
    * letras maiúscula e menúscula?
        * Consitência
    * comentários
        * procure evitá-los
        * seja claro, simples e transmita sua intenção
        * escreve um comentário somente quando você precisar dele
        * exemplo: explicar uma otimização ou algo que você simplesmente não consegue facilitar
        * lembre-se que um código evolui e o comentário deve evoluir com ele
    * Nomes:
        * utilize nomes que comunique e não seja convenientes para digitar
        * normalmente,nomes longos são melhores (dentro do racional)
    * mantendo o padrão:
        * códgo coletivo ajuda a equipe a manter o padrão.
        * o padrão facilita a implantação da prática de código coletivo
* ao identificar um código fora do padrão:
    * alertar a equipe que estava fora do padrão e qual seria a forma correta de utilizar o padrão on caso em questão.
    * fazer o refactoring no código de modo que ele fique no padrão
    * publicar as regras do padrão que geram mais dúvidas nos quadros brandos da sala.
    * as vezes é necessário ajustar o padrão para que ele se aproxime daquilo que a maioria dos programadores já está habituada a fazer.
* dificulade na adoção de um padrão em pares
    * resistência por parte dos programadores.

* <a href="JavaCodeConventions.pdf" target="_blank">Java Code Conventions</a>







