Smooth Car Animation Project

This project is a simple car animation written in C using the graphics.h library. The animation simulates a car moving smoothly across the screen with user input to control the speed and direction.
Features

    Smooth car movement with adjustable speed and direction
    Simple graphical representation of a car, trees, and rocks
    Game over screen with a beep sound

Prerequisites

    Turbo C++ compiler
    graphics.h library
    dos.h library
    windows.h library
    conio.h library
    math.h library

Setup and Installation

    Install Turbo C++
        Download and install Turbo C++ from a reliable source.

    Configure Turbo C++
        Ensure that Turbo C++ is properly configured to use the graphics.h library. This usually involves setting the correct path for the BGI (Borland Graphics Interface) files.

    Compile and Run
        Open the Turbo C++ IDE.
        Copy the provided code into a new project file.
        Compile and run the project.

How to Use

    Start the Program
        Run the program from the Turbo C++ IDE. The graphical window will open and the car animation will start.

    Control the Car
        Use the following keys to control the car:
            a: Decrease speed
            d: Increase speed
            Spacebar: Stop the car

    End of Animation
        The animation will end with a "GAME OVER" screen accompanied by a beep sound.

Code Explanation
Libraries Used

    graphics.h: Used for graphical functions.
    dos.h: Used for delay functions.
    math.h: Used for mathematical functions.
    conio.h: Used for console input/output.
    windows.h: Used for the Beep function.

Main Function

    Initializes the graphics mode and window.
    Sets up the initial conditions for the car's movement.
    Enters a loop where the car's position is updated based on user input.
    Draws the car, trees, and rocks in the window.
    Ends with a "GAME OVER" screen and sound.

User Input

    The program checks for keyboard input using kbhit() and getch().
    Adjusts the car's speed and direction based on the input.

Drawing Functions

    The car is drawn using line, rectangle, and circle functions.
    Trees and rocks are drawn as static objects in the background.

Notes

    This program is created for educational purposes to demonstrate basic graphics programming in C.
    Ensure that the BGI files are correctly located in the specified directory for the graphics functions to work.

Author

    Azmain Inquaid Haque Turjo

License

    This project is licensed under the MIT License.

Feel free to explore and modify the code to add more features or improve the animation!
