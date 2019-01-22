Question 1: From a classification perspective, a setter method is a(n)...?
The Correct Answer is mutator because it is used to determine whether or not a variable is modified by other code.

Question 2: In most cases, programmers provide a                             [ Select ]                          ["retrieve", "setter", "set", "getter", "get"]           method to access the values of their instance variables from other classes. Likewise, they provide a                             [ Select ]                          ["getter", "set", "setter", "updater", "get"]            method to update the values of their instance variables from other classes.
The correct answer is for answer 1: getter and for answer 2: setter because getter by definition is a method to access the values of their instance variable from other classes and setter is a method to update the values of their instance variables from other classes. 
The other answers are incorrect because they do not match the definitions.


Question 4: Consider the following partially implemented class.
public class Quiz {

   private static int id = 1;
   private int questionCount;

   public Quiz(int questionCount) {
       this.questionCount = questionCount;
   }

   public int getId() {
       return id;
   }

   public void incrementId() {
       id++;
   }

   public int getQuestionCount() {
       return questionCount;
   }
}
Now, consider the following usage of the aforementioned class.
Quiz q1 = new Quiz(10);
Quiz q2 = new Quiz(15);
q2.incrementId();

System.out.println(q1.getId());
System.out.println(q2.getId());
System.out.println(q1.getQuestionCount());
System.out.println(q2.getQuestionCount());
What will be printed to the console?
The correct answer is 
2
2
10
15 
This is correct because the last two numbers are the amount of indexes within each array, first one being 10 and the second one being 15.  The first two numbers are the id which when plugged in both respond with the outcome of 2. 
The other answers are incorrect as when ran none of them match the correct output.

Question 5: Consider the following constructor method in the Person class.
public class Person {
 
   private int age;
   private String name;
   public Person(int age, String name) {
       // TODO
   }
}
I need to assign the values of the local variables age and name to their instance variable equivalents. Select the lines of code that do just that.
The correct answer is this.age = age;
this.name = name;
As the the syntax to assign local variables of age and name  match the correct answer.
The other answers are incorrect as the syntax does not match the correct syntax to perform the task asked.
Question 6: In order to implement the toString method, what annotation do you need to include?
The correct answer is @Override as override is the only one that implements the toString method.
The other answers are incorrect as none of them implement the toString method.
Question 7: Consider the following partial class definition.
public class Quiz
 
   private String instructionalUnit;
}
Given the name of the instance variable, what would be the conventionally correct signatures for the getter and setter? Choose two options.
The correct answer is public String getInstructionalUnit()
 And public void setInstructionalUnit(String instructionalUnit)
As both string and retrieve the instruction Unit.
The other answers are incorrect as none of them correctly retrieve and string the instruction Unit.
