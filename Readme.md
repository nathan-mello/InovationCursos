## 



## Implementando uma ApiRest com as principais características  de Orientação a Objetos em java



### Abstração

Na programação, a abstração refere-se à criação de modelos simplificados de sistemas e processos, que permitem a manipulação de conceitos complexos de forma mais fácil e intuitiva. Por exemplo, na programação orientada a objetos, a abstração permite a criação de classes e objetos que representam conceitos abstratos, como pessoas, animais, veículos, entre outros.

### Encapsulamento

Consiste em agrupar dados e métodos relacionados em uma única unidade, chamada de classe, e restringir o acesso aos dados e métodos para que só possam ser manipulados por meio de métodos públicos. Em outras palavras, o encapsulamento busca proteger o estado interno de um objeto, permitindo que ele possa ser modificado apenas por meio de métodos cuidadosamente controlados e evitando que dados sejam acessados ou modificados diretamente por outras partes do programa.

Na prática, o encapsulamento é implementado por meio de modificadores de acesso (public, private e protected) que representação:

**public**: acesso permitido de qualquer classe em qualquer lugar;
**private**:  sem acesso de fora da classe;
**protected**: acessível a partir de todas as classes no mesmo pacote e a partir de qualquer sub-classe em qualquer lugar.

### Herança

Herança permite que uma classe (chamada classe filha ou subclasse) herde características e comportamentos de outra classe (chamada classe pai ou superclasse). A classe filha pode então adicionar seus próprios atributos e métodos, além dos que já foram herdados da classe pai, permitindo a criação de hierarquias de classes com níveis de complexidade crescentes.

A herança também permite que as classes filhas possam reutilizar o código da classe pai, evitando a duplicação de código e tornando o desenvolvimento mais eficiente. Além disso, a herança também pode tornar o código mais organizado e legível, pois ajuda a agrupar classes relacionadas em uma hierarquia clara.



### Polimorfismo

Polimorfismo refere se à capacidade de objetos de classes diferentes responderem a uma mesma mensagem ou chamada de método de maneira diferente, de acordo com sua própria implementação. Existem dois tipos de polimorfismo: o polimorfismo de sobrecarga e o polimorfismo de sobreposição.

O polimorfismo de sobrecarga ocorre quando uma classe tem diversos métodos com o mesmo nome, mas com diferentes parâmetros. O compilador é capaz de determinar qual método deve ser chamado, com base nos argumentos passados para a chamada do método.

Já o polimorfismo de sobreposição (ou override) ocorre quando uma classe filha redefine um método da classe pai, utilizando a mesma assinatura. Nesse caso, quando um objeto da classe filha é criado e esse método é chamado, a implementação da classe filha é utilizada em vez da implementação da classe pai.