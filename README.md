## MARS Assembler
[MARS][1] is a lightweight interactive development environment (IDE) for programming in MIPS assembly language, intended for educational-level use with Patterson and Hennessy's Computer Organization and Design.

MARS has been jointly developed by [Pete Sanderson][4] (programming) and [Ken Vollmar][5] (details and paperwork).

## Purpose of this repo
This project is a fork of MARS 4.5. Pull requests are very much welcomed.

## Documentation (included in the repo)
 - Go to the [documentation][7].
 - In order to run or compile this project **you must have the Java 1.8 (or later) SDK installed on your computer**.

## How to run MARS
 - **Desktop**:
   - Save the jar file on the desktop
   - Run MARS by double-clicking the icon
   
 - **Command line using jar file**:
   - Save the jar file in some folder
   - Rename the jar file to "Mars.jar" for convenience
   - Open a command line shell in that folder
   - Run MARS with the command `java -jar Mars.jar`
   
 - **Command line using Java classes**:
   - Save the jar file in some folder
   - Rename the jar file to "Mars.jar" for convenience
   - Open a command line shell in that folder
   - Rename the jar file to "Mars.jar" for convenience
   - Extract MARS files with the command `jar -xf Mars.jar`
   - Run MARS with the command `java Mars`

## How to compile
 - **Windows**: execute "CreateMarsJar.bat" file to generate an executable.
 - **GNU/Linux** and **Mac**: `find . -name "*.java" | xargs javac` then execute the "CreateMarsJar.sh" to generate an executable. If you can't due of permissions, run `chmod +x CreateMarsJar.sh`.

## License
[MIT][2]. Check the [LICENSE][3] file. All the credits go to the original developers.

  [1]: http://courses.missouristate.edu/KenVollmar/MARS/index.htm
  [2]: http://www.opensource.org/licenses/mit-license.html
  [3]: https://github.com/adolphenom/MARS_Assembler/blob/master/LICENSE
  [4]: http://faculty.otterbein.edu/PSanderson/
  [5]: http://courses.missouristate.edu/KenVollmar/
  [6]: http://courses.missouristate.edu/KenVollmar/MARS/download.htm
  [7]: http://courses.missouristate.edu/KenVollmar/MARS/Help/MarsHelpIntro.html

