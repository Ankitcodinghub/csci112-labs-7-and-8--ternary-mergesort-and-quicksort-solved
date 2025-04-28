# csci112-labs-7-and-8--ternary-mergesort-and-quicksort-solved
**TO GET THIS SOLUTION VISIT:** [CSCI112  Labs 7 and 8- Ternary Mergesort and Quicksort Solved](https://www.ankitcodinghub.com/product/csci112-ternary-mergesort-and-quicksort-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116929&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI112 &nbsp;Labs 7 and 8- Ternary Mergesort and Quicksort Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Documentation: Each file should begin with a docstring that includes your name, the class number and name, the lab number, and a short description of the lab, as well as documentation pertinent to that particular file.

The project: Each of the sorting algorithms mergesort and quicksort divides the list into two portions, sorts the portions, and then puts them back together.

Rewrite each of these algorithms so that they divide the list into three portions, sort the portions, and then put them back together.

Use the implementation that comes with the textbook as a start. Try to make as few changes as possible. Mergesort should be fairly easy.

Quicksort’s partition function will be more difficult. You will have to select two pivots, p1 and p2, and then arrange the list into three sections:

n &lt; p1 p1 ≤ n &lt; p2 p2 &lt;= n

There is a fairly easy way to do it if you let yourself traverse the array twice, instead of once, to make the partition. (Think about using the original partition algorithme, twice.) This, of course, will make the partition algorithm O(2n), but of course, 2n = O(n). Implement this first so that you can create a unit test module and test your sorting implementations.

Lab 6: That’s it for lab 6. Put all four sorting algorithms (mergesort and quicksort, binary and tertiary) in a single file called sorts.py. Put your unit tests in the file sorts_test.py. Zip these files in a folder csci112lab06yourname and turn in to canvas.

Lab 7: For lab 7 develop a better quicksort ternary partition algorithm as follows, and run some timing tests on all four algorithms.

Improved quicksort partition: Develop a quicksort ternary partition that traverses the array only once, and partitions in place (i.e. using constant extra storage, that doesn’t grow with the array size). To partition an array between indices low and hi, you will need two pivots, which will be elements at low and hi. If the first element is larger than the last, swap them first.

Then, the idea is to create three ranges of elements:

range1 &lt; pivot1 ≤ range2 &lt; pivot2 ≤ range3

You can do this with three indices into the array: left, right, which start at low+1 and hi-1, and i which starts out at the same place as left, and moves gradually to the right.

1

When i &gt; right the list will be partitioned. At each step, you need to compare a[i] with both a[low] and a[hi]. Depending on the three possible outcomes of these comparisons, you need to move one or more of right, left, and i.

Think carefully about how this has to be done to accomplish the partitioning required. Implement several variations and test them until you’re sure you’ve got it right.

A trace of the algorithm as I implemented it is shown below:

low left,i right hi

3 9 4 5 1 5 1 9 10 8 2 9

low left,i right hi

3 2 4 5 1 5 1 9 10 8 9 9

low left,i right hi

3 2 4 5 1 5 1 9 10 8 9 9

low left i right hi

3 2 4 5 1 5 1 9 10 8 9 9

low left i right hi

3 2 4 5 1 5 1 9 10 8 9 9

low left i right hi

3 2 1 5 4 5 1 9 10 8 9 9

low left i right hi

3 2 1 5 4 5 1 9 10 8 9 9

low left i right hi

3 2 1 1 4 5 5 9 10 8 9 9

low left i right hi

3 2 1 1 4 5 5 8 10 9 9 9

low left i,right hi

3 2 1 1 4 5 5 8 10 9 9 9

low left right i hi

3 2 1 1 4 5 5 8 10 9 9 9

low left i,right hi

1 2 1 3 4 5 5 8 9 9 9 10

File names: Put all four sorting algorithms (mergesort and quicksort, binary and tertiary) in a single file called sorts.py. Put your unit tests in the file sorts_test.py. Put your runtime tests in a file called sorts_runtime.py. Zip all three together with your writeup into a folder called csci112lab07yourname and submit to canvas.

2
