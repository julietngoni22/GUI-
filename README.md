Creating basic frame(Form) using JFrame class
JFrame is located in the javax.swing package
Making use of JFrames method to initialize the created frame
Create A java class library
name it BasicFrame
create a package and name it secure.all.co.za
create a class and name it Frame
make the class to extend JFrame (public class Frame extends JFrame)
Create a constructor for the frame (public Frame(){})
inside the constructor set attributesof the frame to make it visible
1. setTittle("GUI);
2. setSize(100,50);
3. setDefaultLookAndFeelDecorated(true|);
4. setResizable(true);
5. setDefaultCloseOperation(EXIT_ON_CLOSE);
6. setForeground(color.RED);
7. setVisible(true);

 righ click on the main project and (clean and build), now you have a jar
 select the file tab,dlist, then you will see your Frame class

 Now create a Main class
 import the jar file to the libraries of the main class
 on the main method, declare a Frame and instatiate (Frame fr = new Frame();)
 run the code
