﻿## Exercícios Java
- **1** **O que é um objeto?**
	>  Um objeto em programação é a abstração de um objeto real. Ele representa um objeto existente no mundo real, seja ele físico ou não. Um objeto é algo que possui nome e identidade.

- **2.  Identifique 3 características e 3 comportamentos de um carro.**
	>  Um carro possui cor, quantidade de portas e modelo específico. Um carro pode trocar marcha, andar, parar, ligar, acender o farol etc.
	
- **3. No contexto de Orientação a Objetos, as características e comportamentos são chamados respectivamente de?**
	> Atributos e métodos.
	
- **4. Qual o objetivo da programação orientada à objetos?**
	 >A programação orientada a objetos tem como objetivo trazer o sistema o mais próximo possível dos objetos do mundo real de maneira cooperativa.

-	**5. O que é abstração? Cite um exemplo.**
	>Abstração é a capacidade de focar nas principais características de um objeto sem se apegar a características supérfluas.
	
- **6. O que é classe?**
	>Classe é o esqueleto de um objeto, define as suas características e métodos.


- **7. Qual o padrão utilizado para nomear as classes? Cite um exemplo.**
	>Sempre com letra maiúscula no começo e seguindo o padrão CamelCase.

- **8. Qual opção apresenta corretamente o nome da classe _carro elétrico_?**
	>1. carroeletrico

	>2. carroEletrico

	>3. Carroeletrico

	**4. CarroEletrico**

	>5. carro_eletrico

- **9. Qual o padrão utilizado para nomear os atributos? Cite um exemplo.**
	> CamelCase mas no caso não começa com letra maiúscula.
	

- **10. Qual opção apresenta corretamente o nome do atributo _cor de fundo_?**
	>a. CordeFundo

	>b. CorDeFundo

	**c. corDeFundo**

	>d. _cor_de_fundo

	>e. _corDeFundo

	>f. mCorDeFundo

- **11. Qual é o padrão utilizado para nomear os métodos? Cite um exemplo.**
	>Verbos em Camelcase com a primeira letra minúscula.
	
- **12. Qual opção apresenta corretamente o nome do método _está vazio_?**

	**a. estaVazio**

	>b. _estaVazio

	>c. estavazio

	>d. EstaVazio

	>e. Estavazio

	>f. Esta_vazio
	
- **13. No contexto de orientação à objetos, o que é um objeto? Em que momento existe um objeto? Quando ele deixa de existir?**
	>Objeto é uma instanciação de uma classe, um objeto começa a existir a partir do momento que você declara ele, um objeto só deixa de existir após a execução do programa.

-  **14. Qual é o objetivo do operador new?**
	>O objetivo do operador new é criar um objeto da classe desejada.
	
- **15. O que é o construtor? Qual é o seu objetivo? Qual deve ser o seu nome? Cite um exemplo.**
	> O objetivo do método construtor é fazer com que ao ser criado um objeto da classe, essa receba parâmetros pré-definidos. O método construtor deve ter o mesmo nome da classe e ser público.

-  **16. Caso o construtor da classe Aluno não for declarado, qual será o seu construtor?**
	> O seu construtor será _null_, ou seja, não a passagem de parâmetros

- **17. Crie um exemplo de instanciação da classe Aluno. Utilize o construtor padrão.**
	>`Aluno aluno1 = new Aluno();`

- **18. O que é encapsulamento?**
	> Encapsulamento é “esconder” métodos ou atributos para que outras classes não tenham acesso a eles.

-  **19. Qual é o objetivo do modificador de acesso _public_?**
	> O modificador de acesso _public_ permite que todas as classes tenham acesso ao atributo ou método que foi declarado da seguinte forma.

- **20. Qual é o objetivo do modificador de acesso _private_?**
	> O _private_ permite que somente a classe tenha acesso aos métodos ou atributos que foram declarados com esse modificador de acesso.

-  **21. Como é aplicado o encapsulamento em uma classe? Considere a classe Aluno com o atributo matrícula.**
	>`private class Aluno{
		int Matricula;
		public Aluno(int Matricula){
			this.Matricula = Matricula;
			}
		}`

- **22. Qual o objetivo dos métodos getters? Crie um exemplo.**
	>`public String getNome(){
		return nome;
		}`

