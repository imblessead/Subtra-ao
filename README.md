# Subtra-ao
Subtraçao

package exercicios;

import java.util.Scanner;

public class Subtraçao {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Digite o primeiro valor inteiro: ");
		int valor=scanner.nextInt();
		
		System.out.println("Digite o segundo valor inteiro: ");
		int valor2= scanner.nextInt();
		int subtraçao= valor-valor2;
	
		System.out.println("O valor da subtração é: " + subtraçao);
		
		scanner.close();
	}
	

}
