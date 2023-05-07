Download Link: https://assignmentchef.com/product/solved-introduction-to-computer-organization-final-exam-605-204
<br>



<ul>

 <li>As described by Hennessy and Patterson ,the modern computer is composed of five (4)    classic hardware components.  Given one, list the other four:</li>

</ul>




___________________________ ,    ___________________________ , and <u>OUTPUT</u>,




___________________________ ,    ___________________________ .







<ul>

 <li>The hardware above provides the four <strong>basic</strong> <strong>functions</strong> that every computer performs.</li>

</ul>

(4)        What are these functions ?




data _______________________ ,     data __________________________ ,




data _______________________ ,     and ___________________________ <strong>. </strong>







<ul>

 <li>The <strong>integer </strong>word length and register size of the MIPS machines is (1)

  <ol>

   <li>8 bits. B) 1 byte.        C) 3 bytes.       D) 32 bits.</li>

  </ol></li>

</ul>







<ul>

 <li>How are <strong>negative integer numbers </strong>represented on the MIPS machines ?</li>

</ul>

(1)

<ol>

 <li>B) 1’s complement.   C) 2’s complement.   D) negative integers are not allowed.</li>

</ol>







<ul>

 <li>Today, assembly language programs are more efficient than compiled high-level language (1)             programs, such as C++, for the same large accounting applications.</li>

</ul>

( True / False )




<ul>

 <li>1,099,511,627,776 bytes is known as: A) Gigabyte            B) Terabyte     C) Petabyte</li>

</ul>

(1)




<ul>

 <li>Given this hexadecimal representation of a 16-bit Two’s Complement number:</li>

</ul>

(1)                   <strong>753B </strong>




Is the value    A) less than zero      B) equal to zero      C) greater than zero       D) invalid










<ul>

 <li>Match these people with their noted accomplishments :</li>

</ul>

(4)

<table width="387">

 <tbody>

  <tr>

   <td width="240">                    Alan Turing ____</td>

   <td width="147">A) – ENIAC</td>

  </tr>

  <tr>

   <td width="240">                              L0pht ____</td>

   <td width="147">B) – TCP / IP</td>

  </tr>

  <tr>

   <td width="240">            J. Presper Eckert ____</td>

   <td width="147">C) – computing theory</td>

  </tr>

  <tr>

   <td width="240">              Vinton G. Cerf ____</td>

   <td width="147">D) – Internet Security</td>

  </tr>

 </tbody>

</table>







<ul>

 <li>What is the purpose of each of the following MIPS assembler directives:</li>

</ul>

(4)

<strong>.globl</strong> ____________________________________________________________




<strong>.text    </strong>____________________________________________________________




<strong>.word </strong>____________________________________________________________




<strong>.asciiz</strong> ____________________________________________________________







<ul>

 <li>Convert <strong>435</strong>   to a binary fraction ( total of 8 bits)  For example 0.75 = 0.1100 0000 (3)</li>

</ul>




























<ul>

 <li>The MIPS subroutines generally have <strong>PROLOG</strong>  What is the purpose of this code ?</li>

</ul>

(2)

__________________________________________________________




__________________________________________________________







<ul>

 <li>The MIPS multiply hardware stores the 64 bit product in two registers, HI and LO.</li>

</ul>

(1)        What does it mean when the value in the HI register is minus one (-1) ?




_________________________________________________________________







<ul>

 <li>Which of the following <strong>must be</strong> performed by <strong>every</strong> assembler :</li>

</ul>

(1)

<ol>

 <li>Provide relocatable object code.</li>

 <li>Process a program in two passes.</li>

 <li>Assign machine memory addresses to symbol labels.</li>

</ol>

<ul>

 <li>Floating point arithmetic has problems different from integer arithmetic.</li>

</ul>

(3)        Which of these floating point arithmetic statements are <strong>True </strong>and which are<strong> False</strong>?




<ol>

 <li>Addition of two positive numbers will never overflow.</li>

</ol>




<ol>

 <li>Addition of a positive and a negative number will never overflow.</li>

</ol>




<ol>

 <li>Multiplication of a positive and a negative number will never overflow.</li>

</ol>







<ul>

 <li>What is the <strong>primary</strong> reason a two-pass assembler is necessary rather than a one-pass assembler ?</li>

</ul>

(1)

<ol>

 <li>Instructions may vary in length.</li>

 <li>Symbols need to be stored in the symbol table.</li>

 <li>Symbols may be defined before they are used as operands.</li>

 <li>Symbols may be used as operands before they are defined.</li>

</ol>







