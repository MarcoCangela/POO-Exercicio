Ficha 2.1 de Exerc�cios de POO 2017
Exerc�cios
Exerc�cios Pr�ticos
1. Crie uma classe abstrata ContaBancaria que cont�m como atributos o numero da conta e o saldo, e como m�todos abstratos sacar e depositar que recebem um par�metro do tipo double.

2. Crie as classes Conta Corrente e Conta Poupan�a que herdam da Conta Bancaria. A
primeira possui um atributo taxaDeOpera��o que � descontado sempre que um saque e um dep�sito s�o feitos.
A segunda possui um atributo limite que d� credito a mais para o correntista caso ele precise sacar mais que o saldo. Neste caso, o saldo pode ficar negativo desde que n�o ultrapasse o limite. Contudo isso n�o pode acontecer na classe ContaCorrente.

3. Crie uma interface Imprim�vel que declara um m�todo mostrarDados.

4. Fa�a as classes Conta Corrente e Conta Poupan�a implementarem a interface e na implementa��o do m�todo mostre os atributos de cada conta.

5. Crie uma classe Relat�rio que possui um m�todo gerarRelat�rio que receba um objeto imprim�vel e executa o m�todo mostrarDados do objeto.

6. Crie uma classe execut�vel na qual voc� instancia duas contas (uma de cada tipo), credita algum valor para elas e efetua um saque (obs: no objeto conta poupan�a, fa�a um saque maior que o saldo atual).

7. Crie um objeto relat�rio e execute o m�todo gerar relat�rio para cada conta criada.

8. Incremente a classe ContaBancaria com o m�todo transferir que recebe o par�metro o valor (double) e um objeto conta bancaria e transfere o valor desejado da conta atual para cada conta informada. Use os m�todos sacar e depositar para isso.

9. Crie uma classe Banco que possui um arraylist de contas banc�rias e implemente os m�todos inserir, remover e procurarConta.
O primeiro e o segundo recebem um objeto conta (que pode ser corrente ou poupan�a) e o insere e remove no arraylist, respectivamente. O terceiro recebe um inteiro como par�metro representando o n�mero da conta e retorna um objeto conta banc�ria, caso essa conta exista no arraylist, ou null, caso contr�rio.

10. Fa�a a classe banco implementar a interface imprim�vel, onde a implementa��o de m�todo consiste em executar m�todo mostrar dados de cada conta criada.

11. Crie outra classe execut�vel que instancie um banco e ofere�a o seguinte menu para o usu�rio:

a) Criar conta: o usu�rio informa se � conta poupan�a ou corrente e os dados da conta. O objeto correspondente � criado e inserido no banco atrav�s do m�todo inserir. Exibir uma mensagem de sucesso.
Ficha 2.1 de Exerc�cios de POO 2017

b) Selecionar conta: o usu�rio informa o n�mero da conta. Se a conta existir, mostra o menu abaixo. Caso contr�rio, mostra mensagem de conta inexistente.

c) Remover conta: o usu�rio informa o n�mero da conta. Se a conta existe, ent�o
ela � exclu�da e uma mensagem de sucesso � informada. Caso contr�rio, uma
mensagem de conta inexistente � informada.

d) Gerar relat�rio: mostra os dados de todas as contas cadastradas no banco.

e) Finalizar: termina a aplica��o. Se o usu�rio escolher a op��o 2 mostre o seguinte menu:

a. Depositar: recebe um valor e deposita na conta.
b. Sacar: recebe um valor e tenta sacar da conta.
c. Transferir: recebe um valor e o n�mero de outra conta. Caso a conta exista,
transfere o valor de uma conta para a outra. Caso contr�rio, informar mensagem de
conta inexistente.
d. Gerar relat�rio: mostra os dados da conta selecionada.
e. Retornar ao menu anterior: exibe o menu anterior (op��es 1 a 5).

Use Interface gr�fica.