# Passos

## O que foi feito até agora e os planos para os próximos passos

Parte I - O Cubo Lambda
1. Cálculo Lambda não tipado  
1.1.  O cálculo   
[X] Sintaxe  
[x] Alfa Conversão  
[x] Substituição  
[x] Beta redução    
[x] Forma normal    
[x] Teorema do ponto fixo   
[x] Eta redução    
[x] Codificações dentro do Cálculo Lambda       
1.2. Modelos  
[x] Modelos interpretativos  
[x] Modelos livres de sintaxe  
[x] CPOs  
[x] Modelo de Scott D_\infty  
[ ] Estruturas globais de modelos  
[ ] Outros modelos (Arvores de Bohm, etc)  
1.3 Lógica Combinatória  
[ ] Combinadores  
[ ] Modelos do CL  

2. Teoria dos tipos simples  
2.1 O cálculo Lambda simplesmente tipado  
[x] Motivação  
[x] Sintaxe     
[x] Abordagens para a tipagem   
[x] Cálculo de sequêntes  
[x] Problemas possíveis     
[x] Bem-tipagem  
[x] Checagem de tipos  
[x] Encontrar o termo  
[x] Propriedades   
[x] Redução   
[ ] Provar a redução do sujeito  
[ ] [Fazer a ND fitch funcionar]  
2.2. Extensões do STLC  
[x] Tipo unitário (1)  
[x] O tipo de produto [Currying] (A X B)  
[x] Tipo Vazio  
[x] O tipo de produto disjunto  (A + B)  
[x] O tipo dos números naturais (N)  
[x] O tipo dos booleanos (Bool)  
[x] O Sistema T de Gödel    
[ ] Teorema da normalização e formas canônicas do Sistema T  
[ ] A Teoria dos Tipos simples de Church    
2.3 Maneiras de construir a lógica  
[ ] Proposições como um tipo (PROP)  
[ ] Proposições como tipos  
[ ] Lógica equacional  
[ ] Lógica de predicados de primeira ordem  
[ ] Lógica de predicados de ordem superior     
2.4 Modelos do Sistema T  
[x] Espaços de coerência  
[x] Funções estáveis  
[ ] Espaços de coerência para cada tipo específico     
2.5 Uma discussão sobre HOL  
https://mathoverflow.net/questions/322020/how-can-the-simply-typed-lambda-calculus-be-turing-incomplete-yet-stronger-than

3. Cálculo Lambda Polimórfico  
3.1 O C´alculo Lambda com tipagem de Segunda Ordem
[x] Motivacao  
[x] Abstração e Aplicação em cima de tipos  
[x] Tipos Pi    
[x] Cálculo de sequêntes    
[x] Propriedades    
3.2 O Sistema F de Girard  
[x] O cálculo  
[x] Representações de tipos simples  
[x] Representações de tipos indutivos  
3.3 Modelos do Sistema F  
[ ] Espaços de coerência  


4. Tipos dependentes de tipos  
4.1 \lambda \omega fraco  
[x] Construtores de tipos  
[x] Regra sort e regra var  
[x] Regra do enfraquecimento  
[x] Regra de formação  
[x] Aplicação e Abstração  
[x] Regra da conversão  
[x] Propriedades  
4.2 O Sistema Fw  
[ ] O Sistema Fw  


5. Teoria dos Tipos Dependentes  
5.1 Teoria dos tipos dependentes    
[x] Regras de inferência  
[x] Exemplo de derivação  
[x] Lógica predicativa mínima  
[x] Exemplo de derivação lógica  


6. Cálculo de Construções  
6.1 O cálculo de construções e o cubo lambda  
[x] O sistema \lambda C  
[x] O cubo lambda  
[x] Propriedades   
[ ] Verificar provas das propriedades em artigos de Barendregt  
6.2 Lógica em \lambda C  
[x] absurdo e negação  
[x] Conjunção e disjunção  
[x] Exemplo  
[x] Lógica clássica  
[ ] Lógica predicativa  
[ ] Exemplo de lógica predicativa  
6.3 Calculo de construções indutivas  
[ ] Tipos indutivos e CIC  