<ul>

 <li>Computer Arithmetic has a problem called ‘<strong>Overflow</strong>’. Simply what is this problem ?</li>

</ul>

(1)

___________________________________________________________________







<ul>

 <li>Generate the hexadecimal<strong> <u>object machine code</u></strong> for each line in the following <strong>MIPS</strong> source  (20)               (Use the Green reference card)  Values are decimal numbers.</li>

</ul>




( For example:  sub $s4, $s2, $s1  =  0251 A022 )




.text     2044

.globl strcpy                #  subroutine for memory copy of a string from A to B  strcpy: add      $t0, $zero, $zero         #  index to the next character to copy             loop: add         $t1, $t0, $a0                       #  t1 has address of A                         lb         $t2, 0($t1)                   #  get the next character                          add      $t3, $t0, $a1                #  t3 has the address of B

sb         $t2, 0($t3)                   #  copy it

beq      $t2, $zero, finish         #  if it is null character, then finished

addi     $t0, $t0,1                     #  increment the index

j           loop                             #  continue the copy

finish: jr          $ra                               #  return from the subroutine

<ul>

 <li>Write the MIPS Assembler pair of <u>hardware</u> instructions for this pseudoinstruction:</li>

</ul>

(3)

BGT $s4, $t1, AGAIN



















<ul>

 <li>The MIPS hardware does not have a <strong>subtract immediate</strong> Why ?</li>

</ul>

(1)

_________________________________________________________________







<ul>

 <li>The MIPS architecture has five <strong>Addressing Modes</strong>.</li>

</ul>

(5)        For each of the modes, give an example of an <strong>instruction</strong> that uses each.




<strong>Base</strong>  ____________________________________________________________

<strong> </strong>

<strong>            Register</strong>  _________________________________________________________

<strong> </strong>

<strong>            Immediate  </strong>_______________________________________________________




<strong>Pseudo Direct</strong>  _____________________________________________________

<strong> </strong>

<strong>Program Counter</strong>  _________________________________________________







<ul>

 <li>Floating point numbers are stored in <strong>Normalized</strong> Give three reasons :</li>

</ul>

(3)

<ol>

 <li>_______________________________________________________________</li>

</ol>




<ol>

 <li>_______________________________________________________________</li>

</ol>




<ol>

 <li>_______________________________________________________________</li>

</ol>







<ul>

 <li>From the discussion readings: What was the first Internet ‘killer app’?</li>

</ul>

(1)

_________________________________________________________________







<ul>

 <li>What decimal value does this bit pattern :</li>

</ul>

(1)

0000  0000  0000  0000  0000  0000  0000  0000




represent (exactly) in the IEEE 754 format ?  ______________________







<ul>

 <li>Convert the following decimal value to its MIPS floating point binary value:</li>

</ul>

(4)        (IEEE 754 32-bit format)  Show result as hex digits.

<strong>8765.75 </strong>











































<ul>

 <li>Identify which of these Assembly process functions would <strong>most likely</strong> occur in (4)</li>

</ul>

1)   Pass one  or  2)   Pass two            of a two-pass assembler




_____ a)  Translate mnemonic operation codes to machine codes

_____ b)  Save addresses assigned to labels

_____ c)  Scan for label definitions

_____ d)  Write object code







<ul>

 <li>Match the statements ( a – e ) with the most appropriate <strong>Object Program</strong> record type :</li>

</ul>

(5)

<ol>

 <li>            D)  Data Segment        S)  Symbol</li>

 <li>            H)  Header                   T)  Text Segment</li>

 <li>            R)  Relocation</li>

</ol>




_____ a)  Object instruction code.




_____ b)  Relative address of global symbol.




_____ c)  Modification information.




_____ d)  Program name.




_____  e)  Data values.







<ul>

 <li>Does the MIPS assemble language allow for arithmetic with 1-byte and 2-byte operands?</li>

</ul>

(2)        Yes / No ? Why ?

_______________________________________________________________________




_______________________________________________________________________ <strong>28) </strong>Natural languages are clear and concise, and therefore suitable for use as programming languages.

(1)                                (True / False)







<strong>29)</strong>       Register $t5 contains a negative 32-bit value in two’s complement form. After performing a         1-bit<strong> sll</strong> instruction, followed by a 1-bit <strong>srl</strong> instruction. Register $t5 would contain the absolute       value of the original value.

(1)                                ( True / False )







<strong>30)</strong>       The IEEE 754 floating point standard includes these objects.

(4)        What they are, and how they are used ??




Guard Bit :____________________________________________________________




_____________________________________________________________________




Round Bit : ____________________________________________________________




_____________________________________________________________________




