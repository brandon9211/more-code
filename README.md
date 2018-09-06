# more-code
Legalos
using System;

public class Program
{
public static void Main()
{
    //creating and assigning variables
    int arrows = 3;
    int enemies = 3;
    int percent = 0;
    bool legalaslives;

    bool test = false;

    test = true;

    if (test) {

    }
    //setting up for loop with integers
    for(int numberOfArrows = 0; numberOfArrows <= 3; numberOfArrows++)
{
    //removing a value each time the for loop occurs
    //remove value from arrows count and enemies count
    arrows--;
    enemies--;

    Console.WriteLine("How many arrows are left?" + arrows);
    Console.WriteLine("How many enemies are left?" + enemies);
}

    if(enemies == 0) {
    Console.WriteLine("Legolas lives");
} else {
    Console.WriteLine("Legalos Dies");
}

    if (enemies == 0) {
    //do this
} else if(enemies == 1){
} else if (enemies == 2){}

    Console.WriteLine("Legolas lives");
}
}
}
