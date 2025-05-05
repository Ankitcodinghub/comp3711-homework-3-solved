# comp3711-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP3711 Homework 3 Solved](https://www.ankitcodinghub.com/product/comp3711-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99673&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3711 Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<h1>Problem 1: <em>k</em>-swapped arrays</h1>
An <em>n </em>element array <em>A</em>[1<em>…n</em>] is <em>k</em><strong>-swapped </strong>if <em>k </em>is the <em>minimum </em>integer in [0<em>,n</em>] satisfying the following: for all <em>i,j </em>∈ [1<em>,n</em>] satisfying <em>i &gt; j </em>and <em>A</em>[<em>i</em>] <em>&lt; A</em>[<em>j</em>], we have <em>i </em>− <em>j </em>≤ <em>k</em>.

The problem is to sort a given <em>k</em>-swapped array in <em>O</em>(<em>n</em>log<em>k</em>) time. Time in this problem refers to the number of comparisons performed by the algorithm.

In what follows <em>A </em>is a <em>k</em>-swapped array of size <em>n</em>, where <em>k </em>is provided as an extra parameter to the algorithm, and <em>k </em>can be used in the code.

<ul>
<li>(i) Write documented pseudocode for an <em>O</em>(<em>n</em>log<em>k</em>) time procedure to sort <em>k</em>-swapped array <em>A</em>[1<em>…n</em>]<em>.</em></li>
</ul>
(ii) Below the pseudocode, provide a description in words (as opposed to code) of what your algorithm is doing.

<ul>
<li>Prove why your algorithm is correct.</li>
</ul>
This should be a clear FORMAL mathematical style proof.

<ul>
<li>Prove that your algorithm runs in <em>O</em>(<em>n</em>log<em>k</em>) time.</li>
<li>In class we proved that any comparison-based algorithm requires Ω(<em>n</em>log<em>n</em>) time. Why does this not contradict having an <em>O</em>(<em>n</em>log<em>k</em>) solution for this problem (when <em>k </em>is much smaller than <em>n</em>).</li>
<li>Prove that any algorithm for solving this problem requires Ω(<em>n</em>log<em>k</em>) comparisons (so your solution is the best possible).</li>
</ul>
Rules, recommendations and hints

<ul>
<li>In part (a), your algorithm may use any procedures or algorithms that we learned in class as a black-box subroutine (without having to provide code for that subroutine).</li>
<li>In parts (b)-(d) you may use theorems, lemmas and facts that we learned in class or tutorial. If you use such theorems, lemmas and/or facts you must (i) explicitly state the text of the theorem/lemma/fact that you are using and (ii) identify exactly where in the class notes you are copying them from. Everything else must be proven from scratch.</li>
<li>The solution to part (e) is in one of the tutorials (in a slightly different form).</li>
<li>Proofs of correctness that are not formal and clear will have points deducted. There are multiple algorithms for this problem, some of which are quite intuitive. A main goal of this problem is to show that you can prove the correctness of an intuitive idea.</li>
<li>Your proof of correctness may assume that all elements in the array are distinct.</li>
</ul>
<h1>Problem 2 Decision Trees</h1>
Recall that a comparison-based sorting algorithm can be represented in the (binary) decision tree model.

Following the worked example of Tutorial SS13, the figure below shows part of the decision tree for mergesort operating on a list of 4 numbers, <em>a</em><sub>1</sub>, <em>a</em><sub>2</sub>, <em>a</em><sub>3</sub>, <em>a</em><sub>4</sub>. Please expand subtree <em>T</em><sub>1</sub>, i.e., draw and label all of the edges, internal (comparison) nodes and leaves in subtree <em>T</em><sub>1</sub>.

Edges in the tree must be labelled with ≤ or <em>&gt; </em>and leaves must show the final sorted order.

<h1>Problem 3 Radix sort</h1>
You are given a set of 10 decimal integers in the range of 1 to 65535:

