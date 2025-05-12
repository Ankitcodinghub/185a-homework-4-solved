# 185a-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [185A Homework 4 Solved](https://www.ankitcodinghub.com/product/185a-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91037&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;185A Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions: Download FiniteState.hs and Assignment04.hs from the course website into the same directory on your computer. The import line near the top of Assignment04.hs imports all of the definitions from FiniteState.hs, which you may then use in your assignment. Please submit your assignment as one file: a modified version of Assignment04.hs.

 5 points Please convert the following graphical representation of an FSA into our Haskell

format with the type Automaton:

</div>
</div>
<div class="layoutArea">
<div class="column">
Ethan Poole ling 185a: Comp. Ling. I Due: 29 April 2019

</div>
</div>
<div class="layoutArea">
<div class="column">
(1)

</div>
<div class="column">
False False False False

54 True 73 True 21 True 38 True

</div>
</div>
<div class="layoutArea">
<div class="column">
Specifically, define fsa_1 to be the appropriate thing of type Automaton to repre- sent this FSA. You can use the functions recognize and hat to test the behavior of your implementation:

</div>
</div>
<div class="layoutArea">
<div class="column">
(2) Example behavior:

</div>
</div>
<div class="layoutArea">
<div class="column">
recognize fsa_1 [True, False, True, True, False]

</div>
</div>
<div class="layoutArea">
<div class="column">
ï True 



ï

ï [73]

Page 1 of 3

</div>
</div>
<div class="layoutArea">
<div class="column">
recognize fsa_1 [True, True, True, False, True, True]

</div>
</div>
<div class="layoutArea">
<div class="column">
ï

</div>
</div>
<div class="layoutArea">
<div class="column">
False

</div>
</div>
<div class="layoutArea">
<div class="column">
hat (transitions fsa_1) 54 [True, False, True, True]

</div>
</div>
<div class="layoutArea">
<div class="column">
[38, 54]

</div>
</div>
<div class="layoutArea">
<div class="column">
hat (transitions fsa_1) 73 [True, False, True, True]

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 25 points

Please construct the following FSAs in Haskell with the type Automaton. You may choose to use whatever you want as the state type (though Int is a natural choice in most cases). You can use recognize to test the behavior of your implementation.

</div>
</div>
<div class="layoutArea">
<div class="column">
(3) a.

b.

</div>
<div class="column">
Construct an FSA called fsa_2 that has SegmentCV as its alphabet, and generates all and only those sequences that contain at least two Cs.

Example behavior:

ï True ï False

Construct an FSA called fsa_3 that has SegmentCV as its alphabet, and generates all and only those sequences that have an odd number of Cs and an even number of Vs (treating zero as an even number).

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_2 [C,C,C,C]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_2 [V,V,C,V]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
c.

d.

</div>
<div class="column">
Construct an FSA called fsa_4 that has SegmentCV as its alphabet, and generates all and only those sequences that have C as their third-to-last symbol.

Example behavior:

ï True ï False

Construct an FSA called fsa_5 that has SegmentPKIU as its alphabet, which enforces a simple kind of vowel harmony: treating WB as the word- boundary symbol, all the vowels within a word must be identical to each other. Any sequences built out of the symbols P, K, I, U, and WB are allowed

Page 2 of 3

</div>
</div>
<div class="layoutArea">
<div class="column">
Example behavior:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_3 [C]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ï True

ï True



</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_3 [C, V, V]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_3 [C, C, V]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ï

ï

</div>
</div>
<div class="layoutArea">
<div class="column">
False

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_3 [C, C, V, C, V]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">


</div>
</div>
<div class="layoutArea">
<div class="column">
False

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_4 [C, C, C, V, C]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_4 [C, C, V, V, C]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
as long as they satisfy this requirement. This includes some strange ones such as those that contain two adjacent “word boundaries”, and those including “words” that contain no vowels, etc.; the goal here is just to isolate the vowel-harmony requirement itself.

</div>
</div>
<div class="layoutArea">
<div class="column">
Example behavior:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_5 [P, K, I, K, WB, U, P, U]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ï True ï False

ï True ï False

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_5 [P, K, I, K, U, P, U]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_5 [K, P, P, P]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_5 [K, I, P, U]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
e. Construct an FSA called fsa_6 that has SegmentPKIU as its alphabet, and generates all and only those sequences that (i) do not contain WB, and (ii) satisfy the requirement that U can only appear somewhere after a P.

</div>
</div>
<div class="layoutArea">
<div class="column">
Example behavior:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_6 [P, U]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ï True



ï

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_6 [U, P]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
False

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_6 [P, K, K, K, K, K, K, U]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ï True ï True

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>recognize fsa_6 [K, K, K, K, K, K, K, K]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 3

</div>
</div>
</div>
