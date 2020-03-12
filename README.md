# LFA
Exercícios Linguagens Formais e Autômatos

Maquina de Coca-Cola:

package maquinaDeCoca;

import javax.swing.JOptionPane;

public class Garrafas {

	public static void main(String[] args) {
	
		int moedas = 0;
		int entrada = 0;
							
				do{entrada=Integer.parseInt(JOptionPane.showInputDialog("Insira uma moeda, apenas moedas de 25 e/ou 10 centavos são aceitas"));
				if(entrada ==25 || entrada ==10){
					moedas+=entrada;
				if(moedas >=45) {
					JOptionPane.showMessageDialog (null, "Coca-Cola liberada");
			}
							 }		
												}
				while(moedas<45);
	}
}	
			
