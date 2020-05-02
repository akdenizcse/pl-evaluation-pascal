PASCAL
Pascal is an imperative and procedural programming language, designed by Niklaus Wirth as a small, efficient language intended to encourage good programming practices using structured programming and data structuring. It is named in honor of the French mathematician, philosopher, and physicist Blaise Pascal.

Based on Wirth’s book, Algorithms + Data Structures = Programs, Pascal was developed on the pattern of the ALGOL 60 language. Wirth was involved in the process to improve the language as part of the ALGOL X efforts and proposed a version known as ALGOL W. This was not accepted and the ALGOL X process bogged down. In 1968, Wirth decided to abandon the ALGOL X process and further improve ALGOL W, releasing this as Pascal in 1970. On top of ALGOL’s scalars and arrays, Pascal enabled defining complex datatypes and building dynamic and recursive data structures such as lists, trees, and graphs. Pascal has strong typing on all objects, which means that one type of data cannot be converted or interpreted as another without explicit conversions. Unlike most languages in the C-family, Pascal allows nested procedure definitions to any level of depth, and also allows most kind of definitions and declarations inside subroutines (procedure and functions). A program is thus syntactically similar to a single procedure or function.

Pascal allows the programmers to define complex structured data types and build dynamic and recursive data structures, such as lists, trees, and graphs. Pascal offers features like records, enumerations, subranges, dynamically allocated variables with associated pointers, and sets. Also, Pascal allows nested procedure definitions to any level of depth. This truly provides a great programming environment for learning programming as a systematic discipline based on fundamental concepts. So if you have a dilemma about using the Pascal for programming I hope these specifications help you.

SETUP OF PASCAL

There are several Pascal compilers and interpreters available for general use. Among these are

·       Turbo Pascal − provides an IDE and compiler for running Pascal programs on CP/M, CP/M-86, DOS, Windows, and Macintosh.

·       Delphi − provides compilers for running Object Pascal and generates native code for 32- and 64-bit Windows operating systems, as  well as 32-bit Mac OS X and iOS. Embarcadero is planning to build support for the Linux and Android operating systems.

·       Free Pascal − it is a free compiler for running Pascal and Object Pascal programs. Free Pascal compiler is a 32- and 64-bit     Turbo Pascal and Delphi compatible Pascal compiler for Linux, Windows, OS/2, FreeBSD, Mac OS X, DOS, and several other platforms.

·       Turbo51 − It is a free Pascal compiler for the 8051 families of microcontrollers, with Turbo Pascal 7 syntax.

·       Oxygene − It is an Object Pascal compiler for the .NET and Mono platforms.

·       GNU Pascal (GPC) − It is a Pascal compiler composed of a front end to GNU Compiler Collection.

Installing Free Pascal On Linux

The Linux distribution of Free Pascal comes in three forms

· a tar.gz version, also available as separate files.
· a .rpm (Red Hat Package Manager) version.
· a .deb (Debian) version.

After this part I will explain the installation code for the .rmp version

rpm -i fpc-X.Y.Z-N.ARCH.rpm

Where X.Y.Z is the version number of the .rpm file, and ARCH is one of the supported architectures (i386, x86_64, etc.).
Installation code for the Debian version (like Ubuntu):

dpkg -i fpc-XXX.deb

Where XXX is the version number of the .deb file.

 Installing Free Pascal On Mac
 
If you use Mac OS X, the easiest way to use Free Pascal is to download the Xcode development environment from Apple's web site and follow the simple installation instructions. Once you have Xcode setup, you will be able to use the Free Pascal compiler.

Installing Free Pascal On Windows

For Windows, you will download the Windows installer, setup.exe. This is a usual installation program. You need to take the following steps for installation −
· Select a directory.
· Select parts of the package you want to install.
· Optionally choose to associate the .pp or .pas extensions with the Free Pascal IDE.
 
Text Editor

This will be used to type your program. Examples of few editors include Windows Notepad, OS Edit command, Brief, Epsilon, EMACS, and vim or vi.
The name and version of the text editor can vary on different operating systems. For example, Notepad will be used on Windows, and vim or vi can be used on windows as well as Linux or UNIX.
The files you create with your editor are called source files and contain program source code. The source files for Pascal programs are typically named with the extension .pas.
Before starting your programming, make sure you have one text editor in place and you have enough experience to write a computer program, save it in a file, compile it, and finally execute it.
 
EXAMPLE CODES
1. program A;
2. uses crt;
3. var
4. name, surname: string;
5. id: integer;
6. begin
7. clrscr;
8. name:= ‘Gaye’;
9. surname:= ‘Yılmaz’;
10. id:= 165;
11. readln;
12. end.

