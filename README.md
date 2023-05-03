Download Link: https://assignmentchef.com/product/solved-cs311-coa-assignment-1
<br>
<span class="kksr-muted">Rate this product</span>

Write the following programs in the ToyRISC ISA:

<ol>

 <li>Check if a given number is even or odd. If odd, write ‘1’ to register x10.Else, write ‘-1’ to register x10.</li>

 <li>Write a program to sort an array of numbers in the descending order. The sorted array should be placed in the same addresses in memory as the initial array.</li>

 <li>Write a program to place the first ‘n’ Fibonacci numbers in the memory. The first number is placed at address 216 − 1, the second at 216 − 2, and so on.</li>

 <li>Write a program to check if a given number is a palindrome. If yes, place ‘1’ in x10. If no, place ‘-1’ in x10.</li>

 <li>Write a program to check if a given number is prime. If yes, place ‘1’ in x10. If no, place ‘-1’ in x10.</li>

</ol>

Submission Format

<ul>

 <li>Submit one zipped archive named “&lt;entry-number-1&gt; &lt;entry-number- 2&gt; assignment1.zip”.</li>

 <li>The archive must contain 5 files: even-odd.asm, descending.asm, fibonacci.asm, palindrome.asm, and prime.asm. Name your files exactly as mentioned.</li>

 <li>Use the template programs given. You may change the data values for your testing. But do not change the names given to the addresses, for example, a and n in descending template.asm. Remember to remove the comment lines.</li>

 <li>Test each individual program using the test each script. Make sure the test passes. You may change values in the input and expected output files for your testing purposes.</li>

 <li>Test your final zip archive using the test zip script. Make sure the test passes.</li>

 <li>Both students must submit on Moodle.1</li>

</ul>

Testing Your Programs

<ul>

 <li>Download and unzip the supporting files.</li>

 <li>To test your program, use the given Java application emulator.jar. The commandisjava -jar &lt;path-to-emulator.jar&gt; &lt;path-to-assembly-file&gt; &lt;starting-address&gt; &lt;ending-address&gt; . This command function-ally emulates the program you have written and at the end prints the contents of the register file, as well as the contents of those addresses ofthe memory specified by starting-address and ending address.Use this to test and debug your program. An awkward crash implies your program is syntactically incorrect. A graceful completion with unexpected contents in the register file and / or the memory implies your program is logically incorrect.</li>

 <li>One test case for each program is given. To evaluate, the command is python test each.py &lt;path-to-assembly-file&gt;. Make sure the name of your .asm file is as specified above.</li>

 <li>To test your zip archive, the command is python test zip.py &lt;path-to-zip-archive&gt;. Make sure the name of your .zip file is as specified above. We will use thetest zip script to automatically grade your submissions. So please makesure your submission works before submitting.Troubleshooting• Follow the program syntax given in the ISA specification document closely. • Don’t have any empty lines in your program.</li>

</ul>