Download Link: https://assignmentchef.com/product/solved-csc-cpe101-fundamental-of-computer-science-i-lab-6
<br>
This lab provides additional exercises on iteration over lists and exercises on characters and strings.

Download <u>Lab6.zip</u>, from PolyLearn (place it in your CPE101 directory, and unzip the file) or from:

<strong>            unzip  lab6.zip </strong>

<strong><u>NOTE: For each function you need to write signature and purpose</u></strong><strong> <u>statement before you implement the functions.</u>  </strong>

<h1>Fold Pattern</h1>

Develop these functions in the <sub>fold</sub> directory in files <sub>fold.py</sub> and <sub>fold_tests.py</sub>. Don’t use the <strong>library functions such as sum, index,</strong> etc. The List can be list of list!

Each of the functions for this part of the lab must be implemented using the fold or reduce pattern. In this pattern, the values in the input list are combined in some manner (e.g., an arithmetic or relational operation) to compute a single result value. Each of these functions will use a local variable (or local variables) to hold the computed value as the list is traversed. This variable is often updated at each step of the iteration.

<ul>

 <li>sum</li>

</ul>

The <sub>sum</sub> function returns the sum of all values in the input list.

<ul>

 <li>index_of_smallest</li>

</ul>

The <sub>index_of_smallest</sub> function returns the index of the smallest value in the input list. If the list is empty (i.e., the length is ≤ 0), then the function returns -1. If there is more than one smallest value, return the index of the first occurrence of it.

<h1>Character Manipulation</h1>

Develop these functions in the <sub>char</sub> directory in files <sub>char.py</sub> and <sub>char_tests.py</sub>.







<ul>

 <li>is_lower_101</li>

</ul>

The <sub>is_lower_101</sub> function takes a single character and returns True if the character is lowercase (assuming only the English alphabet) and False otherwise. You are required to write this function without using the predefined <sub>lower</sub> functions. Your solution should use character/string literals; avoid the direct use of the integer values for characters. Recall that you can use the <sub>ord</sub> function to determine the integer representation of a character.

<ul>

 <li>char_rot13</li>

</ul>

The char_rot13 function takes a single character and returns the rot13 encoding of the character (<strong>rot13:</strong> The rot13 algorithm obscures text. It does not encrypt it. The algorithm shifts each character back, or forward, 13 places. It is a cipher algorithm.) Your solution should avoid the direct use of integer values for characters (use character/string literals). You may use the str.isalpha, str.islower,and str.isupper functions, if desired. Recall that you can use the ord function to determine the integer representation of a character and the chr function to determine the character represented by an integer (in the valid range).

<table width="613">

 <tbody>

  <tr>

   <td width="8"> </td>

   <td width="604">Rot-13</td>

  </tr>

 </tbody>

</table>

<strong>rot-13</strong> (rotate by 13 places) is a simple Caesar-cypher encryption that replaces each character of the English alphabet with the character 13 places forward or backward along the alphabet (e.g, ‘a’ becomes ‘n’, ‘b’ becomes ‘o’, ‘N’ becomes ‘A’, etc.). This only works on the characters in the alphabet. All other characters are left unchanged. Moreover, the rotation is only within the characters of the same case (i.e., a lowercase letter always rotates to a lower case letter and the same for uppercase letters). An encoded character can be decoded by applying the rotation a second time. More information, for those curious, can be found at the <a href="https://en.wikipedia.org/wiki/ROT13">Wikipedia entry</a> for rot13.

<h1>String Manipulation</h1>

Develop these functions in the <sub>string</sub> directory in files string_101.py and string_101_tests.py.

<strong>Note:</strong> There are a few different approaches to the following functions. For the sake of learning, you should implement one of them using an explicit loop and one without using an explicit loop.

<ul>

 <li>str_rot_13</li>

</ul>

The <sub>str_rot_13</sub> function takes an input string argument and returns the rot-13 encoding of the input string.




<ul>

 <li>str_translate_101</li>

</ul>

The <sub>str_translate_101</sub> function is a simplification of the <sub>translate</sub> function.

Write <sub>str_translate_101</sub> to take a string and two characters (<em>old</em> and <em>new</em>) as arguments. The function will return a string where each occurrence of <em>old</em> is replaced with <em>new</em> (and all other characters are left unchanged). You are required to write this function without using any predefined string functions with similar behavior (i.e., think of this as an exercise in implementing a provided function).

As an example, str_translate_101(‘abcdcba’, ‘a’, ‘x’) should result in ‘xbcdcbx’.

<h1>Demonstration</h1>

Demonstrate the test cases from each part of the lab to your instructor to have this lab recorded as completed. In addition, be prepared to show the source code to your instructor.

<h1>Submission</h1>

Demo your work and Submit your files in the PolyLearn.

<ol>

 <li>py,</li>

 <li>py,</li>

 <li>py,</li>

 <li>py,</li>

 <li>py<sub>,</sub> and 6. <sub>string_101_tests.py</sub>.</li>

</ol>