Now I will explain the code structure about the Pascal then I will write some example code. Pascal programs start with the program keyword with a list of external file descriptors as parameters it is showed in Line 1. Line 2 adds the crt library to the project. Line 3 starting of the variable block under this tag we have to define the variable which we will use in the project. Line 4 and line 5 describe variables that have type string and an integer. Lİne 6 defines the starting of where we will write our code. Line 7 has a clrscr code, this code clears the screen of the output screen. Some values are assigned to the variables which define under the var block from line 8 line 10. Line 11 has the code readln without this code output screen will just a few second but if we write this code output screen must wait to us for pressing the Enter key. Line 12 defines the end of the code. Semicolons in this language separate statements.
 
Example Code 1:

write (‘Hello World’);
This code print the “ Hello World” to the output screen.
writeln(‘Hello world’);
And this code jump the next line after printing “Hello World”

Example Code 2:

for i:=1 t0 10 do begin
    
writeln(‘Hello World’);
end;
This code writes “Hello World ” 10 times on the screen. end; means that this for loop is the end but the code will contain so don’t end the running but end. means that this code wholely done, end the running.

Example Code 3:

if (a=1) then begin
   write (“A”);
end;
This code print “A” if a equals 2.

Example Code 4:

if (a=1) then begin
   write (“A”)
end
else if (a in [2..3])
begin
write(‘B’)
else
begin
write(‘C’);
end;
This code print “A” if a equals 2, print “B” if a between 2 and 3, and if a different from these will print “C”.

Example Code 5:

case (num) of 
               1:write (‘1’);
               2:write(‘2’);
               3:write(‘3’);
else
               write(‘Nor Valid’);
end;
This code evaluates a variable that was named “num” if this variable equals 1 then will print 1 if equals 2 then will print 2, if equals 3 then will print 3. If “num” has another value different from these then this code will print “Not Valid”.
 
Example Code 6:

readln(x);
This code takes the writing thing on the output screen as input and assigns it to the “x” variable.

Example Code 7:

repeat
               write(‘A’);readln(x);
until(x=’B’);
write(‘It is B’);
This code will start printing an “A” to screen and then ask an input value if this value isn’t “B” then it keeps going print “A” if the user enters the ‘B’ then it will print the ‘It is B’.

Example Code 8:

while (a <= b) do
begin 
        write (a); 
        a:=a+1;
end;
This code keeps running while “a” less or equal to b but after every loop a will increase one by one.

Example Code 9:

students: array [1..5] of string;
This code defines an array which only can have 5 string element and 
   
students[1]:=’ABBA’;
this code assigns the “ABBA” value to the first element of the array.

Example Code 10:

type
   Info=record
          
name: String;
          
no,class:integer;
end;
This code defines a record. Records are like an array but they should have at least 3 variables in it. Defining a record doesn’t do in var block it does in type block above the var block. This code defines the record with the name “Info” this record has 3 variables as one String two integers.
var 
student1,student2: Info
And this code defines two variable which has type info now we can use this variable in our code. I f I want to assign a “name “ to 
“Student1” I will use this structure.
Student1.name:=’Gaye’; 

Example Code 11:

var
a,b: integer
procedure sum;
var
tp: integer;
begin
tp:= a+b;
end;
Procedures are like methods in Java. The procedure writes between the var block and begins the statement. procedures also can have their var block. In this var block if a variable writes then it will valid only in the procedure. Procedures call in the program 
with their name like:
begin 
write (‘Number 1:’);readln(a);
write (‘Number 2:’);readln(b);
sum;
end.
This code will sum up to a and b;
 
SOME SPECIFICATIONS ABOUT THE PASCAL

· Pascal has 6 data types these are integer, real, boolean, char, string, and set. Integers are capable of storing integer (whole numbers), real is capable of storing floating-point numbers, boolean is capable of storing the values True or False, char is capable of storing a single character from an ordered character set, the string is capable of storing a sequence or “string” of characters, lastly set is capable of storing equivalent to an array of boolean values.

· In Pascal if you want to do and division you have to be careful because if you write 
a:=4/2;
write(a);
it gives an output like 2.000000000000…E+0001 so you have to write
a:=4/2;
write(a:8:2) 
this code means that use exactly 8 characters for the output and writes the two-digit for after come. If you want to write the default character number for the output. You should write “a:0:2 “ .

· In the Pascal comment line is described with “{…….}” or (*..*).

· Pascal is nor a case sensitive language.

