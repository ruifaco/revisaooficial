# revisaooficial
QUESTÃO 1

nome, especie, idade
inclui no constructor, além dos atributos de animal, o habitat. (meio certo)

QUESTÃO 2

A nova classe pega os atributos da classe já existente
os elementos que citamos dentro dos parenteses serão herdados da classe inicial e podem ser utilizado dentro das subclasses. métodos podem ser herdados, mas não podem ser colocados dentro do super.

QUESTÃO 3
1. um novo animal é criado
2. referencia nela a classe que vai ser utilizada 
3.atribui os valores aos atributos da classe, ou seja, são definidos os valores de nome, especie, idade e habitat (que são os atributos)
new cria um objeto a partir de acordo com o constructor
animal1 referencia a classe animal e animal2 referencia a classe animal selvagem

QUESTÃO 4
porque os dois objetos remetem a classes que possuem nome, especie e idade (errado)
Porque quando você puxa pelo extends da classe principal, você também puxa o método da classe principal.
não, pois a classe animal não possui habitat como parâmetro. Como animal1 chama a classe animal, que não possui habitat como parâmetro, ela não está disponível em animal1.

QUESTÃO 5
Não precisa repetir this.nome, this.especie, etc….
Reutilizar o código. Fazer o código ficar modular
Na classe animal, pois incluindo na classe animal, a classe animal selvagem já importaria esse método.

QUESTÃO 6
Nome: Tico, Espécie: Macaco, Idade: 4;
Nome: Nala, Espécie: Leoa, Idade: 5; (n entendi se junta com o debaixo ou fica na mesma linha)
Habitat: Savana Africana
quando tira da subclasse, voce tira atributo e metodos da subclasse. para de herdar metodos da classe e nao teria acesso aos atributos, apenas ao atributo de habitat.

QUESTÃO 7 
 
class AnimalDomestico extends Animal {
constructor (nome, especie, idade, nomeDono)
super (nome, especie, idade)
this.nomeDono = nomeDono

exibirNomeDono() {
return `Dono de ${this.nome}: ${this.nomeDono}:
