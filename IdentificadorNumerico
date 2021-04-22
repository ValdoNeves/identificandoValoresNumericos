import java.io.IOException;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class IdentificadorNumerico {

	public static void main(String[] args) throws IOException {
        Scanner leitor = new Scanner(System.in);
        List<Integer> valores = new ArrayList<>();
        List<Integer> pares = new ArrayList<>();
        List<Integer> impares = new ArrayList<>();
        List<Integer> positivos = new ArrayList<>();
        List<Integer> negativos = new ArrayList<>();
        
        
        //declare suas variaveis corretamente
        for(int i = 0; i < 5;i++) {
        	valores.add(leitor.nextInt());
        }

        System.out.println(valores + "\n");
        
        for(int i = 0; i < valores.size(); i++) {
        	
        	if(valores.get(i) % 2 == 0) {
        		pares.add(valores.get(i));
        	}else{
        		impares.add(valores.get(i));
        	}if(valores.get(i) > 0) {
        		positivos.add(valores.get(i));
        	}else if(valores.get(i) != 0){ //ignora o zero como positivo ou negativo
        		negativos.add(valores.get(i));
        	}
        	
        }

        //insira suas variaveis corretamente
        System.out.println(pares.stream().count() + " valor(es) par(es)");
        System.out.println(impares.stream().count() + " valor(es) impar(es)");
        System.out.println(positivos.stream().count()+ " valor(es) positivo(s)");
        System.out.println(negativos.stream().count() + " valor(es) negativo(s)");
    }

}
