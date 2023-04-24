# Aluna
- Clara Padilha Martinhão

# Atividade
- Classe em Java que seja capaz de apresentar a soma de todos os argumentos inteiros ou reais recebidos. Argumentos inválidos devem ser desconsiderados sem provocar a exibição de erros ou exceções.

# Código
import java.util.Scanner;

class Atv01{

    public static void main(String args[]){

        double n1; //Declara variável.
        double n2; //Declara variável.
        double somar; //Declara variável.

        Scanner num = new Scanner(System.in); //Declara o objeto scanner.

        try{
            n1 = num.nextDouble(); //Define o valor para a soma.
            n2 = num.nextDouble(); //Define o valor para a soma.
            somar = n1 + n2; // Realiza a soma.
            System.out.println(n1 + " + " + n2 + " = " + somar); //Mostra a formatação da soma e o resultado.
        } catch (java.util.InputMismatchException e) {
            System.out.print(""); //Evita a exibição de erro caso o valor não seja do tipo 'double'.
        }
    }
}
