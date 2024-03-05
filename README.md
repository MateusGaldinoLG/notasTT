# Notas em Teoria dos Tipos

Esse repositório serve para a escrita de um conjunto de notas que quero faze relacionadas à Teoria dos Tipos, suas subáreas (Por exemplo, a Teoria dos Tipos Homotópica) e suas áreas irmãs (Teoria das Categorias, etc). Para isso, vou me basear nos seguintes textos:

[HoTT] = Homotopy Type Theory: Univalent foundations of mathematics. Voevodsky et al.  
[TTFP] = Type Theory and Formal Proof. Geuvers e Nederpelt  
[TPL] = Types and Programming Languages. Benjamin Pierce  
[IHoTT] = Introduction to Homotopy Type Theory. Egbert Rijke  
etc.


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
[ ] CPOs  
[ ] Modelo de Scott D_\infty  
[ ] Estruturas globais de modelos

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
[ ] Tipo unitário (1)  
[ ] O tipo de produto [Currying] (A X B)  
[ ] O tipo de produto disjunto  (A + B)  
[ ] O tipo dos números naturais  
[ ] O tipo PROP  
[ ] O Sistema T de Gödel finalmente  
[ ] A Teoria dos Tipos simples de Church    
2.3 Maneiras de construir a lógica  
[ ] Proposições como um tipo (PROP)  
[ ] Proposições como tipos  
[ ] Lógica equacional  
[ ] Lógica de predicados de primeira ordem  
[ ] Lógica de predicados de ordem superior     
https://mathoverflow.net/questions/322020/how-can-the-simply-typed-lambda-calculus-be-turing-incomplete-yet-stronger-than

3. Cálculo Lambda Polimórfico  
3.1 O Cálculo Lambda Polimófico  
[ ] Abstração e Aplicação em cima de tipos  
[ ] Tipos Pi    
[ ] Cálculo de sequêntes    
[ ] Propriedades    
3.2 O Sistema F de Girard  
[ ] Sistema F  
3.3 Linguagens de programação  
[ ] Teoria das PL  
3.4 Resumo Histórico  
[ ] Resumo  

4. Tipos dependentes de tipos  
[ ] Construtores de tipos  
[ ] Regra sort e regra var  
[ ] Regra do enfraquecimento  
[ ] Regra de formação  
[ ] Aplicação e Abstração  
[ ] Regra da conversão  
[ ] Apêndice I - Teoria dos Tipos e Aritmética  
[ ] Apêndice II - Construindo \lambda \omega em Coq  
[ ] Apêndice III - A história de \lambda \omega

5. Teoria dos Tipos Dependentes  
5.1 Teoria dos tipos dependentes    
[ ] Calculo de Sequêntes  
[ ] Lógica a partir da teoria dos tipos  
[ ] Apêndice II - Construindo a teoria dos tipos dependentes em Coq?  
[ ] Apêndice III - A história da teoria dos tipos dependentes


6. Cálculo de Construções  
6.1 O cálculo de construções e o cubo lambda  
[ ] O cubo lambda  
[ ] Propriedades  
[ ] Cálculo de Sequêntes  
[ ] Lógica em \lambda C (Predicados como tipos)    
6.2 Calculo de construções indutivas  
[ ] Tipos indutivos e CIC  
6.3 Definições e \lambda D  
[ ] Definições    
[ ] \lambda D  



Parte II - Construções paralelas ao cubo
1. O cálculo lambda-mu  
[ ] Sintaxe  
[ ] Modelagem da lógica clássica  
2. O cálculo Kappa  
[ ] Sintaxe  
(hasegawa - decomposing)   
3. O cálculo Zeta  
[ ] Teoria dos tipos em computadores quânticos  


Parte III - Semântica categorica do cubo  
1. Um resumo de teoria das categorias  
[ ] Categorias  
[ ] Categorias novas de antigas  
[ ] Funtores  
[ ] Transformações naturais  
[ ] Construções universais  
[ ] Categorias cartesianas fechadas  
[ ] A semântica categorial da teoria dos tipos simples
2. Teoria dos Topos  
[ ] Definição de topos  
[ ] Objeto de números naturais  
[ ] A semântica categorial da teoria dos tipos simples, novamente  
[ ] A teoria dos tipos gerada por um Topos  
3. Hiperdoutrinas  
[ ] Hiperdoutrinas  
[ ] A semântica categorial do Sistema F  
4. Categorias com Famílias  
[ ] Definição  
[ ] A semântica categorial da teoria dos tipos dependentes
5. Kappa-Categorias  
[ ] Kappa-Categorias  
6. Monadas  
[ ] Definição  
[ ] A semântica categorial da teoria dos tipos modal  


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
[ ] Definição  
[ ] Topos gerado  
4. Semântica de Kripke  
[ ] Definição  
5. Lógica modal  
[ ] Definição  
6. Lógica paraconsistente  
[ ] Definição  
[ ] Cálculo de sequêntes  
7. Lógica linear  
[ ] Definição  
[ ] Cálculo de sequêntes
8. Teorema da incompletude de Gödel  
[ ] Definição  

Coisas que precisam ser feitas a nível estético/literário:  
[ ] Corrigir erros de digitação e de primeira/terceira pessoa  
[ ] Transformar as citações em ABNT