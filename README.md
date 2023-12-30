# code56
package x;
import java.util.Scanner;
 
 
class Student{
    String name1;
    int a;
    public Student(String n){
        name1=n;
    }
    public Student(String n,int b){
        a=b;
        name1=n;
    }



}

public class x {
    public static void main (String[] args)
    {
        Scanner sc=new Scanner(System.in);
        Student t1=new Student("wdw");
        Student t2=new Student("wede",1);
        t1.name1=sc.next();
    //    System.out.println("efwe"+t1.name1+"efer");
        System.out.println("t2"+t2);
    }



}
