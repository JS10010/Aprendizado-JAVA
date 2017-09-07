# M.-Escolar
package notas;
    import java.util.Scanner;   

    public class Notas {

        public static void main(String[] args) {
                
                String Name; 
            
                    Double Nota1;
                    Double Nota2;
                    Double Nota3;
                    Double media1;
                    Double media2;
                    Double mf;
                    Double pf;
                    Double rf;
                    
                    Scanner sc = new Scanner (System.in);  
                    System.out.println("  Bom dia, digite seu NOME: ");
                        Name = sc.nextLine();
                    System.out.println("  Seja bem vindo "+Name+".");
                        
                    System.out.println("  Digite a nota do 1º Teste: ");
                        Nota1 = sc.nextDouble();
                    System.out.println(  "Digite a nota do 2º Teste: ");
                        Nota2 = sc.nextDouble();
                    System.out.println("  Digite a nota da Prova: ");
                        Nota3 = sc.nextDouble();
                        
                        media1 = (Nota1*2 + Nota2*2 + Nota3*6) / 10;
                    System.out.println("  Sua média é: "+media1+"");
                    
                    if (media1 >= 7) {System.out.println("  Você foi aprovado na 1ª unidade!");
                    } 
                    else if (media1 < 7) {System.out.println("  Você foi reprovado na 1ª unidade!");
                    }
                   
                    System.out.println("  "+Name+", agora digite as notas da 2ª unidade:" );
                    
                    System.out.println("  Digite a nota do 1º Teste: ");
                        Nota1 = sc.nextDouble();
                    System.out.println("  Digite a nota do 2º Teste: ");
                        Nota2 = sc.nextDouble();
                    System.out.println("  Digite a nota da Prova: ");
                        Nota3 = sc.nextDouble();
                
                    media2 = (Nota1*2 + Nota2*2 + Nota3*6) / 10;
                    System.out.println("  Sua média é: "+media2+"");
                    
                    if (media2 >= 7) {System.out.println("  Você foi aprovado na 2ª unidade!");
                    } 
                    else if (media2 < 7) {System.out.println("  Você foi reprovado na 2ª unidade!");
                    }
                    
                        mf = media1 + media2 / 2 ;
                    System.out.println("  Sua média final é: "+mf+" ");
                    
                    if (mf >= 14) {System.out.println("  Você foi aprovado, boas férias! ");
                    }
                    else if (mf < 14 ) {System.out.println("  Você foi reprovado, terá que fazer a prova final!");} 
                       
                    }
                    } 
                   
//Josemar Jr.