7. O cálculo de definições
7.1 Definições  
[ ] Definições    
[ ] Definições indutivas e recursivas  
[ ] formato das definições  
[ ] instanciações  
[ ] formatos formais  
[ ] definições dependentes  
[ ] dando nomes a provas  
[ ] prova geral e versão especializada  
[ ] sentenças matemáticas  
7.2 Extenção de \lambda C com definições
[ ] ...  
7.3 \lambda D  
[ ] \lambda D  

Parte II - Construções paralelas ao cubo
1. Extensões do Cálculo Lambda não tipado  
1.1. O cálculo lambda-mu  
[ ] Sintaxe  
[ ] Modelagem da lógica clássica  
1.2. O cálculo Kappa  
[ ] Sintaxe  
(hasegawa - decomposing)   
1.3. O cálculo Zeta  
[ ] Teoria dos tipos em computadores quânticos  
1.4. Interaction Combinators  
[ ] Definições  
[ ] Turing Completude  
1.5 O cálculo pi  
[ ] calculo para programas simultaneos
2. Extensões a teoria dos tipos polimórfica  
2.1. Sistema de Tipos de Hindley-Milner  
[ ] Definição do sistema  


Parte III - Semântica categorica do cubo  
1. Introdução à teoria das categorias  
[x] Categorias  
[x] Categorias novas de antigas  
[x] Funtores (Explicar prefeixes)  
[x] Transformações naturais  
[x] Construções universais - Limites e Colimites  
[x] Exponenciais  
[ ] Categorias cartesianas fechadas  
[ ] Adjunções  
[ ] Monadas  
[ ] Estudo de caso 1: categoria simplice e conjuntos simpliciais  
[ ] Estudo de caso 2: ações de prefeixes  
[ ] Quebrar o capitulo de limites em outros capitulos ou subcapitulos (pullbacks, equalizers, etc)
2. Semantica categorial da teoria dos tipos simples  
[ ] A semântica categorial da teoria dos tipos simples  
3. Teoria dos Topos  
[ ] Definição de topos  
[ ] Objeto de números naturais  
[ ] A linguagem interna a um topos  
[ ] A semântica categorial da teoria dos tipos simples, novamente  
[ ] A teoria dos tipos gerada por um Topos 
(Possivelmente falar sobre o topos gerado pela categoria de conjuntos simplices)   

4. Hiperdoutrinas  
[ ] Hiperdoutrinas  
[ ] A semântica categorial do Sistema F  

5. Categorias com Famílias  
[ ] Definição  
[ ] A semântica categorial da teoria dos tipos dependentes  

6. A semântica dos prefeixes  
[ ] Prefeixes novamente  

7. Monadas  
[ ] Definição  
[ ] A semântica categorial da teoria dos tipos modal  

8. Kappa-Categorias  
[ ] Kappa-Categorias  

9. Categorias fibradas  
[ ] Definição  
[ ] A semântica categorial da teoria dos tipos simples, novamente, de novo  
[ ] A semântica categorial do cálculo lambda não tipado  
[ ] A semântica categorial do Sistema F, de novo

10. Categorias enriquecidas  
[ ] Definição  
[ ] Objetos monoides  


