# JavaFx-PraktikumModul6


    package Semester3;
  

    /**
     *
        *@author Asri Lestari

    */

    import javafx.application.*;
    import javafx.stage.*;
    import javafx.scene.*;
    import javafx.scene.shape.*;
    import javafx.scene.text.Font;
    import javafx.scene.text.Text;


    public class PraktikumModul6 extends Application{ 
    
    @Override 
    public void start(Stage stage) { 
    //Creating a line object 

    Line line  = new Line (20,20,150,20); 
    Line line2 = new Line (150,20,150,60);
    Line line3 = new Line (20,20,20,60);
    Line line4 = new Line (20,60,150,60);

    Line line5 = new Line (20,80,150,80);
    Line line6 = new Line (150,80,150,120);
    Line line7 = new Line (20,80,20,120);
    Line line8 = new Line (20,120,150,120);

    Line line9  = new Line (20,140,150,140);
    Line line10 = new Line (150,140,150,180);
    Line line11 = new Line (20,140,20,180);
    Line line12 = new Line (20,180,150,180);

    Line line13 = new Line(20,200,150,200);
    Line line14 = new Line (150,200,150,240);
    Line line15 = new Line (20,200,20,240);
    Line line16 = new Line (20,240,150,240);

    Line line17 = new Line(170,2,400,2);
    Line line18 = new Line (400,2,400,240);
    Line line19 = new Line (170,2,170,240);
    Line line20 = new Line (170,240,400,240);

    Text text = new Text();

                text.setFont(new Font(15));
                text.setX(30);
                text.setY(45);
                text.setText("Kotak");
             
                Text text2 = new Text();
                text2.setFont(new Font(15));
                text2.setX(30);
                text2.setY(105);
                text2.setText("Jajar Genjang");
                
                Text text3 = new Text();
                text3.setFont(new Font(15));
                text3.setX(30);
                text3.setY(165);
                text3.setText("Tanggal Sekarang");
                
                Text text4 = new Text();
                text4.setFont(new Font(15));
                text4.setX(30);
                text4.setY(225);
                text4.setText("Jam Sekarang");
                
                Text text5 = new Text();
                text5.setFont(new Font(20));
                text5.setX(250);
                text5.setY(130);
                text5.setText("Output");
 
    //Creating a Group 

    Group root = new Group(line,line2,line3,line4,line5,line6,line7,line8,
                       line9,line10,line11,line12,line13,line14,line15,line16,
                        line17,line18,line19,line20,text,text2,text3,text4,text5); 

    //Creating a Scene 
    Scene scene = new Scene(root, 500, 300); 
    //Setting title to the scene 
    stage.setTitle("Sample application"); 
    //Adding the scene to the stage 
    stage.setScene(scene); 
    //Displaying the contents of a scene 
    stage.show(); 
    } 
    public static void main(String args[]){ 
    launch(args); 
    } 
    }
