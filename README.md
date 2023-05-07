Download Link: https://assignmentchef.com/product/solved-exercise-1-implementing-a-heap
<br>
Due by the end of your Week‐2 laboratory class.                                                                               (2 marks)

This exercise is to be done during your week 3 laboratory class. When you complete the exercise show your work to your lab tutor to have your work marked. The marking is based mainly on correct implementation and code readability. You should implement your code in one file (e.g. ex2.cpp, ex2.c, ex2.java). Make sure your program has a header comment block containing the name of the exercise, your name and your student login (e.g. jfk01). You may implement your solution in C, C++, java or Python.




For this exercise you are to implement a heap, using an array as shown in the lectures. The heap will be built by repeatedly:




<ol>

 <li>Reading an input from a file (in this case an integer)</li>

 <li>Adding it after the last element of the current heap</li>

 <li>Shifting it up into the correct position.</li>

</ol>




At the end of all the inputs you are to print out the first five elements of the heap array. Your heap should be able to hold 100 integers. A pseudo‐code outline for the program is given below:




<strong>    Begin main </strong>

<strong>        display a prompt for the file name </strong>

<strong>        read in the file name         try to open the file         if the file fails to open </strong>

<strong>            print an error message on the screen and exit         fi </strong>

<strong>        while we can read an int from the file             insert the int into the array         elihw </strong>

<strong>        makeheap() </strong>

<strong>        close the file         for i = 1 to 5 </strong>

<strong>            print the i<sup>th</sup> element of the heap         rof     End main </strong>




Do not implement the heap using a class or with STL. The heap must be implemented using a fixed size array of ints (500 entries should be enough). The heap array and the index to the last item in the heap should be global variables.




Information on the above functions is available from moodle and the week 2 lecture notes.




When you are finished, test your program using the provided text file named “Ex2.txt” and show your code and the output to your lab tutor to receive your mark. Also, submit your file via unix (banshee) using the submit command below.




<strong>$ submit -u <em>login </em>-c CSCI203 –a ex2 <em>filename </em></strong>

<strong><em> </em></strong>

where ‘<strong><em>login</em></strong>‘ is your UNIX login ID and ‘<strong><em>filename</em></strong>’ is the name of your file.




.