Parte IV - As várias teorias homotópicas de tipos  
1. Teoria dos Tipos Dependentes novamente, no estilo de Martin-Löf  
[ ] Intuicionismo e Construtivismo  (Interpretação BHK)  
[ ] Dedução natural e cálculo de sequêntes revisitados  
[ ] Tipos Pi revisitados  
[ ] Tipos Sigma  
[ ] Universos  
[ ] Proposições como Tipos  
[ ] Apêndice I - Provando axiomas em MLTT  
[ ] Apêndice II - Agda  
[ ] Apêndice III - A história da teoria dos tipos de Martin-Löf  
2. Teoria homotópica dos tipos de 1ª geração - HoTT conforme o livro  
[ ] Motivação: A correspondência de Curry-Howard-Voevodsky    
[ ] O Axioma da Univalência  
[ ] Caminhos  
[ ] Tipos indutivos superiores  
[ ] Apêndice I - Homotopy Type Theory e Infinito-grupoides  
[ ] Apêndice II - O circulo e outras construções em Agda  
[ ] Apêndice III - A história da teoria dos tipos homotópica  
3. Teoria homotópica dos tipos de 2ª geração - Teoria dos tipos cúbica (CTT)  
[ ] Motivação: canonicidade e normalização   
[ ] Cubos e caminhos  
[ ] O teorema da univalência  
[ ] Apêndice I - Cubos contra triângulos  
[ ] Apêndice II - Agda Cúbica  
[ ] Apêndice III - História da teoria dos tipos cúbica  
4. Teoria homotópica dos tipos simplicial (SHoTT)  
[ ] Motivação: Teoria das categorias infinitas para alunos de graduação  
[ ] ...     
[ ] Apêndice I - ...  
[ ] Apêndice II - SHoTT em RZK  
[ ] Apêndice III - História da SHoTT  
5. Teoria homotópica dos tipos modal (MHoTT)  
[ ] Modalidades e adjunções  
[ ] ...   
[ ] Apêndice I - MHoTT e Mecânica quântica  
[ ] Apêndice II - MHoTT em Agda  
[ ] Apêndice III - História da MHoTT  
6. Teoria dos Tipos de 2 níveis (2LTT)  
[ ]  
7. Teoria homotópica dos tipos de 3ª geração - teoria dos tipos altamente observável (H.O.T.T) e teoria dos tipos mostrados (DTT)  
[ ] Motivação: Computabilidade, novamente  
[ ] Id_U      
[ ] Tipos semi-simpliciais e a marca ^d    
[ ] Multimodalidade  
[ ] Apêndice I - ...  
[ ] Apêndice II - DTT em agda    
[ ] Apêndice III - História de H.O.T.T e DTT

Parte V - Semântica categorial de HOTT
1. Teoria dos Feixes  
[ ] Feixes  
[ ] Feixes em um sítio  
2. Topos de Grothendieck   
[ ] Definição  
3. 2-categorias  
[ ] Definição
4. Um resumo de Teoria das Homotopias    
[ ] Definição  
[ ] Grupoide Fundamental  
[ ] complexos CW  
[ ] Cubos  
4. Infinito-categorias  
[ ] O problema dos modelos de infinito-categorias  
[ ] Quasi-categorias  
[ ] infinito-groupoid  
[ ] infinito-cosmos  


Parte VI - Lógica
1. Dedução natural   
[ ] Regras   
[ ] Fragmento mínimo, fragmento intuicionista, fragmento clássico  
[ ] Fragmento dual-intuicionista
2. Cálculo de Sequêntes  
[ ] Regras  
[ ] Fragmento mínimo, fragmento intuicionista, fragmento clássico  
[ ] Fragmento dual-intuicionista  
3. Algebras de Heyting  
[ ] Definição (Reticulados novamente)  
[ ] Topos gerado  
4. Semântica de Kripke  
[ ] Definição  
5. Lógica modal  
[ ] Definição  
6. Lógica paraconsistente  
[ ] Definição  
[ ] Cálculo de sequêntes  
7. Lógica linear  
[ ] Cálculo de sequêntes linear  
[ ] Redes de Provas  
[ ] Eliminação do corte  
8. Teorema da incompletude de Gödel  
[ ] Definição  

Apêndice Histórico  
[ ] Fazer cronograma das publicações

Coisas que precisam ser feitas a nível estético/literário:  
[ ] Corrigir erros de digitação e de primeira/terceira pessoa  
[ ] Transformar as citações em ABNT

Ver onde encaixar os seguintes tópicos:  
1. teoria dos tipos infinitos (Uemura)  
[ ] Ver onde colocar essa teoria dos tipos  
2. Abstract Stone Duality (Taylor)  
[ ] Definições   