Sticky Bit :____________________________________________________________




_____________________________________________________________________




NaN : ________________________________________________________________




_____________________________________________________________________







<ul>

 <li>What is <strong>RAID 1</strong> ? ________________________________________________</li>

</ul>

(2)

________________________________________________________________________







<ul>

 <li>Which of the following is a primary characteristic of <strong>System Software</strong> ?</li>

</ul>

(1)

<ol>

 <li>It is totally machine independent.</li>

 <li>Will run on any PC or Unix machine.</li>

 <li>Supports the operation of a specific computer.</li>

 <li>Calculates employee paychecks.</li>

</ol>







<ul>

 <li>What is the primary purpose of Pass One of the Two-pass Linker/Loader ? ___________</li>

</ul>

(2)

________________________________________________________________________

<strong> </strong>

<strong> </strong>

<ul>

 <li>A process that is BLOCKED must wait for an event to occur before it can resume processing.</li>

</ul>

(1)                                ( True / False )

<strong>35)       </strong>Given two programs that are multiprogrammed in a single processor computer:

(2)        Program ONE uses a large amount of CPU time and little I/O.

Program TWO uses a small amount of CPU time but performs a large number of I/O operations.  Which program should get the higher priority for <strong>dispatching </strong>the single CPU?   Why?




________________________________________________________________________




________________________________________________________________________







<ul>

 <li>The purpose of the Main Frame Operating System <strong>Job Scheduler</strong> is to assign resourses (2)       to waiting program processes.  The Scheduler has a priority scheme.           List the names of two of these schemes.</li>

</ul>




<ol>

 <li>____________________________________________________________________</li>

</ol>




<ol>

 <li>____________________________________________________________________</li>

</ol>







<ul>

 <li>The Grammar describes the (A) SEMANTICS  or (B) SYNTAX  of the   (1)             programming language.</li>

</ul>







<ul>

 <li>The I / O Channel causes an I / O Interrupt  when the I / O process completes.</li>

</ul>

(1)                                ( True / False )

<strong> </strong>




<ul>

 <li>The purpose of Interrupts and the Interrupt Processing is to (1)

  <ol>

   <li>Stop the computer when a fault occurs.</li>

   <li>Slow down the processing of programs.</li>

   <li>Enable the operating system to efficiently process several concurrent programs.</li>

  </ol></li>

</ul>







<ul>

 <li>Given this binary bit pattern, what is the MIPS instruction as Assembly Language:</li>

</ul>

(3)

1000 1101 0010 1000 0000 0100 1011 0000



















<ul>

 <li>One of the two basic functions of any Operating System is to provide the programming (1)              run-time environment.  What is the other basic function ?</li>

</ul>




_______________________________________________________________________




<ul>

 <li>Given this Intermediate File of a Compiler :</li>

</ul>

(8)

( 1 )       <strong>: =</strong>         #1                             Indx

( 2 )       <strong>JGT</strong>      Indx           #25         (20)

( 3 )       <strong>–</strong>            Indx           #1           t1

( 4 )       <strong>*</strong>            t1               #10         t2

( 5 )       <strong>*</strong>            #2              MLK      t3

( 6 )       <strong>–</strong>            t3               #1           t4

( 7 )       <strong>–</strong>            t4               #1           t5

( 8 )       <strong>+</strong>           t2               t5            t6

( 9 )       <strong>*</strong>            t6               #4           t7

( 10 )     <strong>–</strong>            Indx           #1           t8

( 11 )     <strong>*</strong>            t8               #10         t9

( 12 )     <strong>*</strong>            #2              MLK      t10

( 13 )     <strong>–</strong>            t10             #1           t11

( 14 )     <strong>+</strong>           t9               t11          t12

( 15 )     <strong>*</strong>            t12             #4           t13

( 16 )     <strong>: =</strong>         ZYX[t13]                 CBA[t7]

( 17 )     <strong>+</strong>           #1              Indx        t14

( 18 )     <strong>: =</strong>         t14                            Indx

( 19 )     <strong>JMP</strong>                                      ( 2 )

( 20 )




Optimize the code.

<strong>Mark</strong> which statements would be moved, modified, or removed.

Machine independent code optimization uses many techniques.   List the optimization methods you used.




























<ul>

 <li>In a few phrases, describe these components of a compiler.</li>

</ul>

(3)

SCANNER –




_________________________________________________________




PARSER –




_________________________________________________________




CODE GENERATOR –




_________________________________________________________







<ul>

 <li>From the discussion readings: What is Ubuntu?</li>

</ul>

(1)

_________________________________________________________________

<strong> </strong>

<strong> </strong>

