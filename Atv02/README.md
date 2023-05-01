# Aluna
- Clara Padilha Martinhão

# Atividade
- classe em Java que realize cada uma das seguintes tarefas:

a) Exibir a mensagem "Informe um inteiro: ", deixando o cursor na mesma linha;
b) Atribuir o produto de variáveis b e c para a variável a;
c) Utilizar um comentário para afirmar que um programa executa um cálculo de exemplo de folha de pagamento.

# Código

```

import java.util.Scanner;

class Atv02{

    public static void main(String args[]){

        int c; // Declaração de variável
        int b; // Declaração de variável
        int a; // Declaração de variável

        Scanner num = new Scanner(System.in); //Declara o objeto scanner.

        try{
            System.out.print("Informe um inteiro:"); //
            c = num.nextInt(); // Recebe o primeiro valor(c)
            b = num.nextInt(); // Recebe o segundo valor(b)
                a = c * b; // O programa executa um cálculo de exemplo de folha de pagamento.
                System.out.println(c + "x" + b + "=" + a);
        } catch (java.util.InputMismatchException e) {
            System.out.print(""); //Evita a exibição de erro caso o valor não seja do tipo 'int'.
        }
    }
}

```