<em>A </em>= [29681<em>,</em>53846<em>,</em>43521<em>,</em>39427<em>,</em>32433<em>,</em>35700<em>,</em>30764<em>,</em>16892<em>,</em>52608<em>,</em>19583]<em>.</em>

<ul>
<li>Please conduct Radix sort on A using Base 10. Illustrate your result after each step following the worked example on Page 36 in the 08 Linearsort lecture slides.</li>
<li>Now convert these decimal integers to hexadecimal and conduct Radix sort again, this time using Base 16 (hexadecimal). Illustrate your result after each step following the worked example on Page 36 in the 08 Linearsort lecture slides.</li>
</ul>
<em>Note: a digit in hexadecimal is in the range of </em>[0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>4<em>,</em>5<em>,</em>6<em>,</em>7<em>,</em>8<em>,</em>9<em>,A,B,C,D,E,F</em>]<em>.</em>

<em>To start you off, note that </em>29681 <em>is </em>73<em>F</em>1 <em>in hexadecimal.</em>

<em>There are many decimal to hexadecimal converters available on the intern. We recommend you use one of them to covert the data rather than doing it by hand.</em>

<h1>Problem 4 Greedy Covering</h1>
Consider the following (unrealistic) scenario. You are running a political campaign and want to collect petition signatures in the park. Your research team tells you that everyone who goes to the park visits for one of <em>n </em>known time intervals during the day (if they come for a particular interval, they stay for the entire time interval; note that different time intervals might overlap).

If you go to the park at any time during one of the intervals you will get the signatures of everyone there for that interval. You want to figure out a minimum sized set of times that you have to go to the park to get everyone’s signature.

In computer science such a situation is called a <em>covering problem </em>and is modelled formally as described below.

<ul>
<li>A real <em>interval </em>is <em>I </em>= [<em>s,f</em>] where <em>s </em>≤ <em>f</em></li>
<li>A real <em>point x covers </em>interval <em>I </em>= [<em>s,f</em>] if <em>x </em>∈ <em>I, </em>e., <em>s </em>≤ <em>x </em>≤ <em>f.</em></li>
<li>Let I = {<em>I</em><sub>1</sub><em>,…,I<sub>n</sub></em>} be a set of <em>n </em>intervals and <em>A </em>= {<em>a</em><sub>1</sub><em>,a</em><sub>2</sub><em>,…a<sub>k</sub></em>} a set of points.</li>
</ul>
Then “<em>A </em>covers I” if every interval in I is covered by at least one point in <em>A. </em>More formally, if, for every <em>I<sub>j </sub></em>∈ I there exists <em>a<sub>i </sub></em>∈ <em>A </em>such that <em>a<sub>i </sub></em>∈ <em>I<sub>j</sub>.</em>

<ul>
<li>|<em>A</em>|<em>, </em>the size of <em>A, </em>is just the number of points in <em>A</em>.</li>
</ul>
<em>A </em>is a <em>minimal cover </em>of I if <em>A </em>is a smallest cover of I.

That is, for every cover <em>A</em><sup>0 </sup>of I<em>, </em>|<em>A</em>| ≤ |<em>A</em><sup>0</sup>|.

The input to this problem is the 2<em>n </em>numbers <em>s</em><sub>1</sub><em>,f</em><sub>1</sub><em>,s</em><sub>2</sub><em>,f</em><sub>2</sub><em>,…,s<sub>n</sub>,f<sub>n </sub></em>with <em>s<sub>j </sub></em>≤ <em>f<sub>j</sub></em>, that define I; <em>I<sub>j </sub></em>= [<em>s<sub>j</sub>,f<sub>j</sub></em>]<em>.</em>

The problem is to construct a minimal cover for I in <em>O</em>(<em>n</em>log<em>n</em>) worst-case time. Your output should be a set <em>A </em>which is a minimal cover.

