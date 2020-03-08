package com.company;

import java.util.Random;

public class Person
{
    static Random r = new Random();

    static String[] names = {"Abadubababa", "Person","Person2", "rgsegdsb", "ewgd", "wesfc", "wfegd", "egdef", "esdgs", "sdgwesgd"};
    static String[] second_names = {"Abadubababa", "Person","Person2", "rgsegdsb", "ewgd", "wesfc", "wfegd", "egdef", "esdgs", "sdgwesgd"};

    String name;
    String second_name;
    String email;

    public Person()
    {
        this.name = names[r.nextInt(names.length)];
        this.second_name = second_names[r.nextInt(second_names.length)];
        this.email = this.name + "." + this.second_name + r.nextInt(1000) + "@gmail.com";
    }
}










package com.company;

public class Main
{
    public static int n = 5;
    public static void main(String[] args)
    {

    }
}
