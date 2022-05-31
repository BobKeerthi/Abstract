abstract class Painting{
    abstract void oilPainting();

    public  void PencilDrawing(){
        System.out.println("I love draw to Pencil Drawing");
    }
    static void Watercolour(){
        System.out.println("I love draw to Water colour");

    }
}
 class Crayons extends Painting {


    void oilPainting(){
         System.out.println("I love draw to oil Painting");

     }

       public static void main(String[] args) {
        Painting obj=new Crayons();
        obj.oilPainting();
        obj.PencilDrawing();
        Watercolour();
    }}
