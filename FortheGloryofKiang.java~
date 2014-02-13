public class FortheGloryofKiang
{
  public static void main(String[] args)
  {
    String[][] KiangArray = new String[3][9];
    int player1 = 1; //makes 3 ints to be placemakers for the games for 3 players
    int player2 = 2;
    int player3 = 3;
    
    boolean gameOver = false;
    
    while(!gameOver)
    {
      //check if any possibilty that someone won (this is be ginormous)
      Table(KiangArray);
      //let first player go
    }
  }
  public static void Table(String[][] array)
  {
    System.out.println("Tic-Tac-Toe game");
    for(int row = 0; row < array.length; row++) //goes through the row after making columns
    {
      for(int column = 0; column < array[row].length; column++){
        System.out.print("| |"); // will print down 3 before changing rows
        if(column%3-2==0) //jesus this took a lot of guessing
        {
          System.out.print("        "); //makes 3 separate plots to make a 2d rendering of the 3d game
        }
      }
      System.out.println("");// print new line so we can start a new column
    }
  }
  public static void player1()
  {
    KiangArray[2][6] = "1";
    Table(KiangArray);
  }
}