//inhitence

public class Automobile 
{
    public void start()
    {
        System.out.println("e s r");
    }
    public void stop()
    {
        System.out.println("e stop r");
        
    }
    public void seatings(){
        
    }
}
class Car extends Automobile{
    public void No_of_tyres()
    {
        System.out.println("T a 4 types");
    }
    public void fiel(){
        System.out.println("petrol");
    }
    public void fuel(String fuel)
    {
        System.out.println("Also run on diesel");
    }
    public void seatings(){
        System.out.println("4 seating");
    }
}
class bike extends Automobile{
    public void No_of_types()
    {
        System.out.println(" there are 2 types");
    }
    public void fuel(){
        System.out.println(" petrol");
    }
    public void seatings(){
        System.out.println("2 seating");
    }
}
