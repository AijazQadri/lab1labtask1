# lab1labtask1

package com.mycompany.lab1labtask1;

public class Lab1labtask1 {

    public static void main(String[] args) {
        String A1="Aijaz";
        String A2="Mobariz";
        String A3="Aijaz";
        String A4=new String("Mobariz");
        String A5=new String("Aijaz").intern();
        
        System.out.println(A1==A3);
        System.out.println(A2==A4);
        System.out.println(A1==A5);
    }
}
