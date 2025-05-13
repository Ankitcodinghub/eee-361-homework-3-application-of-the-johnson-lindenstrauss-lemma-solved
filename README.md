# eee-361-homework-3-application-of-the-johnson-lindenstrauss-lemma-solved
**TO GET THIS SOLUTION VISIT:** [EEE-361 Homework 3-Application of The Johnson Lindenstrauss-Lemma Solved](https://www.ankitcodinghub.com/product/eee-361-homework-3-application-of-the-johnson-lindenstrauss-lemma-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94169&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE-361 Homework 3-Application of The Johnson Lindenstrauss-Lemma Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The purpose of this homework assignment is the practical validation of applying The Johnson-Lindenstrauss Lemma. The lemma formally says that, given vectors x1, . . . , xn ∈ Rm, for some n, m ∈ N, and given ε &gt; 0 and k ≥ (8 log n)/ε2 , then there exists a projection J from Rm to Rk that approximately preserves the distances, that is,

(1−ε)∥xi −xj∥2 ≤∥Jxi −Jxj∥2 ≤(1+ε)∥xi −xj∥2 , (1) for all 1 ≤ i, j ≤ n. As stated in page 155 of the book, a key point given in the proof of the lemma is that a

random projection will do for such a purpose, and therefore, there must be many such k × m projections.

Given the values of m, n and ε, you will first determine the value of k to be used and then generate 10 different realizations of the random projection J to be used, as indicated in page 153 of the book. Formally, every column of J will be independently generated from a 0 mean normal distribution with σ2 = 1/k. For each realization of J, you will write a code that determines whether or not condition (1) holds, for all pairs of independent vectors xi and xj , 1 ≤ i, j ≤ n. Note that the cases when i = j should not be checked. Here, you should first determine the number of all possible such pairs (let us denote it by N) and then the number of cases when (1) holds (let us denote it by Ntrue). Denoting by vi the percentage of cases that condition (1) holds for the ith realization of J, you will have

vi = Ntrue × 100. N

Then, vav will denote the average of these percentages over all realizations of J, that is,

1 10

􏰀vi. i=1

So, given the values for m,n,ε, and the vectors xi, 1 ≤ i ≤ n, you now have a number vav. What we want to see is the accuracy of the preservation of distances over different values of m, n and ε. Therefore, you will find the values of vav for the cases when m = 104,5 × 104,105 and ε = 0.1,0.3,0.7,0.9. The value of n is dependent on m and you will have three such values for it, namely, n = m, m/10, m/100. The tasks you should complete are listed below. First, note that for each n and m, you will first generate the vectors xi ∈ Rm, for 1 ≤ i ≤ m. You will do this by independently generating n realizations of length m vectors with i.i.d. zero-mean unit-variance normal random variables.

1. For each m ∈ {104, 5 × 104, 105}, you will plot the values of vav with respect to the values of ε ∈ {0.1, 0.3, 0.7, 0.9}. There will be three lines in the plot, each corresponding to the three different values of n as given above. Note that you will end up with a total of three figures, each containing three lines.

2. For each ε ∈ {0.1, 0.3, 0.7, 0.9}, you will plot the values of vav with respect to the values of m ∈ {104 , 5 × 104 , 105 }. There will be three lines in the plot, each corresponding to the three values of n as given above. Note that you will end up with a total of four figures, each containing three lines.

Report your plots (note that there will be a total of 7 such plots, each of which contains three different lines corresponding to the values of n) and comment on the results. What trend do you see and why? How does the dimension affect the accuracy? How does the sample size and ε affect it?

</div>
</div>
<div class="layoutArea">
<div class="column">
vav =

</div>
<div class="column">
10

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
