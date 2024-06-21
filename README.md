

# O que é o Swift?

- Linguagem de programação criada pela Apple para desenvolvimento de aplicativos iOS. 

- Anunciada em 2014

- Desenvolvida para manter compatibilidade com a API Cocoa e com o código existente em Objective-C. 

- É distribuída desde a versão 2.2. 

- Usa variáveis para armazenar valores e também variáveis que podem ter valores alterados. 

- Apresenta tipos avançados não encontrados em Objective-C

- Apresenta tipos opcionais, que lidam com ausência de valor. 

- É uma linguagem de tipo segura e clara. 

# Noções Básicas do Swift:

| Código | Explicação |
| ----- | --------|
| let | constantes, imutáveis |
| var | variáveis, mutáveis | 

- Pode fornecer uma anotação de tipo ao declarar uma variável ou constante. 

- Podem conter quase qualquer caractere, incluindo caracteres Unicode que são 

- Imprimir valores com a função print. 

# Nomenclatura: 

- Sempre bom evitar dar um nome a uma palavra reservada. Avalie outras opções. 

# Tipos de Dados:

- O Swift fornece tipos inteiros assinados e não assinados em formatos de 8, 16, 32 e 64 bits. Pode acessar valores mínimo e máximo de cada tipo inteiro com suas propriedades min e max. 

| Código | Explicação |
| ----- | --------|
| int | números inteiros |
| Double | números de ponto flutuante com precisão de pelo menos 15 dígitos decimais |
| Float | números de ponto flutuante de apenas 6 dígitos decimais |
| Aliases | define um nome alternativo para um tipo existente |
| Bolean | false or true |

# Conceitos importantes:

- Funções são conjuntos de instruções que serão executados na hora da sua chamada ou execução.

- Closure é um bloco de funcionalidade que pode ser passado durante seu código. Pode ser passado uma closure como um argumento de uma função ou armazená-la como uma propriedade de um objeto.

- Classe representa um conjunto de objetos com características similares. Define o comportamento dos objetos, através de métodos e atributos.

- Objeto é uma instância de uma classe.

- Enum define um tipo comum para um grupo de valores relacionados.

- Struct é um bloco que armazenam diversas informações. Pode deixar o código mais rápido, seguro, flexível e reutilizável.

- Protocolo define um esquema de métodos, propriedades e outros requisitos que se adequam a uma tarefa ou funcionalidade específica.

- Extensões adicionam nova funcionalidade a uma classe, estrutura, enumeração ou tipo de protocolo existente.

### Funções: 
- Use func para declarar uma função. 

- Chame uma função seguindo seu nome com uma lista de argumentos entre parentereses. 

- Use -> para separar os nomes e tipos de parâmetros do tipo de retorno da função. 

### Classes: 

- Para criar uma classe use class seguido pelo seu nome. 

- Propriedades em uma classe são escritas da mesma forma que uma constante ou variável. 

- É uma abstração de um tipo de dado.

- Uma descrição que abstrai um conjunto de objetos com características e comportamentos. 

- Atributos definem dados ou características, métodos definem seu comportamento. 

#### Objetos

- Objetos são instâncias de uma classe. 

- Uma realização concreta e particular da mesma. 



### Enuns: 

- Para criar uma enumeração use enum. 

- Assim como as classes, as enumerações podem ter métodos associados a elas. 

### Structs: 

- Para criar uma estrutura use struct. 

- Structs suportam muitos dos mesmos comportamentos que as classes, incluindo métodos e inicializadores.

### Propriedades: 

- Propriedades de uma classe são atributos comuns que podem ser comportamennto em cada objeto derivado dela. 

- As propriedades descrevem as características do objeto. 

### Métodos: 

- Os métodos são comportamentos ou ações que você pede para o objeto executar. 

### Inicializadores: 

- É uma atribuição de um valor inicial para um objeto. 

- É um tipo especial de função que é usado para criar um objeto de uma classe. 

### Encapsulamento: 

- Oculta as características e as ações de um objeto. 

- Define as informações visíveis apenas para o próprio objeto. 

### Abstração: 

- É um conceito pelo qual expomos dados e métodos relevantes de um objeto ocultando sua implementação interna. 

### Controle de acessos: 

| Código | Explicação |
| ----- | --------|
| open | menos restrito |
| public | semelhante ao open, porém com algumas diferenças. |
| internal | permite o acesso de qualquer lugar no módulo, mas não fora dele. |
| file-private | permite o uso dentro do arquivo. |
| private | nível mais restritivo de todos. |


### Herança: 

Pessoa -> Super classe. 

