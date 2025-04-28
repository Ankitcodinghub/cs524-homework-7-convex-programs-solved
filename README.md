# cs524-homework-7-convex-programs-solved
**TO GET THIS SOLUTION VISIT:** [CS524 Homework 7-Convex programs Solved](https://www.ankitcodinghub.com/product/cs524-homework-7-convex-programs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119635&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS524  Homework 7-Convex programs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
See the course website for instructions and submission details.

1. 4 points

NFL Regression.

We examined the results of the first 10 weeks of the 2000 NFL season, and aim to use regression to determine a rating for each team. The file nfl.inc contains the margins of victory by the home team in each game. In each entry in the parameter margins, the visiting team is listed first, followed by the home team. For example, the entry

2.chiefs.titans 3

indicates that the game was played in week 2, the visiting team was the Chiefs, the home team was the Titans, and the home team (Titans) won by 3 points. Of course, a negative “margin of victory” indicates that the visiting team won the game.

(a) We aim to choose the team ratings to predict the results of all these games as well as possible, according to some loss function. We also aim to find the ”average” home field advantage. If team i (the visiting team) has rating Ri, and team j (the home team) has rating Rj, and the home field advantage is H, then our prediction of the margin of victory for the home team is is Rj −Ri +H

Using a sum-of-squares objective, applied to the difference between our predicted outcomes and the actual outcomes from the data file, determine the ratings for each team and the home field advantage. Apply the following constraint to the ratings: They must sum to zero. Print the ratings for the teams (tabulated by team name).

(b) Repeat part (a) but with an `1 objective function in place of the sum-of-squares to obtain a different set of ratings. Print the ratings. Comment on the differences in the ratings obtained by these two methods.

(c) Now modify the question in part (a) as follows: Use a separate ”home field advantage” variable Hi for each team. Specifically, if team ii (the visiting team) has rating Ri, and team j (the home team) has rating Rj, and the home field advantage for teach j is Hj, then our prediction of the margin of victory for the home team is is Rj +Hj −Ri. Use the sum-of-squares objective to find the best-fit ratings and home field advantages. Print the ratings and home field advantage for all teams.

(d) According to the ratings obtained in parts (a) and (b), who would you expect to win if the dolphins were to visit the seahawks, and what would be the expected margin?

2. 4 points The Huber loss. In statistics, we frequently encounter data sets containing outliers, which are bad data points arising from experimental error or abnormally high noise. Consider for example the following data set consisting of 15 pairs (x,y).

x 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15

y 6.31 3.78 24 1.71 2.99 4.53 2.11 3.88 4.67 4.25 2.06 23 1.58 2.17 0.02

The y values corresponding to x = 3 and x = 12 are outliers because they are far outside the expected range of values for the experiment.

(a) Compute the best linear fit to the data using an `2 cost (least squares). In other words, we are looking for the a and b that minimize the expression:

`2 cost:

Make a plot showing the data points and the fitted line.

`1 cost:

Make a plot containing the data and the best `1 linear fit. Does the `1 cost handle outliers better or worse than least squares? Explain why.

(c) A “hybrid” approach is to use an `2 penalty for points that are close to the line but an `1 penalty for points that are far away. Specifically, we’ll use something called the Huber loss, defined as:

(x2 if − M ≤ x ≤ M

φ(x) =

2M|x| − M2 otherwise

Here, M is a parameter that determines where the quadratic function transitions to a linear function. The plot on the right shows what the Huber loss function looks like for M = 1.

The formula above is simple, but not in a form that is useful for us. As it turns out, we can evaluate the Huber loss function at any point x by solving the following convex QP instead:



minimize

 v,w

subject to:

Find the best linear fit to our data using a Huber loss with M = 1. Find the coefficients a and b by minimizing the cost function

(d) Make one final plot (using starter code supplied) showing the data points and all three fitted lines. Which of the techniques gave the best fit to the non-outlier data?

3. 4 points Heat pipe design. A heated fluid at temperature T (degrees above ambient temperature) flows in a pipe with fixed length and circular cross section with radius r. A layer of insulation, with thickness w, surrounds the pipe to reduce heat loss through the pipe walls (w is much smaller than r). The design variables in this problem are T, r, and w.

Now the problem: maximize the total heat flow down the pipe, subject to an upper limit Cmax on total cost, and the constraints

Tmin ≤ T ≤ Tmax, rmin ≤ r ≤ rmax wmin ≤ w ≤ wmax, w ≤ 0.1r

a) Express this problem as a geometric program, and convert it into a convex optimization problem.

b) Consider a simple instance of this problem, where Cmax = 500 and α1 = α2 = α3 = α4 = 1. Also assume for simplicity that each variable has a lower bound of zero and no upper bound. Solve this problem using JuMP. Use the Ipopt solver and the command @NLconstraint(…) to specify nonlinear constraints such as log-sum-exp functions. Have your code print the optimal values of T, r, and w, as well as the optimal objective value.
