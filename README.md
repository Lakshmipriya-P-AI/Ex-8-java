# EXP-8 -> USING INHERITANCE ONE CLASS CAN ACQUIRE THE PROPERTIES OF OTHERS.
## AIM:
To Write the java program Using Inheritance one class can acquire the properties of others.

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM:
Create the class and declare the main method so that the JVM will identify the main program to run.
Create another class and use the keyword EXTENDS to use the concept of INHERITANCE.
Print a statement to check whether the inner class is accessable or not.
If the extended class's statement is executed then,this program follows the concept of inheritance.
The program will be executed after the compilation and results are printed.

## PROGRAM:
```
package q1;

public class Main {
    public static void main(String[] args) {
        Bird c=new Bird();
        c.fly();
        c.walk();
        c.sing();
    }
}
//CLASS FILE: BIRD
public class Bird extends Animal{
    public void fly(){
        System.out.println("I m flying");
    }
    public void sing(){
        System.out.println(" "+"I m singing");
    }
}
//CLASS FILE: ANIMAL
public class Animal {
    public void walk(){
        System.out.println("I m walking");
    }
}
```
## OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/Ex-8-java/assets/93427923/0a9b3cff-d496-454e-80fe-e53ecb888af7)

### RESULT:
Thus output is verified.
