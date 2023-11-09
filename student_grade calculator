import java.util.Scanner;

public class StudentGradeCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the number of the subjects: ");
        int numSubjects = scanner.nextInt();

        int totalMarks = 0;
        for(int i = 1; i <= numSubjects; i++) {
            System.out.print("Enter marks obtained in subject " + i + ": ");
            int marks = scanner.nextInt();
            totalMarks += marks;
        }

        double averagePercentage = (double) totalMarks / numSubjects;

        String grade;
        if(averagePercentage >= 90) {
            grade = "O";
        } else if(averagePercentage >= 80) {
            grade = "A";
        } else if(averagePercentage >= 70) {
            grade = "B";
        } else if(averagePercentage >= 60) {
            grade = "C";
        } else if(averagePercentage >= 50) {
            grade = "D";
        } else {
            grade = "F";
        }

        System.out.println("Total Marks: " + totalMarks);
        System.out.println("Average Percentage: " + averagePercentage);
        System.out.println("Grade: " + grade);

        scanner.close();
    }
}
