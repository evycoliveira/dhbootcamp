# Lista de Exercícios I: Introdução a linguagem Java

### Programação em Java

> O objetivo deste exercício prático é que possamos consolidar e aprofundar os conceitos de
programação orientada a objetos aplicados à Java. Para isso vamos propor uma série de
exercícios simples e incrementais (já que vamos trabalhar e adicionar lógica às classes que
temos que construir), que nos permitirão rever os tópicos que estudamos.

### Prática Integradora

<p>1. Crie uma classe Pessoa que terá os seguintes atributos: nome, idade, ID (neste caso vamos
representá-la como uma string de caracteres), peso e altura. Que tipo de dado você atribuiria
às variáveis de instância? Como seria a estrutura básica da sua classe? </p>
<p>Os tipos de dados que foram atribuídos às variáveis de instância estão de acordo com os tipos 
de dados definidos na classe Pessoa, como nome do tipo String, idade como int, altura e peso como 
double de acordo com as regras de negócios. Uma classe Pessoa com atributos e seus tipos, e outra 
classe AppPessoa que possui a instância da classe Pessoa e atribuição de dados respeitando seus
respectivos tipos, além da exibição dos resultados no console.</p>

<p>2. Vamos criar diferentes construtores na classe Pessoa, um sem parâmetros, e o outro deve
receber nome, idade e ID como parâmetros; e por fim criaremos um terceiro construtor que
recebe como parâmetro todos os atributos da classe.</p>

<p>3. Crie uma nova classe chamada Main, onde você irá chamar o método main como ensinamos
anteriormente. Isso nos permitirá executar o nosso programa.</p>

<p>4. Na classe Main que acabamos de criar, dentro do método main() pedimos para você criar um
objeto do tipo Pessoa para cada construtor que definimos na classe, lembre-se de colocar um
nome significativo para as variáveis para atribuir cada objeto. A seguir, vamos criar outro
objeto do tipo Pessoa e vamos construí-lo passando apenas um valor para o nome e outro
para a idade no construtor. Isto é possivel? O que acontece se tentarmos fazer isso?</p>

<p>Criar um objeto do tipo Pessoa para cada construtor que definimos na classe é necessário que 
possua o mesmo nome, caracterizado pelos construtores criados com diferença de passagem ou não de 
parâmetros como sobrecarga de métodos. Para o construtor solicitado, foi passado o id, nome e idade
e posteriormente, gerado getters e setters.</p>
<p>Na classe Main(), foi criada uma nova instância da classe Pessoa, passando o getters dos atributos de
id, nome e idade da classe Pessoa. É possível realizar adaptações sem alterar a execução bem sucedida
do projeto.</p>

<p>5. Na classe Pessoa vamos implementar os seguintes métodos: calcularIMC(), a fórmula para
calculá-lo é: peso/(altura^2) - (peso expresso em kg e altura em metros). Se este cálculo
retornar um valor menor que 20, a função deve retornar -1, se retornar um número entre 20 e
25, o método deve retornar 0, por fim, se retornar um número maior que 25 deve retornar 1.</p>
<p>Uma vez que o método anterior foi criado, vamos adicionar o método ehMaiorIdade() que
deve retornar um valor booleano, levando em consideração que a maioridade será
considerada, a partir de 18 anos. Por fim, adicione um método toString() que retornará todas
as informações da pessoa.</p>
<p>Lembre-se, você pode usar os métodos da classe java.lang.Math para calcular a potência.</p>

<p>6. A partir da classe Main vamos calcular o IMC da última pessoa que criamos (aquela que
criamos corretamente através do construtor que recebe todos os atributos como parâmetro).
Também descobriremos se a pessoa é maior de idade ou não; Observe que em ambos os
casos, dependendo dos resultados retornados pelos métodos, você deve imprimir uma
mensagem correspondente ao usuário. Finalmente, queremos mostrar todos os dados dessa
pessoa imprimindo essas informações pelo console. O formato em que você vai exibir os
dados e as mensagens fica a seu critério, mas deve ser legível e descritivo para quem vê a
saída do programa.</p>
<p>Referências:</p>

##### Índice de massa corporal (IMC) | Nível de peso
<p>Menor que 20 | Abaixo do peso</p>
<p>Entre 20 e 25 | Peso saudável</p>
<p>Maior que 25 | Sobrepeso</p>