Funcionário: -> subclasses
- Secretária
- Gerente 
- Vendedor 

### Sobrecarga de métodos:

É o processo pelo qual uma classe possui dois ou mais métodos com o mesmo nome, mas com parâmetros diferentes. 

### Substituição de métodos: 

- É o processo pelo qual dois métodos têm o mesmo nome e parâmetros. 

- Um dos métodos está na classe pai e o outro está na classe filha. 

### Polimorfismo: 

Objetos da mesma classe podem se comportar de forma independente dentro de uma mesma interface. 

### Concorrências: 

- O aplicativo está executando mais de uma tarefa ao mesmo tempo, simultaneamente. 

- Mais de um thread em execução. 

### Async/Await: 

- Simplifica o código. 

- Disponível a partir do Swift 5.5.

### Protocols:

Define um esquema de métodos, propriedades e outros requisitos que atendeme a uma determinada tarefa ou funcionalidade. 

### Extensions: 

Adiciona novas funcionalidades em uma classe, estrutura, enumeração ou tipo de protocolo existente. 





### Error Handling: 
É o processo de responder e se recuperar de condições de erro em seu programa. 
O Swift fornece suporte de primeira classe para lançar, capturar, propagar e manipular erros recuperáveis em tempo de execução.

### Generics: 
Generics permite que você escreva funções e tipos flexíveis e reutilizáveis que podem funcionar com qualquer tipo, sujeito aos requisitos que você definir. Você pode escrever código que evite duplicação e expresse sua intenção de maneira clara e abstrata.


### Diferença entre Struct e Class: 

Classes são reference types e Structs são value types.


# Tuplas e Optionals: 

- As tuplas agrupam vários valores em um único valor composto. Os valores dentro de uma tupla podem ser de qualquer tipo e não precisam ser do mesmo tipo uns dos outros. 

- As Optionals são usadas em situações em que um valor pode estar ausente. Representa duas possibilidades: ou existe um valor e você pode desembrulhar o opcional para acessar esse valor, ou não existe nenhum valor. 

## Tuplas

## Optionals

### Optional Chaining: 

- O encadeamento opcional é um processo para consultar e chamar propriedades, métodos e subscripts em um opcional que pode ser nulo. 

## Controle de fluxo: 
- Use if e switch para fazer condicionais. 

- Use for-in, while e repeat-while para fazer loops. 

## Tipos de coleção:

- O Swift fornece três tipos de coleção principais, arrays, sets e dictionaries. 

- Arrays são coleções ordenadas de valores. 

- Sets são coleções não ordenadas de valores únicos. 

- Dictionaries são coleções não ordenadas de associações de valores-chave. 

## Mutability Collections: 

- Array, set ou dictionary criado como variável será mutável. 

- Array, set ou dictionary criado como constante será imutável. 


# Estruturas de dados:
| Código | Explicação |
| ----- | --------|
| listas | processos executados em um sistema operacional (fila), chamadas de funções em um interpretador (pilha).|
| árvores | diretórios de computadores e aplicativos de busca |
| grafos | redes sociais (sugestão de conexões) |

## Tipos de coleção: 

- Possui 3 tipos de coleção primários, sendo eles: arrays, sets e dicionários. Todos possuem clara tipagem sobre os valores e chaves que podem armazenar. Por isso, não é possível inserir um Int em um array de strings. 

- Se um array, set ou dicionário é atribuído à uma variável, a coleção criada será mutável. 

- Se um array, set ou dicionário é atribuído à uma constante, a coleção criada será imutável. 

### Array: 

Um array armazena valores do mesmo tipo em uma lista ordenada. O mesmo valor pode aparecer em um array múltiplas vezes e em diferentes posições.

### Sets:

Um set armazena valores distintos (do mesmo tipo) em uma coleção sem ordem definida.

### Dicionários: 

Um dicionário armazena uma associação entre chaves (do mesmo tipo) e valores (do mesmo tipo) em uma coleção não ordenada. Cada valor é associado com uma chave única.

### Pilhas: 

São um tipo de estrutura de dados do tipo LIFO (last in, first out). Portanto, em uma pilha o acesso é restrito somente ao elemento mais recente da pilha. 

### Operações de pilhas: 

As operações básicas em uma pilha são:

push(): Insere um elemento no topo 
pop(): Retira um elemento do topo
top(): Observa o topo

| Código | Explicação |
| ----- | --------|
| push() | insere um elemento no topo |
| pop() | retira um elemento do topo |
| top() | observa o topo e retorna o último elemento da pilha |

Em uma pilha “ideal”, operações básicas devem ocorrer em O(1), independentemente do tamanho N da pilha (ou seja, em tempo constante).

Podemos ainda definir métodos auxiliares para uma pilha, que são:

| Código | Explicação |
| ----- | --------|
| isEmpty | checa se uma pilha está vazia |
| isFull | checa se uma pilha está cheia (no caso de linguagens sem alocação dinâmica) |

### Filas: 

São um tipo de estrutura de dados do tipo FIFO (first in, first out). Portanto, em uma fila o acesso é restrito somente ao elemento mais antigo da fila. 

| Código | Explicação |
| ----- | --------|
| enqueue() | insere um elemento na fila |
| dequeue() | retira um elemento da fila |
| peek() | observa o primeiro elemento da fila |


A remoção de um elemento é realizada alterando a posição do último elemento para evitar problemas de não ser capaz de inserir mais elementos na fila, mesmo quando ela não está cheia, as referências 'primeiro' e 'último' circundam até o início do vetor, resultando numa fila circular.

| Código | Explicação |
| ----- | --------|
| isEmpty | checa se uma fila está vazia |
| isFull | checa se uma fila está cheia (no caso de linguagens sem alocação dinâmica) |

### Listas ligadas: 

- São um tipo de estrutura de dados na qual elementos de um mesmo tipo de dado estão organizados de maneira sequencial. Não necessariamente, estes elementos estão fisicamente em sequência, mas a idéia é que exista uma ordem lógica entre eles. Assim, cada elemento da lista é chamado de nó, ou nodo.

- É um tipo de estrutura muito flexível e suporta inserção e retirada de dados de locais arbitrários.

- Vantagem: flexibilidade permitida no uso da memória.

- Desvantagem: alocar memória é uma tarefa demorada (mais lenta que acesso a pilhas e filas, por exemplo)

### As operações básicas em uma lista ligada são:
- Inserção de um elemento da lista
- Remoção de um elemento da lista
- Acesso de um elemento da lista

Às vezes convém tratar a primeira célula de uma lista encadeada como um mero marcador de início e ignorar o conteúdo da célula. Nesse caso, dizemos que a primeira célula é a cabeça (= head cell = dummy cell) da lista encadeada.

### Listas duplamente ligadas:

Em uma lista duplamente ligada, cada nó aponta em duas direções. Com essa estrutura é possível percorrer os dados em ambos os sentidos.

### As operações básicas em uma lista duplamente ligada são:
- Inserção de um elemento da lista
- Remoção de um elemento da lista
- Acesso de um elemento da lista

### Lista Circular: 

Algumas aplicações necessitam representar conjuntos cíclicos. 
Por exemplo, as arestas que delimitam uma face podem ser agrupadas por uma estrutura circular. Para esses casos, podemos usar listas circulares. 

Numa lista circular, o último elemento tem como próximo o primeiro elemento da lista, formando um ciclo.

### Árvores: 

Uma árvore representa uma coleção de dados de uma forma hierárquica. 

### Árvores binárias: 

Uma árvore binária T é um conjunto (finito) de nós, tal que:
- T é vazia, ou
- T consiste de um nó chamado "raiz" e duas árvores binárias que não possuem elementos comum (disjuntas).
- A árvore vazia não contém nenhum nó.
- A árvore trivial contém somente um nó.

### Árvores binárias - terminologias: 

- Um nó que não tem filhos é uma folha. 

- Um caminho é uma sequência de nós tal que cada nó é filho do anterior (excluindo o primeiro nó do caminho).

- Um nó A é chamado ancestral de um nó B se existe um caminho que começa em A e termina em B.

- O nível ou profundidade de um nó pode se definido da seguinte forma:

- A raiz da árvore tem nível 1.

- Se um nó tem um nível i, então os seus filhos têm nível (i+1)

- A altura de um nó A é o número de nós no caminho mais longo começando em A e terminando em um nó antes de uma folha. 

- A altura de uma árvore é a altura da raiz. 

- A altura da árvore vazia é -1. 

# Curiosidades: 

- Swift Playgrounds: app para iPad e Mac para deixar aprendizado do Swift mais divertido. Não exige conhecimento de programação. Vem com lista completa de lições criadas pela Apple. 

- Linguagem type-safe por ser segura para executar o código e fazer verificações de tipo ao compilar seu código e sinaliza quaisquer tipos incompatíveis. Isso não significa que precisa especificar o tipo de cada constante e variável que você declara.

- Criada a partir de uma mistura de antigos conceitos de programação, como POO, PF e POP.

- Não é necessário o uso de ponto e vírgula, sendo necessário apenas para a continuidade do código na mesma linha. 