<ul>

 <li>Machine independent code optimization uses many techniques. List two of the methods   (2)             discussed in the presentation that you <strong>did not</strong> use in <strong>problem #42</strong>  (on previous page).</li>

</ul>




__________________________________




__________________________________







<ul>

 <li>Match the following terms with the <strong>most correct</strong></li>

</ul>

(8)

_____ 1)  CHANNEL PROGRAM                  A)  Set of programs in a Circular Wait.

_____ 2)  CONTEXT SWITCHING               B)  Set mask to prevent Interrupt Processing

_____ 3)  DEAD – LOCK                                C)  Register containing interrupt mask

_____ 4)  DISPATCHING                               D)  Set of instructions for special i/o

_____ 5)  STORAGE PROTECTION KEY   E)  Select next program to process by CPU

_____ 6)  INHIBIT INTERRUPT                    F)  Data area used by the Memory Manager  _____ 7)  PAGE TABLE MAP                        G)  Saving / restoring registers by Interrupt Processor.

_____ 8)  PROGRAM STATUS WORD        H)  Half byte used for memory access control.







<ul>

 <li>Is <strong>memory-protection hardware</strong> necessary on a machine that uses a Virtual (demand-paged) (2)             Memory Management system ? Yes / No ? Why ?</li>

</ul>




____________________________________________________________




____________________________________________________________







<ul>

 <li>In many operating systems, the <strong>Timer</strong> Interrupt (the assigned time interval is used up) is assigned (2) a lower priority than the<strong> Operating System Service Request</strong>  Why is this done?</li>

</ul>




____________________________________________________________




____________________________________________________________







<ul>

 <li>Once the operating system detects that a <strong>Deadlock</strong> has occured,</li>

</ul>

(2)      how does it resolve the conflict between the processes ?   List two methods.




<ol>

 <li>__________________________________________________________</li>

</ol>




<ol>

 <li>__________________________________________________________</li>

</ol>







<ul>

 <li>What actions <strong>must</strong> the Operating System perform when an interrupt is recognized ?</li>

</ul>

(2)

A)___________________________________________________________




B)___________________________________________________________







<ul>

 <li>Is it ever safe (you do not lose data values ) for a MIPS user program to use registers <strong>$k0</strong> or <strong>$k1</strong> ?</li>

</ul>

(2)        Yes / No ? Why ?




_____________________________________________________________________




_____________________________________________________________________







<ul>

 <li>The Textbook, page 36, discusses the Classic CPU Performance Equation. Fill in the blanks:</li>

</ul>

(2)










<strong> </strong>

<strong> </strong>

<strong> </strong>

<ul>

 <li>Given the following Simplified Pascal grammar :</li>

</ul>

(3)

&lt; stmt-list &gt;     : : =      &lt; stmt &gt;  <strong>{ ;</strong>  &lt; stmt &gt; <strong>}</strong>

&lt; stmt &gt;           : : =     &lt; assign &gt;  |  &lt; read &gt;  |  &lt; write &gt;  |  &lt; for &gt;

&lt; assign &gt;        : : =      <strong>id</strong>  <strong>: =</strong> &lt; exp &gt;

&lt; exp &gt;            : : =     &lt; term &gt; <strong>{ +</strong> &lt; term &gt;  |  <strong>–</strong> &lt; term &gt; <strong>}</strong>

&lt; term &gt;          : : =      &lt; factor &gt; <strong>{ *</strong> &lt; factor &gt;  |  <strong>DIV</strong> &lt; factor &gt; <strong>}</strong>

&lt; factor &gt;         : : =     <strong>id</strong> | <strong>int</strong> | <strong>(</strong> &lt; exp &gt; <strong>) </strong>

<strong> </strong>

Modify the above Grammar to include the exponentiation operation.  Make exponentiation the highest priority arithmetic operation.




__________________________________________________________________




__________________________________________________________________




__________________________________________________________________







<strong>54)</strong>       Create quadruples of the form we have used in class for the following &lt;assign&gt; statement:

(6)

<h1>            ZEE :=  3 * EX – 5 * WHY + EX / WHY;</h1>































<strong>55)</strong>       The Optical Mouse includes an embedded processor.

(1)                                (True / False)







<ul>

 <li>Data Security consists of a number of methods and techniques. Name two.</li>

</ul>

(2)

( Extra credit for more than two. Max : 4 extra points.)




____________________________    ______________________________




____________________________    ______________________________




____________________________    ______________________________




<ul>

 <li>Don’t forget to complete the online Course Evaluation Survey.</li>

</ul>

It is the only method to provide the feedback for improving the course.