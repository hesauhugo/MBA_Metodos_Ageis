# Atividade 3 - padrão de código 

1. Pessoal, gostaria que vocês gerassem um padrão de código. No seu padrão você deve incluir.

    * Mecanismo único para as labels de início e fim de programa e rotinas.
        * Resposta
            1. Iniciar com a palavra reservada ´programa´ e envolver por chaves, todo o conteúdo do programa deverá ficar dentro desse bloco de código.
            2. colocar a palavra reservada ´biblioteca´ antes de declarar as bibliotecas
            3. as rotinas devem começar com a palavra ´metodo´ seguido de ´vazio´ ou ´retorno´ quando for ´vazio´ significa que é um método sem retorno. Quando retornar deve conter a palavra ´retornar´ dentro do bloco de código.
            4. o nome do método deve seguir o padrão `PascalCase`.

        ```csharp
            programa{
                biblioteca texto
                bilbioteca fonte

                metodo vazio MeuMetodoVazio(){
                    //codigo aqui
                }

                metodo retorno MeuMetodoComRetorno(){
                    //codigo aqui
                    retorno objeto
                }
            }
        ```
    * Mecanismo único para denominar as variáveis.
        * Resposta
            * a variáve deve ser declarada com a palavra reservada `var`.
            * as variáveis devem seguir o padrão `camelCase` e ao final ter o nome da seu tipo.
            ```csharp 
                var minhaVariavelInteira = 1
                var minhaVariavelDecimal = 1.0
                var minhaVariavaelBooleana= true
                var minhaVariavelTexto = 'texto'
            ```

    * Tamanho único para indentação dos programas. 
        * Resposta
            * a identação deve ser de 6 espaços.

2. Abaixo você encontra alguns microlearning. Leia todos os microlearnings.

    * [https://engenhariasoftware.wordpress.com/2022/09/16/framework/]
        * Resposta:
            * Explica o conceito de framework, segundo o autor esse conceito está ligado maiormente a facilidade de reutilização, o autor cita exemplos relacionado a um projeto de uma casa onde a estrutura é a mesma, ou seja, existe a padronização, no entanto existe também possibilidade de customização. O foco do framework portanto é o reuso.

    * [https://engenhariasoftware.wordpress.com/2022/08/30/vamos-conversar-um-pouco-sobre-lifelong-learning/]
        * Resposta:
            * O autor explica o conceito de life long learning. É um modalidade de formação voluntária, o termo se associa a busca do conhecimento e a aprendizagem contínua. O autor explica algumas formas de estimular a busca pela aprendizagem no ambiente corporativo. Uma forma é na concepção onde todos inputam suas experiências, outra é permitir que os colaboradores inputem conhecimento em uma base.

    * [https://engenhariasoftware.wordpress.com/2021/06/22/a-relacao-entre-analista-de-sistemas-e-usuarios-devops-correto/]
        * Resposta:
            * No texto o autor explica o que é o DevOps, resumidamente é a prática de aproximar o desenvolvedor de software do operador de software, o papel fundamental é aumentar a comunicação e a transparência em todas as fases da construção do software.
    