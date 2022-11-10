# Classes-in-java
Oops concept
class Shivani{
//Declaration of attributes
    int id;
    String name;
    // method initialisation
    public void printDetails(){
        System.out.println("My name is " + name);
        System.out.println("My id is " + id);
    }
}
public class Class{
//main method
    public static void main(String[] args) {
        System.out.println("HEllO");
        //object initialisation
        Shivani obj = new Shivani();
        //setting values of attributes
        obj.id= 12;
        obj.name="Gauravsharma";
        //printing values of attributes
        System.out.println(obj.id);
        System.out.println(obj.name);
        //mathod calling
        obj.printDetails();
    }
}
