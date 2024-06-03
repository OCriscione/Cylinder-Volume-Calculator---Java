import javax.swing.JOptionPane;
import static java.lang.Math.pow;

public class Project3_Ocriscione {
    public static void main(String[] args) {
        // Variables for cylinder
        int diameter, height;
        double radius;
        double circumference, areaOfCircle, cylVolume;
        String name;
        final double PI = 3.1415926;

        // All user inputs
        String input;
        // User's name (user input) with JOptionPane
        name = JOptionPane.showInputDialog("Enter your name and select Ok.");

        // Tells user how many inputs of data are required
        JOptionPane.showMessageDialog(null, "Hello, " + name + ". You have two more values to provide.", "Greeting!", JOptionPane.INFORMATION_MESSAGE);

        // Cylinder diameter (user input) with JOptionPane
        input = JOptionPane.showInputDialog("Enter the integer diameter of a cylinder. ");
        diameter = Integer.parseInt(input);

        // Cylinder height (user input) with JOptionPane
        input = JOptionPane.showInputDialog("Enter the integer height of the cylinder. ");
        height = Integer.parseInt(input);

        // Cylinder calculations
        radius = (diameter / 2.0);
        circumference = (PI * diameter);
        areaOfCircle = (PI * pow(radius, 2));
        cylVolume = (areaOfCircle * height);

        // Output with JOptionPane
        String output =
                "The radius is " + radius + ". \n" +
                        "The diameter is " + diameter + ". \n" +
                        "The height is " + height + ". \n" +
                        "The circumference is " + circumference + ". \n" +
                        "The area of the base is " + areaOfCircle + ". \n" +
                        "The volume of the cylinder is " + cylVolume + ". \n";

        JOptionPane.showMessageDialog(null, output, "Results", JOptionPane.INFORMATION_MESSAGE);
    }
}
