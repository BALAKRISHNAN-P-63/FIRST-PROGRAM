# FIRST-PROGRAM
class Student {
    String name;
    int regno;
    String dept;
    String sec;

    void combination() {
        System.out.println(name);
        System.out.println(regno);
        System.out.println(dept);
        System.out.println(sec);
    }
}

public class Main {
    public static void main(String[] args) {
        Student obj = new Student();
        obj.name = "BALA";
        obj.regno = 35;
        obj.dept = "AI&DS";
        obj.sec = "A";
        obj.combination();
    }
}
# OUTPUT
BALA
35
AI&DS
A
