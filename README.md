Download Link: https://assignmentchef.com/product/solved-ece-4122-6122-hmk-2
<br>
<strong><u>ECE 4122</u></strong><u> students</u> need to do Problems 1 &amp; 2. Each problem is worth 50 points.

<strong><u>ECE 6122</u></strong><u> students</u> need to do Problems 1, 2, &amp; 3. Problems 1&amp;2 are worth 33 points, and problem 3 is worth 34 points.

<strong><u>Note:</u></strong>

You can write, debug and test your code locally on your personal computer.  <u>However, the code you</u> <u>submit must compile and run correctly on the PACE-ICE server</u>.




<strong><u>Submitting the Assignment:</u></strong>

Create a zip file for each problem with the files you created to solve the problem.  Each zip file should be named &lt;FirstName_LastName&gt;_Hmk2Prob#.zip, where # is 1, 2, or 3.  You should upload the 3 zip files to the canvas website under the homework assignment.







<u>Grading Rubric</u>

Speed matters in this homework assignment.  For each homework problem, the students with the fastest run times and correct answer will get full credit.




<strong>AUTOMATIC GRADING POINT DEDUCTIONS PER PROBLEM: </strong>

<table width="619">

 <tbody>

  <tr>

   <td width="154"><strong>Element </strong></td>

   <td width="192"><strong>Percentage Deduction </strong></td>

   <td width="272"><strong>Details </strong></td>

  </tr>

  <tr>

   <td width="154">Does Not Compile</td>

   <td width="192">40%</td>

   <td width="272">Code does not compile on PACE-ICE!</td>

  </tr>

  <tr>

   <td width="154">Does Not Match Output</td>

   <td width="192">10%-90%</td>

   <td width="272">The code compiles but does not produce correct outputs.</td>

  </tr>

  <tr>

   <td width="154">Clear Self-Documenting Coding Styles</td>

   <td width="192">10%-25%</td>

   <td width="272">This can include incorrect indentation, using unclear variable names, unclear/missing comments, or compiling with warnings. (See Appendix A)</td>

  </tr>

  <tr>

   <td width="154">Execution Speed</td>

   <td width="192">0%     &lt; 2x fastest5%     &gt;= 2x but &lt; 10x fastest10%   &gt;= 10x fastest</td>

   <td width="272"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>LATE POLICY </strong>

<table width="619">

 <tbody>

  <tr>

   <td width="154"><strong>Element </strong></td>

   <td width="102"><strong>Percentage Deduction </strong></td>

   <td width="363"><strong>Details </strong></td>

  </tr>

  <tr>

   <td width="154">Late Deduction Function</td>

   <td width="102">score –(20/24)*H</td>

   <td width="363"> H = number of hours (ceiling function) passed deadline  note : Sat/Sun count as one day; therefore H = 0.5*H<sub>weekend</sub></td>

  </tr>

 </tbody>

</table>




<h1><u>Problem 1:</u> Matrix Class</h1>

Create a class called <strong>ECE_Matrix</strong> which will be used to hold a dynamic two dimensional array with M rows and N columns of element type <strong>double</strong>.  Your class must support all of the operations in the attached file Hmk2_Test1.cpp.

You must create a header file called <strong>ECE_Matrx.h</strong> and an implementation file called <strong>ECE_Matrx.cpp</strong> which contains your solution to the assignment.

Use the file <strong>data_Problem1.txt</strong> included in the assignment as a test input file for the constructor that takes a data file string as an input.  The numbers are space delimited. You can assume that the input text file does not contain errors such as missing numbers or nonnumeric numbers.

For the + and – operators for two matrices, the resulting matrix should be sized large enough to handle all the elements from both matrices.  For example, a 2×4 matrix added to a 4×2 matrix should yield a 4×4 matrix.

When outputting the matrix with the stream insertion operator, output <u>just the elements</u> and use something similar to the following statement to output the matrix elements with a linefeed at the end of each row. cout &lt;&lt; scientific &lt;&lt; setw(12) &lt;&lt; setprecision(3) &lt;&lt; values[ii][jj]; Output example for a 2×4 matrix:

3.333e-01   3.536e+01   6.537e+02   4.358e+03

1.002e+02   3.537e+01   6.538e+02  1.798e+308
















<h1><u>Problem 2:</u> Largest Product in a Grid</h1>

<a href="https://projecteuler.net/">(</a><a href="https://projecteuler.net/">www.projecteuler.net</a><a href="https://projecteuler.net/">)</a> Write a console program that takes as a <strong>command line argument</strong> the name of a data file.  The data file will contain a <strong>M x N</strong> grid of numbers.  Your program must read in the data file and determine the <strong>largest product</strong> of four adjacent numbers in the same direction (up, down, left, right, or diagonally).  Below is an example of 4 adjacent diagonal numbers in <strong>Red</strong>:




