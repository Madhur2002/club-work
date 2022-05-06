# club-work
creating a registration form using python tkinter

Description/Explanation of code of mandatory task:

In the code I have used python and created a bank employee registration form using tkinter. It is a GUI interface and Tkinter is a package for Python to use the Tk GUI toolkit. 
Initially we have imported the tkinter file and after that we have used an important concept of geometry manager. Without that the widgets on the screen won’t appear. We can use it in three ways grid, pack, place. In our tutorial we have used place as geometry. Then comes out main code in which we have defined labels to display the name of fields in our form like customer name, customer id, branch etc. To get the value of each field we have used ‘entry’ widget which works same as HTML input tag. We have defined the values of x and y which define the input label positions on x and y plane.  In the field of account – type we have also used radio buttons which are set of buttons which can be pressed only once and user can select their account type i.e., saving or non-saving. To set the amount field we have used another interesting widget scale which is a linear slider providing exact value of current setting with starting and ending points.
At the end we have used buttons which are used to insert a new value, update an existing one, delete some value or search any value.
root. mainloop is a method on the main window which we execute when we want to run our application. This method will loop forever, waiting for events from the user, until the user exits the program – either by closing the window, or by terminating the program with a keyboard interrupt in the console.
