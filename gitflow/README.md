import java.util.Scanner;

public class RestaNumeros {
        public static void main(String[] args) {
                Scanner scanner = new Scanner(System.in);

<<<<<<< HEAD
                System.out.print("Ingrese el primer número que desea restar: ");
                int num1 = scanner.nextInt();

                System.out.print("Ingrese el segundo número que desea restar: ");
=======
                System.out.print("Ingrese el primer número: ");
                int num1 = scanner.nextInt();

                System.out.print("Ingrese el segundo número: ");
>>>>>>> 1.0.1
                int num2 = scanner.nextInt();

                int resultado = restarNumeros(num1, num2);

                System.out.println("El resultado de la resta es: " + resultado);

                scanner.close();
        }

        public static int restarNumeros(int a, int b) {
                return a - b;
        }
}