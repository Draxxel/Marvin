# Marvin
My first Java code
package src;
//src/people/src.Student.java

import java.util.ArrayList;
import java.util.List;

public class Student extends src.person{
    private List<Course>courses;

    public Student(String name, int age){
        super(String.valueOf(name), age);
        courses = new ArrayList<>();
    }

    public static void enroll(Course mathCourse) {
    }

    public List<Course> getCourses() {
        return courses;
    }
    @Override
    public void performDutiers(){
        System.out.println(getName() + " is studying. ");
    }

    @Override
    public void displayRole() {

    }

    public void add(Student student) {
    }


}
