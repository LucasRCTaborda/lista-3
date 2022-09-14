# lista-3
PUCRS Fundamentos  de programação



import java.util.Scanner;
public class Exercicio15l3v1{
public static void main(String args[]){
Scanner teclado = new Scanner(System.in);
int valor=0,salario=0, filhos=0,maiors=0,percentual=0 ,cont=1,filhop;
System.out.print("\f");
cont=0;

while(cont<10){System.out.print(cont);
    System.out.print("Informe o salario;");
    valor=teclado.nextInt();
    if (valor<=0)System.out.println(" Erro -Informe positivo do salario");
        else{
                cont++;  //cont = cont + 1;
                salario = salario + valor;
                if(valor>maiors) maiors = valor;
                if( valor>=2000) percentual++;
           
        System.out.print("Informe a quantidade de filho");
    filhop=teclado.nextInt();
    if (valor<=0)System.out.println(" Erro -Informe positivo de filho");
        else{
                cont++;  //cont = cont + 1;
                filhos = filhos + filhop;
                
            }}
        }
        
        
        
        System.out.println("maior salário : " + maiors);
        System.out.println("média do salário da população : " + salario/5);
        System.out.println("média do número de filhos : " +  filhos/5);
        System.out.println(" percentual de pessoas com salário até R$2000,00. : "+percentual*20 );
    }}
        