When solving this problem you may use any algorithm we taught in class (but not the tutorial) as a black box as long as you quote which algorithm you are using. You can assume that any properties of that algorithm taught in class are correct as long as you quote what the properties are. Any other subroutines and their properties must be derived from scratch.

<ul>
<li>Prove that there exists a minimal cover <em>A </em>such that every point in <em>A </em>is one of the <em>f<sub>j</sub>. </em>That is, <em>A </em>⊆ {<em>f</em><sub>1</sub><em>,…,f<sub>n</sub></em>}<em>.</em></li>
<li>Give documented pseudocode for your algorithm.</li>
</ul>
In addition, below your algorithm’s pseudocode, explain in words/symbols what your algorithm is doing

<ul>
<li>Prove correctness of your algorithm. Your proof must be mathematically formal and understandable.</li>
</ul>
<em>Note: Break your proof up into clear logical pieces and skip space between the pieces. Explicitly state what each part is assuming and proving. For examples of such proofs please see the lecture notes and tutorials.</em>

<em>As seen in class, greedy algorithms tend to be simple. Their proofs of correctness are more complicated.</em>

<ul>
<li>Explain why your algorithm runs in <em>O</em>(<em>n</em>log<em>n</em>) worst case time.</li>
</ul>
<h1>P5: [10 pts] Huffman Coding</h1>
The table below lists 10 letters (<em>a </em>to <em>j</em>) and their frequencies in a document. Apply Huffman coding (following the algorithm on Page 11 of the 10 Huffman.pptx lecture notes) to construct an optimal codebook. Your solution should contain three parts:

<ul>
<li>A full Huffman tree.</li>
<li>The final codebook that contains the binary codewords representing <em>a </em>to <em>j </em>(sorted in the alphabetical order on <em>a </em>to <em>j</em>).</li>
<li>The codebook from part (b) but now sorted by the lengths of the codewords (in increasing order).</li>
</ul>
<table width="336">
<tbody>
<tr>
<td width="48"><em>i</em></td>
<td width="29">1</td>
<td width="29">2</td>
<td width="29">3</td>
<td width="29">4</td>
<td width="29">5</td>
<td width="29">6</td>
<td width="29">7</td>
<td width="29">8</td>
<td width="29">9</td>
<td width="29">10</td>
</tr>
<tr>
<td width="48"><em>a<sub>i</sub></em></td>
<td width="29"><em>a</em></td>
<td width="29"><em>b</em></td>
<td width="29"><em>c</em></td>
<td width="29"><em>d</em></td>
<td width="29"><em>e</em></td>
<td width="29"><em>f</em></td>
<td width="29"><em>g</em></td>
<td width="29"><em>h</em></td>
<td width="29"><em>i</em></td>
<td width="29"><em>j</em></td>
</tr>
<tr>
<td width="48"><em>f</em>(<em>a<sub>i</sub></em>)</td>
<td width="29">36</td>
<td width="29">21</td>
<td width="29">58</td>
<td width="29">16</td>
<td width="29">17</td>
<td width="29">29</td>
<td width="29">45</td>
<td width="29">27</td>
<td width="29">26</td>
<td width="29">28</td>
</tr>
</tbody>
</table>
<strong>Rules, Recommendations and Hints:</strong>

<ul>
<li>In part (a) you should explicitly label each edge in the tree with a ‘0’ or ‘1’. You should also label each leaf with its corresponding character <em>a<sub>i </sub></em>and <em>f</em>(<em>a<sub>i</sub></em>) value.</li>
<li>Part (b) should be a table with 2 columns. The first column should be the letters <em>a </em>to <em>j</em>. The second column should be the codeword associated with each character.</li>
<li>In part (c) you should break ties using the alphabetical order of the characters. For example, if <em>a</em>, <em>d </em>and <em>e </em>all have codewords of length 5, then write the codeword for <em>a </em>on top of the codeword for <em>d </em>on top of the codeword for</li>
</ul>
