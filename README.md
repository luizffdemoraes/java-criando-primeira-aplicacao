

<br/>01. Primeiro programa em Java<br/>
=================
<!--ts-->
* A configurar o ambiente de desenvolvimento, instalando a JDK 17 e a IDE IntelliJ;
* As diferenças entre JVM, JRE e JDK:
    * JVM (Java Virtual Machine) - é a Máquina Virtual do Java responsável por executar o bytecode;
    * JRE (Java Runtime Environment) - Ambiente de Execução do Java que fornece as bibliotecas padrões do Java para o JDK compilar o seu código e para a JVM executar o seu programa;
    * JDK (Java Development Kit) - Kit de Desenvolvimento Java responsável por compilar código-fonte em bytecode.
* A fazer o “Alô Mundo!” no Java e executar seu primeiro programa pelo IntelliJ;
<!--te-->

<br/>02. Construindo o catálogo de filmes<br/>
=================
<!--ts-->
* A trabalhar com variáveis: recurso utilizado para armazenar valores em memória;
* Sobre tipos primitivos:
    * inteiros (byte, short, int, long);
    * ponto flutuante (double e float);
    * char: contém um único caractere;
    * boolean: recebe 2 valores, true e false;
* Como representar textos em Java, utilizando a classe String;
* A realizar casting de valores, para resolver situações de tipos incompatíveis no momento de realizar um cálculo ou atribuição de uma variável.
<!--te-->

<br/>03. Controlando o fluxo da aplicação<br/>
=================
<!--ts-->
* A configurar uma aplicação para que ela escolha entre executar uma ação ou outra baseada em algum elemento;
* Comparações para as condicionais: igual, diferente, maior, menor;
* A usar a leitura do teclado com a classe Scanner;
* Trabalhar com alternativas para as condicionais e escolher a ideal para o caso escolhido;
* A utilizar estruturas de repetição com for e while.
<!--te-->

<br/>04. Consolidando Conhecimento<br/>
=================
<!--ts-->
* A aplicar seus conhecimentos em uma aplicação de um sistema bancário,<br/> utilizando conceitos de variáveis, condicionais, loops e leitura de dados no Java,<br/> juntamente à lógica de programação.
<!--te-->

<br/>

![thumbnail-Desafio Java](https://user-images.githubusercontent.com/66698429/218160231-11c3a759-711e-484d-a856-b5977b065ec6.png)


# Desafio


Implementar uma aplicação para controlar nossa conta bancária, seja ela virtual ou não. 

## 🔨 Objetivos do projeto

- Criar um cabeçalho inicial com os dados do cliente (Nome, Tipo da Conta e Saldo)
- Criar um menu que descreve as operações. Aqui você pode escolher o nome de método que mais lhe agradar, como *saca* (ou *transfere*, *enviaPix*) para simular a **retirada** de valores da conta
e *deposita* (ou *recebeTransferencia*, *recebePix*) para representar a **entrada** de valores na conta.
- O menu deve ter quatro opções: a de entrada de valor, saída de valor, consulta de saldo e finalização da aplicação.
- Lembre-se que para fazer a saída de valores, é necessário ter saldo suficiente.
- O menu deve aparecer continuamente até que o usuário digite a opção para sair.
- Caso ele digite qualquer opção que não seja correta, deve apresentar a mensagem de opção inválida.
- Usaremos a classe Scanner para fazer a leitura da opção do usuário.
<p></p>

Exemplo/Sugestão de tela para o menu: 

<p></p>

![image](https://user-images.githubusercontent.com/66698429/218162389-1b68a232-e91b-44ba-b7b3-317920d69ee1.png)


