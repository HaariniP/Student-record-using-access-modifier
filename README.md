# Student-record-using-access-modifier
class Student {
    private String name;
    private int age;
    protected String grade;
      public void setDetails(String name, int age, String grade) {
        this.name = name;   
        this.age = age;    
        this.grade = grade; 
    }
    public void getDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Grade: " + grade);
    }
}
public class AccessModifierExample {
    public static void main(String[] args) {
            Student student = new Student();
        student.setDetails("John Doe", 21, "A");
        student.getDetails();
    }
}
