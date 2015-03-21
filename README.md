# morseCodeTranslator
Java GUI application to translate natural languages to Morse code.

Morse Code v.2.0

Morse Code Table

	A  *-          N  -*          1  *----       
        B  -***        O  ---         2  **---       
        C  -*-*        P  *--*        3  ***--       
        D  -**         Q  --*-        4  ****-       
        E  *           R  *-*         5  *****       
        F  **-*        S  ***         6  -****       
        G  --*         T  -           7  --***       
        H  ****        U  **-         8  ---**       
        I  **          V  ***-        9  ----*       
        J  *---        W  *--         0  -----       
        K  -*-         X  -**-               
        L  *-**        Y  -*--               
        M  --          Z  --**        
Notes
> The program uses . instead of *
> The program doesn't support special characters such as: , . / \ - + = ...
> Basically, you type words in the first text field and then press enter to get the equivalent Morse code.


Developed and deployed by Will Soares.
Thanks!

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "MorseCode.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