<u>File format:</u>

All values in the text data file are <strong>space</strong> delimited. You can assume that the input data file does not contain errors, such as missing numbers or nonnumeric numbers.  You are free to create as many files as you like and use whatever filenames in order to create a solution.  All the files *.cpp and *.h files you create should reside in a single folder that can be compiled to create the executable.

The first line in the file will have the number of M rows and N columns. The next M lines in the data file will contain the rows of N numbers.

Use the file <strong>data_Problem2.txt</strong> included in the assignment as a test input file.

<u>Output:</u>

Your program should create a text file called <strong><u>output2.txt,</u></strong> in the same directory as the

executable, with just the numerical answer on a single line.

<h1>Problem 3 (ECE 6122 students only): Maximum Path Sum</h1>

<a href="https://projecteuler.net/">(</a><a href="https://projecteuler.net/">www.projecteuler.net</a><a href="https://projecteuler.net/">)</a> By starting at the top of the triangle below and moving to adjacent numbers on the row below, the maximum total from top to bottom is 23.




That is, 3 + 7 + 4 + 9 = 23.

Similar to Problem #1, write a console program that takes as a command line argument the name of a data file.  Your program must read in a triangle of arbitrary size from a data file. The first line will contain the number of levels in the triangle.  A sample data file is attached

(<strong>data_triangle.txt</strong>) to the homework assignment.  Your program must find the maximum sum path through the input triangle starting at the top of the triangle.

<u>Output:</u>

Your program should create a text file called <strong><u>output3.txt,</u></strong> in the same directory as the executable, with just the numerical answer on a single line.










<strong> </strong>

<strong><u>Appendix A: Coding Standards</u></strong> <strong> </strong>

<em><u>Indentation</u></em>:

When using <em>if/for/while</em> statements, make sure you indent 4 spaces for the content inside those.  Also make sure that you use spaces to make the code more readable.

For example:

for (int i; i &lt; 10; i++)

{     j = j + i;

}




