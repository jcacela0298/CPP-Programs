I worked on a payroll tracker program using C++ that utilizes an Object-Oriented Design to capture and display payroll information about employees from your input in Terminal, and it then sends the calculated output to a text file called WageOutput.txt.
.
.
.
.
.
During this project, I learned more specifically about C++ output to a text file, Class syntax, public and private access modifiers, getter functions, how private methods often don't need prototypes because: "private member functions declared within a class are inherently accessible within the class scope, so the compiler doesn't need to know about them (via prototypes) before they're defined. In other words, when you define member functions inside a class declaration, they are implicitly declared inline within the class scope", in addition to learning more about the scope resolution operator, constructors and destructors, and overall C++ syntax.

Most all the updates, compared to the WageObjects program, were in the last two functions, main and the printEmployee function. 
I had to make sure to include the file stream file header:

#include <fstream>   // file I/O
