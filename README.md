Download Link: https://assignmentchef.com/product/solved-cse3122-final-project
<br>
Your makeup project will be similar to HW1, so this project will not depend on any other project s. You will extent the original SPIM OS with some systems calls, you will also write a number of assembly programs.

The operating system that comes with SPIM is very primitive. It only supports a few trivial system calls, such as reading and printing, which are defined in /CPU/syscall.h .

First, download and study the SPIM package very carefully. Then, you will write and test the following MIPS assembly files.

<ol>

 <li>asm : Reads from standard input positive integers (negative integer indicates the end of list), then sorts the integers in increasing order and prints the sorted integers to standard output.</li>

 <li>asm : produces 100 random positive integers and prints them to the standard output. The last integer is a negative number.</li>

 <li>asm : Reads from standard input an integer, then reads a number of positive integers. Makes a search on the list. prints the result to the standard output.</li>

 <li>asm: works like UNIX type command. Prints the contents of a file to the standard output. At the end prints -1.</li>

 <li>asm: very simplified ls command of UNIX. prints the contents of the directory to the standard output. Note that there is only one directory in our system.</li>

 <li>asm: You will write a shell program that will be very similar to tcsh. Note that current SPIM OS does not support many things such as file processing (read, write, create) and multiprocessing. You will have to add many system calls to the new OS. You will change the SPIM source code in two places: /CPU/syscall.h and</li>

</ol>

/CPU/syscall.cpp . Do not modify any other SPIM code other than these files. Your shell will include the following features

<ol>

 <li>Standard piping such as random | sort | search or type a.txt | sort</li>

 <li>Standard redirection such as sort &gt; res.txt &lt; input.txt</li>

 <li>Back ground tasks such as type a.txt&amp;</li>

 <li>Standard screen and keyboard read/write.</li>

</ol>

Below are the instructions for homework submission

<ol>

 <li>Download and Install Vmware Player from official site.</li>

 <li>Download and install our virtual machine from https://drive.google.com/open?id=1YppX3lNkyTsHV_lvA4w9TomNCUkpLeEg 3. Your submission includes only the files below

  <ul>

   <li>ProjectReport.pdf: your detailed project report that includes o How you implemented piping, redirection, standard input and output, screen input and output

    <ul>

     <li>How you added systems calls to the new OS. For each system call, include information about the functionality and the parameters</li>

     <li>How you handled the programs running in parallel o How you handled the file creation, opening, closing, etc.</li>

     <li>Any other points that you like to mention</li>

    </ul></li>

   <li> shell.asm</li>

   <li> sort.asm, random.asm, search.asm, ls.asm, type.asm</li>

   <li> syscall.cpp and syscall.h</li>

  </ul></li>

</ol>

















