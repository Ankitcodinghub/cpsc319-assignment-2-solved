# cpsc319-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CPSC319 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cpsc319-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94386&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC319 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Linked Lists and Sorting

The goal of this assignment is to write a Java program that arranges a list of words into separate lists of anagrams. The input is a text file that contains a list of words, each word on its own line. The number of words in the input is arbitrary and could be very large.

</div>
</div>
<div class="layoutArea">
<div class="column">
The program should print to an output file the lists of anagrams in the following way:

<ul>
<li>All the words that are anagrams of each other are displayed together on a single line; any word without any corresponding anagrams is displayed alone on a line.</li>
<li>The words on each line should be in alphabetic order.</li>
<li>Lines of words are sorted into ascending alphabetic order according to the first word of a line.</li>
<li>Words in a line should be separated by a single space.</li>
</ul>
For example, this input:

<pre>     car
     dog
     bed
     stop
     god
     pots
     arc
     tops
</pre>
should yield the output:

arc car

bed

dog god

pots stop tops

You must use linked lists to deal with the arbitrary number of anagrams in a line, and use an array of references to keep track of all the linked lists. For example:

0 *

.

n-1 * zoo

An acceptable alternative to using an array is to use a vector, provided you program your own vector class (i.e. you cannot use a class such as Vector or ArrayList from the Java libraries for this).

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
arc

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
bed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
dog

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Adapt the insertion sort given in class so that it works on the items in the linked lists, and adapt the quick sort so that it sorts the array of references. Be sure to cite the sources of any code you use or adapt. You must write your own implementation of linked lists and sorting algorithms rather than using calls to a Java library.

Your program should read and store all the words in the file to your data structure first, and then sort as a second step, applying the insertion sort to each row of words, and then the quick sort to the array, using the first word in the list as the sort key. An acceptable alternative to the insertion sort is to insert each word in its row in ascending order as you read it from file. Your program must also print out to the screen the time in seconds it takes to process an input file.

One way to determine if two words are anagrams is to sort the letters in both words. If the sorted words are the same, then the original two words are anagrams of each other. For example, “dog” and “god” are both sorted into “dgo”, so they are anagrams.

Write a program in Java to implement the above requirements. Your program will be invoked from the command line as follows:

<pre>     java Assign2 inputfile outputfile
</pre>
where Assign2 is the name of the file containing executable bytecode for your program, inputfile is the name of the input file, and outputfile is the name of the output file.

Complexity Analysis

<ol>
<li>What is the worst-case complexity of your algorithm when checking if two words are anagrams of each other? Express this using big-O notation, and use the variable k to represent the number of letters in each word. Support this with a theoretical analysis of your code.</li>
<li>Let N be the number of words in the input word list, and L be the maximum length of any word. What is the big-O running time of your program? Justify your answer using both a theoretical analysis and experimental data (i.e. timing data).</li>
</ol>
</div>
</div>
</div>
