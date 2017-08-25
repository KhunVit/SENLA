# SENLA
         Ещё  2 из 37     Печатать все В новом окне Тестовое задание на курсы java SENLA
import java.util.Scanner;
public  class Test{	

public static void main (String[] args) {
		
		System.out.println("Введите любое, целое, положительное число от 1.\n Пожалуйста, по-быстрее!");
		Scanner scn = new Scanner(System.in);
		int nbr = scn.nextInt();
		
	    int N = nbr;
		int i, a[] = new int[N];
		for (i = 2; i < N; i++){
		a[i] = 1;
		}
		for (i = 2; i < N; i++) 
		if (a[i] == 1) 
		for (int j = i; j * i < N; j++){ a[i * j] = 0; 
		}
		for (i = 2; i < N; i++) 
		if (a[i] == 1) 
	    
		System.out.print(" "  + i);
		System.out.println(" -  все простые числа или цыфры(а) в этом интервале");
		}
		
		   
    }
