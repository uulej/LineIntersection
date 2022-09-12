Line Intersection
The purpose of this exercise is to train you to work with classes and methods.
Estimated workload of this exercise is 45 min.

Description
Please, implement the method intersection(Line) in class Line.
It  must return a Point of intersection of two lines.
Note that lines are defined by linear equations: y = k * x + b.
Line constructor takes k and b coefficients as parameters.
If lines coincide or do not intersect, the method must return null.
It may seem surprising that we use int for arguments and fields of coordinates.
The point is that using double will bring some extra complexity we want to avoid for this basic exercise.
All tests are selected in to induce calculations without remainders.
You may check your result in class Main.

Example



public class Main {
  
   public static void main(String[] args) {
       Line line1 = new Line(1,1);
       Line line2 = new Line(-1,3);
        System.out.println(line1.intersection(line2)); // (1;2)
    }
}
