Download Link: https://assignmentchef.com/product/solved-csc3320-lab-2-part-1-and-2
<br>
5/5 - (1 vote)

Purpose: Learn use the man utility to get help on using other Unix utilities. Practice with the basic utilities for managing files and directories in a terminal.

<ul>

 <li> Connect to snowball by typing the following command and press “Enter”.<pre>ssh <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f4b79599848187bdb0b4879a9b8396959898da9787da938781da919081">[email protected]</a></pre>Part A: Try to use the man utility.The man utility can provide the on-line copies of the original UNIX documentation for the other utilities. In the manual page, the first part is the functionality of a utility, the second part is the synopsis, the third part is the description and lists different features of a utility with different options. Then please follow the steps to learn some options provided by cat.</li>

</ul>

<ol>

 <li>(1)  Check the manual page cat by typing the command below and press “Enter”.man cat</li>

 <li>(2)  The terminal only displays one window of the manual page. You can scan through the whole manual page by press “f” or SPACE to forward one window, and “b” to backward one window. Or you can press “h” to find out more commands to scan through the manual page.</li>

 <li>(3)  Check the description for option -n. You may find the description as below:</li>

 <li>(4)  Check the description for option -s. You may find the description as below:</li>

</ol>

(5) Quit the manual page by press “q”Part B: Unix basic commands on managing the files and directories.

(1) Make sure that you are connected to snowball successfully. Then go to your home directory by typing the following command, followed by pressing “Enter”.

cd ~

(2) Display current working directory:

pwd

– Question A): What is the working directory? Please write down the full path

(3) List the content in current working directory:

ls

(4) Create a new folder “csc3320” in your home directory:

<pre>      mkdir csc3320</pre>

(5) Repeat step (3).

– Question B): What is the difference in the output compared to the output from step (3) ? Describe what the difference is.

(6) Navigate to “csc3320”:

cd csc3320

(7) Display current working directory.

– Question C): Which command should be typed?

(8) Create a new folder called “lab2” in csc3320.

– Question D): Which command should be typed?

(9) Go to the newly created “lab2” folder.

– Question E): Which command should be typed?

(10) Create a new file called “myLab2.txt” and put your own name in this file by

typing the command below:

cat &gt; myLab2.txt &lt;Enter&gt;My name is FirstName LastName &lt;Enter&gt; &lt;Ctrl-D&gt;

Note : &lt;Enter&gt; means press the Enter key; &lt;Ctrl-D&gt; means hold Ctrl and press D– Question F): There is a special character “&gt;” between “cat” and “myLab1.txt”.

What does this character do? And why we need to press “Ctrl-D” at the end of input?

(11) Display the content in “myLab2.txt” with line numbers by typing the command below and press “Enter”.

<pre>      cat -n myLab2.txt</pre>

– Question G): Attach a screenshot of the output.

(13) Go to your home directory using the absolute path by typing the command below and press “Enter”.

cd &lt;Answer from step(2)&gt;Note : Please replace the blue part with the answer from step (2)

– Question H): Then issue the command pwd again. Attach a screenshot of the output.

Purpose: Practice with the basic utilities for managing files and directories in terminal.

<ul>

 <li> Lab2_FirstNameLastName.pdf or Lab2_FirstNameLastName.doc) to Google Classroom no later than 11:59 pm a week from the day are taking this lab session.Open your terminal and connect to snowball. Change your directory to your home directory (cd ~ ), and then create a new directory named as “Lab2_P2” (mkdir Lab2_P2). After that, go to directory Lab2_P2 (cd Lab2_P2) and download a test file by the following command (internet access required):cp /home/frondel1/public/RealEstate.csv .Be sure it succeeds using “ls” to see the file name “RealEstate.csv” listed.Then please write the commands you will issue to complete the following tasks step by step. (You cannot use cd to change the working directory during the steps except step (9). Each task requires only one command)(1) You may be curious about what information is stored in this file. So please use cat to display the content in “RealEstate.csv ” using a relative pathname.(2) We know that cat is good for showing the content of a small file. But since the file contains many lines, maybe you still cannot find out what information this files stores after step (1). So please use head to list the first three lines in “RealEstate.csv “.(3) Use wc to check the number of homes sold out in “RealEstate.csv “. (4) Finish the task in step (3) by using the cat command.</li>

</ul>

(5) Use mkdir to create a new directory “public” under your own home directory using relative pathname.

(6) Copy “RealEstate.csv” into your “public” directory and name it as “myRealEstate.csv”.

(7) Display the absolute pathname for current working directory.

(8) Check the existence of “myRealEstate.csv” using ls with an absolute pathname.

(9) Go into your “public” directory using relative pathname.

(10) Use mkdir to create a file structure as below in your “Public” directory using relative pathnames.

Public

Regular

(11) Rename the directory “Regular” as “Others”.

(12) Use cp to copy directory “Lab2_P2” from your home directory to “Lab2” using relative pathname.

(13) Remove the directory “Lab2_P2” which locates at your home directory. (14) Use history to list the commands you previously typed.

(15) Store the last 50 commands you typed neatly into a file “Lab2_2.txt”, one command per line and submit it in Google Classroom.