# Calculator-in-Java
Calculator using Swing in Java
Swing is a GUI widget toolkit for Java. It is part of Oracle's Java Foundation Classes (JFC) – an API for providing a graphical user interface (GUI) for Java programs.Swing was developed to provide a more sophisticated set of GUI components than the earlier Abstract Window Toolkit (AWT). 
Swing was created to address the limitations present in the AWT. It does this through twokey features: lightweight components and a pluggable look and feel. Together they provide anelegant, yet easy-to-use solution to the problems of the AWT. More than anything else, it is thesetwo features that define the essence of Swing. 
 Some of the swing component and its example are:-
JFrame:-   It class implements a window with a title bar and a close control.   
For eg:-JFrame f;
      f=new JFrame("DROP BOX");
  It will create a title bar window named as DROP BOX.
JTextField:-It will create a textfield where user can input string or any character.
For eg:-JTextField t;
      t=new JTextField;
      t.getText();
It will create a new textfield and here the getText will help to get input from user.
JButton:-It will create a Button which may be provided with an actionlistener to create an event.
For eg:-JButton b;
      b=new JButton("1");
It will create a Button named as 1.

Methods or Constructor	Purpose
setLayout()   	It is used for the layout of the frame.
setBounds()	It is used to specify the position of Button in frame                                   It can be used when layout has null as parameter  
setSize()  	It is used to specify the size of button or frame .
setVisible()	It is used for the visibility of the component               depending on the value of parameter.     
addActionListener()	Add an object that listens for action                        events fired by the button.
ActionEvent()   	Constructs an action event object with the help of with the help of which any event taking place on                                  the button will be verified .

Difference between AWT and SWING :-
AWT is an heavyweight whereas the SWING is  lightweight .In AWT the component are designed based on the platform but not on java .hence there will be changes if we switch to different operating system. SWING is pluggable hence its component design does not change on switching top different operating system. Hence it is said that SWING has pluggable look and feel.

