import java.util.Scanner;

public class exemplo01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 Scanner entrada = new Scanner (System.in);
	        
	        System.out.println("Digite o seu nome");
	        String nome = entrada.nextLine();
	        System.out.println("Digite a primeira nota:");
	        float nota1 = entrada.nextFloat();
	        System.out.println("Digite a segunda nota:");
	        float nota2 = entrada.nextFloat();
	        
	        // char = 'a';
	        // String nome = "Gustavo Kgu"; // Valor cadeia
	        // boolean Valor = true;
	        // Processamento
	        float media = (nota1 + nota2) / 2;
	        
	        //Saída
	        //System.out.println("A média das duas notas é:" + media);
	        
	        if (media >= 7) {
	            System.out.println(nome + ", parabéns, você foi aprovado com a média: " + media);
	        }
	        else if(media >= 6 && media < 7) {
	            System.out.printf(nome +", você fpo para a Final... sua nota foi: %.2f", media);
	        }
	        else {
	            System.out.printf("A média de %.2f e %.2f = %.1f e por isso você foi reprovado!!!", nota1, nota2, media);
	        }
	}

}
