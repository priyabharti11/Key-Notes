# Key-Notes
Basic Fundamentals

<h3>(1) Framework and Library Difference</h3>
<h6> Reference : "Difference Between Library and Framework".<br>
                  Nov 17, 2020. https://www.c-sharpcorner.com/. Accessed 30 August 2022.<br>
                  https://www.c-sharpcorner.com/UploadFile/a85b23/framework-vs-library/
</h6>
<img align="center" width="100%" src = "https://user-images.githubusercontent.com/91482888/187289008-ce999a3b-643f-4306-afc2-02a3612b953f.png"/>

<h3>Key Difference and Definition of Library and Framework :</h3> 
<h5>
- The key difference between a library and a framework is "Inversion of Control".<br>
- When you call a method from a library, you are in control. <br>
- But with a framework, the control is inverted: the framework calls you.
</h5>
<h3> Framework :</h3>
 
<h5><p> - In a framework, all the control flow is already there and there are many predefined white spots that we should fill out with our code.<br><br>
        - A framework is normally more complex. It defines a skeleton where the application defines its own features to fill out the skeleton.<br><br>
        - In this way, our code will be called by the framework appropriately.<br><br>
        - A framework can contain libraries. A framework will usually include many libraries to make your work easier.
   </p> 
</h5>

<h3> Libraries :</h3>
<h5> <p>
- A library performs specific, well-defined operations.<br><br>
- A library is just a collection of class definitions. <br><br>
- The reason is it simply code reuse, in other words, gets the code that has already been written by other developers.<br><br>
- The classes and methods normally define specific operations in a domain-specific area. <br><br>
- For example,there are some libraries of mathematics that can let developers just call the function without redoing the implementation of how an           algorithm works. <br><br>
- A library will usually focus on a single piece of functionality that you access using an API.<br><br> 
- You call a library function, it executes some code and then the control is returned to your code. </p></h5>

<h3>(2) OS Study Content : https://www.scaler.com/topics/operating-system/process-synchronization-in-os/</h3>
<h3>(3) SQL Cross join example Study Content : https://www.sqlshack.com/sql-cross-join-with-examples/</h3>
<h3>(4)SQL Join : https://www.interviewbit.com/sql-joins-interview-questions/</h3>
 
<h3> What is Bootloader ?</h3>
<h5> <p>
- A boot loader, also called a boot manager, is a small program that places the operating system (OS) of a computer into memory.<br><br>
- When a computer is powered-up or restarted, the basic input/output system (BIOS) performs some initial tests, and then transfers <br>
  control to the Master Boot Record (MBR) where the boot loader resides. <br><br>
- Most new computers are shipped with boot loaders for some version of Microsoft Windows or the Mac OS. <br><br>
</p>
</h5>
<h5>
<p>
<h4>Linux Bootloader</h4>

- If a computer is to be used with Linux, a special boot loader must be installed.
- For Linux, the two most common boot loaders are known as LILO (LInux LOader) and LOADLIN (LOAD LINux). 
- An alternative boot loader, called GRUB (GRand Unified Bootloader), is used with Red Hat Linux. 
- LILO is the most popular boot loader among computer users that employ Linux as the main, or only, operating system. 
- The primary advantage of LILO is the fact that it allows for fast boot-up. 
- LOADLIN is preferred by some users whose computers have multiple operating systems, 
  and who spend relatively little time in Linux. 
- LOADLIN is sometimes used as a backup boot loader for Linux in case LILO fails. 
- GRUB is preferred by many users of Red Hat Linux, because it is the default boot loader
  for that distribution.
</p>
</h5>

<h3> Java Exception Handeling Questions : https://www.digitalocean.com/community/tutorials/java-exception-interview-questions-and-answers</h3>
<h3>Try, Catch, Throw, Throws, Finally Block : https://www.geeksforgeeks.org/try-catch-throw-and-throws-in-java/</h3>

<p>
- An unchecked exception (also known as an runtime exception) in Java is something that has gone wrong with the program and is unrecoverable. Just because this is not a compile time exception, meaning you do not need to handle it, that does not mean you don't need to be concerned about it.</p>

 <h3>
 Null Pointer exception:</h3>
 
- This type of exception occurs when you try to access an object with the help of a reference variable whose current value is null or  empty.
    
      // Program to demonstrate the NullPointerException
      class SampleNullPointer {
        public static void main(String args[]) {
           try {
              String a1 = null; // null value
              System.out.println(a1.charAt(0));
           } catch(NullPointerException e) {
            System.out.println("NullPointerException is found in the program.");
        }
      }
      }
   <br>
   
   
  <h3>
  Array Out Of Bound Exception :</h3>
 - This type of exception occurs when you try to access an array with an invalid index value. The value you are providing is either negative or beyond the length of the array.

    
       // Program to demonstrate the ArrayIndexOutOfBoundException
       class sample_ArrayIndexOutOfBound {
        public static void main(String args[]) {
        try {
            int b[] = new int[6];
            b[8] = 2; // we are trying to access 9th element in an array of size 7
        } catch(ArrayIndexOutOfBoundsException e) {
            System.out.println ("The array index is out of bound");
        }
       }
       }
   <br>