If you have nested statements, you should use multiple indentions. Each { should be on its own line (like the <em>for</em> loop) If you have <em>else</em> or <em>else if</em> statements after your <em>if</em> statement, they should be on their own line.

for (int i; i &lt; 10; i++)

{

if (i &lt; 5)    {        counter++;         k -= i;     }           else

{                            k +=1;    }         j += i;

}




<em><u>Camel Case:</u> </em>

This naming convention has the first letter of the variable be lower case, and the first letter in each new word be capitalized (e.g. firstSecondThird). This applies for functions and member functions as well! The main exception to this is class names, where the first letter should also be capitalized.

<em><u>Variable and Function Names</u>:</em>

Your variable and function names should be clear about what that variable or function is. Do not use one letter variables, but use abbreviations when it is appropriate (for example: “imag” instead of

“imaginary”). The more descriptive your variable and function names are, the more readable your code will be.  This is the idea behind self-documenting code.

<em>                 </em>

<em><u>File Headers</u>: </em>

Every file should have the following header at the top

/*

Author: &lt;your name&gt;

Class: ECE4122 or ECE6122

Last Date Modified: &lt;date&gt;




Description:




What is the purpose of this file?




*/

<em><u>Code Comments:</u> </em>




<ol>

 <li>Every function must have a comment section describing the purpose of the function, the input and output parameters, the return value (if any).</li>

 <li>Every class must have a comment section to describe the purpose of the class.</li>

 <li>Comments need to be placed inside of functions/loops to assist in the understanding of the flow of the code.</li>

</ol>







<strong> </strong>

<strong><u>Appendix B: Accessing PACE-ICE Instructions</u></strong> <strong> </strong>

<strong><em><u>ACCESSING LINUX PACE-ICE CLUSTER (SERVER)</u></em></strong>

To access the PACE-ICE cluster you need certain software on your laptop or desktop system, as described below.




<strong><u>Windows Users:</u></strong>

<u>Option 0 (Using SecureCRT)- THIS IS THE EASIEST OPTION!</u>

The Georgia Tech Office of Information Technology (<em>OIT) </em>maintains a web page of software that can be downloaded and installed by students and faculty. That web page is:   http://software.oit.gatech.edu

From that page you will need to install SecureCRT.

To access this software, you will first have to log in with your Georgia Tech user name and password, then answer a series of questions regarding export controls.

Connecting using SecureCRT should be easy.

<ul>

 <li>Open SecureCRT, you’ll be presented with the “Quick Connect” screen.</li>

 <li>Choose protocol “ssh2”.</li>

 <li>Enter the name of the PACE machine you wish to connect to in the “HostName” box (i.e. <em> </em></li>

</ul>

<em>  coc-ice.pace.gatech.edu</em>)

<ul>

 <li>Type your username in the “Username” box.</li>

 <li>Click “Connect”.</li>

 <li>A new window will open, and you’ll be prompted for your password.</li>

</ul>




<u>Option 1 (Using Ubuntu for Windows 10):</u>

Option 1 uses the Ubuntu on Windows program. This can only be downloaded if you are running  Windows 10 or above. If using Windows 8 or below, use Options 2 or 3. It also requires the use of simple bash commands.

<ol>

 <li>Install Ubuntu for Windows 10 by following the guide from the following link:</li>

</ol>




<u>https://msdn.microsoft.com/en-us/commandline/wsl/install-win10</u>

<ol start="2">

 <li>Once Ubuntu for Windows 10 is installed, open it and type the following into the command line:</li>

</ol>




<em>ssh **YourGTUsername**@coc-ice.pace.gatech.edu </em>where **YourGTUsername** is replaced with your alphanumeric GT login. Ex: bkim334

<ol start="3">

 <li>When it asks if you’re sure you want to connect, type in:</li>

</ol>

<em>yes </em>

and type in your password when prompted (Note: When typing in your password, it will not show any characters typing)

<ol start="4">

 <li>You’re now connected to PACE-ICE. You can edit files using vim by typing in:</li>

</ol>




<em>vi filename.cc                </em>OR <em>                  nano vilename.cpp </em>

For a list of vim commands, use the following link:   <u>https://coderwall.com/p/adv71w/basic-vim-commands-for-getting-started</u>

<ol start="5">

 <li>You’re able to edit, compile, run, and submit your code from this command line.</li>

</ol>




<u>Option 2 (Using PuTTY):</u>

Option 2 uses a program called PuTTY to ssh into the PACE-ICE cluster. It is easier to set up, but doesn’t allow you to access any local files from the command line. It also requires the use of simple bash commands.

<ol>

 <li>Download and install PuTTY from the following link: <u>putty.org</u></li>

 <li>Once installed, open PuTTY and for the Host Name, type in:</li>

</ol>

<em>coc-ice.pace.gatech.edu </em>and

for the port, leave it as 22.

<ol start="3">

 <li>Click Open and a window will pop up asking if you trust the host. Click Yes and it will then ask you for your username and password. (Note: When typing in your password, it will not show any characters typing)</li>

</ol>




<ol start="4">

 <li>You’re now connected to PACE-ICE. You can edit files using vim by typing in: <em>vim filename.cc </em></li>

</ol>

<em>            </em>OR <em>                  nano vilename.cpp </em>

<em> </em>

For a list of vim commands, use the following link:

<u>https://coderwall.com/p/adv71w/basic-vim-commands-for-getting-started</u>

<ol start="5">

 <li>You’re able to edit, compile, run, and submit your code from this command line.</li>

</ol>







<strong><u>MacOS Users:</u></strong>. <strong> </strong>

<u>Option 0 (Using the Terminal to SSH into PACE-ICE):</u>

This option uses the built-in terminal in MacOS to ssh into PACE-ICE and use a command line text editor to edit your code.

<ol>

 <li>Open Terminal from the Launchpad or Spotlight Search.</li>

</ol>




<ol start="2">

 <li>Once you’re in the terminal, ssh into PACE-ICE by typing:</li>

</ol>




<em>ssh **YourGTUsername**@ coc-ice.pace.gatech.edu </em>where **YourGTUsername** is replaced with your alphanumeric GT login. Ex: bkim334

<ol start="3">

 <li>When it asks if you’re sure you want to connect, type in:</li>

</ol>

<em>yes </em>

and type in your password when prompted (Note: When typing in your password, it will not show any characters typing)

<ol start="4">

 <li>You’re now connected to PACE-ICE. You can edit files using vim by typing in:</li>

</ol>




<em>vi filename.cc                </em>OR <em>                  nano filename.cpp </em>

For a list of vim commands, use the following link:  <u>https://coderwall.com/p/adv71w/basic-vimcommands-for-getting-started</u>

<ol start="5">

 <li>You’re able to edit, compile, run, and submit your code from this command line.</li>

</ol>




<strong><u>Linux Users:</u></strong>

If you’re using Linux, follow Option 0 for MacOS users.


