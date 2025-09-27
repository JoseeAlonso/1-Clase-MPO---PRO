package PimerProyecto;

import java.util.Scanner;

public class Pruebas {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);

        int numero1;
        int numero2;

        System.out.println("Escriba un número entre el uno y el nueve");
        numero1 = scn.nextInt();
        System.out.println("Ahora escriba otro número entre el uno y el nueve");
        numero2 = scn.nextInt();
        System.out.println("Has elegido los números: "+numero1+ " y el "+numero2);


    }
}