- **23. Qual o objetivo dos métodos setters? Crie um exemplo.**
	> Ele da um SET em algum valor.
	> `public void setNome(String nome){
		This.nome = nome;
		}`

- **24. O diagrama de classe UML é composto por 3 partes. O que vai em cada parte?**
	> Nome da classe, Atributos e métodos.

- **25. Qual é o padrão utilizado para representar um atributo no diagrama de classe UML? Crie um exemplo.**
	>"+"Nome : String.

- **26. Qual é o padrão utilizado para representar um método no diagrama de classe UML? Crie um exemplo.**
	>"-" getNome(): String.

- **27. Como o construtor de uma classe pode ser diferenciado no diagrama de classe UML? Crie um exemplo.**
	> O método possui o mesmo nome da classe e possui um retorno void.

- **28. Quais são os símbolos utilizados no diagrama de classe UML para representar os modificadores de acessos aos atributos e métodos? Crie um exemplo.**
	>"+" público, -privado, # protected.

- **29. Considere a classe Cliente, com os atributos nome, email e telefone com os respectivos métodos getters e setters. Desenvolva o diagrama de classe UML.**
	![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/1.png) 

- **30. Considere a classe Cliente apresentado no Problema 29, e desenvolva o código Java correspondente.**
	>`public class Cliente{
		String nome = null;
		String Email = null;
		int Telefone = 0;
		public Cliente(String nome, String Email, int Telefone{
			this.nome = nome;
			this.Email = Email;
			this.Telefone = Telefone;
			}
		public string getNome(){
			return nome;
			}
		public string getEmail(){
			return Email;
			}
		public Email getTelefone(){
			return telefone;
			}
		}`

- **31. Desenvolva o código java classes do apresentadas no diagrama de classes UML abaixo:**
	![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/2.png)

	>`public class Produto{
		private String nome;
		public string getNome(){
			return nome
			}
		public void setNome(String nome){
			this.nome = nome;
			}
		}
	public class Password{
		private String value;
		public void Password(String value){
			this.value = value;
			}
		public bool isEsqual(Password obj){
			if(value == obj.value){
				return true;
			}
			else{
				return false;
			}
		}
	}
	public class Animal{
		private bool Avlive;
		public void isAlive(){
			return true;
			}
		private void die(){
			Alive = false;
			}
		}`

- **32.** **Desenvolva o diagrama de classe dos códigos Java abaixo.**
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/3.png)
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/4.png)
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/5.png)
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/6.png)


- **33. O que é o estado de um objeto? Cite um exemplo com a classe Aluno com os atributos nome, idade, matrícula e curso. Utilize o diagrama de estado de objeto.**
	>É quando um objeto é instanciado e é setado os parâmetros para esse objeto.
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/7.png)

- **34. Qual é o estado do objeto da classe Dog quando é inicializado? Desenvolva o diagrama de objetos.**
	>`public class Dog{
		private int years;
		private String name;
		private boolean alive;
		//Getters e setters suprimido}`
		![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/8.png)

- **35. Qual é o estado do objeto dog no final da execução do método main? Desenvolva o diagrama de objetos.**
	> `public static void main(String args[]){
			Dog dog = new Dog();
			dog.setYears(10);
			dog.setName("Spike");
			dog.setAlive(true);
		}`
		![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/9.png)

- **36. Qual é o estado do objeto pug e buldog após a execução da linha 6? Desenvolva o diagrama de objetos.**
	>`Dog pug = new Dog();
	Dog buldog = new Dog();
	pug.setName("Spoke");
	buldog.setName("Spike")
	pug.setAlive(true);
	pug.setYears(2);
	buldog.setName("Floquinho");
	pug.setYears(1);`
![enter image description here](https://github.com/LucasMontalvao/ImagensPOO/blob/master/10.png)

- **37. Analise o código abaixo. Verifique se existem problemas, caso sim, indique o problema e sugere as correções.**
	>`public class Cat{
		private String name;
		public double weith;
		//Getters e Setters suprimidos}
	public class Main{
	public static void main(String args[]){
		Cat c = new Cat();
		c.weight = 3.5;
		c.name = "BlackCat";
	}`
	>A classe Cat possui um atributo name com o modificador de acesso privado, o que não permite que um objeto chame o atributo de fora da classe. Para o acesso ser possível o modificador de acesso deveria ser público.

