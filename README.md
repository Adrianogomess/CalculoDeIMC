# CalculoDeIMC

import java.util.Scanner;

public class CalculoDeIMC {
	
	public static void main(String[] args) {
		Scanner scanner = new Scanner (System.in);
		
		System.out.print(" Digite o peso: ");
		Double peso = scanner.nextDouble();
		
		System.out.print(" Digite a altura: ");
		Double altura = scanner.nextDouble();
		
		
		Double multiplicacao = altura * altura;
		
		Double resultado = peso / altura;
		
		System.out.println("Seu IMC é: " + resultado);
		
	}
	
	}

