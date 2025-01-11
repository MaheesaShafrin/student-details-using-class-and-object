# student-details-using-class-and-object

class Person {
String name;
int age;
public void display() {
System.out.println(&quot;Name: &quot; + name);
System.out.println(&quot;Age: &quot; + age);
}
}
public class ClassAndObject {
public static void main(String[] args) {
Person person = new Person();
person.name = &quot;Alice&quot;;
person.age = 25;
person.display();
}
}

Output
Name: Alice
Age: 25
