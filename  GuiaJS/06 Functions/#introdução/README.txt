

> functions são um tipo de estrutura de dado.

> Tem como seu intuito a reciclagem e agrupamento de codigo.
    > com uma function vc podera reutilizar todo o codigo q a ela imposta e/ou
    organizar o seu código dando significado a um bloco que executa uma determinada 
    tarefa, facilitando a leitura e compreensão.  

> Estrutura
    > A estrutura da function é composta por uma palavra chave, reservada 
    pelo sistema (function), em seguida um nome declarativo que pode 
    ser qualquer palrava que o desenvolvedor deseja usar (atentar para 
    functions especificas que possuem nome padrões adotados pela 
    comunidade afim facilitar a leitura e compreensão do seu código por outros 
    desenvolvedores), ainda no nome declarativo temos que adicionar um 
    par de () como no exemplo abaixo, e depois um par de {}, cada um para um 
    uso específico. 
    Atentar para a ortografia, pois o JavaScript e case sensitive, significa 
    que faz diferença entre maiúsculas e minusculas, e também a acentuações, e no 
    caso do nome declarativo ter mais de uma palavra, ele não pode ser 
    escrito com espaço, deve ser feito como no exemplo

> Parenteses() e chaves{} na function
    Em uma function as parenteses que vai após o nome é usado para passar parâmetros
     que recebem argumentos que serão utilizados na regra criada dentro do escopo.
    As chaves da function criam um escopo que vai armazenar todo o conjunto de regras
     que for criado dentro dele, podem ser variáveis, outras functions, eventos, laços
     de repetição e etc., Ou seja, qualquer tipo de regra que você criaria no escopo mãe, você pode 
     criar dentro do escopo da function
     

        > Exemplo 1
            function nameDeclarative() {
                console.log("Hellou World")
            }

            > Lembra q eu comentei sobre padroes da comunidade? Aqui podemos 
            ver um deles, ao declarar um nome que possua mais de uma palavra, 
            as palavras seguintes devem ser escritas com a primeira letra em 
            maiúsculo.
            De sempre preferencias para utilizar nomes em inglês, a fim de 
            padronizar, organizar e economizar caracteres na hora de escrever 
            seus códigos.

    > Ok, voce ja declarou a sua function e ja atribuiu um codigo a ela,
    porem ela ainda não está funcionando, por quê?
    Fazer uma function que execute uma determinada tarefa não é como apenas
    digitar o código daquela tarefa, no exemplo, se colocarmos aquele 
    console.log fora da function ele prontamente ira funcionar, porem, 
    como se trata de uma functin você precisa chama-la em algum lugar

         > Exemplo 2
                function helloWorld() {
                    console.log("Hello World")
                }

                helloWorld() <- isso é chamar a função 
        
        > Agr todas as vezes q vc chamar a function ela sera executada.
        > Isso acontece pq quando o JavaScript le a sua funcao ele apenas armazena 
            o código do escopo para ser executado em outro momento, no momento que
            você determinar, no momento em que você chamar.
           > Lembrando q o JS le o teu codigo de cima pra baixo, sendo assim sempre
            declare suas funções antes de chama-las. Regras de escopo também devem ser
            respeitadas
